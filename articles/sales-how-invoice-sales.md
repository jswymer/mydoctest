<properties
                pageTitle="How to: Invoice Sales| Financials"
                description="Describes how to use sales invoices."
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
    ms.date="10/31/2016"
    ms.author="SorenGP" />

# How to: Invoice Sales
You create a sales invoice or sales order to record your agreement with a customer to sell certain products on certain delivery and payment terms.  
  
**Note:** There are a couple of scenarios where you must use a sales order instead of a sales invoice:  

- If you need to ship only part of an order quantity, for example, because the full quantity is not onhand.  
- If you sell items that your vendor delivers directly to your customer, known as drop-shipping. For more information, see [How to: Make Drop Shipments](sales-how-drop-shipment.md).  
  
In all other aspects, sales orders and sales invoices work the same way. For more information, see [How to: Sell Products](sales-how-sell-products.md).

You can negotiate with the customer by first creating a sales quote, which you can convert to a sales invoice when you agree on the sale. For more information, see [How to: Make Offers](sales-how-make-offers.md).

If the customer decides to buy, you post the sales invoice to create the related quantity and value entries. When you post the sales invoice, you can also email the document as a PDF attachment. You can have the email body prefilled with a summary of the invoice and payment information, such as a link to PayPal. For more information, see [How to: Send Documents by Email](ui-how-send-documents-email.md).

In business environments where the customer must pay before products are delivered, such as in retail, you must wait for the receipt of payment before you deliver the products. In most cases, you process incoming payments some weeks after delivery by applying the payments to their related posted, unpaid sales invoices. For more information, see [How to: Reconcile Payments Using Automatic Application](receivables-how-reconcile-payments-auto-application.md).

You can easily correct or cancel a posted sales invoice before it is paid. For example, this is useful if you want to correct a typing mistake or if the customer requests a change early in the order process. For more information, see [How to: Correct or Cancel Unpaid Sales Invoices](sales-how-correct-cancel-sales-invoice.md). If the posted sales invoice is paid, then you must create a sales credit memo to reverse the sale. For more information, see [How to: Process Sales Returns or Cancellations](sales-how-process-sales-returns-cancellations.md).

Products can be both inventory items and services. For more information, see [How to: Register New Products](inventory-how-register-new-products.md). The sales invoice process is the same for both product types.

**Note:** In Financials, a product is referred to with the term “item”.

You can fill customer fields on the sales invoice in two ways depending on whether the customer is already registered.

## To create a sales invoice
1. On the Home page,  choose the **Sales Invoice** action.  
3. In the **Customer** field, enter the name of an existing customer.

   Other fields in the **Sales Invoice** window contain standard information about the selected customer. If the customer is not registered, follow these steps:
      
4. In the **Customer** field, enter the name of the new customer.
5. In the dialog box about registering the new customer, choose the **Yes** button.
6. In the **Select a template for a new customer** window, choose a template to base the new customer card on, and then close the window.
7. A new customer card displays the information on the selected customer template. Fill in the remaining fields. For more information, see [How to: Register New Customers](sales-how-register-new-customers.md).  
8. After you complete the customer card, choose the **OK** button to return to the **Sales Invoice** window.
  
   Several fields on the sales invoice are now filled with information that you specified on the new customer card.  
  
9. Fill in the remaining fields in the **Sales Invoice** window as necessary. Choose a field to read a short description of the field or link to more information.  
  
   You are now ready to fill in the sales invoice lines with inventory items or services that you want to sell to the customer.  
  
   If you have set up recurring sales lines for the customer, such as a monthly replenishment order, then you can insert these lines on the invoice by choosing the **Get Recurring Sales Lines** action.  
  
10. On the **Lines** FastTab, in the **Item** field, enter the number of an inventory item or service.  
11. In the **Quantity** field, enter the number of items to be sold.  
  
    **Note:** If the item is a service, the quantity is a time unit, such as hours, as indicated in the **Unit of Measure Code** field on the line.  
  
    The value in the **Line Amount** field is calculated as *Unit Price* * *Quantity*.  
  
    The price and line amounts are with or without sales tax, depending on what you selected in the **Prices Including Tax** field on the customer card.  
  
12. If you want to give a discount, enter a percentage in the **Line Discount %** field. The value in the **Line Amount** field updates accordingly.  
  
    If special item prices are set up on the **Sales Prices and Sales Line Discounts** FastTab on the customer or item card, the price and amount on the quote line automatically update if the price criteria is met. For more information, see [Record Sales Price, Discount, and Payment Agreements](sales-how-record-sales-price-discount-payment-agreements.md).  
  
13. To add a comment about the quote line that the customer can see on the printed sales quote, write a text in the **Description** field on an empty line.  
14. Repeat steps 10 through 13 for every item that you want to offer to the customer.  
  
    The totals under the lines are automatically calculated as you create or modify lines.  
  
15. In the **Invoice Discount Amount** field, enter an amount that should be deducted from the value shown in the **Total Incl. Tax** field.
  
    If you have set up invoice discounts for the customer, then the specified percentage value is automatically inserted in the **Invoice Discount %** field if the criteria are met, and the related amount is inserted in the **Inv. Discount Amount Excl. Tax** field. For more information, see [Record Sales Price, Discount, and Payment Agreements](sales-how-record-sales-price-discount-payment-agreements.md).  
  
17. When the sales invoice lines are completed, choose the **Post and Send** action.  
  
The **Post and Send Confirmation** dialog box displays the preferred sending method for the customer. You can change the sending method by choosing the lookup button for the **Send Document to** field. For more information, see [How to: Set Up Document Sending Profiles](sales-how-setup-document-send-profiles.md).

The related item and customer ledger entries are now created in your system, and the sales invoice is output as a PDF document. The sales invoice is removed from the list of sales invoices and replaced with a new document in the list of posted sales invoices.
  
## See Also  
[Manage Sales](sales-manage-sales.md)  
[Set Up Sales](sales-setup-sales.md)  
[Inventory](inventory-manage-inventory.md)  
[How to: Send Documents by Email](ui-how-send-documents-email.md)  
[Work With Dynamics 365 for Financials](ui-work-product.md)
