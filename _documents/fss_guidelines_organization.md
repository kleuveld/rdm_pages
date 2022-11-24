---
title: VU FSS guidelines for data organization
subtitle: Second Draft
date: 22-11-2022
---

**Note on this draft**: *The goal of this document is to provide some examples of data organization, as researchers may struggle to find an organization that works for them. This draft functions as a placeholder that provides an idea of what these guidelines will look like. More detailed guidelines, that cover more types of research and ways of working, will be developed with input from researchers. If you would like to contribute, please contact k.leuveld@vu.nl so that together we can update and restructure this document for it to be more inclusive.*

# Introduction

Researchers of the Faculty of Social Sciences (FSS) are responsible for organizing their data in such a way that they can be archived without excessive effort. In general terms, the aim is to ensure that a fellow researcher can use the data without asking too many questions. This ensures that the results of the research can be verified if the need arises. Furthermore, should additional researchers be added to a project - or a researcher gets back from a long hiatus - they can get started quickly. These guidelines are not prescriptive; they are meant to inspire researchers on how to manage their data when starting a new project, since changing folder structures once a project has stared can be very difficult. 

These guidelines are structured as follows: advice for organizing quantitative data and qualitative data are given in separate sections. The sections give an outline of a folder organization that is used during the research.


## Quantitative

### Simple project using Git, Research Drive and Yoda

The below folder structure is for a simple project based on survey data. The main tool for collaboratively working on outputs such as papers and analysis scripts is GitHub. However, since the input data is survey data, which is almost always personal data, it cannot be stored on GitHub, so for this Research Drive is used. Documentation is in the form of pdf files, and would thus not benefit from GitHub, and is stored on Research Drive.

- **Research Drive**
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
- **GitHub**
	- Data cleaning
		- R scripts to pseudonymize, check and clean data.
	- Paper 1
		- Text of paper
		- Analysis R script, sources cleaning script
		- Tables and figures
	- Paper 2
		- Text of paper
		- Analysis R script, sources cleaning script
		- Tables and figures
	- Readme file

Once a paper is published, the researchers archives the raw data on Yoda, and creates a DataVerseNL entry containing:
	- A readme file (including a link to Yoda and GitHub)
	- Pseudonymized and cleaned data files
	- The Paper folder from GitHub
	- The Data Cleaning folder from GitHub
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

