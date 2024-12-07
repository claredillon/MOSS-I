---
title: "Framework for Managing University Open Source Software "
author: [Kevin]
date: "05/12/2024"
subject: "Markdown"
keywords: [Markdown, Example]
subtitle: "NORF MOSS-I Project for Irish Universities"
lang: "en"
toc: true,
toc-own-page: true,
titlepage: true,
titlepage-rule-color: "360049"
titlepage-background: "backgrounds/background1.pdf"
...

# Framework for Managing University Open Source Software 

> “Open source is present everywhere. All around the world, companies and public services are using the open source collaborative methods
> to innovate and build new solutions. It powers the cloud and provides professional tools for big data and for information and knowledge management.
> It is in supercomputers, blockchain, the internet of things and artificial intelligence. It is in the internet. It is in our phones and our TVs.
> It provides us with streaming media. It is in our cars. It runs Europe’s air traffic control. The chances are that, in any new project involving software, 
> from kitchen appliances, through web-based public services to highly specialised industrial tools, most of the code will be based on open source.”
>
> – European Commission Open Source Strategy 2020-2023

## Introduction

Open Source Software (OSS) is the foundation of today’s digital economy, powering critical innovations across industries, from artificial intelligence and quantum computing to cloud technologies and data analytics. For universities, OSS offers a strategic opportunity to enhance research capabilities, accelerate technological advancements, and enable valuable knowledge transfer that collectively generates both economic and social impact. This is particularly relevant in the Irish university sector, where fostering knowledge transfer and innovation can have a direct impact on national economic growth.

In today’s technology landscape, enabling responsible open source practices is not a trivial undertaking. The choice between open source and proprietary software is not a simple "either-or" decision. Most modern systems are a blend of both, with organizations leveraging the strengths of each to meet their goals. The real challenge—and skill— for all those operating in an academic context lies in understanding when to use or create open source software (OSS) and when proprietary solutions may be more appropriate. Success comes from managing this combination responsibly, balancing transparency, innovation, and control to ensure security, scalability, and sustainability while addressing institutional and individual goals.

This document serves as a comprehensive guide for universities looking to develop or refine an open source software framework. It provides the foundational knowledge and tools needed to create an environment that supports open source that is aligned with the unique needs and goals of each institution.

## Key Recommendations
![Open Source Framework Approach](assets/images/MOSSI-OSFramework-Approach.jpg)
*Figure 1\. Key recommendations to establish an open source framework*

1. Establish clear mandate for an open source framework for faculty, staff and students.  
2. Provide dedicated resources and support services to establish and implement the open source framework.  
3. Build open source skills and literacy across the institution.  
4. Create pathways for recognition of open source contributions and impact.  
5. Review and evolve the open source framework over time.

## What Is Open Source?

Open source software (OSS) refers to software with source code that is made publicly available under a license that allows anyone to view, use, modify, and distribute the software for any purpose. Open source software is powerful because it lowers barriers to technology adoption, enabling innovation, flexibility, and customization while providing transparent, secure, and efficient solutions. In its most basic form, open-sourcing your software means putting your code online with an open source license where it can be viewed and reused by others. More details can be found in the Open Source Initiative’s [Open Source Definition](https://opensource.org/osd).[^1]

Open Source Hardware is also an important topic with related opportunities and challenges, but for the purposes of this document we are focusing on open source software. 

## Why Is Open Source So Important?

**Open source is in everything, everywhere**. Open source enables the frictionless reuse of software. As a result, it’s used everywhere. The majority of the code in all code bases is open source.[^2] Therefore, even if a project isn’t intended to be open source, it’s crucial to understand the risks, obligations, and security considerations that come with adopting open source projects to ensure responsible use and compliance. Understanding OSS adoption is essential for maintaining secure and efficient software ecosystems.

**Open source positively impacts the economy.** Recent research shows that open source software is worth up to $8.8 trillion to the world’s economy.[^3] Additional research from the European Commission predicted that an increase of 10% in contributions to Open Source Software code would annually generate an additional 0.4% to 0.6% GDP, as well as more than 600 additional ICT start-ups in the EU.[^4] OSS may be free to view, use, modify, and distribute, but it is not necessarily free of cost. We have seen a significant rise in the number of Commercial Open Source Software (COSS) companies that offer open-source software, but monetize their offerings by providing value-added services such as professional support, consulting, training, and premium features. Investment in COSS companies has risen to \+$500B and the growth of COSS companies has been faster than that of companies with proprietary source code at their core.[^5]

**Open source maximizes the social impact of technology**. The UN and other organisations have acknowledged the huge potential for social impact related to investments in open source, giving the global south immediate and unrestricted access to the latest research innovation. They promote the creation and use of open source Digital Public Goods for a more equitable world.[^6]

**Open source is becoming standard policy**. Throughout the world, open source is becoming a recommended practice for those building software. Europe has had active engagement in shaping open source policies and leveraging them in strategic areas like AI.[^7] The European Union directive on government use of FOSS was adopted in 2009\. The European Commission’s first strategy for open source was adopted in 2000.[^8] In 2020, the European Commission approved its new Open Source Software Strategy 2020-2023 of the Commission.[^9] It promotes the sharing and reuse of software solutions, knowledge and expertise, to deliver better European services that benefit society and lower costs to that society. Organizations such as UNESCO, European Commission, and the US National Academies of Sciences, Engineering and Medicine all have recommendations stating that open source is a primary requirement for open science and open research. [^10][^11]

**Open source delivers more trustworthy computing.** Open source software enhances security through transparency. With open access to the source code, many developers and users can inspect, audit, and identify potential vulnerabilities. The principle of "many eyes make all bugs shallow" means that issues are often discovered and addressed faster than in closed systems. Furthermore, in a time where mistrust in formal institutions is growing, open source fosters trust with end users by offering full visibility into how the technology works, removing the uncertainty often associated with proprietary solutions. This transparency helps ensure that users can rely on the integrity and security of their systems.

**Open source skills are required to be successful.** Leveraging the opportunities related to open source requires a unique set of skills. Building these skills is crucial to foster a successful modern software development environment. These skills include technical skills and strong collaboration skills to navigate diverse and often decentralized team dynamics. Other roles within the software ecosystem—such as legal and business professionals—must also develop specialized skills. Legal experts need to understand various open source licenses and their implications for intellectual property and compliance. Business professionals must learn how to leverage open source for strategic advantage, such as fostering innovation, reducing costs, and engaging with developer communities. There is a recognised gap in all these skills globally.[^12]

## Addressing Open Source Myths

1. **Open source is not just for hobbyists.** These days,open source is no longer the domain of hobbyist developers working alone. It is estimated that over 90% of all the world’s software is open source code. Most of the world’s largest organisations adopt, create and contribute to open source with professional developers in all domains using open source to collaborate with their innovation partners. Often organisations invest in Open Source Program Offices (OSPOs) to manage their open source use and contributions.  
2. **You retain IP and copyright**. It's important to note that open-source licensing does not relinquish intellectual property (IP) rights. The original creator or contributors still retain IP ownership, and the license merely governs how others can interact with the project. This control ensures that while the code is freely accessible, the rights of the creators are respected, allowing them to define how their work is used or credited in derivative projects.   
3. **You can commercialise open source software.** Many open-source projects lead to the creation of commercial open-source software (COSS) companies, which monetize through services and support, a growing trend in the tech industry.  
4. **Open source is as secure as proprietary software**. OSS is often now considered to be as secure or even more secure than proprietary software.[^13] The security of both depends on the quality of the software and the software development process. However, unlike proprietary software, where security issues can remain hidden, open source benefits from transparent review processes, which lead to faster detection and resolution of security flaws.

## Open Source In Academia

### Why Is Open Source Important In An Academic Context?
![Why an Open Source Framework is Essential](assets/images/MOSSI-OSFramework-Essential.jpg)
<!-- This image will be updated when available. Image above is placeholder --> 
*Figure 2\. Why open source is important in academia.*

#### University Relevance & Leadership

**Open Source Provides New Opportunities for University Leadership.** Excellence in open source enables universities to accelerate the impact of research and attract top-tier talent. A proactive approach to open source positions an institution as a global leader, capable of shaping the future of research and education through widespread dissemination and application of software research outputs.  
**Open Source Aligns with Global Best Practices.** Integrating open source software and practices into research and education builds the skills necessary to engage with the broader open source ecosystem. In this way, universities can demonstrate their alignment with software development best practices and their commitment to transparency, effective industry collaboration, and cutting-edge research. 

#### Research Excellence & Influence

**Open source Enables Open Research Excellence.** Open source software and tools form a critical part of Open Research practices. Open data published without related source code hampers open research by limiting transparency, reproducibility, and collaboration. To enable the Open Research principles, it is essential that we build open source capacity and competencies within the researcher community.  
**Open Source Increases Researcher Influence.** Taking an open source approach can accelerate the pace of innovation around a particular domain, and dictate market trends. As a result, open source contributions can also enhance researchers’ and institutions’ reputations and influence in their field, demonstrating impact through the widespread dissemination and application of their work.

#### Research Impact \- Commercialisation

**Open Source Increases Spin-out Opportunities.** There is a rise in investment and growth of Commercial Open Source Software (COSS) companies. Facilitating the spin-out of COSS companies alongside traditional companies based on proprietary source code increases the opportunities for commercialisation of research.  
**Open Source Improves Industry Collaboration.** With the rise of corporate open source investment, many organisations are now funding academic research with the explicit ask for open source output. This has been proven to accelerate the adoption and impact of funded research. 

#### Research Impact \- Social & Economic

**Open Source Increases Economic Impact.** Apart from short-term commercialisation opportunities, making research software available as open source has the potential to deliver additional indirect economic impact for a university, through accelerated innovation and the potential for hubs of start-up activity that can evolve around open source projects.   
**Open Source Delivers Social Impact.** Universities care about the positive impact they have on the world around them. The UN explicitly recommends digital public goods be made available as open source. Open source projects from universities can contribute to social impact across a wide range of areas, ranging from healthcare and agriculture to urban planning and policy analysis. 

#### Education Excellence & Student Success

**Open Source Enables Hands-on Learning.** By engaging with open source projects, students gain real-world practical experience in their field of study, learn collaboration and problem-solving skills. The focus on mentorship within open source communities provides additional learning opportunities, personalised guidance and peer support.  
**Open Source Increases Employability.** As open source makes up most of the world’s software today, skills related to the use, contribution to, creation of, and maintenance of open source are in high demand in industry.  Open source contributions provide real-world evidence of skills valued by recruiters. Universities that help students build open source skills prepare them for future careers in real-world software development environments. 

#### Openness & Inclusivity

**Open Source Democratizes Education.** Open source promotes the democratisation of education by making knowledge and educational tools accessible to a wider audience, including underrepresented and marginalised communities. Moreover, collaborating on open source courseware allows institutions to develop best-in-class material and keep it fresh with input from a diverse range of contributors and subject matter experts.  
**Open Source Builds Inclusive Communities.** Open source projects foster a sense of community and belonging among contributors, who work together towards common goals, increasing feelings of connection, building networks, and ultimately resulting in more meaningful work. Because it is accessible to all, it enables contributions and collaboration with individuals from diverse backgrounds. 

#### Sustainability

Sustainability can mean many things. Open source forms the basis of many software projects focused on tackling climate change. Open source can also help make all the software we build more environmentally sustainable. Building an open source community around a project can help ensure software projects themselves are sustained over time.

**Open Source Helps Address Climate Change.** The UN has published information on the critical role of open source in dealing with our climate challenges.[^14] Open source software can also contribute to the environmental sustainability of the broader technology industry by optimising resource use and reducing waste through shared services and infrastructure.   
**Open Source Increases Long-term Project Viability.** Open source projects often have active communities dedicated to their maintenance and development, ensuring that educational and research tools remain up-to-date and viable over the long term.

## Why An Open Source Framework Is Essential For Universities

![Why an Open Source Framework is Essential](assets/images/MOSSI-OSFramework-Essential.jpg)
*Figure 3\. Benefits of an open source framework.*

In today's digital academic landscape, open source software development spans all disciplines, from computer science to the humanities, often occurring without formal governance structures. Increasingly, European regulations, funding programs, and open research guidelines require open software outputs, while industry voices call for more open collaboration opportunities grounded in open source practices.[^15]

Without a structured framework for open source, universities risk losing opportunities to amplify research impact, drive innovation, and showcase institutional excellence. Moreover, the lack of clear guidelines exposes institutions to significant risks, including intellectual property conflicts, security vulnerabilities, and compliance issues stemming from unmanaged open source activities. By adopting a comprehensive framework, universities can transform fragmented open source efforts into strategic assets, aligning institutional goals with best practices.

A well-defined open source framework offers substantial opportunities. Many researchers and students are already successfully using and creating open source in universities today. An open source framework enhances research impact through improved code sharing, fosters stronger industry partnerships through aligned practices, and accelerates the adoption of research outputs. Additionally, it creates pathways for research commercialization, leveraging the rapidly growing Commercial Open Source Software (COSS) models that attract global investment. Such a framework also supports the recognition and reward of open source contributions that deliver significant social impact.

Unmanaged open source activities present real risks. Without governance, universities remain vulnerable to intellectual property disputes, security risks, and regulatory non-compliance, all of which could harm reputation and incur legal liabilities. Proactively addressing these challenges is critical for protecting institutional interests.

As open source becomes central to open science and research, universities must establish clear policies and procedures for managing it. This is essential not only for staying competitive but also for advancing their academic mission. Globally, institutions are addressing these challenges through initiatives like academic Open Source Program Offices (OSPOs). Ireland has already taken a leadership role by establishing Europe’s first academic OSPO. Building on its uniquely networked academic ecosystem, Ireland has the opportunity to develop coordinated, effective approaches to open source management that can serve as a global model.

## Who Engages With a University Open Source Framework?

![University roles that engage with a University Open Source Framework](assets/images/MOSSI-OSFramework-Essential.jpg)
*Figure 4\. University roles that interact with an open source framework.*

There is a diverse set of people who can interact with an OSS framework, including:

- **University Leadership:** leadership support of an OSS framework is essential to ensure that it integrates into strategic planning, academic programs, and operational management along with promoting openness and innovation across the institution.  
- **Researchers**: Open source software is a critical output of research activities. It should be noted that this is not confined to computer science or other technical domains. Open source software is often now produced across all domains including health sciences, arts and the humanities. Many researchers also contribute to OSS in their own time.   
- **Students**: Students may be asked to use, contribute to or create OSS projects as part of their curricula. Many students also contribute to OSS in their own time or organize hackathons with OSS outputs.  
- **University IT**: Whereas university OSS frameworks typically do not cover procurement within university IT departments, they sometimes can include any supports IT departments may offer staff and students in using or creating OSS, for example provision of code hosting platforms such as GitHub or automated building or testing.   
- **Tech Transfer Office**: OSS strategies can be informed to permit a variety of commercialisation pathways.    
- **Impact Officers**: Those who catalogue/chart University's impact activities have an interest in tracking OSS activity and impact.  
- **University Staff**: Additional university staff are also interested in an institution's OSS framework including those in the Office of the Vice President for Research, Legal Affairs, Technology Transfer Office, Research Support Services, Libraries, and staff involved in innovation activites. These professional support services play crucial roles in enabling and governing open source activities across the institution.

## Open Source Roles in a University Context

It is important to consider that individuals in a university may engage with open source in different ways. As open source framework should address various use cases, acknowledging the challenge posed by varying coding principles and standards of maintainability across different institutions and departments. Any framework should ensure that principles are open for department-specific nuances while emphasising good coding and technology practices. The framework must be flexible enough to accommodate diverse disciplinary contexts, recognizing that the needs and technical expertise of researchers in computer science will differ substantially from those in humanities, medicine, or social sciences, while maintaining appropriate standards for each domain.

**Using OSS in Projects ("Consumers")**  
Open source software is widely used by students, researchers, and university staff. Responsible use of OSS requires an understanding of license choices and their implications, especially if the OSS is incorporated into a derivative research output that may later be released. 

**Creating New OSS Initiatives ("Creators")**  
What license should I use? Where should I host my OSS project? Those that are creating open source software often require support and advice on how to do it for maximum impact.

**Contributing to OSS Projects ("Contributors")**  
Often the optimal route to sharing OSS is not creating a new OSS project, but rather contributing source code to an existing project. There are many best practices related to how to engage and contribute to existing OSS projects. 

**Maintaining OSS Projects ("Maintainers")**  
Once an OSS project has been created, it is necessary to consider the goals around project growth and maintenance. If the goal is to maximise community use and engagement, there are many related best practices around fostering inclusive contributions, e.g. providing clear and comprehensive documentation, community management, and project governance.

![University open source roles](assets/images/MOSSI-OS-Roles.jpg)
*Figure 5\. Open source university roles.*

## Implementing and Open Source Framework

This section outlines the key considerations necessary for fostering effective open source practices within a university. By establishing clear guidelines, policies, or charters, the university can cultivate a culture that leverages open source to enhance research excellence, facilitate knowledge sharing, and foster industry partnerships. A comprehensive framework is critical to balancing openness with governance, ensuring that open source contributions are sustainable, secure, and aligned with the institution's broader objectives.

### What is included in an Open Source framework?

An Open Source Framework tailored for a university can include any combination of policies, charters, and guidelines, depending on the level of formality and governance needed. A policy establishes formal rules and compliance requirements, a charter sets out high-level goals and guiding principles, and guidelines offer practical, detailed advice for day-to-day open source engagement. Together, they form a comprehensive approach to integrating open source into university life.

![Open Source Framework Options](assets/images/MOSSI-OSFramework-Can-Be-Tailored.jpg)
*Figure 6\. Options for an open source framework.*

Here's a breakdown of what might be included in each:

#### **1\. Open Source Policy**

An **Open Source Policy** is a formal, high-level document that outlines the institution's overarching principles, commitments, and regulations regarding the use and development of open source software. It is typically mandatory and governs the university's official stance and actions related to open source. It may be a stand-alone policy document, or an addition to existing policy documents, such as the IP Management or Open Research policy documents. 

**Potential Inclusions:**

* **Commitment to Open Source**: A declaration of the university's dedication to promoting responsible open source usage and contribution.  
* **Licensing and Compliance**: Clear rules regarding the appropriate open source licenses for use and contribution, ensuring compliance with both legal and institutional requirements.  
* **Intellectual Property (IP) Management**: Guidelines on how IP rights are handled in open source projects, balancing openness with IP protection.  
* **Security and Risk Management**: Procedures for auditing and addressing vulnerabilities in open source projects used or created within the university.  
* **Contribution Requirements**: Rules governing how faculty, students, and staff can contribute to external open source projects, ensuring their work aligns with university values and IP policies.

#### **2\. Open Source Charter**

An **Open Source Charter** is a less formal document than a policy and is typically used to define a specific mission or set of principles for engaging with open source within certain parts of the university, such as a department, research group, or student body. A charter outlines aspirational goals and guiding principles, providing flexibility and a focus on collaboration.

**Potential Inclusions:**

* **Vision and Objectives**: An outline of the university’s or department’s long-term goals for OSS involvement, including fostering innovation, education, and community engagement.  
* **Community and Collaboration**: Encouragement for open collaboration within academic and external communities, providing guidance on participation in open source projects and community-building initiatives.  
* **Principles of Openness**: Emphasis on transparency, inclusivity, and open access to research and educational tools.  
* **Project Governance**: Guidelines for how open source projects are managed, including decision-making processes, project leadership, and roles within the university’s open source ecosystem.  
* **Support for Contributions**: Encouragement for faculty, staff, and students to contribute to open source projects, both internally and externally, and recognition of their contributions in academic and professional evaluations.

#### **3\. Open Source Guidelines**

**Open Source Guidelines** are the most flexible and practical element of a framework. They provide detailed, actionable instructions on how to use, develop, and contribute to open source within the university context. Guidelines are often updated frequently to reflect best practices and new developments.

**Potential Inclusions:**

* **Best Practices for Using Open Source**: Practical advice on how to select, adopt, and use open source software in academic projects and institutional IT environments.  
* **Licensing Choices**: Guidance on how to choose appropriate open source licenses for university projects, ensuring compatibility with project goals and compliance with institutional policies.  
* **Contributing to Open Source**: Steps for contributing code to external open source projects, including how to attribute university affiliation and how to ensure compliance with open source licenses.  
* **Creating and Publishing Open Source**: Detailed instructions on how to start, manage, and publish new open source projects, including recommendations on repositories (e.g., GitHub), code maintenance, and community engagement.  
* **Security and Code Quality**: Recommendations for secure coding practices and conducting security audits for open source projects, as well as maintaining code quality through peer reviews and automated testing.  
* **Ensuring Open Source Sustainability**: Best practices for maintaining the long-term viability of open source projects, including creating a clear governance structure, fostering an active contributor community, securing funding or institutional support, and implementing processes for ongoing maintenance, documentation, and user engagement.  
* **Education and Training**: Resources and training programs to help faculty, staff, and students improve their open source skills, covering areas like collaborative development, code versioning, and compliance with licenses.

### Approach to Implementing an Open Source Framework

The implementation of an open source framework must be tailored to each institution's unique culture, existing policies, and strategic objectives. While some universities may require comprehensive formal policies from the outset, others might benefit from starting with lightweight guidelines that can evolve over time. Research-intensive institutions might prioritize frameworks that support complex research software projects, while institutions focused on teaching might emphasize student engagement and learning opportunities. The following set of steps represents **one possible approach** to implementing an open source framework, which can be adapted based on institutional context and needs.

![Open Source Framework Approach](assets/images/MOSSI-OSFramework-Approach.jpg)
*Figure 7\. Approach to implementing an open source framework.*

1. **Establish Clear Institutional Mandate**  
* Develop formal documentation that explicitly supports OSS activities, integrated with existing research and IP policies  
* Create clear guidance on roles and responsibilities for OSS management across departments  
* Ensure leadership visibly champions OSS initiatives through strategic plans and public commitments  
2. **Provide Dedicated Resources and Support**  
* Establish a coordinating body (such as a university Open Source Program Office[^16]) to oversee framework development and implementation  
* Allocate specific budget and staff resources for OSS support services including legal expertise and technical guidance  
* Create centralized resources potentially including documentation, tools, and platforms for OSS development and hosting  
3. **Build Open Source Skills and Literacy**  
* Develop training programs tailored to different roles and disciplines, from basic OSS concepts to advanced development practices  
* Integrate OSS practices into relevant curricula and research methodologies across departments  
* Create mentorship programs pairing experienced OSS contributors with newcomers  
4. **Create Recognition Pathways**  
* Establish metrics and processes for tracking OSS contributions and impact  
* Include OSS outputs in research assessment frameworks and academic evaluations  
* Develop rewards and incentives for significant OSS contributions, such as consideration in promotion and tenure decisions  
5. **Review and Evolve**  
* Schedule regular framework reviews to assess effectiveness and identify areas for improvement  
* Gather feedback from all stakeholder groups to ensure the framework continues to meet their needs  
* Monitor global trends in open source and academic practices to maintain framework relevance  
* Update policies, guidelines, and support resources based on lessons learned and emerging best practices

## Conclusion

The establishment of an open source framework is pivotal for universities aiming to align with global best practices, foster innovation, and maximize the impact of their research and educational activities. By implementing the recommended steps—such as establishing a clear institutional mandate, providing dedicated resources, building open source literacy, creating recognition pathways, and committing to ongoing review and evolution—universities can strategically harness the benefits of open source while mitigating associated risks. These measures ensure that open source practices are sustainable, secure, and fully integrated into the institution’s operations and goals. As open source becomes a cornerstone of modern academic and industry practices, universities equipped with such frameworks are well-positioned to lead innovation, drive societal impact, and ensure long-term competitiveness in the digital economy.

### Recommendations for Future NORF Projects

1. **Application of the Framework in Irish Universities**  
Pilot the implementation of the recommended open source framework in one or more Irish universities, leveraging Ireland’s leadership in establishing Europe’s first academic Open Source Program Office (OSPO). This pilot could focus on integrating open source principles into strategic planning, research, and teaching while showcasing how the framework can amplify research impact, foster industry partnerships, and enhance sustainability efforts.  
2. **Building Open Source Skills**  
Build on other NORF projects such as TROPIC[^17] to collaboratively develop tailored training programs for irish unviersities that address diverse disciplines and include both technical and non-technical open source skills.  
3. **Fostering Industry Collaboration**  
Provide guidelines and collaboration patterns on how to best co-create open source projects that involve academia and industry partners. Focus on examples that align with market trends and address real-world challenges, increasing research adoption and employability for students.  
4. **Metrics and Recognition**  
Implement advanced metrics to identify open source contributions and propose how irish universities might recognize impactful work.  
5. **Global Networking**  
Engage with international academic OSPOs to share best practices, collaborate on large-scale open source projects, and contribute to global standards for research and education.

## Acknowledgements

<!-- Add in acknowledgements - individuals and institution logos -->

<!-- FOOTNOTES AND REFERENCES -->

[^1]: ‘The Open Source Definition’, Open Source Initiative. Accessed: Dec. 07, 2024\. \[Online\]. Available: [https://opensource.org/osd](https://opensource.org/osd)\[1\]  
[^2]: ‘2024 Open Source Security and Risk Analysis Report (OSSRA) | Black Duck’. Accessed: Dec. 07, 2024\. \[Online\]. Available: [https://www.blackduck.com/blog/open-source-trends-ossra-report.html](https://www.blackduck.com/blog/open-source-trends-ossra-report.html)  
[^3]: M. Hoffmann, F. Nagle, and Y. Zhou, ‘The Value of Open Source Software’, Jan. 01, 2024, *Social Science Research Network, Rochester, NY*: 4693148\. doi: [10.2139/ssrn.4693148](https://doi.org/10.2139/ssrn.4693148).  
[^4]: Directorate-General for Communications Networks, Content and Technology                                          (European Commission) *et al.*, *The impact of open source software and hardware on technological independence, competitiveness and innovation in the EU economy: final study report*. Publications Office of the European Union, 2021\. Accessed: Dec. 07, 2024\. \[Online\]. Available: [https://data.europa.eu/doi/10.2759/430161](https://data.europa.eu/doi/10.2759/430161)  
[^5]: ‘Open Source Is Eating Software FASTER than Software Is Eating The World’, COSS Community 🌱. Accessed: Dec. 07, 2024\. \[Online\]. Available: [https://www.coss.community/cossc/open-source-is-eating-software-faster-than-software-is-eating-the-world-3b01](https://www.coss.community/cossc/open-source-is-eating-software-faster-than-software-is-eating-the-world-3b01)  
[^6]: ‘Digital Public Goods | Office of the Secretary-General’s Envoy on Technology’. Accessed: Dec. 07, 2024\. \[Online\]. Available: [https://www.un.org/techenvoy/content/digital-public-goods](https://www.un.org/techenvoy/content/digital-public-goods)  
[^7]: C. O’Riordan, ‘Overview of EU legislation on FOSS | Interoperable Europe Portal’. Accessed: Dec. 07, 2024\. \[Online\]. Available: [https://interoperable-europe.ec.europa.eu/collection/open-source-observatory-osor/news/overview-eu-legislation-foss](https://interoperable-europe.ec.europa.eu/collection/open-source-observatory-osor/news/overview-eu-legislation-foss)  
[^8]: ‘Open Source Strategy: History \- European Commission’. Accessed: Dec. 07, 2024\. \[Online\]. Available: [https://commission.europa.eu/about/departments-and-executive-agencies/digital-services/open-source-strategy-history\_en](https://commission.europa.eu/about/departments-and-executive-agencies/digital-services/open-source-strategy-history_en)  
[^9]: ‘The European Commission adopts its new Open Source Software Strategy 2020-2023 \- European Commission’. Accessed: Dec. 07, 2024\. \[Online\]. Available: [https://commission.europa.eu/news/european-commission-adopts-its-new-open-source-software-strategy-2020-2023-2020-10-21\_en](https://commission.europa.eu/news/european-commission-adopts-its-new-open-source-software-strategy-2020-2023-2020-10-21_en)  
[^10]: ‘UNESCO Recommendation on Open Science | UNESCO’. Accessed: Dec. 07, 2024\. \[Online\]. Available: [https://www.unesco.org/en/open-science/about](https://www.unesco.org/en/open-science/about)  
[^111]: P. O. of the E. Union, ‘Commission Recommendation (EU) 2018/790 of 25 April 2018 on access to and preservation of scientific information, C/2018/2375’, Publications Office of the EU. Accessed: Dec. 07, 2024\. \[Online\]. Available: [https://op.europa.eu/en/publication-detail/-/publication/2ea66d3f-649a-11e8-ab9c-01aa75ed71a1](https://op.europa.eu/en/publication-detail/-/publication/2ea66d3f-649a-11e8-ab9c-01aa75ed71a1)  
[^12]: ‘Report- Open Source and InnerSource Skills in Ireland: A Call for Action’, Open Ireland Network. Accessed: Dec. 07, 2024\. \[Online\]. Available: [https://openirelandnetwork.com/report/](https://openirelandnetwork.com/report/)  
[^13]: ‘Open Source Maturity in Europe’. Accessed: Dec. 07, 2024\. \[Online\]. Available: [https://www.linuxfoundation.org/research/world-of-open-source-eu-2024](https://www.linuxfoundation.org/research/world-of-open-source-eu-2024)  
[^14]: ‘The climate data challenge: the critical role of open-source and neutral data platforms’. Accessed: Dec. 07, 2024\. \[Online\]. Available: [https://www.unepfi.org/themes/climate-change/the-climate-data-challenge-the-critical-role-of-open-source-and-neutral-data-platforms/](https://www.unepfi.org/themes/climate-change/the-climate-data-challenge-the-critical-role-of-open-source-and-neutral-data-platforms/)  
[^15]: CURIOSS, ‘Academic-Industry Collaboration’, CURIOSS. Accessed: Dec. 07, 2024\. \[Online\]. Available: [https://curioss.org/news/nov24-industry-partnerships/](https://curioss.org/news/nov24-industry-partnerships/)  
[^16]: J. Young, L. A. Barba, S. Choudhury, C. Flanagan, D. Lippert, and R. Littauer, ‘A Definition of an Academic OSPO’, Oct. 2024, Accessed: Dec. 07, 2024\. \[Online\]. Available: [https://zenodo.org/records/13910683](https://zenodo.org/records/13910683)  
[^17]: D. Lakhzoum *et al.*, ‘NORF \- TROPIC project’, Sep. 2023, Accessed: Dec. 07, 2024\. \[Online\]. Available: [https://osf.io/chxgd/](https://osf.io/chxgd/)  

