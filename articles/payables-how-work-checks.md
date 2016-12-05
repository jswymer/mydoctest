<properties
                pageTitle="How to: Work With Checks| Financials"
                description="How to: Work With Checks"
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
    ms.date="11/08/2016"
    ms.author="SorenGP" />

# How to: Work With Checks
Financials supports electronic and manual check issuance. Both methods use the payment journal to issue checks to vendors. You can also void checks and view check ledger entries.

The process of issuing checks suggests payments, creates ledger entries, and prints the computer checks.

**Note**: To make sure that your bank only clears validated checks and amounts, you can send them a file that contains vendor, check, and payment information. For more information, see [How to: Export a Positive Pay file](finance-how-positive-pay.md).

Your printer must be correctly set up with the check forms, and you must define which check layout to use. For more information, see [How to: Define Check Layouts](finance-how-define-check-layouts.md)

## To issue checks
1. In the top right corner, choose the **Search for Page or Report** icon, enter **Payment Journals**, and then choose the related link.
2. Fill in the journal with relevant payments, for example by using the Suggest Vendor Payments function. For more information, see [How to: Suggest Vendor Payments](payables-how-suggest-vendor-payments.md).
3. In the **Bank Payment Type** field on journal lines for payment that you want to make with checks, select one of the following options:

 - **Computer Check**: Select this option if you want to print a check for the amount on the payment journal line. You must print the checks before you can post the journal lines. You can only select **Computer Check** if the **Bal. Account Type** or the **Account Type** is **Bank Account**.

 - **Manual Check**: Select this option if you have created a check manually and want to create a corresponding check ledger entry for this amount. By using this option, you cannot print checks from Financials. You can only select **Manual Check** if the **Bal. Account Type** or the **Account Type** is **Bank Account**.

    **Note**: You must print computer checks before you post the related journal lines.
4. In case of computer checks, choose **Print Check**.
5. In the **Check** window, fill in the fields as necessary. Choose a field to read a short description of the field or link to more information.
6. Choose the **Print** button.

**Note**: If you want to print checks in more than one currency from different bank accounts, you must run the **Print Check** batch job separately for each currency and specify the appropriate bank account.

## To cancel printed checks that are not posted
You can cancel non-posted checks after they have been printed by using the **Void Check** action in the **Payment Journal** window.
1. In the **Payment Journal** window, choose the **Void Check**, and then choose which checks to cancel.

## To void checks
When check payment have been posted, you can only cancel (void) checks from the resulting bank ledger entries.

1. In the top right corner, choose the **Search for Page or Report** icon, enter **Bank Accounts**, and then choose the related link.
2. Select the relevant bank account, choose the **Edit** action, and then choose the **Check Ledger Entries** action.
3. In the **Check Ledger Entries** window, choose the **Void Check** action.
4. Select the **Void Check Only** check box.
5. Choose the **OK** button.

## See Also
[Manage Payables](payables-manage-payables.md)  
[Set Up Banking](bank-setup-banking.md)  
[How to: Export a Positive Pay file](finance-how-positive-pay.md)  
[Work With Dynamics 365 for Financials](ui-work-product.md)  
