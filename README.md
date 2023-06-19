## Application Details
|               |
| ------------- |
|**Generation Date and Time**<br>Tue Jun 13 2023 17:08:26 GMT+0200 (Central European Summer Time)|
|**App Generator**<br>@sap/generator-fiori-freestyle|
|**App Generator Version**<br>1.9.6|
|**Generation Platform**<br>Visual Studio Code|
|**Template Used**<br>2listdetail|
|**Service Type**<br>SAP System (ABAP On Premise)|
|**Service URL**<br>https://a03z.ucc.ovgu.de//sap/opu/odata/sap/ZSD_011_MOVEMENT1_SRV
|**Module Name**<br>project_erp|
|**Application Title**<br>Applicatie: Verplaatsingen|
|**Namespace**<br>|
|**UI5 Theme**<br>sap_horizon|
|**UI5 Version**<br>1.114.0|
|**Enable Code Assist Libraries**<br>False|
|**Enable TypeScript**<br>False|
|**Add Eslint configuration**<br>False|
|**Object collection**<br>MovementSet|
|**Object collection key**<br>Id|
|**Object ID**<br>Id|
|**Line item collection**<br>Unknown|
|**Line item collection key**<br>Unknown|
|**Line item ID**<br>Unknown|
|**Line item number**<br>Unknown|
|**Line item unit of measure**<br>Unknown|

## project_erp

A Fiori application.

### Starting the generated app

-   This app has been generated using the SAP Fiori tools - App Generator, as part of the SAP Fiori tools suite.  In order to launch the generated app, simply run the following from the generated app root folder:

```
    npm start
```

- It is also possible to run the application using mock data that reflects the OData Service URL supplied during application generation.  In order to run the application with Mock Data, run the following from the generated app root folder:

```
    npm run start-mock
```

#### Pre-requisites:

1. Active NodeJS LTS (Long Term Support) version and associated supported NPM version.  (See https://nodejs.org)

EXTRA OPMERKING (functionaliteiten die ik niet gedebuged kreeg) 
- Vanonder in de applicatie zou normaal gezien de lading te zien krijgen met het product en hoeveel het aan lading is. Deze is niet zichtbaar vanwege in fout in mijn SAP project. In mijn table ZSD_11_MOV_ITEM zou er eigenlijk bij 'Input Help/Check' bij 'Check tabel' in de colom van mov_id de table ZSD_11_MOVEMENT staan om het mov id's met elkaar te vergelijken. Dit omdat ik de objecten (met id) zelf hebben ingevuld in mijn eigen tabel dus moeten ze ook in mijn tabel gecheckt worden en niet in de table van ZSD_000_MOVEMENT. Ik kreeg dit niet meer aangepast. Er staat nu nodata omdat ze met de verkeerde tabel aan het vergelijken is.
- Zoals u wel zal zien beginnen alle projecten/klasses/structures/... in ZSD_011_PROJECTOPDRACHT met ZSD_11_... ipv ZSD_011_... Dit is omdat ik een package had verwijderd en opnieuw wou beginnen maar de namen al gebruikt waren

