
<!-- 
author:   C3L
email:    antje.ahrens@uol.de
Version:  1.0
language: en
license:  http://creativecommons.org/licenses/by/4.0/

mode:     Presentation|Slides|Textbook

narrator: US English Female

icon:   img/efzn-logo.png

script: https://ajax.googleapis.com/ajax/libs/jquery/1.11.3/jquery.min.js
        https://cdn.jsdelivr.net/chartist.js/latest/chartist.min.js

link:   https://cdn.jsdelivr.net/chartist.js/latest/chartist.min.css

-->
[cc-by]: http://creativecommons.org/licenses/by/4.0/
[cc-by-image]: https://i.creativecommons.org/l/by/4.0/88x31.png

# Research Data Management

![Logo-Block](img/Logoblock.png)

## <a name="intro"></a> Introduction

Welcome to "Research Data Management in the Energy Sector"! This course teaches all skills necessary to understand the principles and motivation behind Research Data Management (RDM) and enable you to implement RDM in your work and research group.

The course focuses on applicability in the energy sector.

There are three possible ways to work with this course: 
1. Do you want to gain a thorough understanding of RDM? Follow the course outline described in the following graph. When you complete the course, you will have established a basic Data Management Plan for a project of your choice that you can build upon and adapt. 
2. Are you looking for a challenge? Answer the questions at the end of each chapter to find the solution to our RDM-puzzle.
3. Do you already have some knowledge of RDM? Great! Choose individual chapters that are of interest for your field of work by clicking on the plus-signs.

<iframe src="https://wp.uni-oldenburg.de/innovative-hochschule-jade-oldenburg-wise20182019/wp-admin/admin-ajax.php?action=h5p_embed&id=19" width="660" height="1292" frameborder="0" allowfullscreen="allowfullscreen" title="Research Data Management in the Energy Sector"></iframe><script src="https://wp.uni-oldenburg.de/innovative-hochschule-jade-oldenburg-wise20182019/wp-content/plugins/h5p/h5p-php-library/js/h5p-resizer.js" charset="UTF-8"></script>

### LiaScript 
A quick word on the course format. The course is written in [Markdown](https://de.wikipedia.org/wiki/Markdown) and implemented in [LiaScript](https://liascript.github.io/). 

In the upper right corner, you can switch between textbook mode, presentation mode and slides. You may choose to have the course read aloud to you by clicking on the symbol on the bottom of the page in presentation mode. If you want to adapt the course for your own use, you may do so by going on [GitHub](https://github.com/FlourBerry/EFZN_RDM) and opening a branch of your own or downloading individual files. 

[![License: CC BY 4.0](https://licensebuttons.net/l/by/4.0/80x15.png)](https://creativecommons.org/licenses/by/4.0/)

---


## <a name="rdm"></a> What is Research Data Management?

### Case Study 

{{1}}
In early 2020, the COVID-19 disease, caused by the coronavirus SARS-CoV2, broke out globally, which led to the closure of many shops and businesses for quarantine reasons. The result, especially in the USA, was a large number of unemployed people who urgently needed money for their next rent payment, food or other expenses. As a consequence, the government decided to set up a relief package for anyone who registers as unemployed - but why didn't the money get to the people?

{{1}}
The reason for this was the overload of critical systems on which COBOL is still running. COBOL is a programming language that was developed in the late 1950s to control commercial applications. From today's perspective, the programming language is very outdated and no longer taught in the training of programmers. That is why there was no personnel to take care of the systems when they collapsed. Unfortunately, many applications with the outdated programming language are still running in the business sector. 

{{1}}
Source: [FDM Thüringen: Scarytales, Licensed under CC-BY 4.0](https://forschungsdaten-thueringen.de/fdm-scarytales/articles/ueberblick.html)

{{1}}
>__Exercise:__ Suggest two possible process changes that could have prevented the outcome of the scenario:

{{2}}
> There are several solutions possible: Existing systems should be questioned, since requirements can change and established habits can lead to problems from today's perspective. For example, at some point data might no longer be able to be called up or might exist in formats that are increasingly difficult to be processed. A thorough documentation of the programs might also help in some cases to rebuild them in other languages. For timely relief, the administration called out to retired COBOL programmers to work on the issues.

{{3}}
While maybe not as critical for society at large, scientists can face similar problem when trying to access old data or programs that were written for other purposes but are know needed for the current tasks: Data are insufficiently labeled, have been overwritten, commercial computer programs have been discontinued or process details have not been recorded.

{{3}}
**Research Data Management** (RDM) aims to break this dynamic by ensuring a sustainable and coherent strategy for all data types throughout the research process, enabling researchers to store, access and re-use their own work effectively and safely and opening their findings worldwide to improve on cross-disciplinary collaboration, monitoring and replication.

{{3}}
RDM includes all activities associated with

* processing
* storage
* preserving and
* publication of research data.

### The Research Data Lifecycle

![Lifecycle](img/DataLifecycle.png "The Research Data Lifecycle")

The Research Data Lifecycle. Original source: [UK Data Service](https://ukdataservice.ac.uk/learning-hub/research-data-management/), recreated by Antje Ahrens. Licensed under [CC-BY-4.0](https://creativecommons.org/licenses/by/4.0/deed.de)

<!-- --{{1}}--
The "Research Data Lifecycle" describes a cyclic process of data generation and management. First, data is created, then processed. The next step is analyzing data, followed by preserving the results. Now, it is time to give access to the data. Ideally, the cycle closes at this point: Data is being re-used and new, well-documented data is being created.
-->

{{2}}
>**Exercise**: 
> Try to look at each step of the cycle with your data in mind: 
>
> - Which tools or software do you use at each step? 
>
> - Which infrastructure is needed?
>
> - How sensitive is the data at this point?
>
> - How well is the data protected against data loss? Where are possible flaws where data could get lost?
>
> - Does the cycle "close"? Which repositories or platforms do you use to store your results?


### Benefits of RDM

---

## <a name="fair"></a> Make it FAIR

### Open Science
--{{1}}--
Open Science strives to to make scientific research and its dissemination **accessible to all levels of society**. It encompasses practices such as publishing open research, campaigning for open access, encouraging scientists to practice **open-notebook science** (such as openly sharing data and code), broader dissemination and engagement in science and generally making it easier to publish, access and communicate scientific knowledge. 

Source: https://en.wikipedia.org/wiki/Open_science 

<!-- --{{2}}--
Research Question: Is there an Open Science or Research Data Policy at your institution?
What is its scope? What is regulated and how? If not: Would you like to have a Research Data Policy? What content should it have?
-->
{{2}}
> **Research Question**:
> 
>Is there an Open Science or Research Data Policy at your institution?
> 
> What is its scope? What is regulated and how?
>
> If not: 
> Would you like to have a Research Data Policy?
> What content should it have?

For our 

### FAIR Guiding Principles

--{{1}}--
"As open as possible, as closed as necessary" 
This is the main idea behind the FAIR principles. The acronym stands for

* Findable
* Accessible
* Interoperable
* Re-Usable

{{2}}
> **Exercise**: Look closely at the graph to identify which measures especially apply to your area of work and data types you are using.

{{2}}![FAIR Guiding Principles](img/FAIR.png "Source: https://www.go-fair.org/fair-principles/")

<!-- --{{2}}--
The FAIR Guiding Principles in detail:
1. To make data findable, you should assign unique and persistent identifiers, that stay active. Also, provide extensive and useful metadata - avoid acronyms, for example. You should also use common repositories. You can find a list on Re3data.com. For the energy sector, we recommend the Open Energy Platform.
2. Accessible data use stanrdized communications protocol such as HTTP or FTP. Make sure anyone with a computer and internet connection can access at least the metadata. Your (meta)data should be long-term accessible. For sensitive data, you may use authentification routines.
3. In order to achieve interoperability, use a formal, accessible, shared and boradly applicable language. Also, use tools and software that are FAIR themselves. Cross-reference your data and metadata.
4. Re-usable data is described by as much information as possible, such as process details. Clearly describe data usage licenses. Be transparent about data provenance and know and meet your own community's data standards.
-->

{{3}}
> **Quiz**: What can you do to make your data FAIRer?    
>
> [[X]] use Creative-Commons or GNU Licenses
> [[ ]] keep processing details undisclosed
> [[ ]] ensure access security 
> [[X]] create detailed Metadata    
> [[X]] ensure long-term accessibility in repositories


## <a name="dmp"></a> Data Management Plan

[^GhentUniversity]: Ghent University Data Stewards (2020): Knowledge clip: Data Management Plans (DMPs). Available at: https://www.youtube.com/watch?v=GRNsLTQGjCo. Licensed under [Attribution 4.0 International (CC BY 4.0)](https://creativecommons.org/licenses/by/4.0/deed.en)^

--{{1}}--
 The **Data Management Plan (DMP)** contains all information that describes and documents sufficiently the collection, processing, storage, archiving and publication of research data within a research project.  

>**Exercise**: Watch the following video and answer the questions.

!?[Ghent University Data Stewards (2020)](https://www.youtube.com/watch?v=GRNsLTQGjCo "Data Management Plans (DMPs) [^GhentUniversity]")
--> enter interactive h5p Video link with questions in it

--{{2}}--
Many public funding organizations require a DMP prior to granting funds for research projects, thus making DMPs an integral part of the scientific process, especially in data-intensive research fields such as the energy sector.

{{3}}
| Funder | Plan demanded? | Content | Updates? |
|:-------|:--------------------------|:--------|:---------------|
|Horizon Europe| Data Management Plan|see [Horizon Europe Online Manual](https://op.europa.eu/en/web/eu-law-and-publications/publication-detail/-/publication/9570017e-cd82-11eb-ac72-01aa75ed71a1)|Yes|
|[German Research Foundation (DFG)](https://www.dfg.de)     |Information on the handling of research data|[DFG Guidelines on the Handling of Research Data](https://www.dfg.de/en/research_funding/principles_dfg_funding/research_data/), Checklist|No|
|[German Ministry for Economic Affairs and Climate Action (BMWK)](https://www.bmwk.de/)| Research Data Exploitation Plan|scientific and economic potential, connectivity and transferability|once a year|
|[German Ministry of Education and Research (BMBF)](https://www.bmbf.de/bmbf/de/forschung/digitale-wirtschaft-und-gesellschaft/aktionsplan-forschungsdaten/aktionsplan-forschungsdaten_node.html)   |Plan sometimes required|Content depends on the respective programme||
|[German Ministry for Digital and Transport (BMDV)](https://bmdv.bund.de)|Research Data Exploitation Plan sometimes required |Content depends on the respective programme||


## <a name="tools"></a> Tools and Strategies

### Tools

--{{1}}--
You can create a DMP in a simple Excel-Sheet or use various format templates or tools.
In many tools, you can choose a set of questions that you want to have included in your DMP. Some are focused on data and data formats, other focus on the project structure. If you want to take a look at an example DMP, you can look [here](https://cloud.uol.de/f/7510018536).

<!-- --{{2}}--
DMP Task: Now it is time to start your DMP! Choose a tool and a set of questions that you want to work with and enter your basic project parameters:
1. Title and Research Question
2. Project Partners and Institutions
Depending on your settings, you can add other details required by the respective questionnaire. 

Congratulations! You have started your first DMP!
-->

> **DMP Task**:
> 
> Now it is time to start your DMP! Choose a **tool** and a set of **questions** that you want to work with and enter your basic project parameters:
>1. Title and Research Question
>2. Project Partners and Institutions
>
>Depending on your settings, you can add other details required by the respective questionnaire. 

Congratulations! You have started your first DMP!

### Legal Aspects
Licenses, informed consent, protection of personal data, access

You should start early to decide which license you would like to put 

---
### Data Types 
--{{1}}--
Depending on your field of expertise, there will be different data types relevant to your work. In your DMP, you can specify individual datasets and name their identifiers, file size, origin and so forth.
Simulations and software programmes are a special case. Here, not only the resulting datasets are of scientific value but also the programmes, algorithms and settings leading up to the data. ...
The data types you choose to publish have consequences for your Research Data Management in regard to the "Accessible", "Interoperable" and "Re-Usable" Criteria of the FAIR Guidelines.

--{{2}}--
**1. Accessible**  
--> Make sure that (meta)data are long-term accessible

The amount of memory space needed for long-term, save storage may vary greatly between data types. For example, if your reasearch data consist  of high-resolution images of potential wind turbine sites, memory space needed for backup and repositories will be much higher than a handful .csv files with projected power loads.

--{{2}}--
**2. Interoperable**
--> Use tools and software that are FAIR themselves
Try to remember the idea of "as open as possible, as closed as necessary.": Strive to choose, where possible, programs and data types that are open and FAIR. For example, do not describe your processing details in a .pdf file, but rather use a .txt-file that can be read and edited with various programs.

--{{2}}--
**3. Re-Usable**
--> know and meet community standards
As the expert in your own field, you are the one to decide here: which data types are most likely to be found, easily re-used and shared in your scientific community? If these are "closed", you could provide two files: one that adheres to the common standards and a more open alternative that promotes the idea of open science. 

<!-- --{{3}}--
Exercise: Make a list of the data types commonly used in your working group and their "FAIR value".
-->

> **Exercise:**
> 
> Make a list of the data types commonly used in your working group and their "FAIR value". Use the criteria in the table below.


| FAIR value|	Machine Readability	| Human Readability	| Long-time Stability|	Metadata   | Example|
| :--------- | :---------| :--------- | :--------- | :---------|:-----------|
|very good |with common open software	|yes and without special software	|normed standard	|completely preserved |  .csv|
|good	|with common and well-documented software	| compressed with standard procedures, but practically yes	|longterm or widely established	| technical details are provided| .xlsx|
|moderate	| proprietary standard format   | with open software (reliably?) convertible to higher class| 	relatively new format	| some important ones (e.g. units) are included | MATLAB file|
|bad	| self-developed reading software| no|	newly developed	| no information    | |

Source: translated and adapted from [forschungsdaten.info](https://forschungsdaten.info/themen/veroeffentlichen-und-archivieren/formate-erhalten/), [CC-BY 4.0](https://creativecommons.org/licenses/by/4.0/deed.en)


<!-- --{{3}}--
DMP Task: If you already know datasets that you will be (re-)using or producing, enter them in your DMP as thoroughly as you can at this point. 
If you do not know your datasets yet, enter one or two dummy datasets and follow the respective questionnaire to get an idea of the amount of detail required in the DMP.
-->

>**DMP Task**: 
>
> If you already know datasets that you will be (re-)using or producing, enter them in your DMP as thoroughly as you can at this point. 
>
> If you do not know your datasets yet, enter one or two "dummy" datasets and follow the respective questionnaire to get an idea of the amount of detail required in the DMP.


## <a name="Infrastructure"></a> Infrastructure


### Repositories

### Back-Up 

--> save your DMP and your data in multiple spaces

### Access 

---
## <a name="meta"></a> Metadata

---

## <a name="congrats"></a> Congratulations


Did you find all clues and solve all puzzles? Then you can enter the resulting letters in the box below to see if you are a DMP-Champion!

## <a name="sources"></a> Sources: 

* Maxi Kindling, Peter Schirmbacher, Elena Simukovic:
  Forschungsdatenmanagement an Hochschulen:
  das Beispiel der Humboldt-Universität zu Berlin.
  LIBREAS.
  Library Ideas, 23 (2013).
  https://doi.org/10.18452/9041

* Biernacka, Katarzyna; Maik Bierwirth; Petra Buchholz, Dominika Dolzycka; Kerstin Helbig; Janna Neumann; Carolin Odebrecht; Cord Wiljes and Ulrike Wuttke:
  Train-the-Trainer Concept on Research Data Management.
  Version 3.0.
  Berlin, 2020.
  https://doi.org/10.5281/zenodo.4071471

* FAIR Guiding Principles:
  https://www.go-fair.org/

* UK Data Service:
  https://ukdataservice.ac.uk/learning-hub/research-data-management/ 

 * https://forschungsdaten.info/praxis-kompakt/glossar/#c269829


[![CC BY 4.0][cc-by-image]][cc-by]  This work is licensed under a [Creative Commons Attribution 4.0 International License][cc-by]. 
