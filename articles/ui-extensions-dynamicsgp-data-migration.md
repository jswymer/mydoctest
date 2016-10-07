<properties
	pageTitle="Microsoft Dynamics GP Data Migration | Project “Madeira”"
        description="Provides information about the Dynamics GP Data Migration extension"
        services="project-madeira"
        documentationCenter=""
        authors="edupont04"/>
<tags
    ms.service="project-madeira"
    ms.topic="article"
    ms.devlang="na"
    ms.tgt_pltfrm="na"
    ms.workload="na"
    ms.date="10/07/2016"
    ms.author="edupont04" />

# The Dynamics GP Data Migration Extension for Project "Madeira"
This extension makes it easy to migrate customers, vendors, inventory items, and accounts from Dynamics GP to Project “Madeira”. If your business uses Dynamics GP today, you can export the relevant master records and then open an assisted setup guide to add the data to Project "Madeira".  
For more information, see [Migrate Business Data from Other Finance Systems](upload-data.md).

## Exporting Data from Dynamics GP
You must have exported some or all of your existing customers, vendors, inventory items, and accounts to a file, using the Dynamics GP functionality for data export. For the purposes of Project "Madeira", you can export the following types of data:
- Account  
- Customer  
- Item  
- Vendor  

The Dynamics GP Data Migration extension automatically maps the exported data so that your data is quickly available to you in your new Project "Madeira" company. During the process, supporting setup information is created, such as posting groups. Inventory items will be brought into the system with FIFO as the cost valuation method. Accounts will be set up as the main account segment from Dynamics GP with dimensions, because Dynamics 365 for Financials does not have account segments.

## See Also  
[Migrate Business Data from Other Finance Systems](upload-data.md)  
[Customizing Project "Madeira" Using Extensions ](ui-extensions.md)  
