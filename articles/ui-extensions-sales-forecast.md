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
    ms.date="07/15/2016"
    ms.author="edupont04" />

# Sales and Inventory Forecast for Project "Madeira"
Inventory management is a trade-off between customer service and managing your cost. On one hand, a low inventory requires less working capital, but, on the other hand, stock-outs potentially lead to missed sales. The Sales and Inventory Forecast extension predicts potential sales using historical data and gives a clear overview of expected stock-outs. Based on the forecast, the extension helps create replenishment requests to your vendors and saves you time.  

## Setting up forecasting
In Project "Madeira", the connection to Azure Machine Learning (Azure ML) is already set up for you. But you can configure the forecast to use a different type of period to report by, such as changing from forecasting by month to forecasting by quarter. You can also choose the number of periods to calculate the forecast by, depending on how granular you want the forecast to be. We suggest that you forecast by month and with a 12 month horizon for the forecast.  

## Using the forecasts
The extension uses Azure ML capabilities to predict future sales based on your sales history to help you avoid inventory shortage. For example, when you choose an item in the **Items** window, the chart in the **Item Forecast** pane shows the estimated sales of this item in the coming period. This way you can see if you are likely to run out of stock of the item soon.  

You can also use the extension to suggest when to stock up on inventory. For example, if you crate a purchase order for Fabrikam because you want to buy their new desk chair, the Sales and Inventory Forecast extension will suggest that you also restock on the LONDON swivel chair that you usually buy from this vendor. This is because the extension forecasts that you will run out of stock of the LONDON swivel chair in the coming two months, so you might want to order more chairs already now.  

## See Also
[Manage Sales](sales-manage-sales.md)  
[Manage Inventory](inventory-manage-inventory.md)  
[Customizing Project “Madeira” Using Extensions](ui-extensions.md)  
