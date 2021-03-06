<properties
	pageTitle="How to: Run Batch Jobs | Financials"
        description="Learn how batch jobs work in Dynamics 365 for Financials."
        services="project-madeira"
        documentationCenter=""
        authors="SusanneWindfeldPedersen"
/>
<tags
    ms.service="project-madeira"
    ms.topic="article"
    ms.devlang="na"
    ms.tgt_pltfrm="na"
    ms.workload="na"
    ms.date="05/12/2016"
    ms.author="SusanneWindfeldPedersen" />

# How to: Run Batch Jobs
A batch job is a routine that processes data in batches, for example the **Adjust Exchange Rates** batch job. There are batch jobs that perform periodic accounting activities, such as closing the income statement at the end of a fiscal year. Many batch jobs do calculation work, such as calculation of finance charges, exchange rate adjustment, and calculation of unit prices.

A batch job is like a report, except the batch job uses the result of its work to update information directly, instead of printing the results.

## To run a batch job
1. To open the request window for the relevant batch job, in the top right corner, choose the **Search for Page or Report** icon, enter the name of the batch job, and then choose the related link.
2. If there is an **Options** FastTab for the batch job, fill in the fields to determine what the batch job will do.
3. The window may contain one or more FastTab with filters, which you can use to limit the data included in the batch job. You can enter criteria in the suggested filters or add more filters.
4. Choose the **OK** button to start the batch job.

## See Also
[Entering Criteria in Filters](ui-enter-criteria-filters.md)  
[Work With Dynamics 365 for Financials](ui-work-product.md)
