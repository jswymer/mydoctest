<properties
                pageTitle="Manage Inventory| Financials"
                description="Describes how to manage physical items."
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
    ms.date="11/10/2016"
    ms.author="SorenGP" />

# Manage Inventory
For each physical product that you trade in you must create an item card of type Inventory. Items that you offer to customers but do not keep in inventory you can register as nonstock items, which you can convert to inventory items when necessary. You can increase or decrease the quantity of an item in inventory by posting directly to the item ledger entries, for example, after a physical count or if you do not record purchases. 

Inventory increases and decreases are naturally also recorded when you post purchase and sales documents respectively. For more information, see [How to: Record Purchases](purchasing-how-record-purchases.md), [How to: Sell Products](sales-how-sell-products.md), and [How to: Invoice Sales](sales-how-invoice-sales.md).

To increase your overview of items and to help you find them, you can categorize items and give them attributes to search and sort by.

## Inventory Reconciliation
When you post inventory transactions, such as sales shipments, purchase invoices, or inventory adjustments, the changed item costs are recorded in item value entries. To reflect this change of inventory value in your financial books, the inventory costs are automatically posted to the related inventory accounts in the general ledger. For each inventory transaction that you post, the appropriate values are posted to the inventory account, adjustment account, and COGS account in the general ledger.

Even though inventory costs are automatically posted to the general ledger, it is still necessary to ensure that the costs of goods are forwarded to the related outbound sales transaction, especially in situations where you sell goods before you invoice the purchase of those goods. This is referred to as cost adjustment, which you can perform manually or set up to happen automatically when you post an item transaction. For more information, see [How to: Adjust Item Costs](inventory-how-adjust-item-costs.md).   

**Note**: In Financials, a product is referred to using the term “item”.

|To |See |
|---|----|
|Create item cards for inventory items that you trade in.|[How to: Register New Products](inventory-how-register-new-products.md)|
|Increase or decrease an item’s inventory quantity, for example, after a physical count or as a simple way to record purchase receipts.|[How to: Adjust Inventory](inventory-how-adjust-inventory.md)|
|Appreciate or depreciate the value of one or more items in inventory by posting their current, calculated value.|[How to: Revalue Inventory](inventory-how-revalue-inventory.md)|
|Maintain an overview of items and help you find and sort items by organizing them in categories.|[How to: Categorize Items](inventory-how-categorize-items.md)|  
|Assign item attributes of different value types to your items to help you sort and find items.|[How to: Work with Item Attributes](inventory-how-work-item-attributes.md)|
|Create special item cards for items that you offer to customers but do not maintain inventory for.|[How to: Work with Nonstock Items](inventory-how-work-nonstock-items.md)|
|Adjust item costs, either automatically or manually, to forward cost changes from inbound entries to their related outbound entries.|[How to: Adjust Item Costs](inventory-how-adjust-item-costs.md)|

## See Also  
[Manage Purchasing](purchasing-manage-purchasing.md)  
[Manage Sales](sales-manage-sales.md)    
[Supply Chain](supply-chain.md)  
[Work With Dynamics 365 for Financials](ui-work-product.md)  
[Across Business Areas](ui-across-business-areas.md)
