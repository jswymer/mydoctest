<properties
	pageTitle="Work with General Journals | Project “Madeira”"
        description="Welcome to Project "Madeira"" 
        services="project-madeira" 
        documentationCenter=""
        authors="edupont04"/>
<tags
    ms.service="project-madeira"
    ms.topic="article"
    ms.devlang="na"
    ms.tgt_pltfrm="na"
    ms.workload="Madeira"
    ms.date="05/12/2016"
    ms.author="edupont04" />
    
# Work with General Journals
General journals are used to post to general ledger accounts and other accounts such as bank, customer, vendor, and fixed assets accounts. Posting with a general journal always creates entries on general ledger accounts. This is true even if, for example, a journal line is posted to a customer account, because an entry is posted to a general ledger receivables account through a posting group.

There are other journals in addition to general journals, such as item transfer journals, physical inventory journals, resource journals and FA journals. Posting these journals does not create entries on general ledger accounts, but it does create other types of ledger entries. For example, the physical inventory journal is used to compare the results of a physical inventory count to the calculated quantity on hand. When you post the journal, a physical inventory ledger entry is created for every journal line and an item ledger entry is created for each journal line on which there is a difference between the physical inventory count and the calculated quantity on hand.

The information that you enter in a journal is temporary and can be changed while it is in the journal. When you post the journal, the information is transferred to entries on individual accounts, where it cannot be changed. You can, however, unapply posted entries, and you can post reversing or correcting entries.

## Journal templates and batches
There are several general journal templates, such as the Cash Receipt Journal and the FA G/L Journal. Each journal template has a separate window with particular functions and the fields that are required to support those functions.

If necessary, you can set up multiple journal batches (individual journals) for each journal template. For example, certain employees can have their own general journal batch, with their initials as the journal batch names. For more information, see

## Main accounts and balancing accounts
If you have set up default balancing accounts for the journal batches, the balancing account will be filled in automatically when you fill in the **Account No.** field. Otherwise, fill in both the **Account No.** field and the **Bal. Account No.** field manually. A positive amount in the **Amount** field is debited to the main account and credited to the balancing account. A negative amount is credited to the main account and debited to the balancing account.

**Note**: VAT is calculated separately for the main account and the balancing account, so they can use different VAT percentage rates.

## Recurring journals
A recurring journal is a general journal with specific fields for managing transactions that you post frequently with few or no changes. Using these fields for recurring transactions, you can post both fixed and variable amounts. You can also specify automatic reversal entries for the day after the posting date and use allocation keys with the recurring entries.

## See Also
[Managing Payables](payables-manage-payables.md)









