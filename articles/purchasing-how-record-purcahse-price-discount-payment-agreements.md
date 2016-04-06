<properties
                pageTitle="How to: Record Purchase Prices and Discounts| Project “Madeira”" 
                description="Welcome to Project "Madeira"" 
                services="" 
                documentationCenter="Madeira"
                authors="edupont"/>

#How to: Record Purchase Prices and Discounts 
The different price and discount agreements that apply when you buy from different vendors must be defined so that the agreed rules and values are applied to purchase documents that you create for the vendors.

Concerning prices, you can have a special purchase price inserted on purchase lines if a certain combination of vendor, item, minimum quantity, unit of measure, or starting/ending date exists.

Concerning discounts, you can set up and use two types of purchase discounts:

|Discount Type|Description|
|-------------|-----------|
|**Purchase Line Discount**|An amount discount that is inserted on purchase lines if a certain combination of vendor, item, minimum quantity, unit of measure, or starting/ending date exists. This works in the same way as for purchase prices.|
|**Invoice Discount**|A percentage discount that is subtracted from the document total if the value amount of all lines on a purchase document exceeds a certain minimum.|

Because purchase line discounts and purchase prices are based on a combination of item and vendor, you can also enter this configuration from the item card, where the rules and values are defined. For more information, see [How to: Register New Products](inventory-how-register-new-products.md).

##To set up a special purchase price for a vendor
1. In the **Search** box, enter **Vendors**, and then choose the related link.
2. Open the relevant vendor card, and then choose the **Prices** action. 

    The **Purchase Type** field is prefilled with **Vendor**, and the **Purchase Code** field is prefilled with the vendor number.
3. Fill the fields on the line as necessary. Choose a field to read a short description of the field or link to more information. 
4. Fill a line for each combination for which the vendor grants you a purchase line discount.

##To set up a line discount for a vendor
1. In the **Search** box, enter **Vendors**, and then choose the related link.
2. Open the relevant vendor card, and then choose the **Line Discounts** action. 

    The **Purchase Type** field is prefilled with **Vendor**, and the **Purchase Code** field is prefilled with the vendor number.
3.  Fill the fields on the line as necessary. Choose a field to read a short description of the field or link to more information. 
4. Fill a line for each combination for which the vendor grants you a purchase line discount.

## To set up an invoice discount for a vendor
When your vendors have informed you which invoice discounts they grant, enter the invoice discount code on the vendor cards and set up the terms for each code.

1. In the **Search** box, enter **Vendors**, and then choose the related link.
2. Open the vendor card for a vendor that will be eligible for invoice discounts.
3. In the **Invoice Disc. Code** field, select a code for the relevant invoice discount terms to use to calculate invoice discounts for the vendor. 

    **Note**: Invoice discount codes are represented by existing vendor cards. This enables you to quickly assign invoice discount terms to vendors by picking the name of another vendors who will have the same terms.
    
    Proceed to set up new the purchase invoice discount terms.
4. In the **Vendor Card** window, choose the **Invoice Discounts** action. The **Vend. Invoice Discounts** window opens.
5. In the **Currency Code** field, enter the code for a currency that the invoice discount terms on the line applies to. Leave the field blank to set up invoice discount terms in LCY.
6. In the **Minimum Amount** field, enter the minimum amount that an invoice must have to be eligible for the discount.
7. In the **Discount %** field, enter the invoice discount as a percentage of the invoice amount.
8. Repeat steps 5 through 7 for each currency that the vendor will receive a different invoice discount for.

The invoice discount is now set up and assigned to the vendor in question. When you select the vendor code in the **Invoice Disc. Code** field on other vendor cards, the same invoice discount is assigned to those vendor.

##See Also  
[Set Up Purchasing](purchasing-setup-purchasing.md)  
[Manage Purchasing](purchasing-manage-purchasing.md)