---
title: VU FSS guidelines for data organization
subtitle: First Draft
date: 28-10-2022
---

**Note on this first draft**: This first draft functions firstly as a placeholder while more detailed guidelines are developen, and secondly to collect comments on data organization practices. As such, this version of these guidelines should not considered advice. If good data organization practices are missing, or you have comments about the practices described in this document, please contact k.leuveld@vu.nl

# Introduction

Researchers of the Faculty of Social Sciences (FSS) are responsible for organizing their data in such a way that they can easily be archived. In general terms, the aim is to ensure that a fellow research can use the data without asking too many questions. This ensures that data can easily be stored in such a way that the results of the research can be verified if the need arises. Furthermore, should additional researchers be added to a project - or a researcher gets back from a long hiatus - they can get started quickly. These guidelines are not prescriptive; they are meant to inspire researchers on how to manage their data. 

These guidelines are structuered as follows: advice for organizing quantitative data and qualitative data are given in separate sections. The sections give an outline of a folder organization that is used during the research. The aim is that if the research is concluded (parts of) the data can be easily archived: either by moving them to a separate archiving service, or assigning the folder to a vault in Yoda.


## Quantitative

The below folder structure is for a simple project based on survey data. It stores all research outputs on GitHub. Since the data is personal data, it cannot be stored on GitHub, so for this Research Drive is used. Documentation is in the form of pdf files, and would thus not benefit from GitHub, and is stored on Research Drive.

- Research Drive
	- Raw data
	- Pseudonymized data
	- Analyzed data
	- Documentation
		- Questionnaires
		- Interviewer manuals
		- Sampling procedures
		- Ethics review information
		- Blank informed consent form
	- Readme file
- GitHub
	- Data cleaning
		- R scripts to pseudonymize, check and clean data.
	- Paper 1
		- Text of paper
		- Analysis R script
		- Tables and figures
	- Paper 2
		- Text of paper
		- Analysis R script
		- Tables and figures
	- Readme file

Once a paper is published, the researchers archives the raw data on yoda, and creates a DataVerseNL entry containing:
	- A readme file (including a link to Yoda and GitHub)
	- Pseudonymized and cleaned data files
	- The Paper folder from GitHub
	- The Documentation folder from Research Drive

## Qualitative

The following is a basic qualitative project. All data is stored on Yoda. Once data collection is complete, the data folder is added to Yoda vault, a DOI of which is included in every paper.

- Yoda
	- Data 
		-Interview recordings
		- Pseudonymized interview transcripts
	- Documentation
		- Sampling information
		- Topic lists
		- Ethics review information
		- Blank informed consent form
	- Paper 1
		- Text of paper
		- Figures

