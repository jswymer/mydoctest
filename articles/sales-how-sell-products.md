<properties
                pageTitle="How to: Sell Products| Financials"
                description="Describes how to use sales orders."
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
    ms.date="08/29/2016"
    ms.author="SorenGP" />

# How to: Sell Products
You create a sales order or sales invoice to record your agreement with a customer to sell certain products on certain delivery and payment terms.

**Note**: You use sales orders if your sales process requires that you can ship parts of an order quantity, for example, because the full quantity is not available at once. If you sell items by delivering directly from your vendor to your customer, as a drop shipment, then you must also use sales orders. For more information, see [How to: Make Drop Shipments](sales-how-drop-shipment.md). In all other aspects, sales orders work the same way as sales invoices. For more information, see [How to: Invoice Sales](sales-how-invoice-sales.md).

You can negotiate with the customer by first creating a sales quote, which you can convert to a sales order when you agree on the sale. For more information, see [How to: Make Offers](sales-how-make-offers.md).

After the customer has confirmed the agreement, for example after a quote process, you can send an order confirmation to record your obligation to deliver the products as agreed.

When you deliver the products, either fully or partially, you post the sales order as shipped or as shipped and invoiced to create the related item and customer ledger entries in your system. When you post the sales order, you can also email the document as a PDF attachment. You can have the email body prefilled with a summary of the order and payment information, such as a link to PayPal. For more information, see [How to: Send Documents by Email](ui-how-send-documents-email.md).

In business environments where the customer must pay before products are delivered, such as in retail, you must wait for the receipt of payment before you deliver the products. In most cases, you process incoming payments some weeks after delivery by applying the payments to their related posted, unpaid sales invoices. For more information, see [How to: Reconcile Payments Using Automatic Application](receivables-how-reconcile-payments-auto-application.md).

You can easily correct or cancel a posted sales invoice resulting from a sales order before it is paid. This is useful if you want to correct a typing mistake or if the customer requests a change early in the order process. For more information, see [How to: Correct or Cancel Unpaid Sales Invoices](sales-how-correct-cancel-sales-invoice.md). If the posted sales invoice is paid, then you must create a sales credit memo to reverse the sale. For more information, see [How to: Process Sales Returns or Cancellations](sales-how-process-sales-returns-cancellations.md).

Products can be both inventory items and services. For more information, see [How to: Register New Products](inventory-how-register-new-products.md). The sales order process is the same for both product types.

**Note**: In Financials, a product is referred to with the term “item”.

You can fill customer fields on the sales order in two ways depending on whether the customer is already registered.

## To create a sales order
1. On the Home page, choose the **Sales Order** action.  
2. In the **Customer** field, enter the name of an existing customer.

    Other fields in the **Sales Order** window are now filled with the standard information of the selected customer. If the customer is not registered, then follow these steps:

3. In the **Customer** field, enter the name of the new customer.
4. In the dialog box about registering the new customer, choose the **Yes** button.  
5. In the **Select a template for a new customer** window, choose a template to base the new customer card on, and then choose the **OK** button.

    A new customer card opens, prefilled with the information on the selected customer template. The **Name** field is prefilled with the new customer’s name that you entered on the sales order.
6. Proceed to fill in the remaining fields on the customer card. For more information, see [How to: Register New Customers](sales-how-register-new-customers.md).  
7. When you have completed the customer card, choose the **OK** button to return to the **Sales Order** window.

    Several fields on the sales order are now filled with information that you specified on the new customer card.
8. Fill in the remaining fields in the **Sales Order** window as necessary. Choose a field to read a short description of the field or link to more information.

    You are now ready to fill in the sales order lines with inventory items or services that you want to sell to the customer.

    If you have set up recurring sales lines for the customer, such as a monthly replenishment order, then you can insert these lines on the order by choosing the **Get Recurring Sales Lines** action.
9. On the **Lines** FastTab, in the **Item** field, enter the number of an inventory item or service.  
10. In the **Quantity** field, enter the number of items to be sold.

    **Note**: For items of type Service, the quantity is a time unit, such as hours, as indicated in the **Unit of Measure Code** field on the line.

    The **Line Amount** field is updated to show the value in the **Unit Price** field multiplied by the value in the **Quantity** field.

    The price and line amounts are shown with or without sales tax depending on what you selected in the **Prices Including Tax** field on the customer card.
11. In the **Line Discount %** field, enter a percentage if you want to grant the customer a discount on the product. The value in the **Line Amount** field is updated accordingly.

    If you have set up special item prices on the **Sales Prices and Sales Line Discounts** FastTab on the customer or item card, then the price and amount on the quote line are automatically updated if the agreed price criteria are met. For more information, see [Record Sales Price, Discount, and Payment Agreements](sales-how-record-sales-price-discount-payment-agreements.md).
12. To add a comment about the quote line that the customer can see on the printed sales quote, write a text in the **Description** field on an empty line.  
13. Repeat steps 10 through 13 for every item that you want to offer to the customer.

    The totals under the lines are automatically calculated as you create or modify lines.
14. In the **Invoice Discount Amount** field, enter an amount that should be deducted from the value shown in the **Total Incl. Tax** field.

    If you have set up invoice discounts for the customer, then the specified percentage value is automatically inserted in the **Invoice Discount %** field if the criteria are met, and the related amount is inserted in the **Inv. Discount Amount Excl. Tax** field. For more information, see [Record Sales Price, Discount, and Payment Agreements](sales-how-record-sales-price-discount-payment-agreements.md).
15. To only ship a part of the order quantity, enter that quantity in the **Qty. to Ship** field. The value is copied to the **Qty. to Invoice** field.
16. To only invoice a part of the shipped quantity, enter that quantity in the **Qty. to Invoice** field. The quantity must be lower than the value in the **Qty. to Ship** field.   
17. When the sales order lines are completed, choose the **Post and Send** action.
The **Post and Send Confirmation** dialog box opens showing the preferred sending method for the customer.

You can change the sending method by choosing the lookup button for the **Send Document to** field. For more information, see [How to: Set Up Document Sending Profiles](sales-how-setup-document-send-profiles.md).

The related item and customer ledger entries are now created in your system, and the sales order is output as a PDF document. When the sales order is fully posted, it is removed from the list of sales orders and replaced with new documents in the list of posted sales invoices and the list of posted shipments.

## See Also  
[Manage Sales](sales-manage-sales.md)  
[Set Up Sales](sales-setup-sales.md)  
[Inventory](inventory-manage-inventory.md)  
[How to: Send Documents by Email](ui-how-send-documents-email.md)  
[Work With Dynamics 365 for Financials](ui-work-product.md)
