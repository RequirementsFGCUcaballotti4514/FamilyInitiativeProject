# Introduction
The proposed system for Family Initiative, Inc. is aimed at improving the organization's ability to provide services to autistic children and their families. The system will be a web platform that streamlines various business processes such as identification and assessment of children's needs, designing individualized treatment plans, monitoring progress, and communicating with parents and caregivers. The system will also interface with other processes such as fundraising, donor management, volunteer management, and administrative tasks like record-keeping, reporting, and compliance. By implementing an integrated system that supports these processes, the organization can focus on providing high-quality care to autistic children and their families, and ultimately achieve its mission of improving lives.

## Business purpose


## Business scope


## Overview


## Definitions


## Major stakeholders 



# References
[Family Initiative Website](https://www.fi-florida.org/)

[Business Analysis Document](https://github.com/RequirementsFGCUcaballotti4514/FamilyInitiativeProject/wiki)

[Business Requirments Specification(BRS)](https://github.com/RequirementsFGCUcaballotti4514/FamilyInitiativeProject/blob/main/Business%20Requirements%20Specification%20(BRS).md)


# Business management requirements


## Business environment


## Mission, goals, and objectives


## Business model


## Information environment



# Business operational requirements


## Business processes


## Business operational policies and rules


## Business operational constraints


## Business operational modes


## Business operational quality


## Business structure



# Preliminary operational concept of proposed system
![login page](https://github.com/RequirementsFGCUcaballotti4514/FamilyInitiativeProject/blob/main/Diagrams/Family%20Hub.jpg)
![landing dash](https://github.com/RequirementsFGCUcaballotti4514/FamilyInitiativeProject/blob/main/Diagrams/Family%20Hub%20(1).jpg)
![client page](https://github.com/RequirementsFGCUcaballotti4514/FamilyInitiativeProject/blob/main/Diagrams/Family%20Hub%20(2).jpg)
![chat](https://github.com/RequirementsFGCUcaballotti4514/FamilyInitiativeProject/blob/main/Diagrams/Family%20Hub%20(3).jpg)
Description of wireframe: The first page is the login. After a successful login, the second slide shows the home page with the left side containing different pages that can be navigated to. The top displays what page you are currently on along with your user name and photo. The home page on the left side contains scheduling information of the current user, along with company events. The right side is a brief overview of client information. Clicking on the clients tab on the left side will display client information, a graph displaying behavior improvements(lower is better) along with notes about the client. Clicking on the chat will bring up slide four where you can group chat with team members, managers, and client parents.

## Preliminary operational concept


### operational policies and constraints
* [privacy policy](https://www.fi-florida.org/privacy/)
* [terms of use](https://www.fi-florida.org/terms/)
* [accessibility](https://www.fi-florida.org/accessibility/)
### description of the proposed system
The system is used by the BCBA with conjunction of the RBT to allow the client's parents to see progress of their child over time. The system will also allow for communication of concerns of both FI and parents, along with events that the client or parent may be interested in. 
### modes of system operation
* web
* database
* office 365
### user classes and other involved personnel
* management
* BCBA
* RBT
* Parents of the Client
* Admin
* OT
### support environment
Support will be via a web app accessible from both computer and smartphone.
## Preliminary operational scenarios
upon getting a new client, the manager or admin will generate a new client profile. The profile will be assigned to parents, BCBA, and RBT that are directly working with the client. After the BCBA and parents have gone through the needs assessment, the client profile will be updated to show behaviors being worked on. After a session the RBT will enter data from the session to the database. The parent will look at the profile to see the behavior profile of the client. The parent will be notified of events FI is having. 



# Other preliminary life-cycle concepts

## Preliminary acquisition concept
the system needs to pull from a database that holds client information. FI is very interested in the security of this information. They currently store their information in physical files and office 365. File uploads to a cloud server is ideal for the website to utilize information. The domain and database would need to be acquired.

## Preliminary deployment concept
Users will be able to login and access their clients and update information. Parents will be able to login and access information about their children. The web app will need to be built in conjunction with the database to appropriately and safely display data. 

## Preliminary support concept
There will have to be support for the database and operations of the website, this would most likely be a third party IT company. The Admin for the website would ideally be management, but more likely to be HR. Admin would be responsible for Handling workers and Assigning BCBAs and OTs. Admins would need to set privileges for each role. The BCBAs would be responsible for the assigning RBTs to clients.

## Preliminary retirement concept
The company would need to hold control of the domain for a (three) year period to avoid any security information being obtained. 


# Project Constraints
The company is a non-profit, so there are constraints around the fiscal year. The ending and beginning of school years. Thanksgiving and winter brake.


# Appendix

## Acronyms and abbreviations
* FI - Family Initiative
* RBT - Registered Behavior Technician
* BCBA - Board Certified Behavior Analyst
* ABA - Applied Behavior Analysis
* DRO - Differential Reinforcement of Other Behavior
* DTT - Discrete Trial Training
* OT - Occupational Therapy
* NET - Natural Environment Training
* ASD - Autism Spectrum Disorder
* TBRI - Trust Based Relational Intervention
* FCN - Family Care Network
