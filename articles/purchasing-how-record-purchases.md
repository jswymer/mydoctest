<properties
                pageTitle="How to: Record Purchases| Project “Madeira”"
                description="How to: Record Purchases"
                services=""
                documentationCenter="Madeira"
                authors="edupont"/>

# How to: Record Purchases
You create a purchase invoice to record the cost of purchases and to track accounts payable. If you need to control an inventory, purchase invoices are also used to dynamically update inventory levels so that you can minimize your inventory costs and provide better customer service. The purchasing costs, including service expenses, and inventory values that result from posting purchase invoices contribute to profit figures and other financial KPIs on your Home page.

When you receive the inventory items, or when the purchased service is completed, you post the purchase invoice to update inventory and financial records and to activate payment to the vendor according to the payment terms. For more information, see [Make Payments](payables-make-payments.md)

**Caution**: Do not post a purchase invoice until you receive the products and know the final cost of the purchase, including any additional charges. Otherwise, your inventory value and profit figures may be skewed.

You can easily correct or cancel a posted purchase invoice before you pay the vendor. This is useful if you want to correct a typing mistake or if you want to change the purchase early in the order process. For more information, see [How to: Correct or Cancel Unpaid Purchase Invoices](purchasing-how-correct-cancel-unpaid-purchase-invoices.md). If you have already paid for products on the posted purchase invoice, then you must create a purchase credit memo to reverse the purchase. For more information, see [How to: Process Purchase Returns or Cancellations](purchasing-how-process-purchase-returns-cancellations.md).

Products can be both inventory items and services. For more information, see [How to: Register New Products](inventory-how-register-new-products.md). The purchase invoice process is the same for both product types.

**Note**: In Project "Madeira", a product is referred to with the term “item”.

You can fill vendor fields on the purchase invoice in two ways depending on whether the vendor is already registered.

## To create a purchase invoice
1. On tghe Home page, choose the **Purchase Invoice** action.  
2. In the **Vendor** field, enter the name of an existing customer.

    Other fields in the **Purchase Invoice** window are now filled with the standard information of the selected vendor. If the vendor is not registered, then follow these steps:
3. In the **Vendor** field, enter the name of the new vendor.
4. In the dialog box about registering the new vendor, choose the **Yes** button.
5. In the **Select a template for a new vendor** window, choose a template to base the new vendor card on, and then choose the **OK** button.
6. A new vendor card opens, prefilled with the information on the selected vendor template. The **Name** field is prefilled with the new vendor’s name that you entered on the purchase invoice.
7. Proceed to fill the remaining fields on the vendor card. For more information, see [How to: Register New Vendors](purchasing-how-register-new-vendors.md).  
8. When you have completed the vendor card, choose the **OK** button to return to the **Purchase Invoice** window.

    Several fields in the **Purchase Invoice** window are filled with information that you specified on the new vendor card
9. Fill the remaining fields in the **Purchase Invoice** window as necessary. Choose a field to read a short description of the field or link to more information.

    You are now ready to fill the purchase invoice lines with inventory items or services that you have purchased from the vendor.
    
    You are now ready to fill the purchase invoice lines with inventory items or services that you have purchased from the vendor.
    
    **Note**: If you have set up recurring purchase lines for the vendor, such as a monthly replenishment order, then you can insert these line on the invoice by choosing the **Get Recurring Purchase Lines** action.
10. On the **Lines** FastTab, in the **Item No.** field, enter the number of an inventory item or service.
11. In the **Quantity** field, enter the number of items purchased.

    **Note**: For items of type **Service**, the quantity is a time unit, such as hours, as indicated in the **Unit of Measure Code** field on the line.

    **Note**: For items of type **Service**, the quantity is a time unit, such as hours, as indicated in the **Unit of Measure Code** field on the line. 

    The **Line Amount** field is updated to show the value in the **Direct Unit Cost** field multiplied by the value in the **Quantity** field.

    The price and line amount are shown with or without sales tax depending on what you selected in the **Prices Including Tax** field on the vendor card.
11. In the **Invoice Discount Amount** field, enter an amount that should be deducted from the value shown in the **Total Incl. Tax** field at the bottom of the invoice.

12. In the **Invoice Discount Amount** field, enter an amount that should be deducted from the value shown in the **Total Incl. Tax** field at the bottom of the invoice. 
    
    **Note**: If you have set up invoice discounts for the vendor, then the specified percentage value is automatically inserted in the **Vendor Invoice Discount %** field if the criteria are met, and the related amount is inserted in the **Invoice Discount Amount** field.
13. When you receive the purchased items or services, choose **Post**. The purchase is now reflected in inventory and financial records, and the vendor payment is activated. The purchase invoice is removed from the list of purchase invoices and replaced with a new document in the list of posted purchase invoices.

## See Also  
[Manage Purchasing](purchasing-manage-purchasing.md)  
[Set Up Purchasing](purchasing-setup-purchasing.md)  
[How to: Purchase Products for a Sale](purchasing-how-purchase-products-sale.md)  
[How to: Register New Vendors](purchasing-how-register-new-vendors.md)  
[Work with Project "Madeira"](ui-work-product.md)
