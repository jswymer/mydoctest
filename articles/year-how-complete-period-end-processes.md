<properties
	pageTitle="Close Periods | Financials"
	description="Explains the processes to complete to close a period."
	services="project-madeira"
	documentationCenter=""
	authors="jswymer"
/>
<tags
    ms.service="project-madeira"
    ms.topic="article"
    ms.devlang="na"
    ms.tgt_pltfrm="na"
    ms.workload="na"
    ms.date="10/26/2016"
    ms.author="jswymer" />

# Close Periods
Financials does not force you to close periods, however, there are many period-end (month-end) activities that you can do. This topic provides an overview of optional processes and activities for closing periods.  

## General Ledger  
* Specify system-wide and user-specific posting periods.  

	This specifies the dates between which you allow posting. Depending on your business, you may want to allow posting at the start of the period, or toward the end. For more information, see [How to: Specify Posting Periods](finance-how-specify-posting-periods.md).  
* Make all necessary G/L adjustments.  
* Update and post Recurring Journals.  
<!--* Process Consolidations-->
* Run account schedules as follows:  
  - Open the **Account Schedule** window, and choose the **Print** action.  

## Sales and Receivables  
* Post all sales orders, invoices, credit memos, and return orders.  
* Post all cash receipt journals.  
* Update and post recurring journals that are related to sales and receivables.  
* Reconcile accounts receivable to the general ledger.  
* Run the **Delete Invoiced Sales Orders** batch job.  

## Purchases and Payables
* Post all purchase orders, invoices, credit memos, and return orders.  
* Post all payment journals.  
* Update and post recurring journals that are related to purchases & payables.  
* Run the **Aged Accounts Payable** report and reconcile accounts payable to the general ledger.  
* Run the **Delete Invoiced Purchase Orders** batch job.  

<!-- ### Fixed Assets
* Post all maintenance costs have been posted through the fixed asset journals or invoices.
* Post adjustments.
* Post appreciation.
* Post depreciation.
* Update and post the recurring fixed asset journal.-->

<!--### Intercompany
* Process Intercompany Postings.-->

## Calculate and Process Sales Tax
*  Complete Tax Statements.  

## See Also  
[Closing Years and Periods](year-close-years-periods.md)  
[Close Books](year-close-books.md)  
[Work With Dynamics 365 for Financials](ui-work-product.md)
