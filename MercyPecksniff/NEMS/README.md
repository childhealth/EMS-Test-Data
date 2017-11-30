# Mercy Pecksniff
## Context
Story and test data files created by NHS Digital as part of the NEMS project. Last updated 30/11/2017
## Child

| | |
|---|---|
| Name | Mercy Pecksniff |
| Gender | Female |
| DOB | 17/09/2017 |
| NHS Number | 9912003926 |

## Story

| Step | Description | Data |
|---|---|---|
| 1 | Mercy is born. She is registered on PDS and issued an NHS Number. A birth notification event is published by PDS to the NEMS.| Demographic data (new)<br>Birth Notification event message (new)|
| 2 |  Mercy has her newborn hearing test. It is recorded on the national Screening for Hearing (S4H) service which then publishes the result to the NEMS. | Newborn Hearing event message (new)|
| 3 |  Mercy has her 8 week 6-in-1 vaccine administered by the health visitor (Bradford District Care NHS Foundation Trust), which publishes the event to the NEMS | [Immunisation Administration event message (new)](https://github.com/childhealth/EMS-Test-Data/blob/master/JackDawkins/NEMS/NEMS-A-9912003926-001.xml) |
| 4 |  Mercy moves to Leeds and registers with Shadwell Medical Centre GP. | Demographic data (update)|
| 5 |  Mercy has her 12 week 6-in-1 vaccine administered by the GP (Shadwell Medical Centre), which publishes the event to the NEMS | [Immunisation Administration event message (new)](https://github.com/childhealth/EMS-Test-Data/blob/master/JackDawkins/NEMS/NEMS-A-9912003926-002.xml) |
