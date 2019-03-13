# Azure Discovery Day
## Microservices in Azure

### Overview
This hack is intended to be delivered over the course of a single day that walks through how one can migrate on-premises workloads using the 4-"R" options:
* Rehost
* Refactor
* Rearchitect
* Rebuild

The hack focuses on 3 common methods -- rehost, refactor and rearchitect using a 2-tier ASP.NET webform line-of-business (LOB) application connected to a SQL database. There is a small-amount of content available in the delivery slides to walk through the idea behind these migration paths as well as a primer on Azure PaaS capabilities and Containers.

Option: To save time; the instructor could pre-migrate the IaaS SQL database to Azure SQL DB and provide the connection string to the class to ensure the course material is able to be completed during the day 

### Resources
* [ARM Templates to build jump-box with Visual Studio for Lab](https://github.com/007FFFLearning/ADS-Containers/tree/master/Sources)
* [Self-Contained Web Application](./Application)
* [Azure Migration Documentation](https://docs.microsoft.com/en-us/azure/migrate/contoso-migration-overview)

### Suggested Schedule
The idea is to go over theory and concept in the morning and get to the Hack as soon as possible.  Lunch is recommended to go an hour but doesn't mean the Proctor couldn't be going over some of the content during the second half of Lunch.

| Time          | Topic
| ------------- |:---------------------------------------------------------------
| 09:00–09:30   | Registration
| 09:30-10:15   | Migration Strategies:  Microservices Overview
| 10:15-10:30   | Break
| 10:30-11:30   | Microservices in Azure
| 11:30-12:00   | Hack prep
| 12:00-12:30   | Lunch
| 12:30-16:00   | Hack: Deploying a working Microservices application in Azure
| 16:00-17:00   | Recap
