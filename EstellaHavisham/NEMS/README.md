# Estella Havisham
## Context
Story and test data files created by NHS Digital as part of the NEMS project. Last updated 30/11/2017
## Child

| | |
|---|---|
| Name | Estella Havisham |
| Gender | Female |
| DOB | 28/08/2017 |
| NHS Number | 9912003896 |

## Story

| Step | Description | Data |
|---|---|---|
| 1 | Estella is born. She is registered on PDS and issued an NHS Number. A birth notification event is published by PDS to the NEMS.| Demographic data (new)<br>Birth Notification event message (new) |
| 2 |  Estella has her newborn hearing test. It is recorded on the national Screening for Hearing (S4H) service which then publishes the result to the NEMS. | Newborn Hearing event message (new) |
| 3 |  Estella has her newborn infant and physical exam (NIPE). It is recorded on the national NIPE SMaRT service which then publishes the result to the NEMS. | Physical Examination event message (new) |
| 4 |  Estella registers with New Croft Surgery GP. | Demographic data (update)|
| 5 |  Estella has her 12 week 6-in-1 vaccine administered by the health visitor (Leeds Community Healthcare NHS Trust), which publishes he event to the NEMS | [Immunisation Administration event message (new)](https://github.com/childhealth/EMS-Test-Data/blob/master/EstellaHavisham/NEMS/NEMS-A-9912003896-001.xml) |
