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
| 1 | Jack is born. He is registered on PDS and issued an NHS Number. A birth notification event is published by PDS.| Demographic data<br>Birth Notification event message |
| 2 |  Jack has his newborn hearing test. It is recorded on thhe national Screening for Hearing (S4H) service which then publishes the result to the NEMS. | Newborn Hearing event message |
| 3 |  Jack has his newborn infant and physical exam (NIPE). It is recorded on the national NIPE SMaRT service which then publishes the result to the NEMS. | Physical Examination event message |
| 4 |  Estella registers with New Croft Surgery GP. | Demographic data |
| 5 |  Estella has her 12 week 6-in-1 vaccine administered by the health visitor (Leeds Community Healthcare NHS Trust), which publishes he event to the NEMS | [Immunisation Administration event message](https://github.com/childhealth/EMS-Test-Data/blob/master/EstellaHavisham/NEMS/NEMS-A-9912003896-001.xml) |
