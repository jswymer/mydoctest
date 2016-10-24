<properties
                pageTitle="How to: Use Resources in Projects| Financials"
                description="Describes how to use time sheets to manage projects."
                services="project-madeira"
                documentationCenter=""
                authors="SorenGP"
/>
<tags
    ms.service="project-madeira"
    ms.topic="article"
    ms.devlang="na"
    ms.tgt_pltfrm="na"
    ms.workload="na"
    ms.date="10/17/2016"
    ms.author="SorenGP" />

# How to: Use Resources in Projects
You sell resources on sales invoices and sales orders. Sales quotes and sales credit memos also support resources.

You record the usage of resources in the job journal, including keep track of costs, prices, and the work types that are linked to jobs.

You can also post the usage of a resource in a resource journal. Entries posted in a resource journal have no effect on the general ledger. 
  
## To sell a resource used in a job  
  
1. In the top right corner, choose the **Search for Page or Report** icon, enter **Sales Orders**, and then choose the related link. 
2. Create a new sales order for an existing customer. For more information, see [How to: Sell Products](sales-how-invoice-sales.md). Remember to enter a resource in the **No.** field, not an item. 
3. In the **Job No.** field, select the relevant job.
4. When the sales invoice is complete, choose the **Post** action.  

  
## To record resource usage in a job 

1. In the top right corner, choose the **Search for Page or Report** icon, enter **Job Journals**, and then choose the related link.  
2. In the **Work Type Code** field, on the first line, select a work type.  
3. In the **Job No.** field, select the relevant job. 
4. When the journal is complete, choose the **Post** action.

## To adjust resource prices  
If you want to change costs or prices for a large number of resources, you can use a batch job.  
    
1. In the top right corner, choose the **Search for Page or Report** icon, enter **Adjust Resource Costs/Prices**, and then choose the related link. 
2. Fill in the fields on a line as necessary, and then choose the **OK** button. 
  
**Note**: This batch job does not create or adjust alternate costs or prices for resources. It only changes the contents of the field on the resource card for the **Adjust Field** field that you selected in the batch job. The adjustment will take effect immediately for resources, so check your adjustment factors before you run the batch job.

## To get resource price change suggestions based on existing alternate prices  
If you have already set up alternate prices for a number of resources, you can use a batch job to set up alternate resource prices. 
  
1. In the **Search** box, enter **Suggest Res. Price Chg. (Price)**, and then choose the related link.  
2. Fill in the fields as necessary. 
3. Choose the **OK** button.  
4. When the batch job is finished, open the **Resource Price Changes** window to see the results of the batch job.

## To get resource price change suggestions based on standard prices  
If you want to set up one or more sets of alternative prices based on the standard prices on the resource cards, you can use a batch job.  
  
1. In the **Search** box, enter **Suggest Res. Price Chg. (Res.)**, and then choose the related link. 
2. Fill in the fields as necessary.  
3. Choose the **OK** button.  
4. When the batch job is finished, open the **Resource Price Changes** window to see the results of the batch job.

## See Also
[Manage Projects](projects-manage-projects.md)  
[Finance](finance.md)  
[Manage Purchasing](purchasing-manage-purchasing.md)         
[Manage Sales](sales-manage-sales.md)     
[Work With Dynamics 365 for Financials](ui-work-product.md)  
