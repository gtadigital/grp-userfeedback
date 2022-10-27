# gta Research Portal | User Feedback and Testing Scenarios
Test Window of October 1st – 15th, 2022

## Note
Please see also the [demo videos](https://github.com/gtadigital/grp-userfeedback/wiki) on ho to use the research portal



## Introduction

The purpose of the gta Research Portal is to provide access to the numerous resources of the gta Archives and related Research Projects Data to a wide public/scholarly audience. The goal is to serve a broad range of search interests and strategies, tailored to the nature of its content. In view of ETH Zurich's Open Research Data strategy, the portal provides both human-interpretable and machine-processable FAIR access based on semantic technology, thus leveraging also the potential of linked open data. 

The purpose of the current testing phase is to test the features, functionalities, ergonomics of use, quality and granularity of the data, as well as the performance of the current version of the gta Research Portal in view of its further development. Please see below on [how to contribute](https://github.com/gtadigital/grp-userfeedback/blob/main/README.md#how-to-send-feedback).  


## Features
The current Version 1.3.5 of the gta Research Portal includes the following feature set: 

- Simple search across all object types (Google-like search)
- Object-specific search for Places, Persons, Groups, Archival collections etc.
  - incl. faceting for linked places, actors, time-spans etc. 
- Display of individual records
  - incl. full-screen view of digital images (where available)
  - incl. links to digital objects, reference data, external identifiers etc.    
  - incl. visual data exploration and representation (Ontodia)
- Semantic Search for Archival Collections, Documents, Groups, Persons, Places
  - incl. faceting for linked Places, Actors, Timespans etc.
- Access to the underlying data for research/reuse purposes (SPARQL queries) 


The upcoming versions of the gta Research Portal will include the additional features (Public Version 1.4, planned October/November 2022):

- Additional relattions between Archival Holdings and Persons, Groups, Places (planned v1.40) </li> 
- Updates Version of the BuiltWork and Project Data (v1.4.0) 
- Additional Archival Object Data (v1.4.0)
- Enhanced alignment between Archival Objects and Digital Objects 
- Enhanced linking to internal and external reference data 
- Image Similarity Search



## Published Data 
The currently published Data Version (1.3) from the gta Archives include: 
- 107'000 Archival Objects (representing approx. 80% of the total holdings)
  - including updated links to Persons, Groups, Places
- 112'000 Digital Assets
  - with updated IIIF-Service to deliver pyramidal TIFFs for better scalability 
- 20’500 BuiltWorks and Projects 
- 39’000 Persons and Groups (incl. Institutions, Legal Entities etc.)
  - including Long From Biographic Information (BSA Project)
- 14’000 Places  
  - including updated links to persons, Groups, Archival Objects




## What to test? 
In view of future updates of the portal, your feedback regarding the search experience is vital. However, here we provide a (non-exclusive) list of test scenarios that may be helpful to explore and assess all major features of the gta Research Portal. 
 
### Simple Search [→ Link](https://researchportal-public.gta.arch.ethz.ch/resource/Start)
- Does the simple search respond to my questions?
- Does the ranking of the search results behave according to expectations?    
- Does the simple search performance/speed 
- Does the display of sample resources provide an initial understanding of the collection? 
- How can the above features be improved? 

### Archival Objects Search [→ Link](https://researchportal-public.gta.arch.ethz.ch/resource/:LandingPageCollection) 
- Does the Archival Objects Search allow me to find what I need? 
- Does the display of the search results allow me to understand the nature and content of the holdings
- Does the facetting mechanism allow me to refine my search as needed? 
- How can the search for Archival Objects be improved? 


### Person and Group Search [→ Link](https://researchportal-public.gta.arch.ethz.ch/resource/:LandingPagePerson) [→ Link](https://researchportal-public.gta.arch.ethz.ch/resource/:LandingPageGroup)
- Does the Person and Group Search allow me to find what I need? 
- Does the facetting mechanism allow me to refine my search as needed? 
- How can the search for Person/Group be improved? 

### Individual Records 
- Does the display of individual records allow me to understand the content of the Archival Objects, Groups, Persons etc.?
- Does the image viewer meet my needs (where available)?

## Known Issues
Being updated frequently with updated content from the gta Archives Collection System and extended by external data sources, the public gta Research Portal undergoes steady development and regular updates. Currently, known issues include: 
- Archival Objects and Digital Images granularity and alignment [→ Discussion](https://github.com/gtadigital/grp-userfeedback/issues/2)
- Archival Objects and Digital Images completeness [→ Discussion](https://github.com/gtadigital/grp-userfeedback/issues/3)
- Built Works and Project Data granularity and de-duplication [→ Discussion](https://github.com/gtadigital/grp-userfeedback/issues/4)
- Person and Group Data completeness and de-duplication (currently under revision) [→ Discussion](https://github.com/gtadigital/grp-userfeedback/issues/5)

## Roadmap
The gta Research Portal will undergo periodical updates to load newly generated/edited daat from the gta Archives (and othersources, where needed). New and additinal data are planned be be released monthly. The durrent release roadmap is: 
- Version 1.4 (October 2022), updated Built Work Data and Frontend
- Version 1.5 (November/December 2022), additional holding data (reaching 100% coverage)

## How to send feedback?
The preferred way to contribute is to send us feedback using our [Issue Tracker](https://github.com/gtadigital/grp-userfeedback/issues). In order to contribute you will need to login or to [signup](https://github.com/signup) for a personal GitHUb Account (free). Another option to send us your feedback by mail to both Thomas Hänsli and Elisabet Jönsson Steiner.  


