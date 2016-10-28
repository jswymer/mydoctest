<properties
                pageTitle="How to: Record Usage for Jobs| Financials"
                description="Describes how to record usage of items or resources on jobs."
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
    ms.date="10/26/2016"
    ms.author="SorenGP" />

#How to: Record Usage for Jobs
In the **Job Planning Lines** window, you can review and record usage on various parts of your job, which is automatically updated as you modify and transfer information between jobs and job journals or job invoices. This requires that you have set up a job so that the **Apply Usage Link** is turned on. For more information, see [How to: Set Up: Jobs](projects-how-setup-jobs.md).  

For example, for planning lines of type **Budget**, you can enter the quantity of a resource, and indicate what quantity to transfer to the job journal. If the type of the planning line is **Billable**, you can enter the quantity of the resource, and indicate what quantity to transfer to an invoice. By comparing the quantity that has been transferred to the journal or invoice with the remaining quantity, you can quickly review usage information. 

The following procedures describe how to record actual (billable) or budgeted job prices and costs. For information about estimating budgeted values during planning, see [How to: Manage Job Budgets](projects-how-manage-budgets.md).

## To record usage for a job planning line of type Budget 

1. In the top right corner, choose the **Search for Page or Report** icon, enter **Jobs**, and then choose the related link.  
2. Select the relevant job, and then choose the **Job Planning Lines** action.
3. Select a job planning line of type **Budget** or **Both Budget and Billable** for which you want to record usage. 
4. In the **Qty. To Transfer to Journal** field, enter the number that you want to transfer. The default quantity is the value that you enter in the **Quantity** field. 
  
    The **Remaining Quantity** field shows the quantity that remains to complete the job and be transferred to the journal.  
  
5. Choose the **Create Job Journal Lines** action. 
6. In the **Job Transfer Job Planning Line** window, fill in the fields as necessary, and then choose the **OK** button. Choose a field to read a short description of the field or link to more information.
7. Choose the **Open Job Journal** action.  
8. In the **Job Journal** window, select the relevant line and then choose the **Post** action. 
9. In the **Job Planning Lines** window, review the recorded usage by observing the **Quantity**, **Remaining Quantity**, and **Qty. To Transfer to Journal** fields.  
10. Repeat steps 3 through 8 to record additional usage.  
  
## To record usage for a job planning line of type Billable  
In the next task, you also record usage, but for a job planning line of type **Billable**. Typically, in this case, you invoice your usage, but you can also transfer it to a journal. However, when you do that, a job planning line of type **Budget** is created to match the billable line. For more information, see the "To estimate the budgeted costs for a job" section.
  
1. In the top right corner, choose the **Search for Page or Report** icon, enter **Jobs**, and then choose the related link. 
2. Select the relevant job, and then choose the **Job Planning Lines** action.  
3. Select a job planning line of type **Billable** for which you want to record usage.
4. In the **Qty. To Transfer to Invoice** field, enter the number that you want to transfer. The default quantity is the value that you enter in the **Quantity** field.
  
    The **Quantity to Invoice** field shows the quantity that remains to complete the job and be invoiced.  
  
5. Choose the **Create Sales Invoice** action.
6. In the **Job Transfer to Sales Invoice** window, fill in the fields as necessary, and then choose the **OK** button.
7. In the **Job Planning Lines** window, select the relevant line, and then choose the **Post** action.
8. Review the recorded usage by observing the **Quantity**, **Quantity to Invoice**, **Qty. To Transfer to Invoice** fields, and, if the sales invoice is posted, the **Qty. Invoiced** fields.
9. Repeat steps 3 through 8 to record additional usage.  
10. To review a related posted sales invoice, choose the **Sales Invoices/Credit Memos** action.  
11. In the **Job Invoices** window, select the relevant invoice, and then choose the **Open Sales Invoice/Credit Memo** action.         

## To create job journal lines from job planning lines  
When you are ready to post financial information for jobs, you must create job journal lines that you can post. 
  
1. In the top right corner, choose the **Search for Page or Report** icon, enter **Jobs**, and then choose the related link.  
2. Select a relevant open job, and then choose the **Job Task Lines** action.  
3. In the **Job Task Lines** window, select a relevant line, and then choose the **Job Planning Lines** action.
4. In the **Job Planning Lines** window, on a relevant job planning line, in the **Qty. to Transfer to Journal** field, enter the quantity that you want to transfer to a job journal.  
5. Choose the **Create Job Journal Lines** action.
6. In the **Job Transfer Job Planning Line** window, fill in the fields as necessary.  
7.  Choose the **OK** button. Job journal lines are created. 
8. To verify the transfer, open the relevant job journal batch and check the entries.  
9. When the job journal lines are complete, choose the **Post** action.  

## To create job journal lines manually  
  
1. In the top right corner, choose the **Search for Page or Report** icon, enter **Job Journals**, and then choose the related link.  
2. In the **Batch Name** field, choose a relevant job journal batch.  
3. On a new line, enter journal information that includes document number, job number, job task number, type, and quantity of the type being consumed.  
4. When the job journal lines are complete, choose the **Post** action.  

## To review planning lines for a job ledger entry  
After you have posted job journal lines, you can see the planning lines that are associated with the job journal entries that have been posted. 

**Note**: This requires that the **Apply Usage Link** check box has been selected for the job, or is the default setting for all jobs in your organization. For more information, see [How to: Set Up Jobs](projects-how-setup-jobs.md).  
  
1. In the top right corner, choose the **Search for Page or Report** icon, enter **Job Journals**, and then choose the related link.  
2. Select a relevant job journal, and then choose the **Ledger Entries** action.  
3. In the **Job Ledger Entries** window, choose **Show Linked Job Planning Lines** action.

## See Also
[Manage Projects](projects-manage-projects.md)  
[Finance](finance.md)  
[Manage Purchasing](purchasing-manage-purchasing.md)         
[Manage Sales](sales-manage-sales.md)      
[Work With Dynamics 365 for Financials](ui-work-product.md)  
