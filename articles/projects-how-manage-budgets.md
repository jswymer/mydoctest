<properties
                pageTitle="How to: Manage Job Budgets| Financials"
                description="Describes how to budget for jobs."
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
    ms.date="10/25/2016"
    ms.author="SorenGP" />

# How to: Manage Job Budgets
You can set up a budget for each job. The budget is used to plan the resources that you allocate to a job. The budget can be either general with few entries or it can contain more entries that are divided into activity levels. You can then compare the budgeted amounts with the actual usage as recorded in the job journal. By monitoring differences between actual usage and budgeted usage, you can control an ongoing project and improve the quality of future jobs by reducing the risk of underestimating costs.

The following procedure describes how to estimate budgeted costs during planning. For information about recording budgeted versus actual job prices and costs, see [How to: Record Usage for Jobs](projects-how-record-job-usage.md).  

## To estimate the budgeted costs for a job  
When a customer wants to know the price of a job that will be invoiced based on usage, you must have to determine the budgeted costs for the job. You use the **Job Task Lines** window to do this. 
  
1. In the top right corner, choose the **Search for Page or Report** icon, enter **Jobs**, and then choose the related link.  
2. Select the relevant job, and then choose the **Job Task Lines** action.  
3. Select a job task of type **Posting**, and then choose the **Job Planning Lines** action.
4. On a new line, fill in the fields as necessary. Choose a field to read a short description of the field or link to more information.   

For the **Line Type** field, refer to the following information.  
  
|Line Type |Description |  
|----------|------------|  
|Both Budget and Billable|The cost and price amounts entered on the planning line are the budgeted costs for the particular planning line. The price amount will be invoiced.|  
|Budget|The customer is not charged for usage. Usage is not transferred to an invoice, but will still be used in the calculation of WIP.|  
|Billable|The customer is charged for usage. Usage is transferred to the invoice, based on the quantity specified in the Qty. to Transfer to Invoice field.|  
  
**Note**: The **Planning Date** field for the planning line contains the date when usage related to the planning line is expected to be completed. It is also the date when the planning line may be transferred to a sales invoice and posted.  
  
**Note**: When you fill in the **Quantity** field, all total price and total cost information will be calculated and filled in for that planning line. You can edit them at any time.
  
In the **Job Task Lines** window, you can now see a summary of the total budgeted costs, budgeted price, billable cost and billable price for each task.

For information about recording budgeted versus actual job prices and costs, see [How to: Record Usage for Jobs](projects-how-record-job-usage.md).

## See Also
[Manage Projects](projects-manage-projects.md)  
[Finance](finance.md)  
[Manage Purchasing](purchasing-manage-purchasing.md)         
[Manage Sales](sales-manage-sales.md)      
[Work With Dynamics 365 for Financials](ui-work-product.md)  
