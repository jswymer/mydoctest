<properties
                pageTitle="How to: Manage Job Supplies| Financials"
                description="Describes how to supply material and services to jobs."
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
    ms.date="10/28/2016"
    ms.author="SorenGP" />

# How to: Manage Job Supplies
Managing project supplies of items, services, and expenses is an integral and critical aspect of the execution of all jobs. You can use inventory quantities or make job-specific purchases using purchase orders or purchase invoices. For example, a service job on a computer requires a new disk. You create a purchase invoice to buy a new disk and record the job that it will be used on.

If the purchase process does not require that the physical transaction be recorded separately, then a purchase may be processed in the **Job G/L Journal** window. For more information, see [How to: Record Usage for Jobs](How to: Record Usage for Jobs.md).

## To purchase items or services for a job  
The following procedure shows how to use a purchase invoice to purchase products for a job. The same steps apply when using a purchase order.  

1. In the top right corner, choose the **Search for Page or Report** icon, enter **Purchase Invoices**, and then choose the related link.  
2. Choose the **New** action and fill in the fields as necessary. For more information, see [How to: Record Purchases](purchasing-how-record-purchases.md).
3. In the **Job No.** and **Job Task No.** fields, select the information of the job that you want to purchase items or services for.  

    The value that you select in the **Job Line Type** field defines whether a planning line is created when you post the usage of the item. If the field contains **Billable**, then job planning lines that are ready to be invoiced to the customer are created. For more information, see [How to: Invoice Jobs](projects-how-invoice-jobs.md).

4. Choose the **Post** action.

## To view the value of purchases for a job  

1. In the top right corner, choose the **Search for Page or Report** icon, enter **Jobs**, and then choose the related link.
2. Open a relevant job card.

    On the **Tasks** FastTab, the **Outstanding Orders** field shows the total outstanding amount, in local currency, of inventory items and services on purchase documents for the job task line.  

    The **Amt. Rec. Not Invoiced** field shows the value of items delivered on purchase documents, but not yet invoiced.  

3. Choose either of the fields to open the **Purchase Lines** window where you can review information about the related purchase document lines, including which items or services have been received.

## To post a job-related expense  
If you incur extraordinary or one-time job expenses, you can use the **Job G/L Journal** window to post them directly to the relevant job account.

1. In the top right corner, choose the **Search for Page or Report** icon, enter **Job G/L Journals**, and then choose the related link.  
2. Create a new line and enter information about the expense, including information in the **Job No.** and **Job Task No** fields.  
3. When the journal is complete, choose the **Post** action.


## See Also
[Manage Projects](projects-manage-projects.md)  
[Finance](finance.md)  
[Manage Purchasing](purchasing-manage-purchasing.md)         
[Manage Sales](sales-manage-sales.md)      
[Work With Dynamics 365 for Financials](ui-work-product.md)  
