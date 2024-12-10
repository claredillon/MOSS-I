# MOSS-I project document outputs: Framework for Managing University Open Source Software
 👉 [Download the latest **Framework for Managing University Open Source Software** PDF](https://github.com/SFI-Lero/MOSS-I/tree/main/output/document.pdf)

## Summary of the MOSS-I project
Summary here

## Repository organisation 
### Documents and outputs 
This repository contains the main source for the **Framework for Managing University Open Source Software** document in the form of a markdown document in the main folder called `document.md` (to learn more about markdown, see [this "cheatsheet"](https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet)).  Using the processes detailed below this markdown file is converted to a PDF file called [`document.pdf`](https://github.com/SFI-Lero/MOSS-I/tree/main/output/document.pdf) contained in the [`output`](https://github.com/SFI-Lero/MOSS-I/tree/main/output) folder.

### Template 
The PDF document produced here is generated from the markdown using a custom version of the [Eisvogel template](https://github.com/Wandmalfarbe/pandoc-latex-template). The main changes implemented here are the rendering of authors and DOI links. The template used here can be found under `/assets/templates` folder and is called [eisvogel.tex](https://github.com/SFI-Lero/MOSS-I/tree/main/assets/templates/eisvogel.tex). 

### GitHub action 
The GitHub is defined by a YAML file (see below) found in the `.github/workflows` folder. The action (to convert the markdown document to a pdf file) is triggered uppon a push to the repository. 

## Locally processing the markdown to PDF conversion
Assuming [pandoc](https://pandoc.org/installing.html) is installed you can run the following locally (from a terminal navigated to the main project folder) to build the PDF:
```
pandoc document.md --output=output/document.pdf --template assets/templates/eisvogel.tex --listings --number-sections --bibliography=bibliography.bib --citeproc 
```

## GitHub action based markdown to PDF conversion
The below reproduces a so called [YAML](https://en.wikipedia.org/wiki/YAML) file which configures a GitHub action to trigger the updating of the repository hosted PDF when a _push_ occurs. Here the YAML file is called `markdown2pdf.yml` and is found in the [`.github/workflows`](https://github.com/SFI-Lero/MOSS-I/tree/main/.github/workflows) folder. Glossing over the YAML file one may see it sets up pandoc, issues a command using pandoc to export the `document.md` file to a file called `document.pdf` using the template called `eisvogel.tex`. Once completed the next step configures git and adds and commits the updated PDF file. Finally the PDF is pushes to the repository.  
```
name: markdown2pdf

on: push

jobs:
  convert_via_pandoc:
    runs-on: ubuntu-22.04
    steps:
      - uses: actions/checkout@v4
      - uses: docker://pandoc/extra:3.5
        with:
          args: document.md --output=output/document.pdf --template assets/templates/eisvogel.tex --listings --number-sections --bibliography=bibliography.bib --citeproc 
      - uses: actions/upload-artifact@v4
        with:
          name: output
          path: output
      - name: Commit files # transfer the new pdf files back into the repository
        run: |
          git config --local user.name "Kevin-Mattheus-Moerman"
          git add .
          git commit -m "Updating pdfs"
      - name: Push changes # push the output folder to your repo
        uses: ad-m/github-push-action@master
        with:
          github_token: ${{ secrets.GITHUB_TOKEN }}
          force: true
  ```

## How to contribute
If you'd like to help improve this project, we welcome all contributions! Your contribution can be anything, e.g. language changes, code improvements, or documentation. 
For more information we refer to the [contributing guidelines](https://github.com/SFI-Lero/MOSS-I/blob/main/CONTRIBUTING.md). All contributors and team members are expected to act in accordance to the [project's code of confuct](https://github.com/SFI-Lero/MOSS-I/blob/main/CODE_OF_CONDUCT.md).

## Licenses 
The code/software shared here is licensed under the [MIT open source license](https://github.com/SFI-Lero/MOSS-I/blob/main/LICENSE). All other assets shared here, such as documents and images, are licensed under the [Creative Commons CC-BY-SA license](https://creativecommons.org/licenses/by-sa/4.0/). 