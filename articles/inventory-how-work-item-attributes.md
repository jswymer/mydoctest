<properties
                pageTitle="How to: Work with Item Attributes| Project “Madeira”"
                description="How to: Work with Item Attributes"
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

# How to: Work with Item Attributes
When a customer inquiries about an item, either in correspondence or through a web shop, the customer may ask or search according to characteristics, such as size and color. To provide this customer service, you can assign item attribute values of different types to your items, which can then be used when searching for items.

## To create an item attribute
1. In the top right corner, choose the **Search for Page or Report** icon, enter **Item Attributes**, and then choose the related link.
2. In the **Item Attributes** window, choose the **New** action.
3. In the **Item Attribute** window, fill the fields as necessary. Choose a field to read a short description of the field or link to more information.

**Note**: If you select **Option** in the **Type** field, then you can choose the **Item Attribute Values** action to select or set up item attribute values. For more information, see the "To assign item attribute values to item attributes" section.  

## To assign item attribute values to an item attribute
1. In the **Item Attributes** window, select the item attribute that you want to assign values to, and then choose the **Item Attribute Values** action.
2. In the **Item Attribute Values** window, fill the fields as necessary. Choose a field to read a short description of the field or link to more information.


**Note**: You can also assign item attribute values from an item attribute card. For more information, see the note in the ""To create an item attribute"" section.
 
## To assign item attributes to an item
1. In the top right corner, choose the **Search for Page or Report** icon, enter **Items**, and then choose the related link.
2. In the **Items** window, select the item that you want to assign item attributes to, and then choose the **Attributes** action.
3. In the **Item Attribute Values** window, choose the AssistEdit button in the **Attribute** field, and then select an existing item attribute.
4. In the **Value** field, choose the AssistEdit button and select an existing item attribute value. 
5. Repeat step 3 and 4 for all item attributes that you want to assign to the item.

## To filter by item attributes
1. In the top right corner, choose the **Search for Page or Report** icon, enter **Items**, and then choose the related link.
2. In the **Items** window, choose the **Filter by Attributes** action.
3. In the **Filter Items by Attribute** window, choose the AssistEdit button in the **Attribute** field and select an item attribute.
4. In the **Value** field, choose the AssistEdit button and select an attribute value to filter items by.

    **Note**: You can only select values directly for item attributes that have fixed values, such as Color. For item attributes that have variable values, such as Width, you must specify the item attribute value by first selecting a condition. See step 5.
5. In the **Value** field for a variable item attribute, choose the AssistEdit button.
6. In the **Specify Filter Value** window, in the **Condition** field, choose the drop-down arrow and select a condition.
7. In the **Value** field, enter an attribute value to filter items by.

    **Example**: To filter on items where the material description begins with "blue", fill the fields as follows: **Attribute** field: Material Description, **Condition** field: Begins With, **Value** field: blue.
8. Choose the **OK** button.   

The items in the **Items** window are filtered by the specified item attribute values.
 
## See Also  
[How to: Register New Products](inventory-how-register-new-products.md)  
[Manage Inventory](inventory-manage-inventory.md)  
[Work With Project "Madeira"](ui-work-product.md)
