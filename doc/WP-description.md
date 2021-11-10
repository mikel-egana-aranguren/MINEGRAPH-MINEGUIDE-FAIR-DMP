# Description

The data obtained in both MINEGRAPH and MINEGUIDE will be managed and published following FAIR principles, aiming at facilitating its reuse by a wider scientific community. In order to achieve an optimal level of “FAIRness”, two main processes will be carried out: (1) Design and creation of a Data Management Plan (DMP); (2) Implementation and deployment
of the DMP.

## DMP creation

A DMP will be produced in the first 6 months of the project, after requirements are gathered from the project members. The DMP will include:

* The policies to ensure long term persistence and curation of the data.
* The processes to capture the metadata and data, with the help of the data owners.
* The dataset catalog and the agreement of all the participants to publish it, under which conditions and with which licenses.
* Standards and metadata to be used to annotate the data.
* Persistent identifiers.
* Data sharing methodology.
* Any other consideration or problem that needs to be addressed as the project continues.

The [ERC DMP Template](https://erc.europa.eu/content/erc-data-management-plan-template) will be used as a starting point to write the DMP. Additionally, tools like [DMPOnline](https://dmponline.dcc.ac.uk/) or [Data Stewardship Wizard](https://ds-wizard.org/) will be evaluated for creating and maintaining the DMP. The DMP will be updated as the project advances after the initial creation phase.

## DMP deployment

The DMP will act as a framework to ensure a thorough implementation of the FAIR principles. This entails that data and metadata will be:

* Persistently identified, defining adequate identifiers and rich metadata.
* Stored and published for appropriate human and specially machine access.
* Structured for combination with other datasets.
* Clearly licensed for optimal reuse.

In order to ensure a correct implementation of the items above, a data publishing infrastructure will be created and deployed, comprising:

* A Linked Data server hosted in the UMU network, in a *um.es subdomain. This will include a Triple Store and a Web proxy.
* A Web server for static content that might be referenced from the Linked Data server above.
* A Web page describing the access to the data for humans but specially machines. This Web page will also include the DMP and any other data-related information: for example, pointers to any external repositories used for depositing project data (e.g.
Zenodo, Dataverse, etc.).
* A GitHub project storing the technical processes (Scripts, data sources, etc.) for the management and deployment of the data. This project will also be used to manage the progress of the DMP deployment following, to the extent possible, the Kanban
Project Management principles.
* Benchmarks based on [FAIR metrics](https://github.com/FAIRMetrics/Metrics).