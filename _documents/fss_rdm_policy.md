---
title: VU FSS guidelines for data management
subtitle: Fourth Draft
date: 24-11-2022
---

<!---
author: Koen Leuveld
compile with Pandoc
File history can be found in the git repo: https://github.com/kleuveld/rdm_pages
-->

**Things to keep in mind when reading this draft version**: 

- For the most part, these guidelines are based on existing guidelines that already apply to our work, so the scope for substantive changes in these guidelines is limited. However, not everyhting is set in stone, for example: data should be verifiable, but how do we organize the verification? Department Heads are responsible for many RDM tasks, but how do we make sure they can do this in practice? Input is welcome on these and other procedures.
- Currently all documents are hosted on [GitHub][rdm-pages], which may cause layout issues in some of the linked documents (e.g. the policy comparisons); once finalized, all documents will be hosted on the VU website removing these problems.
- While these guidelines don't bring a lot of new things to the table, the expectation is that many colleagues will experience this as an additional burden. Part of this is because the old policies were poorly communicated with colleagues, who have little ownership in them. Advice on how to prevent that this time around is welcome. 

# Introduction

As a faculty committed to excellence in the quality of the research our staff and students undertake, it is essential to have guidelines on good practice in Research Data Management (RDM) as part of our framework to support the integrity of our research. These FSS guidelines serve both as a means of developing and supporting a culture of good practice in data management and demonstrating that we are committed to a culture and environment where high standards are encouraged and expected.

The purpose of these guidelines is to reduce work pressure by condensing the various, and often conflicting, regulations into one cohesive set of procedures that ensure maximum compliance. The list below contains the regulations that these guidelines are based on. Since there are often conflicts between the regulations, the list includes a comparison between each item and these guidelines, so that any deviation from the regulation is made explicit.

<!---
	Seda had nog wat interessants gevonden
-->
<!--
	EB: eScience Center: FAIR principles for research software

	https://www.esciencecenter.nl/news/fair-principles-for-research-software-released/
-->

- [General Data Protection Regulation (GDPR, 2018)][gdpr] (GDPR is too large to include a point-by-point comparison here.)
- [VU central RDM policy (2018)][vu-rdm-policy] ([Comparison][fss-vu])
- [Guideline for the archiving of academic research for faculties of behavioural and social sciences in the Netherlands (2022)][dsw-guidelines] (Public link not available yet, [Comparison][fss-dsw])
- [Netherlands Code of Conduct for Research Integrity , Standards for good research practices (2018)][nlcoc] ([Comparison][fss-coc])
- National Codes of conduct for relevant disciplines:
	- Anthropology: [Guidelines for Anthropological Research: Data Management, Ethics and Integrity (2019)][ABV-guidelines] ([Comparison][fss-abv])
	- Management Science and Business Administration: [Code of Ethics Academy of Management (undated)][aom-guidelines] ([Comparison][fss-aom])
	- Political Science: [Beroepscode Nederlandse kring voor Wetenschap der Politiek (2008)][nkwp-guidelines] ([Comparison][fss-nkwp])
	- Sociology: [Beroepscode Nederlandse Sociologische Vereniging (2002)][nsv-guidelines] ([Comparison][fss-nsv])

- The [FAIR principles (2016)][fairprinciples] ([Comparison][fss-fair]).

In this document, the following verbal forms are used:

- "shall", "are required to" and "must" indicate a requirement;
- "should" indicates a recommendation;
- "may" indicates a permission;
- "can" indicates a possibility or a capability


# To whom do these guidelines apply?

These guidelines apply to all faculty staff members who conduct research in the context of a temporary or permanent employment contract, all PhD candidates who conduct research under the supervision of a professor, and all research master’s students. The guidelines do not apply to bachelor’s and one-year master’s students, unless their research results in an academic publication. Research conducted by bachelor’s and one-year master’s students falls under the formal responsibility of their supervisors. 

# Stepping stones for good data management
<!--
	SO: I think that Researchers need to read the different guidelines before they start, otherwise they cannot make a strong plan. So maybe they need to be referred to also on this section and not afterwards…
-->
## Before
<!-- 
	Before the project starts? As preparation for the proposal, when it exists?
-->

- Researchers must follow the [ethics review procedure][rerc] of the Research Ethics Review Committee (RERC).
- Researchers must write a Data Management plan (DMP) using [https://dmponline.vu.nl](https://dmponline.vu.nl)), so that they can easily provide an up-to-date version to their department head at any moment.

<!--
	SO:
	- I don’t think it helps the Researcher to know that this is provided by the Library, what matters is that they have to fill in DMP Online. Also, if everyone has to fill DMP online, then the rest of the sentence is not necessary… this is already archived in a central place? 
	- I cannot see the template unless I open an account. Are these templates simple? I think the rule should be that for simple projects we should require a very simple DMP.
	- Who approves the plan? Only the Researcher? Or the HoD also has to approve? Then maybe they should be all archived in a central directory?
	- 
-->
- Researchers shall ensure that all planned activities with personal data comply with GDPR. In particular:
	- They must take appropriate technical and organization measures to secure data. Because of the wide variety of data used in the faculty, there is not one answer as to what measures are appropriate. Researchers should discuss the measures they take with colleagues, department heads, with the faculty data steward, privacy champion and/or the [RDM support desk][rdmsupport].
	<!-- SO: Data steward: connect to page -->
	- They should ensure that all personal data is processed with full consent of all data subjects. If consent cannot be obtained, the researcher must ensure that there is another legal ground for processing the data. A privacy champion can assist with this.
	- They shall ensure that if personal data is handled by third parties, the proper agreements are in place to do this securely, for example Data Processing Agreements. A privacy champion can assist with this.
	- They shall ensure that all data processing activities (collection, analysis, publishing, archiving, etc.) are entered in the VU's central data processing registry. Currently, DMPs created using the VU template in [DMP Online][dmponline] are linked automatically to this registry, meaning the researcher does not need to take additional action for this.
- Contracts and agreements relating to the commissioning, funding and conduct of research, including data sharing, intellectual property rights, collaboration and non-disclosure agreements must all be processed through IXA-GO to ensure the safeguarding of (the autonomy of) your research. Such contracts must be signed by those with the appropriate delegated authority to do so on behalf of the University. The signature process is a chain of responsibility that starts with the submission from the Researcher for approval of the Head of Department, before the final signature from the Managing Director of the faculty or a member of the Executive Committee of the University.


<!-- 
	Jac: All? Perhaps above 25k? This is related to service agreements on the 4hoek agenda as well. And what is the procedure, do researcers directly contaxt IXA-GO or do we start at faculty level first (f.i. Koen)?
	Marcel Ras: Hoe doe je dat? Formulier, contactpagina opnemen
	SO: IXA-GO: Link to page with contacts/ procedures.
-->


## During

<!--
	SO: During the project?
-->

<!-- 
	Add link to example readme
-->


- Researchers shall keep their DMP up to date.
- Researchers should ensure that their data is stored in such a way that it can later be archived in accordance with section 3.3 of these guidelines without excessive effort. This includes:
	- Ensuring data is well-organized (for more information, see the [FSS Guidelines on Data Organization][fss-guidelines-organization]);

<!-- This should be linked also to the “Before” phase, so that Researchers can better prepare the DMP? -->

	- Data is stored in the same place as vital documentation. Depending on the discipline of the researcher, this can include interviewer guides, questionnaires, topic lists, sampling information, power calculations, etc.
	- Making sure the data is accompanied by a basic "Readme File" containing basic metadata such as an explanation of the purpose of the data, who is responsible for collecting it, and how the folder is organized, etc.
- Researchers must ensure that data is reliably, traceably and securely stored throughout the research life cycle. The VU offers storage infrastructure that meets these requirements (see the [storage finder][storage-finder]). If project data needs to be stored elsewhere (for example with project partners), researchers must ensure that the storage solution chosen meets these requirements. The data steward will help in this assessment.
- Researchers must take appropriate technical and organizational measures to secure any personal data.
	- They can store directly identifiable data (see definitions, below) separately from other data, either by storing it on a different server or device, or through encryption.
	- They must not store directly identifiable data longer than needed. Note that it may be impossible to remove directly identifying data without editing the raw data, which would compromise data integrity and provenance. In such cases, the directly identifiable data may be stored as long as long as the rest of the raw data. Researchers are expected to decide what data to destroy what data to keep. Researchers should discuss the choices they make with colleagues, department heads, with the faculty data steward, privacy champion and/or the [RDM support desk][rdmsupport], and record these choices in their DMP. 

## After

### Archiving and Registration
Researchers must ensure that the underlying data for each published empirical study (article, volume, book chapter, PhD thesis chapter, Research Master’s thesis, consultable internal report, etc.) is archived according to the following:

- **What**: all data than can be reasonably deemed necessary to verify the findings of the research. This includes the raw data (or a link to it, if secondary data was used), the data that was analysed and a description of all modifications to obtain the analysed data from the raw data (or the computer code used to perform these modifications) and full documentation of all steps involved in acquiring, processing and analysing the data. [Detailed guidelines on what to archive can be found here][fss-guidelines-archiving].
- **When**: the data must be archived no later than one month after the publication date, and be available until at least 10 years after the publication date. If this is not possible, a justification for deviating from this should be provided in the DMP.
- **Where**: a secure and reliable location that is accessible for verification (see the section on verification below), and that provides a persistent identifier. The archiving options provided by the VU satisfy these criteria. If data needs to be archived elsewhere (for example with project partners), researchers must ensure that the storage solution chosen meets these requirements. FSS follows the ERC's approach "as open as possible, as closed as necessary". In practice, this means that public data is preferable, but that personal data does not need to be published[^EUexceptions]. Should researchers want to publish such data, they should ensure that they meet all legal and ethical requirements to do so, consulting with the faculty data steward if needed. Public data must always be accompanied by a license and, in case of personal data, information about the informed consent procedure. The decision to publish data or not should be explained in the DMP.
- **Who**: the first author of the publication is responsible for archiving the data. Second or later authors must know that the data have been carefully stored and how this has been arranged. This is particularly important if the first author does not work at FSS. For PhD candidates and research master’s students, the primary supervisor or the day-today supervisor respectively are responsible for archiving, but can delegate the work to the PhD candidate.

Furthermore:

- Researchers should include in their published empirical studies a data statement containing the repository where the data is archived, the persistent identifier of the data, and instructions on how this data can be accessed and for what reasons. For sensitive data that is not published and that can only be accessed for verification purposes, a persistent email address may be provided where questions regarding the data can be directed.
- Researchers should ensure that all datasets that they produce are registered on the VU's Research Portal, including sufficiently descriptive metadata, and the persistent identifier of the data set.

[^EUexceptions]: Valid grounds not to publish data include Intellectual Property Rights, personal data protection and confidentiality, security concerns, as well as global economic competitiveness, and other legitimate interests. These exceptions can be found [here][eucouncilopendata] (paragraph 14)

### Data verification

In case of doubts about the research integrity of FSS research, the faculty board can decide that verification of archived (non-public data) is needed. In making this decision, the board shall balance the need for confidentiality and security with the interests of transparency. If it is decided that the data needs to be reviewed, the Faculty Board will then decide who will access the data while ensuring confidentiality of the data and work with VU IT and the Data Steward to ensure that this access is possible.

## Administrative procedures

### End of employment

If a researcher leaves the VU, the department head should work with the researcher to ensure:

- That the data for any ongoing projects is properly stored according to these guidelines;
- That the data for any pending publications is properly archived according to these guidelines;
- That responsibility for any data sets archived by the researcher on VU infrastructure is transferred to an FSS colleague; and,
- That the researcher doesn't lose access to data they need for their further career, if such access can be reasonably organized; for example through the signing of a data transfer agreement between the VU and the researcher's new institution. 

### Performance and appraisal reviews

Adherence to these RDM guidelines will be discussed in performance and appraisal interviews. Formal final responsibility lies with the dean. 


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
| Data 			 |																	|
| Storage        | Storing data during the research process, when it's actively     |
|			     | being worked on                                                  |
+----------------+------------------------------------------------------------------+
|                |                                                                  |
| Data 			 |																	|
| Archiving      | Keeping data for verification purposes, usually not              |
|                | publicly available                                               |
+----------------+------------------------------------------------------------------+
| Registration   | Entering the details of a data set (but not the data set itself) |
|                | on a public page, such as PURE.                                  |
|                |                                                                  |
|                |                                                                  |
+----------------+------------------------------------------------------------------+


<!-- 
	MR: add more resources herel such as the portal etc.
-->


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


<!---
Rules, regulations and guidelines
-->

[gdpr]: https://gdpr-info.eu
[dsw-guidelines]: https://vunl-my.sharepoint.com/:b:/g/personal/k_leuveld_vu_nl/EUjMpC_8Yy5HsIkhFZ8SMecB9mET_yO0xgBh8rtbdjvw3g?e=QIw5Qg
[erc-guidelines]: https://ec.europa.eu/research/participants/data/ref/h2020/other/hi/oa-pilot/h2020-hi-erc-oa-guide_en.pdf
[vu-rdm-policy]: https://libguides.vu.nl/ld.php?content_id=32045526
[nlcoc]: https://doi.org/10.17026/dans-2cj-nvwu
[eucouncilopendata]: https://data.consilium.europa.eu/doc/document/ST-9526-2016-INIT/en/pdf
[fairprinciples]: https://www.go-fair.org/fair-principles/
[ABV-guidelines]: https://antropologen.nl/app/uploads/2019/01/guidelines-for-anthropological-research.pdf
[NSV-guidelines]: https://www.nsv-sociologie.nl/?page_id=17
[nkwp-guidelines]: http://politicologie.nl/wp-content/uploads/2021/10/Beroepscode-2008.doc
[aom-guidelines]: https://aom.org/about-aom/governance/ethics/code-of-ethics


<!---
Policy comparions
-->

[fss-vu]: https://github.com/kleuveld/rdm_pages/blob/fss_rdm_policy/_documents/rdm_policy_comparison_FSW-VU.md
[fss-dsw]: https://github.com/kleuveld/rdm_pages/blob/fss_rdm_policy/_documents/rdm_policy_comparison_FSW-DSW.md
[fss-coc]: https://github.com/kleuveld/rdm_pages/blob/fss_rdm_policy/_documents/rdm_policy_comparison_FSW-CoC.md
[fss-fair]: https://github.com/kleuveld/rdm_pages/blob/fss_rdm_policy/_documents/rdm_policy_comparison_FSW-FAIR.md
[fss-abv]: https://github.com/kleuveld/rdm_pages/blob/fss_rdm_policy/_documents/rdm_policy_comparison_FSW-ABV.md
[fss-nsv]: https://github.com/kleuveld/rdm_pages/blob/fss_rdm_policy/_documents/rdm_policy_comparison_FSW-NSV.md
[fss-nkwp]: https://github.com/kleuveld/rdm_pages/blob/fss_rdm_policy/_documents/rdm_policy_comparison_FSW-NKWP.md
[fss-aom]: https://github.com/kleuveld/rdm_pages/blob/fss_rdm_policy/_documents/rdm_policy_comparison_FSW-AoM.md


<!-- 
	Specific advice/guidelines
-->

[fss-guidelines-archiving]: https://github.com/kleuveld/rdm_pages/blob/fss_rdm_policy/_documents/fss_guidelines_archiving.md
[fss-guidelines-organization]: https://github.com/kleuveld/rdm_pages/blob/fss_rdm_policy/_documents/fss_guidelines_organization.md


<!-- 
	Tools
-->
	
[dmponline]: https://dmponline.vu.nl
[storage-finder]: https://vu.nl/en/research/storagefinder

