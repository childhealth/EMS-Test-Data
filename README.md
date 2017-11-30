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

| Project | Folder Name  |
|----------|-------|
| NHS Digital NEMS       | NEMS   |
| Lancashire and South Cumbria STP LEMS | LANCS  |

Within each project folder there will be a `README.md` markdown file that:
* Describes the source of the test data e.g. copy of NEMS test data but customised to use provider identities within a regional boundary
* Identifies the child i.e. name, gender, NHS number and a mutable DOB
* Details the child's story

The story consists of a sequence of chronological steps. Each step has a description and a set of associated test data files.

The test data files are stored in the project folder and use the follwing naming convention:
* Project prefix e.g. `NEMS`
* Followed by a hyphen `-`
* If the file represents a demographic record, followed by `D`
* Else the file represents a FHIR event and the specification maturity level the test file is based on is indicated by:
  * Experimental `X`
  * Alpha `A`
  * Beta `B`
  * Release Candidate `R`
  * Live `L`
* Followed by a hyphen `-`
* Followed by NHS number (no spaces) `9912003888`
* Followed by hyphen `-`
* Followed by three digit (with leading zeros) sequence number `002`
* Followed by file type extension - `.json` or `.xml`

Example:
```
NEMS-A-9912003888-002.json
```

## The Children

* [Estella Havisham](https://github.com/childhealth/EMS-Test-Data/blob/master/EstellaHavisham/NEMS/README.md)
* [Jack Dawkins](https://github.com/childhealth/EMS-Test-Data/blob/master/JackDawkins/NEMS/README.md)
* [Mercy Pecksniff](https://github.com/childhealth/EMS-Test-Data/blob/master/MercyPecksniff/NEMS/README.md)
