
<!-- 
author:   C3L
email:    c3l@uol.de
Version:  1.0
language: en
license:  http://creativecommons.org/licenses/by/4.0/

mode:     Presentation

narrator: US English Female

logo:   img/Background_2.png

icon:   img/efzn-logo.png

script: https://ajax.googleapis.com/ajax/libs/jquery/1.11.3/jquery.min.js
        https://cdn.jsdelivr.net/chartist.js/latest/chartist.min.js

link:   https://cdn.jsdelivr.net/chartist.js/latest/chartist.min.css
        https://cdn.jsdelivr.net/gh/NFDI4Energy/EFZN_rdm@main/style.css
-->

# Research Data Management

![Logo-Block](img/Logoblock.png)

Welcome to "Research Data Management in the Energy Sector"! This course teaches all skills necessary to understand the principles and motivation behind Research Data Management (RDM) and enables you to implement RDM in your work and research group.

The course focuses on applicability in the energy sector.

There are three possible ways to work with this course: 

1. Do you want to gain a thorough understanding of RDM? Follow the course outline described in the following graph. When you complete the course, you will have established a basic data management plan for a project of your choice that you can build upon and adapt. 
2. Are you looking for a challenge? In the quizzes, collect the letters in brackets after the correct solution, and together they form the solution word. 
3. Do you already have some knowledge of RDM? Great! Choose individual chapters that are of interest for your field of work by clicking on the plus signs.

A quick word on the course format. The course is written in [Markdown](https://de.wikipedia.org/wiki/Markdown) and implemented in [LiaScript](https://liascript.github.io/). 
In the upper right corner, you can switch between textbook mode, presentation mode and slides. You can have the course read aloud by clicking on the symbol at the bottom of the page in presentation mode. If you want to adapt the course for your use, you may do so by opening a branch on [GitHub](https://github.com/NFDI4Energy/EFZN_rdm) or downloading individual files. 

<iframe src="https://www.twillo.de/edu-sharing/eduservlet/render?node_id=291a02e3-2fd0-4276-b49d-37c205fe945d" width="100%" height="840" frameborder="0" allowfullscreen="allowfullscreen" title="Research Data Management in the Energy Sector"></iframe>


## What is Research Data Management?

In early 2020, the COVID-19 disease, caused by the coronavirus SARS-CoV2, broke out globally, which led to the closure of many shops and businesses for quarantine reasons. The result, especially in the USA, was a large number of unemployed people who urgently needed money for their next rent payment, food or other expenses. As a consequence, the government set up a relief package for anyone who registers as unemployed - but the money didn't get to the people. This was a huge problem!

The reason for this was that critical systems collapsed on which COBOL is running. COBOL is a programming language that was developed in the late 1950s to control commercial applications. From today's perspective, the programming language is very outdated and no longer taught in the training of programmers. That is why there was no personnel to take care of the systems when they collapsed. Unfortunately, many applications with the outdated programming language are still running in the business sector.

Source: [FDM Thüringen: Scarytales, Licensed under CC-BY 4.0](https://forschungsdaten-thueringen.de/fdm-scarytales/articles/ueberblick.html)

> **Exercise**: 
> 
> Suggest two possible process changes that could have prevented the outcome of the scenario.

<details>

<summary> Solution (click to enlarge):</summary>

There are several solutions possible: Existing systems should be questioned, since requirements can change and established habits can lead to problems from today's perspective. For example, at some point, data might no longer be able to be called up or might exist in formats that are increasingly difficult to be processed. A thorough documentation of the programs might also help in some cases to rebuild them in other languages. For timely relief, the administration called out to retired COBOL programmers to work on the issues.

</details>

<br>

While maybe not as critical for society at large, scientists can face similar problems when trying to access old data or programs that were written for other purposes but are now needed for current tasks: Data are insufficiently labeled, have been overwritten, commercial computer programs have been discontinued or process details were not recorded.

**Research Data Management (RDM)**  aims to break this dynamic by ensuring a sustainable and coherent strategy for all data types throughout the research process. This enables researchers to store, access and re-use their own work effectively and safely and opening their findings worldwide to improve on cross-disciplinary collaboration, monitoring and replication.

RDM includes all activities associated with processing, storage, preserving and publication of research data.

### The Research Data Lifecycle

    {{0-1}}
![DataLifecycle](img/DataLifecycle.png "The Research Data Lifecycle. Original source: [UK Data Service](https://ukdataservice.ac.uk/learning-hub/research-data-management/), recreated by A. Ahrens. Licensed under [CC-BY-4.0](https://creativecommons.org/licenses/by/4.0/deed.de)")

    {{0-1}}
The "Research Data Lifecycle" describes a cyclic process of data generation and management. First, data is created, then processed. The next step is analyzing the data, followed by preserving the results. Now, it is time to give access to the data. Ideally, the cycle closes at this point: Data is being re-used and new, well-documented data is being created.

    {{0-1}}
> __Exercise:__
> Look at each step of the cycle with your data in mind:
>
> - Which steps do you actively apply in your research process?
> -  Which tools or software do you use at each step?
> - How well is the data protected against data loss? Where are possible flaws where data or information could get lost?
> - Does the cycle "close"? Which repositories or platforms do you use to store your results?



### Benefits of RDM

    {{0-1}}
<iframe src="https://www.twillo.de/edu-sharing/eduservlet/render?node_id=e7272cc1-7e1a-409b-aff4-feb578a988a8" title="Prof. Dr.-Ing. Astrid Niesse on RDM" width="100%" height ="600" frameborder="0" allowfullscreen="allowfullscreen" ></iframe>


    {{1-2}}
__Benefits of RDM in your projects__

    {{1-2}}
Are you frustrated with the time you invest in searching for data? Do you want to apply structured RDM cost-effectively? But in the moment, you lack the expertise, resources, or incentives to share your data with your group and in your field?
Perhaps you worry whether your data is transferable at all because some data have ethical or epistemological restrictions or your project includes many stakeholders with competing interests in your project? In this chapter, we will prove to you that RDM is not as tricky as you think.

    {{1-2}}
![Benefits](img/Benefits.png "Benefits of RDM. By N. Seitz. Licensed under [Attribution 4.0 International (CC BY 4.0)](https://creativecommons.org/licenses/by/4.0/deed.en) Source: https://www.go-fair.org/fair-principles/")

    {{1-2}}
If done right, RDM will...

    {{1-2}}
1. __...save time, resources, effort and money:__

   - Preserve time that is otherwise lost while searching for, recovering, and deciphering data.
   - Make data reusable.
   - Benefit from high quality datasets from other researchers.
   - Simplify cooperation and collaboration (e.g. through better documentation and affiliation of the data collected).

2. __...improve impact and speed up scientific progress:__

    - Make research results reproducible and reusable, so others can verify and build upon your findings. This strengthens __integrity__ and increases your citations.
    - Improve your research reputation and increase your __visibility__.
    - Continually influence research developments long after the original research has been completed.
    - Permit new and innovative research to be built on existing information.

3. __...help to prevent errors and enhance data security:__

    - Secure your data against loss and protect sensitive data against misuse, theft, damage and disaster.
    - Ensure records are synchronized, complete and reliable.
    - Improve research workflows to make them more resilient to human error and software vulnerability.

4. __...show compliance with research obligations of your institution and funder:__

    - Fulfill grant requirements and comply with practices conducted in industry and commerce in order to demonstrate a high-quality research output.
    - Ensure transparency since individual contributions are documented on-the-fly throughout the complete research and archiving process.
    - Increase your chances of funding since many funding organizations require a DMP.



{{2-3}}<iframe src="https://www.twillo.de/edu-sharing/eduservlet/render?node_id=8592e4d6-37e9-4bb1-a356-73803e3f3971"  title="Henrik Wagner (TU Braunschweig) on RDM" width="100%" height ="600" frameborder="0" allowfullscreen="allowfullscreen" ></iframe>

    {{3}}
__It's Quiz Time__

    {{3}}
1. RDM helps preserve time that is otherwise lost while:

    {{3}}
    [[ ]] Collecting data (M)
    [[ ]] Analyzing data (A)
    [[x]] Searching for, recovering, and deciphering data (W)
    [[ ]] Archiving data (G)

    {{3}}
2. One of the benefits of RDM is making data:

    {{3}}
    [[ ]] Irreversible (F)
    [[ ]] Obsolete (R)
    [[x]] Reusable (O)
    [[ ]] Inaccessible (S)

    {{3}}
3. RDM enables researchers to benefit from high-quality datasets from:

   {{3}}
    [[ ]] Social media platforms (C)
    [[x]] Other researchers (R)
    [[ ]] Government agencies (L)
    [[ ]] Non-profit organizations (E)

    {{3}}
4. RDM can influence research developments:

    {{3}}
    [[ ]] Immediately after the original research is completed (T)
    [[ ]] Only within the same discipline (U)
    [[x]] Continually, long after the original research is completed (L)
    [[ ]] Only across disciplines (D)

    {{3}}
5. One way RDM helps prevent errors is by:

    {{3}}
    [[ ]] Encrypting data (S)
    [[ ]] Backing up data (Q)
    [[x]] Synchronizing records (D)
    [[ ]] Archiving data (Y)

## Open Science and RDM

    {{0-1}}
*Open Science* strives to make scientific research and its dissemination accessible to all levels of society. It is based on the four principles of __transparency__, __reproducibility__, __reusability__ and __open communication__.
Open Science can encompass publishing open research, campaigning for open access, encouraging scientists to practice **open-notebook science** (such as openly sharing data and code), broader dissemination and engagement in science and generally making it easier to publish, access and communicate scientific knowledge (https://ag-openscience.de/open-science/).

    {{0-1}}
> **Exercise**:
>
> Find out if your institution has an Open Science or Research Data Policy.
>
> What is its scope? What is regulated and how?
>
> If not:
> Would you like to have a Research Data Policy?
> What content should it have?

### Make it FAIR

The main idea behind the FAIR principles is: __As open as possible, as closed as necessary!__  The acronym stands for

- **F**indable
- **A**ccessible
- **I**nteroperable
- **R**eusable

> **Exercise**:
>
> Look closely at the graph to identify which measures especially apply to your area of work and data types you are using.

![FAIR Guiding Principles](img/FAIR.png "Fair Guiding Principles by A. Ahrens. Licensed under [Attribution 4.0 International (CC BY 4.0)](https://creativecommons.org/licenses/by/4.0/deed.en) Source: https://www.go-fair.org/fair-principles/")

<!-- --{{0}}--
As open as possible, as closed as necessary. This is the main idea behind the FAIR principles. The acronym stands for: Findable, Accessible, Interoperable and Re-Usable.

In Detail, that means:
1. To make data findable, you should assign unique and persistent identifiers, that stay active. Also, provide extensive and useful metadata - for example, avoid acronyms. You should also use common repositories. You can find a list on Re3data.com. For the energy sector, we recommend the Open Energy Platform.
2. Accessible data use stanrdized communications protocol such as HTTP or FTP. Make sure anyone with a computer and internet connection can access at least the metadata. Your data and metadata should be long-term accessible. For sensitive data, you may use authentification routines.
3. In order to achieve interoperability, use a formal, accessible, shared and boradly applicable language. Also, use tools and software that are FAIR themselves. Cross-reference your data and metadata.
4. Reusable data is described by as much information as possible, such as process details. Clearly describe data usage licenses. Be transparent about data provenance and know and meet your own community's data standards.
-->

> **It's Quiz Time**:
>
> What can you do to make your data more FAIR?
>
> [[X]] use Creative-Commons or GNU licenses (S)
> [[ ]] keep processing details undisclosed (I)
> [[ ]] ensure access security (A)
> [[X]] create detailed Metadata (B)
> [[X]] ensure long-term accessibility in repositories (E)

## Data Management Plan

    {{0-1}}
The **Data Management Plan (DMP)** contains all information that describes and documents sufficiently the collection, processing, storage, archiving and publication of research data within a research project.

    {{0-1}}
>**Exercise**:
>
> Watch the following video and answer the questions that pop up.


    {{0-1}}
<iframe src="https://wp.uni-oldenburg.de/innovative-hochschule-jade-oldenburg-wise20182019/wp-admin/admin-ajax.php?action=h5p_embed&id=22" width="100%" height ="600" frameborder="0" allowfullscreen="allowfullscreen" title="Data Management Plan - Interactive Video" ></iframe>

    {{1-2}}
Many public funding organizations require a DMP prior to granting funds for research projects, thus making DMPs an integral part of the scientific process, especially in data-intensive research fields such as the energy sector.

    {{1-2}}
| Funder | Plan demanded? | Content | Updates? |
|:-------|:--------------------------|:--------|:---------------|
|Horizon Europe| Data Management Plan|see [Horizon Europe Online Manual](https://op.europa.eu/en/web/eu-law-and-publications/publication-detail/-/publication/9570017e-cd82-11eb-ac72-01aa75ed71a1)|Yes|
|[German Research Foundation (DFG)](https://www.dfg.de)     |Information on the handling of research data|[DFG Guidelines on the Handling of Research Data](https://www.dfg.de/en/research_funding/principles_dfg_funding/research_data/), Checklist|No|
|[German Ministry for Economic Affairs and Climate Action (BMWK)](https://www.bmwk.de/)| Research Data Exploitation Plan|scientific and economic potential, connectivity and transferability|once a year|
|[German Ministry of Education and Research (BMBF)](https://www.bmbf.de/bmbf/de/forschung/digitale-wirtschaft-und-gesellschaft/aktionsplan-forschungsdaten/aktionsplan-forschungsdaten_node.html)   |Plan sometimes required|Content depends on the respective program||
|[German Ministry for Digital and Transport (BMDV)](https://bmdv.bund.de)|Research Data Exploitation Plan sometimes required |Content depends on the respective program||


## Legal Aspects

Because research projects have very diverse legal requirements, consider the following areas and their relevance to your project and research data (RD).

![Legal Areas in RDM](img/LegalAspects.png "Relevant Legal Areas.  Source: Biernacka et al. 2020. Licensed under [Attribution 4.0 International (CC BY 4.0)](https://creativecommons.org/licenses/by/4.0/deed.en).")

> __Exercise:__
>
> Which legal questions do you need to clarify with your funder or institution?

### Licenses

     {{0-1}}
The internet has made it incredibly easy for people to share and collaborate. However, copyright laws can often pose obstacles to this process. Generally, others cannot use or remix your work without obtaining your permission first.
But what if you want to encourage others to reuse your work? In such cases, you may consider publishing your work under a [Creative Commons](https://creativecommons.org/) license or [GNU General Public License](https://www.gnu.org/licenses/).


    {{0-1}}
Creative Commons licenses are a set of copyright licenses that allow creators to grant others permission to use their work. They are designed to be easily understood and applied, providing a flexible framework for sharing and collaboration. By assigning a Creative Commons license, researchers can clearly communicate how others can use, distribute, modify, and build upon their work.

    {{0-1}}
For software, you may also use a [GNU General Public License](https://www.gnu.org/licenses/gpl-3.0.html), guaranteeing end users the four freedoms to run, study, share, and modify the software. For other options to license software, you can consult [this Wikipedia comparison](https://en.wikipedia.org/wiki/Comparison_of_free_and_open-source_software_licenses).

    {{0-1}}
So "free" licenses provide you with the flexibility to choose which rights you wish to retain and allow you to clearly communicate to others how they can use your work. This way, you can strike a balance between protecting your rights as author and fostering a culture of sharing and collaboration on the internet.

    {{1}}
__Step 1: Selecting License Features__

    {{1-2}}
First, you need to choose the specific conditions that you want to apply to your work. Here are the "building blocks" to consider:

    {{1-2}}
1.	__Attribution (BY):__ requires to give attribution to the creator.

2.	__ShareAlike (SA):__ If others use your work, they are required to share it under the same conditions that you specified.

3.	__NoDerivatives (ND):__ This license allows reusers to copy and distribute the material in unadapted form only.

4.	__NonCommercial (NC):__ This feature allows the reuse of your work only for non-commercial purposes.


{{1-2}} These features can now be combined to make the license of your choice:

    {{1-2}}
![CC License Requirements](img/CCLicenseChart.png "Foter.com (2015): CC License Requirements. Cropped by A. Ahrens. Licensed under [Attribution 4.0 International (CC BY 4.0)](https://creativecommons.org/licenses/by/4.0/deed.en) Source: https://foter.com/blog/how-to-attribute-creative-commons-photos/")

    {{1-2}}
You may also choose to give your work to the Public Domain and resign all rights you have by assigning "CC0".

    {{2}}
__Step 2: Obtaining a License__

    {{2-3}}
When giving attribution to a Creative Commons-licensed work, it's important to follow certain guidelines. A useful mnemonic to remember is __TASL__, which represents the key elements to include:

    {{2-3}}
1.	Title: Include the name of the material if it has been provided. This helps to identify the specific work you are attributing.
2.	Author: Clearly state the name of the person or entity that owns the material. This gives credit to the original creator of the work.
3.	Source: Mention where you found the material. Provide the URL or hyperlink that directs others to the location where the work is hosted. This allows others to easily access the original source.
4.	License: Specify the Creative Commons license that applies to the work. Simply saying "Creative Commons" is not sufficient. Name the CC license and provide a direct link to the license text. This informs others of the rights and permissions granted by the license.


{{2-3}} A final word on "openness": you might be tempted to protect as many of your rights as possible. Try to think the other way around, though: how open can you make your data? For example, a researcher from a commercial institution might be prohibited to use your data because of its NC-license or someone else might be forced to reproduce datasets because they are licensed under CC-BY-ND.

    {{2-3}}
![Degrees of Freedom](img/Foter.com_infographic_CC.jpg "Foter.com (2015): Degrees of Freedom. Cropped by A. Ahrens. Licensed under [Attribution 4.0 International (CC BY 4.0)](https://creativecommons.org/licenses/by/4.0/deed.en) Source: https://foter.com/blog/how-to-attribute-creative-commons-photos/")

    {{3}}
__It's Quiz Time!__

    {{3}}
<iframe src="https://www.twillo.de/edu-sharing/eduservlet/render?node_id=587d9a6c-9889-440d-ba19-2f16d2d5f23b" width="100%" height="740" frameborder="0" allowfullscreen="allowfullscreen" title="Quiz - Licensing in RDM" ></iframe>


### Access Rights

    {{0-1}}
If you want to limit access to your published data, this does not contradict the FAIR guidelines, but you should make the access scheme transparent (e.g. by using appropriate licenses) and give access to as much detail as possible.


    {{0-1}}
Try to assign roles to all collaborators. Each role is associated with a set of access rights that are necessary to carry out the duties and tasks associated with that role.
The following principles are typically followed:

    {{0-1}}
1.	__Principle of least privilege:__ Individuals should be granted the minimum access rights necessary to perform their job functions effectively. Assigning excessive privileges increases the risk of unauthorized access or misuse of data.

2.	__Role-based access control (RBAC):__ Assign roles to individuals and associating access rights with those roles. This simplifies the management of access rights as permissions are granted to roles rather than to individual users. Role assignment is based on the individual's job responsibilities, ensuring that access rights are aligned with their needs.

3.	__Regular review and updates:__ Access rights and role assignments should be periodically reviewed and updated to reflect changes in job roles, responsibilities, or organizational structure.

    {{1}}
__It's Quiz Time!__

    {{1}}
1. What are some aspects of access security?

     {{1}}
    [[x]] Privacy, integrity, availability, and controllability (S)
    [[ ]] Authentication, encryption, authorization, and auditing (L)
    [[ ]] Authentication, vulnerability assessment, encryption, and monitoring (V)
    [[ ]] Privacy, vulnerability assessment, authorization, and auditing (O)

    {{1}}
2.	What is a recommended practice for password protection?

    {{1}}
    [[ ]] Use sequential characters on the keyboard for easy memorization (B)
    [[ ]] Use dictionary words to make passwords more secure (R)
    [[x]] Use strong passwords with at least eight characters, including upper and lower case letters, special characters, and numbers (T)
    [[ ]] Avoid using special characters and numbers in passwords (P)

    {{1}}
3.	What is the purpose of access rights and role assignment?

    {{1}}
    [[x]] To limit access to sensitive data to authorized individuals only (D)
    [[ ]] To increase data availability for all users (U)
    [[ ]] To delegate data backup responsibilities to multiple individuals (H)
    [[ ]] To restrict data access based on file formats (A)


## Infrastructure

To better handle research data, specific tools, and services are needed. On the one side, they can support the handling of research data and software. On the other side, they can provide places to store data and/or metadata. Within this chapter, you can learn more about different tools and resources which already exist.

In the context of the German National Research Data Infrastructure (NFDI) multiple existing services are harmonized and further services will be developed. If you want to learn more about the NFDI in general, check out [their video](https://www.youtube.com/watch?v=uJ01g9m8uE4). For the energy domain, NFDI4Energy is responsible. You can check out their latest developments on [their website](https://nfdi4energy.uol.de/).


### Tools

    {{0-1}}
Tools can help you to...

    {{0-1}}
-	comply with data management requirements by providing guidance and templates for data management planning. They facilitate data sharing and preservation.
-	organize, analyze and visualize your data in order to  make it easier to draw insights and conclusions from your research. Many research projects generate large and complex datasets that can be difficult to manage without the right tools.
-	facilitate collaboration by allowing multiple researchers to access and analyze data.
-	ensure accuracy and reliability of your data by providing features such as data validation, version control and audit trails.
-	long-term preserve your data with backups, archives, and structured metadata.

    --{{1}}--
The specific features and capabilities of research data management tools can vary widely depending on the tool and the intended use case.

    {{1-2}}
In general, there are 6 steps when choosing the suitable tool:

    {{1-2}}
1.	Choose your tool
2.	Plan a data management strategy
3.	Set up the tool
4.	Put in and manage your data
5.	Collaborate and share your data
6.	Preserve and archive your data

{{1-2}}| Tools for internal DM: | Tools to share and register your research data:  | DMP Tools   |
| :--------- | :--------- | :--------- |
| [Coscine](https://www.coscine.de/)    | [Zenodo](https://zenodo.org/)     | [RDMO](https://rdmorganiser.github.io/en/)   |
| [IndiScale](https://www.indiscale.com/) | [Open Energy Platform](https://openenergy-platform.org/) |  [DMPOnline](https://dmponline.dcc.ac.uk/) |
| |[GitHub](https://github.com/)/[GitLab](https://about.gitlab.com/) | [DMPTooI](https://dmptool.org/) |

    {{1-2}}
You can also create a DMP in a simple "Excel"-type document.
The tools above provide additional help by letting you choose a set of questions that you want to follow in your DMP. If you want to take a look at an example DMP, you can look [here](img/DMP_GridCapacity.pdf). We recommend to use RDMO or DMPOnline due to their broad spectrum of available questionnaires.

    {{2-3}}
> **DMP Task**:
>
> Now it is time to start your DMP! Choose a **tool** and a set of **questions** that you want to work with and enter your basic project parameters:
>
>1. Title and Research Question
>2. Project Partners and Institutions
>
> Depending on your settings, you can add other details required by the respective questionnaire.

    {{2-3}}
Congratulations! You have started your first DMP!

    {{3}}
**It`s Quiz Time!**

    {{3}}
<iframe src="https://www.twillo.de/edu-sharing/eduservlet/render?node_id=981a8688-f44b-4811-a912-585d421daf82" width="100%" height ="750" frameborder="0" allowfullscreen="allowfullscreen" title="Tools for RDM" ></iframe>


### Data Types

    {{0-1}}
Depending on your field of expertise, there will be different data types relevant to your work. In your DMP, you can specify individual datasets and name their identifiers, file size, origin and so forth.

    {{0-1}}
The data types you choose to publish have consequences for your Research Data Management in regard to the "Accessible", "Interoperable" and "Reusable" criteria of the FAIR Guidelines.

    {{0}}
**1. Accessible**  --> Make sure that (meta)data are long-term accessible.

    {{0-1}}
    The amount of memory space needed for long-term, safe storage may vary greatly between data types. For example, if your reasearch data consist  of high-resolution images of potential wind turbine sites, memory space needed for backup and repositories will be much higher than a handful of CSV files with projected power loads.

    {{0}}
**2. Interoperable** --> Use tools and software that are FAIR themselves

    {{0-1}}
    Strive to choose, where possible, programs and data types that are open and FAIR. For example, do not describe your processing details in a .pdf file, but rather use a .txt-file that can be read and edited with various programs.

    {{0}}
**3. Reusable** --> Know and meet community standards

    {{0-1}}
    Which data types are most likely to be found, easily reused and shared in your scientific community? If these are "closed", you could provide two files: one that adheres to the common standards and one more open alternative that promotes the idea of open science.

    {{1-2}}
> **Exercise:**
>
> Make a list of the data types commonly used in your working group and their "FAIR value". Use the criteria in the table below.

    {{1-2}}
| FAIR value|	Machine Readability	| Human Readability	| Long-time Stability|	Metadata   | Example|
| :--------- | :---------| :--------- | :--------- | :---------|:-----------|
|very good |with common open software	|yes and without special software	|normed standard	|completely preserved |  .csv|
|good	|with common and well-documented software	| compressed with standard procedures, but practically yes	|longterm or widely established	| technical details are provided| |
|moderate	| proprietary standard format   | with open software (reliably?) convertible to higher class| 	relatively new format	| some important ones (e.g. units) are included | MATLAB file|
|bad	| self-developed reading software| no|	newly developed	| no information    | .xlsx|

    {{1-2}}
Source: translated and adapted from [forschungsdaten.info](https://forschungsdaten.info/themen/veroeffentlichen-und-archivieren/formate-erhalten/), [CC-BY 4.0](https://creativecommons.org/licenses/by/4.0/deed.en)

    {{2}}
>**DMP Task**:
>
> If you already know datasets that you will be (re-)using or producing, enter them in your DMP as thoroughly as possible at this point.
>
> If you do not know your datasets yet, enter one or two "dummy" datasets and follow the respective questionnaire to get an idea of the amount of detail required in the DMP.


### Software and Simulation

    {{0-1}}
Simulations and software programs are a special case. Here, not only the resulting datasets are of scientific value but also the programs, algorithms and settings leading up to the data. Research programs and simulation software are essential in energy research. Some researchers are very reluctant in sharing this part of their research work, sometimes because of economic considerations.

    {{0-1}}
The German Research Alliance (DFG) adresses software development in a research context in its [Guidelines for Safeguarding Good Research Practice](https://www.dfg.de/en/research_funding/principles_dfg_funding/good_scientific_practice/index.html), stating that "software programmed by researchers is made publicly available along with the source code". The source code must be persistent, citable and documented. Certain individual exceptions are possible, though.

   {{0-1}}
So, whether you plan to publish some, all or none of your self-developed software, you have to document well, plan ahead and ensure a good access strategy in your development team.

    {{0-1}}
- Versioning: Various cloud programming platforms such as [GitLab](https://about.gitlab.com/de-de/) ensure a consistent preservation of all of your software versions, make contributions transparent and simplify collaboration.

- Documentation: Programs should be documented and commented, e.g. by stating origin, purpose and scope of a program, limitations of variables and ideally a short manual.

- Publication: With journal publication of an article, corresponding software should be cited with version number and a persistent identifier such as a Digital Object Identifier (DOI). Choose a software archive with version control. Sometimes, timely open access is not possible. In this case, at least the algorithm used must be outlined completely. If the source code is not published, state the reason and potentially the time period until release.

    {{1}}
 __Simulation__

    --{{1}}--
With regard to simulation, we are presented with some additional challenges.

    {{1-2}}
The longevity of simulation outputs is harder to assess than that of observational data. In a paper from 2021 on Open Science in Earth System Modelling, [Mullendore et. al. (2021)](https://doi.org/10.3389/fclim.2021.763420) identify the following problems:

    {{1-2}}
- Simulations can generate massive output.
- Interdependencies between hardware and software can limit the portability of models and make the longterm accessibility of their output problematic. Models in many cases involve interconnections between community models, open source software components, and custom code written to investigate particular scientific questions.
- A lack of standardization and documentation for models and their output makes it difficult to achieve the goals of open and FAIR data initiatives.

{{1-2}}The following strategies may be applied when working with simulations:

    {{1-2}}
 - Analyze your project: does it focus on **knowledge** or **data production**? "Most scientific research projects are undertaken with the main goal of knowledge production (e.g., running an experiment with the goal of publishing research findings). Other projects are designed and undertaken with the specific goal of data production, that is, they produce data with the intention that those data will be used by others to support knowledge production research." [(Mullendore et. al. (2021))](https://doi.org/10.3389/fclim.2021.763420)
-  Publish all elements relevant to the simulation, not just source code.
- Publish enough output data to evaluate and reuse your findings, but not all simulation runs.
- Some software may be released openly while others remain restricted due to security or proprietary concerns. In this case, the documentation should provide enough information to reproduce the process.

{{1-2}}![simulation](img/simulation.png  "[Mullendore et. al. (2021):](https://doi.org/10.3389/fclim.2021.763420) Data and software elements to be preserved and shared by all projects.")

    {{2-3}}
__Checklist for RDM in simulation and software development:__

    {{2-3}}
- Train yourself and your team in software development quality
- State the purpose of each program in a few words
- Keep your software up to date with quality management
- Keep the intention of every function clear (by naming or comments)
- Choose an appropriate license
- Establish quality management in your simulation process

    {{3}}
>**DMP Task**:
>
> If you have self-developed programs in your project, enter them as a separate dataset in your DMP, name all contributors and the purpose of each program.


    {{4}}
**It's Quiz Time!**

    {{4}}
1. What is the principle behind "as open as possible, as closed as necessary"?

    {{4}}
    [[ ]] Openly sharing all research data and tools (G)
    [[ ]] Using closed and proprietary software for data analysis (U)
    [[x]] Striving to choose open and FAIR tools and data types when possible (A)
    [[ ]]Restricting access to research data and tools (W)

    {{4}}
2. What should researchers do if timely open access to the software is not possible?

    {{4}}
    [[ ]] Provide a detailed algorithm without outlining the source code. (I)
    [[ ]] Delay the publication of the article until the software is open access. (P)
    [[x]] State the reason for not publishing the source code and the expected release timeframe. (T)
    [[ ]] Exclude any mention of the software in the article. (S)

    {{4}}
3. What are the challenges associated with the longevity of simulation outputs?

    {{4}}
    [[ ]] Simulation outputs are easily assessable and portable. (M)
    [[ ]] Simulation outputs are often small in size, making long-term accessibility simple. (N)
    [[x]]Simulations can generate massive output, and interdependencies between hardware and software can limit their portability. (A)
    [[ ]] Standardization and documentation for simulation outputs are well-established. (X)

    {{4}}
4. What should be done if some software used in simulations cannot be openly released?

    {{4}}
    [[ ]] Provide no documentation or information about the restricted software. (T)
    [[ ]] Exclude any mention of the restricted software in the documentation. (O)
    [[x]] Ensure the documentation provides enough information to reproduce the process. (M)
    [[ ]] Delay the publication until all software used in simulations can be openly released. (F)

    {{4}}
5. What is one of the considerations for ensuring long-term accessibility of research data?

    {{4}}
    [[ ]] Using tools and software that are FAIR themselves. (V)
    [[x]] Choosing data types that require minimal memory space. (A)
    [[ ]] Storing data in repositories with high backup capacity. (J)
    [[ ]] Describing processing details in a .pdf file. (Z)

    {{4}}
6. What are the recommended characteristics of software documentation in research?

    {{4}}
    [[ ]] Avoid documenting the origin, purpose, and scope of the program. (R)
    [[ ]]Provide a detailed manual with step-by-step instructions. (K)
    [[x]] Comment the program with limitations of variables. (N)
    [[ ]] Keep the documentation minimal and concise. (C)

### Backup

    {{0-1}}
Backup needs to be prepared by well-structured and named data. When naming files and folders, you should adhere to the following standards:

    {{0-1}}
- Give comprehensive names
- Use uniform schemes
- Develop logical structure
- Include date in the following form: YYYYMMDD
- Avoid spaces and special characters


{{0-1}}| DO   | DON'T   |
| :--------- | :--------- |
| 20230312_h2oSample1      | BDD extract_edited colored.jpg |
| 20230315\_location5\_processed     | original.jpg|
| 2018_weatherlogfiles     | table1_john(copy)  |

{{0-1}} Source: inspired by [Biernacka et al (2020)](https://doi.org/10.5281/zenodo.4071471): p. 31.

    --{{0}}--
You should develop a backup policy early on in your project, since later down the road it is very hard to re-structure established processes.

    {{1-2}}
A handy rule is the 3-2-1 rule:

    {{1-2}}
![backup](img/Backupregel_CCBY4.jpg "I. Lang/Bearbeitung E. Böker: 3-2-1 Backupregel. Edited by A. Ahrens: Translation. Licensed under [CC-BY 4.0](https://creativecommons.org/licenses/by/4.0/deed.en). Source: https://forschungsdaten.info/")

    --{{1}}--
The 3 2 1 rule states that you are to create at least three copies of your data, secure them on two different kinds of storage medium and make sure that one of those mediums is located off-site. This way, your data is protected from natural disaster, which will most likely only hit one location at a time, against accidental deletion and against deterioration of one kind of storage medium. For example, CDs have quite a long lifespan but CD drives as a reading device have become increasingly scarce.

    {{1-2}}
> __Exercise__:
>
> Which backup solutions does your institution offer? If they do not meet your requirements, calculate additional costs in order to include them in your project proposal.
 <br>


### Archiving

    --{{0}}--
Archiving refers to the process of creating backups of selected data and storing it for long-term retention. It involves preserving important information, such as __final__ versions of documents or records, in a secure and accessible manner.

    {{0-1}}
When archiving data, it is crucial to ensure its integrity. This means that the data remains unchanged and tamper-proof during the archival process and throughout its storage. Techniques such as checksums or digital signatures can be used to verify the integrity of archived data, providing assurance that it has not been altered or corrupted. An essential aspect of archiving is the ability to search and retrieve archived data efficiently. Implementing effective indexing, metadata tagging, and search capabilities enables users to locate and retrieve the required data without having to sift through vast amounts of archived content manually.

    {{0-1}}
There are various commercial providers for backup and archiving solutions. Consider the following questions before choosing one:

    {{0-1}}
- Does it carry a seal for trustworthy long-term archives (e.g. [CoreTrustSeal](https://www.coretrustseal.org/), [nestor seal](https://www.langzeitarchivierung.de/Webs/nestor/EN/Zertifizierung/nestor_Siegel/nestor_siegel_node.html), [DIN 31644](https://www.din.de/de/mitwirken/normenausschuesse/nid/veroeffentlichungen/wdc-beuth:din21:147058907))?
- Does it fulfill your technical requirements?
- Can you cover the expenses?
- Is the data readily available to you?
- Does the service provider guarantee long-term storage?

    {{1}}
__It's Quiz Time__

    {{1}}
1. What are some risks that can lead to data loss?

    {{1}}
    [[x]] Technical defects, catastrophes, theft, oblivion (A)
    [[x]] Software updates, power outages, human error and viruses (G)
    [[x]] Natural disasters, software malfunctions, hardware upgrades (E)
    [[x]] Data corruption, cyber attacks, accidental deletion, system crashes (M)

    {{1}}
2. Which of the following is NOT a strategy for data protection?

    {{1}}
    [[ ]] Storage on university servers with automatic regular backup. (B)
    [[ ]] Backup of important files in at least three copies on spatially separated storage media. (D)
    [[ ]] Regularly backing up data and testing data recovery (K)
    [[x]] Deleting unnecessary files to save storage space (E)

    {{1}}
3.	What are some physical protection measures for data?

    {{1}}
    [[ ]] FileVault, Bitlocker, dm-crypt (T)
    [[ ]] Password protection, two-factor authentication, role assignment (I)
    [[x]] Lockable rooms, safes, data trustees (N)
    [[ ]] Regular data backups, firewall protection, antivirus software (U)

    {{1}}
4.	Why is secure data handling important?

    {{1}}
    [[x]] To prevent accidental data deletion (T)
    [[x]] To protect against data theft and misuse (P)
    [[ ]] To increase data storage capacity (W)
    [[ ]] To improve system performance and speed (A)

    {{1}}
5. What is the recommended strategy for backup?

    {{1}}
    [[ ]] At least two copies of a file on two different media, one of which is decentralized (W)
    [[ ]] At least three copies of a file on three different media, one of which is decentralized (C)
    [[x]] At least three copies of a file on two different media, one of which is decentralized (L)
    [[ ]] At least two copies of a file on three different media, one of which is decentralized (M)

    {{1}}
6.	What is the difference between backup and archiving?

    {{1}}
    [[ ]]Backup is the storage of selected data for long-term storage, while archiving is the automatic backup of all data. (S)
    [[ ]]Backup involves making multiple copies of data, while archiving involves storing final versions only. (R)
    [[ ]] Backup is the protection against data theft, while archiving is the prevention of data misuse. (U)
    [[x]] Backup is the (semi)automatic backup of all data, while archiving is the backup of selected data for long-term storage. (A)


## Metadata

    --{{0}}--
Well-structured metadata are of high value for re-users. Therefore, all four of the FAIR criteria stress their importance.

    {{0-1}}
Metadata in research contain structural information on research results such as datasets or code. There are different types of metadata with varying functions.

    {{0-1}}
> __Exercise:__
> 
> Enter the correct term for each metadata type.
>
> __descriptive  - administrative - bibliographic - process__

    {{0-1}}
| Type                    | Content    | Function   |
| :---------------------- | :--------- | :--------- |
| [[bibliographic  ]] metadata  | title, author, description, keywords    | make data findable and thematically fitting |
| [[administrative  ]] metadata | data types, location, access rights, licenses     | administration, long-term preservation  |
| [[process  ]] metadata        | methods, tools, analysis steps    | reproducibility, traceability    |
| [[descriptive  ]] metadata    | additional information on content, scope and data genesis    | close information gaps     |

    {{1}}
__Choosing the right standard__

    --{{1}}--
Bibliographic and administrative metadata can be standardized cross-disciplinary, while information on process details or content are often structured and described in a way highly specific to the respective field. Nevertheless, they are often crucial for findability and traceability of research data. Therefore, some disciplines have developed their own metadata standards.

    {{1-2}}
You can find a list of existing standards in the [RDA's Metadata Standards Catalog](https://rdamsc.bath.ac.uk/), under [FairSharing.org](https://fairsharing.org/search?fairsharingRegistry=Standard) or at the [Digital Curation Centre (DDC))](https://www.dcc.ac.uk/).

    {{1-2}}
- [DOIs (digital object identifiers)](https://www.doi.org/): This standard defines which information is required to be provided with a dataset (e.g. author, title), which is recommended (e.g. discipline, description) and which are optional (e.g. funding, licenses). Data are published as .xml. 

- [PREMIS](https://www.loc.gov/standards/premis/) is a standard for administrative metadata in longterm storage, describing relationships of contributors and rights. 

- [METS (Metadata Encoding & Transmission Standard)](http://www.loc.gov/standards/mets/) is a container standard specifying a structure of seven sections: header, descriptive metadata, administrative details, file section, structural map, structural links and behavior. 

    
{{2}}__Metadata Plan__

     {{2-3}}
| Type   | Function   |  Level of detail (low-very high)  | Effort required|
| :--------- | :--------- |  :--------- |:-----|
| simple .xml-file    | defines, in which format each information is to be given   |  [[low  ]]  | low, can be implemented for personal use|
| Vocabulary   | list of standardized names, preventing spelling mistakes    |  [[low ]]    |can already be useful in study groups|
| Taxonomy/Thesaurus |defines acronyms, synonyms, sub and umbrella terms    |  [[high  ]]   |requires regular review|
| Ontology    | model of characteristics and relationships between variables and concepts   | [[very high  ]]   | use community-developed templates |

    {{2-3}}
The Open Energy Platform offers an ontology that is under constant development. You can find an overview of other existing terminologies in the [Basic Register of Thesauri, Ontologies and Classifications BARTOC](https://bartoc.org/). Finally - whenever possible, use templates and automatization to facilitate your processes. 

    {{3}}
> __DMP Task__:
>
> 1.  Which information is necessary for outsiders to understand and reuse your datasets? What are possible keywords or criteria for filtering? 
>
>2. Which standards, ontologies or classifications will be used to describe data and context?
>
>3. How are the data structured? How are the individual components related?
>
>4. Are you planning to assign persistent identifiers (PIDs) for the datasets?
>
>5. Describe costs related to metadata and PID assignment.
>
>6. Describe other information on generation, analysis and processing of the data.

    {{3}}
Source: [forschungsdaten.info](https://forschungsdaten.info/themen/beschreiben-und-dokumentieren/metadaten-und-metadatenstandards/), translated by A. Ahrens, licensed under [CC-BY 4.0](https://creativecommons.org/licenses/by/4.0/deed.en).


### Repositories

    {{0-1}}
As a last step, you need to decide which data should be permanently archived. As we discussed in [Section "Simulation"](#software-and-simulation), you should carefully decide which data to archive in a repository and which to discard. 

    {{0-1}}
The following questions can lead you in the decision process:

     {{0-1}}
- Are the data the foundation of an article?
- Can the data be reproduced with reasonable effort?
- Is reuse likely?
- How high is the data quality?
- Is the dataset unique?
- How much storage volume is needed? 

    --{{0}}--
Choosing the right repository is often regulated by your institution or funding agency. In-house repositories might be mandatory for research data and you should find out which policies apply to you and your project.

    {{0-1}}
If you are free to choose a repository, you should use one that is common for your field or discpline. If you are unsure, go to the [Registry of Research Data Repositories (r3data)](https://www.re3data.org/), where a wide range of platforms are listed.

<br>

    --{{0}}--
If your license terms allow, you may upload your data on multiple platforms. Make sure to use PIDs and cross-reference to link the data to your published article. 

    {{1}}
__Open Energy Platform__

    {{1-2}}
For energy-related topics, we suggest the [Open Energy Platform](https://openenergy-platform.org/). This platform helps you to apply structure or even a thorough ontology, and provides tutorials in order to prevent confusion or mistakes.

{{1-2}}![oep](img/OEP.png "The Open Energy Platform. Licensed under [CC-BY 4.0](https://creativecommons.org/licenses/by/4.0/deed.en). Source: https://openenergy-platform.org/")

    {{1-2}} 
Features of the Open Energy Platform:

    {{1-2}}
- Upload via GitHub
- Data comparison with other projects
- Take part in developing a domain ontology for energy system sciences
- Data Review Service 
    
{{1-2}} Please visit https://openenergy-platform.org/ for a detailed description of the upload and review process.

     {{1-2}}
>**Exercise**: 
>
> Choose a repository for your data and create an account.

    {{2-3}}
**It`s Quiz Time!**

    {{2-3}}
1. What factors should you consider when deciding which data to permanently archive?

    {{2-3}}
    [[ ]] The data's foundation in an article and its reproducibility. (Y)
    [[ ]] The data's uniqueness and storage volume needed. (H)
    [[ ]] The data's potential for reuse and its quality. (W)
    [[x]] All of the above. (N)

2. How can you determine which repository to choose for archiving your data?

    {{2-3}}
    [[ ]] By following the regulations set by your institution or funding agency. (E)
    [[ ]] By selecting a repository that is common in your field or discipline. (T)
    [[ ]] By using the Registry of Research Data Repositories (r3data) for guidance. (U)
    [[x]] All of the above. (N)

3. What is the benefit of using PIDs and cross-referencing when uploading data to multiple platforms?

    {{2-3}}
    [[ ]] It ensures the data is securely stored in multiple locations. (V)
    [[ ]] It allows for easy access and retrieval of the data. (I)
    [[x]] It helps to link the data to your published article. (E)
    [[ ]] It prevents unauthorized access to the data. (L)

4. What is one of the features of the Open Energy Platform?

    {{2-3}}
    [[ ]] Data upload via GitHub. (O)
    [[ ]] Data comparison with other projects. (F)
    [[ ]] Development of a domain ontology for energy system sciences. (A)
    [[x]] All of the above. (R)

5. What service does the Open Energy Platform provide to prevent confusion or mistakes?

    {{2-3}}
    [[x]] Data Review Service (S)
    [[ ]] Data Validation Service (U)
    [[ ]] Data Cleaning Service (K)
    [[ ]] Data Archiving Service (N)

    
{{3-4}}>**DMP Task**: 
>
> Look through your DMP to find open questions that you have not covered so far and fill any gaps you can find.

    {{4}}
__Congratulations!__

    --{{4}}--
Congratulations! You have successfully finished the course and set up your first DMP-prototype! By the way - did you find all clues and solve all puzzles?

    {{4}}
> __Final:__
>
> Fill in the letters of the quizzes to spell out the solution: 
>
>[[WORLDS BEST DATA MANAGEMENT PLANNERS]]
<script>
let input = "@input".trim().toLowerCase()

input == "worlds best data management planners" || input == "worldsbestdatamanagementplanners"
</script>

## Sources 

* Biernacka, Katarzyna; Maik Bierwirth; Petra Buchholz, Dominika Dolzycka; Kerstin Helbig; Janna Neumann; Carolin Odebrecht; Cord Wiljes and Ulrike Wuttke:
  Train-the-Trainer Concept on Research Data Management.
  Version 3.0.
  Berlin, 2020.
  https://doi.org/10.5281/zenodo.4071471

* GO FAIR International Support and Coordination Office (2023): FAIR Guiding Principles:
  https://www.go-fair.org/

* Friedrich-Alexander-Universität - Universitätsbibliothek (2023): Advantages of Research Data Management.
    https://ub.fau.de/en/research/data-and-software-in-research/advantages-of-research-data-management/

* Mullendore GL, Mayernik MS and Schuster DC (2021): 
    Open Science Expectations for Simulation-Based Research. 
    Front. Clim. 3:763420. https://doi.org/10.3389/fclim.2021.763420

* Maxi Kindling, Peter Schirmbacher, Elena Simukovic:
  Forschungsdatenmanagement an Hochschulen:
  das Beispiel der Humboldt-Universität zu Berlin.
  LIBREAS.
  Library Ideas, 23 (2013).
  https://doi.org/10.18452/9041 

* Universität Konstanz (2023): Informationsplattform forschungsdaten.info. 
    https://forschungsdaten.info/

* University of Pittsburgh - Library Service (2023): Guide to Research Data Management
    https://pitt.libguides.com/managedata

* University of St. Andrews (2023): Benefits of good data management. 
    https://www.st-andrews.ac.uk/research/support/open-research/research-data-management/working-with-data/benefits-of-good-data-management/


![CC BY 4.0](https://i.creativecommons.org/l/by/4.0/88x31.png) This work is licensed under a [Creative Commons Attribution 4.0 International License](http://creativecommons.org/licenses/by/4.0/). 


