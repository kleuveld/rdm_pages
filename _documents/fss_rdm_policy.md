---
title: VU FSW guidelines for data management
subtitle: First Draft
date: 22-08-2022
---

<!---
author: Koen Leuveld
compile with Pandoc
File history can be found in the git repo: https://github.com/kleuveld/rdm_pages
-->

**Note on this draft version**: This is a draft version intended to collect feedback, which can be sent to k.leuveld@vu.nl. Currently all documents are hosted on [GitHub][rdm-pages], which may cause some layout issues in some of the linked document (e.g. the policy comparisons); once finalized, all documents will be hosted on the VU website removing these problems.

# Introduction

There are many different regulations, codes of conduct and guidelines that apply to the storage of research data which aim to ensure that research is transparent and/or protect the rights of respondents and other stakeholders. The purpose of these guidelines is to boil down these various regulations into one cohesive set of procedures that ensure  maximum compliance. The list below contains the regulations that these guidelines are based on. Since there are often conflicts between the regulations, the list includes a comparison be between each item and these guidelines, so that any deviation from the regulation is made explicit.

- [General Data Protection Regulation (GDPR)][gdpr] (GDPR is too large to include a point-by-point comparison here)
- [VU central RDM policy][vu-rdm-policy] ([Comparison][fss-vu])
- [Guideline for the archiving of academic research for faculties of behavioural and social sciences in the Netherlands][dsw-guidelines] (Public link not available yet, [Comparison][fss-dsw])
- [Netherlands Code of Conduct for Research Integrity , Standards for good research practices][nlcoc] ([Comparison][fss-coc])
- National Codes of conduct for relevant disciplines:
	- [Guidelines for Anthropological Research: Data Management, Ethics and Integrity][ABV-guidelines] ([Comparison][fss-abv])
	- [Beroepscode Nederlandse Sociologische Vereniging ][nsv-guidelines] ([Comparison][fss-nsv])
- The [FAIR principles][fairprinciples] ([Comparison][fss-fair]).


# To whom do these guidelines apply?

These guidelines apply to all faculty staff members who conduct research in the context of a temporary or permanent employment contract, all PhD candidates who conduct research under the supervision of a professor, and all research master’s students. The guidelines do not apply to bachelor’s and one-year master’s students, unless their research results in an academic publication. Research conducted by bachelor’s and one-year master’s students falls under the formal responsibility of their supervisors. 

# General Procedures

## Before

- Researchers follow the [ethics review procedure][rerc] of the Research Ethics Review Committee (RERC).
- Researchers write a Data Management plan (DMP), using a template of their funder or the template provided by the VU library[^templates]. The researcher makes sure that the DMP is stored in such a way that they can easily provide an up-to-date version to their department head at any moment.
- Researchers ensure that all planned activities with personal data comply with GDPR. In particular:
	- They take appropriate technical and organization measures to secure data. Because of the wide variety of data used in the faculty, there is not one answer as to what measures are appropriate. Researchers will discuss the measures they take with colleagues, department heads, with the [RDM support desk][rdmsupport] and/or the data steward.
	- They ensure that all personal data is processed with full consent of all data subjects. If consent cannot be obtained, the researcher ensures that there is another legal ground for processing the data. The faculty data steward can assist with this.
	- They ensure that if personal data is handled by third parties, the proper agreements are in place to do this securely, for example Data Processing Agreements. The faculty data steward can assist with this. 
	- The activities are entered in the VU's central data processing registry. Currently, DMPs created in [DMP Online][dmponline] are linked automatically to this registry.
- In research with external partners, researchers make clear written agreements about research integrity and related matters such as intellectual property rights.


[^templates]: Currently, all templates are available through [https://dmponline.vu.nl](https://dmponline.vu.nl)

## During

- Researchers keep their DMP up to date.
- Researchers ensure that their data is stored in such a way that it can later be archived in accordance with these guidelines without excessive efforts. Examples of this are:
	- Ensuring data is well-organized;
	- Data is stored in the same place as vital documentation. Depending on the discipline of the researcher this can include interviewer guides, questionnaires, topic lists, sampling information, power calculations, etc.
	- Making sure the data is accompanied by a basic "Readme File" containing basic metadata such as an explanation of the purpose of the data, who is responsible for collecting it, and how the folder is organized, etc.
- Researchers ensure that data is stored on suitable storage infrastructure provided by the VU. If this is not possible, researchers ensure that the chosen infrastructure can reliably, traceably and
securely store the research data throughout the research life cycle. The data steward will help in this assessment.
- Researchers take appropriate technical and organizational measures to secure any personal data. Examples:
	- They store directly identifiable data (see definitions, below) separately from other data, either by storing it on a different server or device, or through encryption.
	- They do not store directly identifiable data longer than needed. However, it may be important to the integrity of the data and to demonstrate data provenance not to edit raw data files. Researchers are expected to decide what data to destroy what data to keep, and provide reasoning for their choices in their DMP. 

## After

Researchers ensure that the underlying data for each published empirical study (article, volume, book chapter, PhD thesis chapter, Research Master’s thesis, consultable internal report, etc.) is archived according to the following:

- **What**: all data than can be reasonably deemed necessary to verify the findings of the research. This includes the raw data (or a link to it, if secondary data was used), the data that was analysed and a description of all modifications to obtain the analysed data from the raw data (or the computer code used to perform these modifications) and full documentation of all steps involved in acquiring, processing and analysing the data. This should be organized in such a way that a relevant colleague can use the data wihtout asking many questions. [Detailed guidelines on what to archive can be found here][fss-archiving].
- **When**: the data will be archived no later than one month after the publication date, and be available until at least 10 years after the publication date. If this is not possible, a justification for deviating from this should be provided in the DMP.
- **Where**: a secure and reliable location that is accessible for verification (see the section on verification below), and that provides a persistent identifier. The archiving options provided by the VU satisfy these criteria. FSS follows the ERC's approach "as open as possible, as closed as necessary", and hence does not recommend researchers to publish personal data[^EUexceptions]. Should researchers want to publish such data, they should ensure that they meet all legal and ethical requirements to do so, consulting with the faculty data steward if needed. Public data is always accompanied by a license, and information about the informed consent procedure (if applicable). The decision to publish data or not should be motivated in the DMP.
- **Who**: the first author of the publication is responsible for archiving the data. Second or later authors must know that the data have been carefully stored and how this has been arranged. This is particularly important if the first author does not work at FSS. For PhD candidates and research master’s students, the primary supervisor or the day-today supervisor respectively are responsible for archiving, but can delegate the work to the PhD candidate.

Furthermore:

- Where possible, researcher include in their published empirical studies should a data statement containing the persistent identifier of the data, the repository where the data is archived, and instructions on how this data can be accessed and for what reasons. For sensitive data that is not published and that can only be accessed for verification purposes, a persistent email address should be provided where questions regarding the data can be directed.
- Researcher ensure that all datasets that they produce are registered on the VU's Research Portal, including rich metadata describing the data, and the persistent identifier.

[^EUexceptions]: Valid grounds not to publish data include Intellectual Property Rights, personal data protection and confidentiality, security concerns, as well as global economic competitiveness, and other legitimate interests. These exceptions can be found [here][eucouncilopendata] (paragraph 14)

# Special procedures

## Data verification

If a request to verify sensitive (non-public) data is received, the Faculty Board will decide how to act on the request. For this, the board will balance the need for confidentiality and the interests of transparency. If it is decided that the data needs to be reviewed, the Faculty Board will then decide who will access the data while ensuring confidentiality of the data and work with VU IT and the Data Steward to ensure that this access is possible.

## End of employment

If a researcher leaves the VU, the department head will work with the researcher to ensure:

- that the data for any ongoing projects is properly stored according to these guidelines;
- that the data for any pending publications is properly archived according to these guidelines;
- that the researcher doesn't lose access to data they need for their further career, if such access can be reasonably organized, for example through the signing of a data transfer agreement. 


## Performance and appraisal reviews

Adherence to the guideline will be discussed in performance and appraisal interviews. Formal final responsibility lies with the dean. 


# Abbreviations
<!---
These tables may require pandoc
-->

-------------	-----------------------------------------------
DMP 			Data Management Plan

RDM 			Research Data Management

FSS				Faculty of Social Sciences

VU				Vrije Universiteit Amsterdam

GDPR 			General Data Protection Regulation

RERC 			Research Ethics Review Committee
-------------	-----------------------------------------------

# Definitions:

+----------------+------------------------------------------------------------------+
| Personal Data  | All data that can be directly or indirectly tied to              |
|                | a living person.                                                 |
|                |                                                                  |
+----------------+------------------------------------------------------------------+
| Identification | Two types of identification are possible, based on research      |
|                | data:                                                            |
|                |                                                                  |
|                | - Direct: the data includes information that directly            |
|                | reveal the identify of a respondent, such as name address,       |
|                | phone number date of birth, etc.                                 |
|                | - Indirect: the data can be combined with other information      |
|                | to reveal the identity of a respondent. Indirect                 |
|                | identification is extremely difficult to prevent, and            |
|                | possible with most FSS Data sets.                                |
+----------------+------------------------------------------------------------------+
|                |                                                                  |
| Archiving      | Storing data for verification purposes, usually not              |
|                | publicly available                                               |
+----------------+------------------------------------------------------------------+
| Registration   | Entering the details of a data set (but not the data set itself) |
|                | on a public page, such as PURE.                                  |
|                |                                                                  |
|                |                                                                  |
+----------------+------------------------------------------------------------------+

<!---
Links
-->

[rdm-pages]: https://github.com/kleuveld/rdm_pages/blob/fss_rdm_policy/_documents/

<!---
VU Information
-->


[rerc]: https://vu.nl/en/employee/social-sciences-getting-started/research-ethics-review-fss
[self-check]: https://vuletteren.eu.qualtrics.com/jfe/form/SV_6hCj2czIWzboW6V
[rdmsupport]: mailto:RDM@vu.nl 
[fss-archiving]: https://github.com/kleuveld/rdm_pages/blob/fss_rdm_policy/_documents/fss_archiving_guidelines.md
[dmponline]: https://dmponline.vu.nl

<!---
Rules, regulations and guidelines
-->

[gdpr]: https://gdpr-info.eu
[dsw-guidelines]: https://vunl-my.sharepoint.com/:b:/g/personal/k_leuveld_vu_nl/UjMpC_8Yy5HsIkhFZ8SMecB9mET_yO0xgBh8rtbdjvw3g?e=R7Pawx
[erc-guidelines]: https://ec.europa.eu/research/participants/data/ref/h2020/other/hi/oa-pilot/h2020-hi-erc-oa-guide_en.pdf
[vu-rdm-policy]: https://libguides.vu.nl/ld.php?content_id=32045526
[nlcoc]: https://doi.org/10.17026/dans-2cj-nvwu
[eucouncilopendata]: https://data.consilium.europa.eu/doc/document/ST-9526-2016-INIT/en/pdf
[fairprinciples]: https://www.go-fair.org/fair-principles/
[ABV-guidelines]: https://antropologen.nl/app/uploads/2019/01/guidelines-for-anthropological-research.pdf
[NSV-guidelines]: https://www.nsv-sociologie.nl/?page_id=17


<!---
Policy comparions
-->

[fss-vu]: https://github.com/kleuveld/rdm_pages/blob/fss_rdm_policy/_documents/rdm_policy_comparison_FSW-VU.md
[fss-dsw]: https://github.com/kleuveld/rdm_pages/blob/fss_rdm_policy/_documents/rdm_policy_comparison_FSW-DSW.md
[fss-coc]: https://github.com/kleuveld/rdm_pages/blob/fss_rdm_policy/_documents/rdm_policy_comparison_FSW-CoC.md
[fss-fair]: https://github.com/kleuveld/rdm_pages/blob/fss_rdm_policy/_documents/rdm_policy_comparison_FSW-FAIR.md
[fss-abv]: https://github.com/kleuveld/rdm_pages/blob/fss_rdm_policy/_documents/rdm_policy_comparison_FSW-ABV.md
[fss-nsv]: https://github.com/kleuveld/rdm_pages/blob/fss_rdm_policy/_documents/rdm_policy_comparison_FSW-ABV.md