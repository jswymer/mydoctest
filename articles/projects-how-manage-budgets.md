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
    ms.date="10/24/2016"
    ms.author="SorenGP" />

# How to: Manage Job Budgets
You can set up a budget for each job. The budget is used to plan the resources that you allocate to a job. The budget can be either general with few entries or it can contain more entries that are divided into activity levels. You can then compare the scheduled amounts with the actual usage as recorded in the job journal. By monitoring differences between actual usage and budgeted usage, you can control an ongoing project and improve the quality of future jobs by reducing the risk of underestimating costs.

## To estimate the budgeted costs for a job  
When a customer wants to know the price of a job that will be invoiced based on usage, you must have to determine the budgeted costs for the job. You use the **Job Task Lines** window to do this. 
  
1. In the top right corner, choose the **Search for Page or Report** icon, enter **Jobs**, and then choose the related link.  
2. Select the relevant job, and then choose the **Job Task Lines** action.  
3. Select a job task of type **Posting**, and then choose the **Job Planning Lines** action.
4. On a new line, fill in the fields as necessary. Choose a field to read a short description of the field or link to more information.   

For the **Line Type** field, refer to the following information.  
  
|Line Type|Invoice Structure|Description|  
|---------|-----------------|-----------|  
|**Both Schedule and Contract**|Default.|The cost and price amounts entered in the planning line are the budgeted costs for the particular planning line. The price amount will be invoiced.|  
|**Both Schedule and Contract**|Do not charge customer usage, but display information about the planning line in the customer invoice. Set **Unit Price** to 0.|The planning line details are transferred to an invoice, but will not include pricing information.<br /><br /> You can accomplish the same result by creating two planning lines, one of type **Schedule** and one of type **Contract**, and then set the **Unit Price** on the contract line to **0**.|  
|**Schedule**<br /><br /> **Contract**|Invoice details are not related to specific usage entries. Requires two matching planning lines:<br /><br /> -   Schedule<br />-   Contract|For the **Schedule** line type, the cost and price amounts entered in the planning line are the scheduled cost and scheduled price of the usage for the planning line. It is not necessarily the amount that will be invoiced to the customer.<br /><br /> Conversely, for the **Contract** line type, the cost and price amounts entered in the **Contract** planning line are the contracted costs and price that will be invoiced for this particular planning line. This may relate to one or many scheduled usage amounts.|  
|**Schedule**|Do not charge customer usage and do not display amount in the customer invoice.|Usage is not transferred to an invoice, but will still be used in the calculation of WIP.|  
|**Contract**|Charge the customer usage and display the usage on the invoice.|Usage is transferred to the invoice, based on the quantity specified in the **Qty. to Transfer to Invoice** field.|  
  
**Note**: The **Planning Date** field for the planning line. This is the date when usage related to this planning line is expected to be completed. It is also the date when the planning line may be transferred to a sales invoice and posted.  
  
**Note**: When you fill in the **Quantity** field, all total price and total cost information will now be calculated and filled in for that planning line. You can edit them at any time.
  
5. Close the **Job Planning Lines** window and return to the **Job Task Lines** window. You can now see a summary of the total budgeted costs, budgeted price, contract cost and contract price for each task.

## To record usage fora job planning line of type **Schedule** 
In the **Job Planning Lines** window, you can review and record usage on various parts of your job, which is automatically updated as you modify and transfer information between jobs and job journals or job invoices. This requires that you have set up a job so that the **Apply Usage Link** is turned on. For more information, see [How to: Set Up: Jobs](projects-how-setup-jobs.md).  

For example, for planning lines of type **schedule**, you can enter the quantity of a resource, and indicate what quantity to transfer to the job journal. If the type of the planning line is **Contract**, you can enter the quantity of the resource, and indicate what quantity to transfer to an invoice. By comparing the quantity that has been transferred to the journal or invoice with the remaining quantity, you can quickly review usage information.
  
1. In the top right corner, choose the **Search for Page or Report** icon, enter **Jobs**, and then choose the related link.  
2. Select the relevant job, and then choose the **Job Planning Lines** action.
3. Select a job planning line of type **Schedule** or **Both Schedule and Contract** for which you want to record usage. 
4. In the **Qty. To Transfer to Journal** field, enter the number that you want to transfer. The default quantity is the value that you enter in the **Quantity** field. 
  
    The **Remaining Quantity** field shows the quantity that remains to complete the job and be transferred to the journal.  
  
5. Choose the **Create Job Journal Lines** action. 
6. In the **Job Transfer Job Planning Line** window, fill in the fields as necessary, and then choose the **OK** button.
7. Choose the **Open Job Journal** action.  
8. In the **Job Journal** window, select the relevant line and then choose the **Post** action. 
9. In the **Job Planning Lines** window, review the recorded usage by observing the **Quantity**, **Remaining Quantity**, and **Qty. To Transfer to Journal** fields.  
10. Repeat steps 3 through 8 to record additional usage.  
  
## To record usage for a job planning line of type **Contract**  
In the next task, you also record usage, but for a job planning line of type **Contract**. Typically, in this case, you invoice your usage, but you can also transfer it to a journal. However, when you do that, a job planning line of type **Schedule** is created to match the contract line. For more information, see the "To estimate the budgeted costs for a job" section.
  
1. In the top right corner, choose the **Search for Page or Report** icon, enter **Jobs**, and then choose the related link. 
2. Select the relevant job, and then choose the **Job Planning Lines** action.  
3. Select a job planning line of type **Contract** for which you want to record usage.
4. In the **Qty. To Transfer to Invoice** field, enter the number that you want to transfer. The default quantity is the value that you enter in the **Quantity** field.
  
    The **Quantity to Invoice** field shows the quantity that remains to complete the job and be invoiced.  
  
5. Choose the **Create Sales Invoice** action.
6. In the **Job Transfer to Sales Invoice** window, fill in the fields as necessary, and then choose the **OK** button.
7. In the **Job Planning Lines** window, select the relevant line, and then choose the **Post** action.
8. In the **Job Planing Lines** window, review the recorded usage by observing the **Quantity**, **Quantity to Invoice**, **Qty. To Transfer to Invoice** fields, and, if the sales invoice is posted, the **Qty. Invoiced** fields.
9. Repeat steps 3 through 8 to record additional usage.  
10. To review a related posted sales invoice, choose the **Get Sales/Credit Memo** action.  
11. In the **Job Invoices** window, select the relevant invoice, and then choose the **Open Sales Invoice/Credit Memo** action.x        

## See Also
[Manage Projects](projects-manage-projects.md)  
[Finance](finance.md)  
[Manage Purchasing](purchasing-manage-purchasing.md)         
[Manage Sales](sales-manage-sales.md)      
[Work With Dynamics 365 for Financials](ui-work-product.md)  
