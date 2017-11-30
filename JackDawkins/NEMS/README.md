# Jack Dawkins
## Context
Story and test data files created by NHS Digital as part of the NEMS project. Last updated 30/11/2017
## Child

| | |
|---|---|
| Name | Jack Dawkins |
| Gender | Male |
| DOB | 02/10/2017 |
| NHS Number | 9912003888 |

## Story

| Step | Description | Data |
|---|---|---|
| 1 | Jack is born. He is registered on PDS and issued an NHS Number. A birth notification event is published by PDS.| Demographic data (new)<br>Birth Notification event message (new)|
| 2 |  Jack has his newborn hearing test. It is recorded on the national Screening for Hearing (S4H) service which then publishes the result to the NEMS. | Newborn Hearing event message (new)|
| 3 |  Jack has his newborn infant and physical exam (NIPE). It is recorded on the local maternity system which then publishes the result to the NEMS. | Physical Examination event message (new)|
| 4 | The maternity service correct Jack's NIPE record on the maternity system as they have entered it incorrectly. The local maternity system republishes the result to the NEMS | Physical Examination event message (update) |
| 5 |  Jack registers with Shadwell Medical Centre GP. | Demographic data (update)|
| 6 |  Jack has his 8 week 6-in-1 vaccine administered by the GP (Shadwell Medical Centre), which publishes he event to the NEMS | [Immunisation Administration event message (new)](https://github.com/childhealth/EMS-Test-Data/blob/master/JackDawkins/NEMS/NEMS-A-9912003888-001.xml) |
