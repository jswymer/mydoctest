<properties
	pageTitle="How to: Close Income Statement | Project “Madeira”"
	description="Explains how to close an income statement."
	services="project-madeira"
	documentationCenter=""
	authors="jswymer"/>
<tags
    ms.service="project-madeira"
    ms.topic="article"
    ms.author="jswymer" />
	
# Close Income Statement
When a fiscal year is over, you must close the periods that comprise it. To do this, you run the **Close Income Statement** batch job. This job transfers the year's result to an account in the balance sheet and closes the income statement accounts. You do this by creating lines in a journal, which you then can post.

## To run the Close Income Statement batch job 
1. Close the fiscal year. The fiscal year must closed before the batch job can be run. For more information, see [How to: Close Accounting Periods](year-close-account-periods.md).
2. To run the batch job, in the Seacrh box, enter **Close Income Statement**, and then choose the related link.

## About the Close Income Statement Batch Job
The batch job processes all general accounts of the income statement type and creates entries that cancel out their respective balances. That is, each entry is the sum of all the general ledger entries on the account in the fiscal year. These new entries are placed in a journal in which you must specify a balancing account and retained earnings account in the balance sheet before you post. When you post the journal, an entry is posted to each income statement account so that its balance becomes zero and at the same time the year's result is transferred to the balance sheet.

You must post the journal yourself. The batch job does not post the entries automatically, except when an additional reporting currency is being used. When an additional reporting currency is being used, the batch job posts entries directly to the general ledger.

The date on the lines that the batch job inserts in the journal is always a closing date for the fiscal year. The closing date is a fictitious date between the last day of the old fiscal year and the first day of the new year. The advantage of posting on a closing date is that you maintain the correct balances for the ordinary dates of the fiscal year.

The **Close Income Statement** batch job can be used several times. You can post in a previous fiscal year, even after the income statement accounts have been closed, if you run the batch job again.
 
## See Also
[Close Books](year-close-books.md)  
[How to: Post the Year-End Closing Entry](year-how-post-year-end-close-entry.md)  
[How to: Open a New Fiscal Year](finance-how-open-new-fiscal-year.md)





