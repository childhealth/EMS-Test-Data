# EMS Test Data
## Introduction
This is a repository to store test data to help developers of Event Management Services (EMS).

The data represents fictional health events in the lives of a set of fictional children.

The test data files are either:
* FHIR event messages as described in [Digital Child Health Service - Events Catalogue](https://nhsconnect.github.io/Digital-Child-Health/Generated/Chapter.1.About/index.html)
* Demographic records (definition to be determined)

## Repository Structure
Each child has a seperate folder within the repository bearing their name. For example:
```
/JackDawkins
```
Within a child's folder there will be a folder named `NEMS`. This will contain the child's story and associated test data files as created by NHS Digital for the National Events Management Service (NEMS).

There maybe additional folders which relate to other EMS development projects, for example the Lancashire Local Events Management Service (LEMS) - `LANCS`. These projects may have taken copies of the NEMS story and test data files, and customised them. These projects may have provided their own story and test data files. These projects may have done a combination of the two.

The following EMS projects have contributed test data to the repository:

