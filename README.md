# SAP S/4HANA & SAP Business Suite extension sample apps
This repository contains sample SAPUI5 applications, which are used in two tutorial groups on [developers.sap.com](https://developers.sap.com):

1.  [Create custom UI extension for Business Suite app on Cloud Platform](https://www.sap.com/developer/groups/cp-s4-ext-ui.html)
2.  [Create SAP S/4HANA data mart on SAP Cloud Platform](https://www.sap.com/developer/groups/cp-s4-ext-datamart.html)


## Description: Data Mart Sample
In some cases you might want to build a data mart for analyzing data in your SAP on-premises backend system.

In the **SAP Cloud Platform Data Mart tutorial** you will learn how to build a data mart on SAP Cloud Platform, and how to build your custom analytics application on top of this data mart. You will set up a SAP NetWeaver 7.50 system in a Virtual Machine on your computer. Subsequently you will set up a SAP HANA database in your SAP Cloud Platform account, establish connectivity between your backend system and the HANA database, and then set up a data replication between the two systems. You will model a new analytics view on the HANA database, and expose the custom view as an OData service. Finally, you will build a custom analytics application on SAP Cloud Platform using SAPUI5.

**This repository contains the sources for this custom analytics SAPUI5 application (available in the folder [./datamart/html5](./datamart/html5)), as well as the sources for the SAP HANA database view (available in the folder [./datamart/hana](./datamart/hana))**.

## Description: UI Extension Sample Apps

In the tutorial group **Create a custom UI extension for a SAP Business Suite application on SAP Cloud Platform** you will learn how to build a new User Interface application on top of SAP Cloud Platform, based on an OData API from your SAP Business Suite or SAP S/4HANA on-premises system. You will set up a SAP NetWeaver 7.50 system in a Virtual Machine on your computer. Subsequently you will enable the required OData service in your SAP NetWeaver system, set up a SAP Cloud Connector to establish connectivity between SAP Cloud Platform and your backend system. You will then set up a SAP Fiori Launchpad using the Cloud Portal service, and register the SAPUI5 app from your backend system there. Finally, you will learn how to extend and adapt SAPUI5 applications using SAP Web IDE.

**This repository contains source code for adding sorting and filtering functionality for an existing SAPUI5 application. You can find the sources in the folder [./ui-extension](./ui-extension)).**

## Requirements
This application will only run, if you have followed the tutorials on sap.com.

## Download and Installation
The download and installation procedure is described in detail in the tutorials on sap.com.

## How to obtain support
This project is provided "as-is" with no expected changes or support.

## License
Copyright (c) 2018 SAP SE. All rights reserved.
This project is licensed under the Apache Software License, Version 2.0 except as noted otherwise in the [LICENSE](/LICENSE.txt) file.
