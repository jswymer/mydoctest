<properties
	pageTitle="Sales and Inventory Forecast | Project “Madeira”"
        description="Provides information about the Sales and Inventory Forecast extension."
        services="project-madeira"
        documentationCenter=""
        authors="edupont04"/>
<tags
    ms.service="project-madeira"
    ms.topic="article"
    ms.devlang="na"
    ms.tgt_pltfrm="na"
    ms.workload="na"
    ms.date="06/24/2016"
    ms.author="edupont04" />

# Sales and Inventory Forecast for Project "Madeira"
This extension uses Microsoft Azure Machine Learning (Azure ML) capabilities to predict future sales based on your sales history to help you avoid inventory shortage.  
The Sales and Inventory Forecast extension is installed and ready to use when you first sign up for Project "Madeira". However, you must set up how often you want to refresh the forecast before you can see the sales forecast for your inventory items.  
  
## Use Forecasting in Daily Work
The first place you meet the extension is probably in the **Items** list. For each item in your inventory, the extension calculates predicted sales based on historical sales data for that item. The forecast shows up in the grey FactBox pane, and if you choose Item Forecast, you will see a menu of the things that the extension can help you do:
- Create purchase invoices  
    This opens the **Purchase Invoice** window for you. Here, the extension uses Azure ML to automatically add a line for the inventory item you were looking at earlier, and add the vendor that you usually buy that item from. You can change the vendor and add other items to the purchase invoice as appropriate. 
- See a sales forecast  
    This shows a forecast of future sales based on historical data. The chart is blank if the calculation shows that the variance is too high. For more information, see the troubleshooting section.  
- See an inventory forecast  
    This shows a forecast of future stock based on historical data. The chart is blank if your current inventory is negative for the item. For more information, see the troubleshooting section.

From the same menu, you can also access the setup. Here you specify how frequently you want to refresh the calculation that generates the forecast. We recommend that you set this to monthly or weekly.   

### Troubleshooting
 
  
## See Also
[Manage Sales](sales-manage-sales.md)  
[Manage Inventory](inventory-manage-inventory.md)  
[Customizing Project “Madeira” Using Extensions](ui-extensions.md)  
  