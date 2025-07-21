![image-20250721165331549](/media/FCA.png)

**Solution accelerator for Fabric platform to monitor cost**

The solution aims to facilitate the understanding and monitoring of the Microsoft Fabric Cost.

Customers may not always clearly distinguish between costs that are included or excluded within the Data Platform, the handling of reservations (particularly those not rationalized within a defined scope), or their capacity usage. They may also need guidance on strategies for optimizing resources and implementing effective FinOps practices, including chargeback and show back to stakeholders. This free solution was developed in France by several passionate CSA experts in FinOps and Data: Cedric Dupui, Manel Omani, Antoine Richet, and led by Romain Casteres.

IMAGE: ANSWERING ALL ENONCED PROBLEM

⚠️ Caution: The FCA solution accelerator is not an official Microsoft product! It is a solution accelerator, which can help you implement a cost monitoring solution within and for Fabric. Consequently, there is no official support provided, and there remains a potential risk of system failures.

### Introduction

Fabric Cost Analysis (short: FCA) is a solution to enable holistic monitoring of Microsoft Fabric Cost with the help of Microsoft Fabric. Today monitoring of cost can be done through different solution: [Choose a Power BI data source](https://learn.microsoft.com/en-us/cloud-computing/finops/toolkit/power-bi/help-me-choose#comparison-table).

FSA has the goal to provide a more holistic view specified on Microsoft Fabric aspect and particularities (joining Financial and Operational forces) on top of the various information, which can be extracted from Azure Cost Management, personal enriched source of information, … allowing its users to analyze at a very high level, but also to deep dive into specific usage, reservation and particularity of the platform for a more fine granular data analysis. 

FCA is fully developed utilizing Fabric capabilities, with Pipelines and Notebooks serving as key tools for data extraction and transformation. Data is maintained both in its raw format and as Delta Parquet, allowing users to access it directly through Power BI Direct Lake. FCA includes standard reports that provide an overview of data and allow users to customize or create their own reports using the data model. Fabric's open framework enables integration with external data sources for further analysis as needed.

### FCA Content

IMAGE: ARCHITECTURE (Will be reused in the Support Page)

FCA extracts the following data:

- Azure Cost in FOCUS (x version)
- Enriched data (Git Connections)
- Azure Cost of Reservations (Next version)

 

| **#** | **Page** | **Info**                                                     |
| ----- | -------- | ------------------------------------------------------------ |
| **1** |          | Home Page  - Cost overview  - Cost per category  - Warnings  |
| **2** |          | Summary Page  - Capacities number  - Region number  - Cost per category / capacity |
| **3** |          | Usage Page  - Detail meters / capacity  - Usage info in regards of the ‘Compute  Pool Capacity Usage CU’ meter |
| **4** |          | Detail Page  - Detail cost per capacities  - Cost per category / capacity / dates |
| **5** |          | Reservation Page  - Reservation rate  - Capacities usage of the RI |
| **6** |          | Support Page  - Architecture  - Learnings  - Links           |

 

### Setup

Are you ready to try FCA ? We have prepared two step-by-step documentations, which help you to deploy CSA in your workspace to your tenant:

- Configure export of FOCUS Data

- Create a Workspace

- Create a Lakehouse

- Create a Shortcut

- [Click here to deploy or update FCA](https://github.com/Pulsweb/FCA/blob/main/script/Deploy_FCA.ipynb)

  

### Support

The FCA solution accelerator template is not an official Microsoft service.

Ideas/Suggestions: Submit ideas and suggestions as issues in this repository.

Bug Reports: A backlog is maintained on the project issues page. If you encounter problems or have suggestions, add an entry to the issues section.

Important: Support tickets should not be opened for issues related to these templates. For any questions or concerns about the templates, create an issue in this repository.

### Other helpful resources

- Demo Recorded
- …
