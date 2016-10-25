<properties
                pageTitle="Manage Receivables| Financials"
                description="Manage Receivables"
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
    ms.date="05/12/2016"
    ms.author="SorenGP" />

# Manage Receivables#
A regular step in any financial rhythm is to reconcile bank accounts, which requires that you apply payments to customer or vendor ledger entries to close sales invoices and mark purchase credit memos.  
  
In Financials, you can quickly register payments in the **Payment Reconciliation Journal** window by importing a bank statement file or feed. The payments are applied to open customer or vendor ledger entries based on data matches between payment text and entry information. You can review and change the matches before you post the journal. You can close any open bank account ledger entries related to the applied ledger entries when you post the journal. The bank account is reconciled when all payments are applied.  
  
**Note**: You can also reconcile bank accounts as in the **Bank Account Reconciliations** window, which also supports check ledger entries. For more information, see [How to: Reconcile Bank Accounts Separately](bank-how-reconcile-bank-accounts-separately.md).  
  
Alternatively, you can apply payments in the **Payment Registration** window by manually checking payments received as cash, check, or bank transaction against a generated list of unpaid sales documents. Note that this functionality is only available for sales documents.  
  
Another way to manually reconcile payments is to post each receipt to the relevant general ledger, customer, or other account by entering a payment line in the **Cash Receipt Journal** window. In that case, you can either apply the receipt or refund to one or more open entries before you post the cash receipt journal, or you can apply from the created customer ledger entries.  
  
Another task in managing receivables is to collect outstanding balances, including to manage finance charges and issue reminders.  
  
The following table describes a sequence of tasks, with links to the topics that describe them.  
  
|To |See |
|---|----|
|Apply payments to open customer or vendor ledger entries based on an imported bank statement file or feed, and reconcile the bank account when all payments are applied.|[Apply Payments Automatically and Reconcile Bank Accounts](receivables-apply-payments-auto-reconcile-bank-accounts.md)|
|Apply payments to open customer ledger entries based on manual entry in a list of unpaid sales documents. | [How to: Reconcile Customer Payments Manually From a List of Unpaid Sales Documents](receivables-how-reconcile-customer-payments-list-unpaid-sales-documents.md)|
|Post cash receipts or refunds for customers in the cash receipt journal and apply to customer ledger entries, either from the journal or from posted ledger entries. | [How to: Reconcile Customer Payments Manually](receivables-how-apply-sales-transactions-manually.md) |
|Remind customers of overdue amounts, calculate interest and finance charges, and manage accounts receivable. | [How to: Collect Outstanding Balances](receivables-collect-outstanding-balances.md) |
  
## See Also  
[Manage Sales](sales-manage-sales.md)  
[Manage Payables](payables-manage-payables.md)  
[Work With Dynamics 365 for Financials](ui-work-product.md)  
[Across Business Areas](ui-across-business-areas.md)
