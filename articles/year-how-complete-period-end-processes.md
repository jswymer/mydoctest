<properties
	pageTitle="Close Periods | Project “Madeira”"
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
    ms.date="05/12/2016"
    ms.author="jswymer" />

# Close Periods
The application does not force you to close periods, however, there are many period-end (month-end) activities that can be performed in the application if you want. This topic provides an overview of these processes and activities, which may or may not be necessary for your company.

## General Ledger
* Specify system-wide and user-specific posting period.

	This specifies the dates between which postings are allowed. Depending on your business needs, you may want to restrict user posting date ranges at the start of the period-end process or at later time towards the end of the period. For more information, see [How to: Specify Posting Periods](finance-how-specify-posting-periods.md).
* Make all necessary G/L adjustments.
* Update and post Recurring Journals.
<!--* Process Consolidations-->
* Run account schedules as follows:
  1. Open the **Account Schedule** page, and choose the **Print** action.
  2. Fill in the **Account Schedule** request page and choose the **Print** action.

## Sales & Receivables
* Post all sales orders, invoices, credit memos, and return orders.
* Post all cash receipt journals.
* Update and post recurring journals that are related to Sales & Receivables.
* Reconcile accounts receivable to the general ledger.
* Run the **Delete Invoiced Sales Orders** batch job.

## Purchases & Payables
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
