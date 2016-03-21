<properties
	pageTitle="Using the Project "Madeira" Content Pack for Power BI | Project Madeira"
    description="Using the Project "Madeira" content pack for Power BI" 
	services="" 
	documentationCenter="Madeira"
	authors="edupont"/>
# Using the Project "Madeira" Content Pack for Power BI
Getting insights into your Project "Madeira" data is easy with Power BI and the Project "Madeira" content pack. Power BI retrieves your data and then builds an out-of-the-box dashboard and reports based on that data.  

The content pack is preconfigured to work with sales data and financial data from the demonstration company that you get when you sign up for the Project "Madeira" preview. Choose any visual on the dashboard to bring up one of seven underlying reports. Filter the report or add fields that you want to monitor. Pin this customized view to the dashboard to continue tracking. The dashboard and underlying reports refresh daily. You can control the refresh schedule and modify the frequency on the dataset.  

## Using the Content Pack in Power BI
To use the content pack, you must have the following:
1. Access to Project "Madeira".
For more information, see [Project "Madeira](http://go.microsoft.com/fwlink/?LinkID=759714).
2. Access to Power BI.
For more information, see [powerbi.microsoft.com](https://powerbi.microsoft.com).

On the Power BI site, you can find additional information about adding the Project "Madeira" content pack to Power BI[here](http://go.microsoft.com/fwlink/?LinkID=760850).  

### Getting the URL
When you add Project "Madeira" to Power BI, you must specify a URL so Power BI can access data from your company. In the connection page, the URl is referred to as the **OData Feed URL**, which is rather cryptic, but the URL follows format as shown in this example:

        - https://*mycronusus*.projectmadeira.com:7048/NAV/OData/Company('*CRONUS%20US*')
  
In this example, *mycronusus* is the name of your Project "Madeira" instance, and *CRONUS US* is the name of the demonstration company with *%20* representing the space in the name.  

### Web Service Access Keys
In order to use data from Project "Madeira", you will need to create a web service access key for your user account. This can be done on the User page in Project “Madeira”
On the User Card page select the Web Service Access Fasttab and select the Assistedit button on the Web service Access Key field


## Getting Data from Project "Madeira"
The Project "Madeira" content pack for Power BI uses web services to read your data. In Project "Madeira", the Web Services window lists the web services that have been set up for you, including the following that are consumed by the content pack in Power BI:
- ItemSalesAndProfit
- ItemSalesByCustomer
- powerbifinance
- SalesDashboard
- SalesOpportunities
- SalesOrdersBySalesPerson
- TopCustomerOverview
>**Note**: If you change the name of any of these web services, the data will not show up in Power BI.  
If you want to add use other data in Power BI, you must find the tables in Project "Madeira", expose them as web services, and then add them to the content pack. This is an advanced scenario, and we recommend that you start with teh data that is already available in Power BI.  
  

## Troubleshooting

## See Also
["Welcome to Project "Madeira"](madeira-get-started.md)  