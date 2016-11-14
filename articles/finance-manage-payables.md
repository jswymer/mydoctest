<properties
	pageTitle="Manage Payables | Financials"
	description="Introduction to paying your vendors and other payments."
	services="project-madeira"
	documentationCenter=""
	authors="bholtorf"
	manager="edupont"
	editor=""/>
	
<tags
	ms.service="project-madeira"
	ms.workload="na"
	ms.tgt_pltfrm="na"
	ms.devlang="na"
	ms.topic="article"
	ms.date="11/11/2016"
	ms.author="bholtorf" />
	
# Manage Payables
Dynamics 365 for Financials has what you need to effectively manage accounts payable.  

## Payments
It's easy to prioritize payments, and account for penalties for overdue payments and payment discounts for early payments. You can record payments in a general journal, and then print checks before posting the payment journal.

You can apply payments to close invoices when you post the payment, or after you post the payment. The **Application Method** specified for the vendor (on the **Vendor Card**) determines whether you apply the payment manually, or automatically. You can always apply transactions manually. However, if the application method for the vendor is **Apply to Oldest**, and you do not specify a document to apply the payment to, the payment is applied to the oldest open entry for the vendor.

## Suggest Vendor Payments
Financials can suggest various payments to vendors, such as payments that will be due soon, or payments where a discount is available. The payment suggestion can consider an amount that you specify as available funds for payment, and eligibility for payment discounts.

## Issue Checks
Financials lets you issue checks to vendors manually and electronically. Both methods happen in the **Payment Journals** window, where you can also void checks and view check ledger entries.

## Export Payments to a Bank File
When you are ready to pay a vendor, from the **Payment Journal** window you can export a file with the payment information from the journal lines. You can then upload the file to your electronic bank to process the money transfers.

If you do not want to post a payment journal line for an exported payment, for example because you are waiting for the bank to confirm the transaction, you can just delete the journal line. Later, when you create a payment journal line to pay the remaining amount on the invoice, the **Total Exported Amount** field shows how much of the payment amount has already been exported. Also, you can find detailed information about the exported total by choosing the **Credit Transfer Reg. Entries** button.

If you wait for your bank to confirm that it has processed transactions before you post payments, there are two ways to avoid accidently re-exporting payments for open documents:

- In a payment journal with suggested payment lines, sort on either the **Exported to Payment File** column, or the **Total Exported Amount** and then delete payment suggestions for open invoices for which payments have already been made and you do not want to make payments for.

    **Note** You might have to add these columns to the list. For more information, see [User Personalization](ui-user-personalization.md).  

- Alternatively, on the **Suggest Vendor Payments** batch job, where you specify the payments to include in the payment journal, you can specify not to insert journal lines for payments that have already been exported by choosing the **Skip Exported Payments** check box.

## See Also  
[Payment Methods](finance-payment-methods.md)  
[Finance](finance.md)




