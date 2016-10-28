<properties
	pageTitle="Log Changes in Dynamics 365 for Financials | Financials"
    description="Log changes made by users."
	services="project-madeira"
	documentationCenter=""
	authors="edupont04"/>
<tags
    ms.service="project-madeira"
    ms.topic="get-started-article"
    ms.devlang="na"
    ms.tgt_pltfrm="na"
    ms.workload="na"
    ms.date="09/08/2016"
    ms.author="edupont04" />

# Log Changes in Dynamics 365 for Financials
You can enable the change log in Financials so you have a history of activities. The log is based on changes that are made to data in the tables that you track. In the change log, entries are chronologically ordered and show changes that are made to the fields on the specified tables. The change log collects all changes that are made to the table.  

## Working with the change log
A common problem in many financial systems is to locate the origin of errors and changes in data. It could be anything from an incorrect customer telephone number to an incorrect posting to the general ledger. The change log lets you track all direct modifications a user makes to data in the database. You must specify each table and field that you want the system to log, and then you must activate the change log.  

You activate and deactivate the change log in the **Change Log Setup** window. When you activate or deactivate the change log, this activity is logged, so you can always see which user deactivated or reactivated the change log. This cannot be turned off.  

<!-- In the **Change Log Setup** window, on the Actions tab, you specify which tables you want to track changes for. Financials also tracks a number of system tables.-->

After you have set up the change log, activated it, and made a change to data, you can view and filter the changes in the **Change Log Activated** window. If you want to delete entries, you can do that in the **Delete Change Log Entries** window, where you can set filters based on dates and time.  

## See Also
[Change Basic Settings](ui-change-basic-settings.md)  
[Sorting](ui-sorting.md)  
[Using Search for Page or Report](ui-search.md)  
