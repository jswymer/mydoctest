<properties
                pageTitle="How to: Correct or Cancel Unpaid Purchase Invoices| Financials"
                description="How to: Correct or Cancel Unpaid Purchase Invoices"
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

# How to: Correct or Cancel Unpaid Purchase Invoices
You can correct or cancel a posted purchase invoice. This is useful if you want to correct a typing mistake, or if you want to change the purchase early in the order process.

If you have already paid for products on the posted purchase invoice, you cannot correct or cancel it from the posted purchase invoice itself. Instead, you must manually create a purchase credit memo to reverse the purchase. For more information, see [How to: Process Purchase Returns or Cancellations](purchasing-how-process-purchase-returns-cancellations.md).

In the **Posted Purchase Invoice** window, you can choose the **Correct** button or the **Cancel** button. When you correct or cancel a posted purchase invoice, the corrective purchase credit memo is applied to all general ledger and inventory ledger entries that were created when the initial purchase invoice was posted. This reverses the posted purchase invoice in your financial records and leaves the corrective posted purchase credit memo for your audit trail. In the following the use of **Correct** and **Cancel** is described.

## To correct a posted purchase invoice
1. In the top right corner, choose the **Search for Page or Report** icon, enter **Posted Purchase Invoices**, and then choose the related link.  
2. Select the posted purchase invoice that you want to correct.  

    **Note**: If the **Canceled** check box is selected, then you cannot correct the posted purchase invoice because it has already been corrected or canceled.
3. In the **Posted Purchase Invoice** window, choose **Correct**.

    A new purchase invoice with the same information is created where you can make the correction. For more information, see [How to: Record Purchases](purchasing-how-record-purchases.md). The **Canceled** field on the initial posted purchase invoice is changed to **Yes**.

    A purchase credit memo is automatically created and posted to void the initial posted purchase invoice.
4. Choose **Show Corrective Credit Memo** to view the posted purchase credit memo that voids the initial posted purchase invoice.

## To cancel a posted purchase invoice
1. In the top right corner, choose the **Search for Page or Report** icon, enter **Posted Purchase Invoices**, and then choose the related link.  
2. Select the posted purchase invoice that you want to cancel.

    **Note**: If the **Canceled** check box is selected, then you cannot cancel the posted purchase invoice because it has already been canceled or corrected.
3. In the **Posted Purchase Invoice** window, choose **Cancel**.

    A purchase credit memo is automatically created and posted to void the initial posted purchase invoice. The **Canceled** field on the initial posted purchase invoice is changed to **Yes**.
5. Choose **Show Corrective Credit Memo** to view the posted purchase credit memo that voids the initial posted purchase invoice.

## See Also
[Manage Purchasing](purchasing-manage-purchasing.md)  
[How to: Record Purchases](purchasing-how-record-purchases.md)  
[Work With Dynamics 365 for Financials](ui-work-product.md)
