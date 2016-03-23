<properties
	pageTitle="Using the Project “Madeira” Content Pack for Power BI | Project Madeira"
    description="Using the Project “Madeira” content pack for Power BI" 
	services="" 
	documentationCenter="Madeira"
	authors="edupont"/>
# Using the Project "Madeira" Content Pack for Power BI
Getting insights into your Project "Madeira" data is easy with Power BI and the Project "Madeira" content pack. Power BI retrieves your data and then builds an out-of-the-box dashboard and reports based on that data.  

The content pack is preconfigured to work with sales data and financial data from the demonstration company that you get when you sign up for the Project "Madeira" preview. Choose any visual on the dashboard to bring up one of seven underlying reports. Filter the report or add fields that you want to monitor. Pin this customized view to the dashboard to continue tracking. The dashboard and underlying reports refresh daily. You can control the refresh schedule and modify the frequency on the dataset.  

## Accessing Project "Madeira" in Power BI
To see your Project "Madeira" data in Power BI, you must have the following:
- Access to Project "Madeira".
For more information, see [Project "Madeira"](http://go.microsoft.com/fwlink/?LinkID=759714).
- Access to Power BI.
For more information, see [powerbi.microsoft.com](https://powerbi.microsoft.com).

On the Power BI site, you can find additional information about adding the Project "Madeira" content pack to Power BI[here](http://go.microsoft.com/fwlink/?LinkID=760850).  
  
To access the Project "Madeira" content pack in Power BI, you must get two pieces of information from Project "Madeira": The OData URL and the web service access key for your user account.
- **Getting the URL**  
When you add Project "Madeira" to Power BI, you must specify a URL so Power BI can access data from your company. In the connection page, the URL is referred to as the **OData Feed URL**, and it must have the following format:

        - https://*mycronusus*.projectmadeira.com:7048/NAV/OData/Company('*CRONUS%20US*') 
In this example, *mycronusus* is the name of your Project "Madeira" instance, and *CRONUS US* is the name of the demonstration company with *%20* representing the space in the name. To get the URL, in Project "Madeira", search for the **Web Services** page, and then copy the link from one of the default OData web services.
- **Getting the web service access key**  
In order to use data from Project "Madeira", you will need to create a web service access key for your user account. In Project “Madeira”, search for the **Users** page, and then open the card for your user account. Here you can generate a new web services access key and copy it to the Password field in the Power BI connection page. The user name is the email account that you use for Project "Madeira".  
  
## Getting Data from Project "Madeira"
The Project "Madeira" dashboard shows the most typical reports that you will want to use to track your business. The data is extracted from your Project "Madeira" company using web services to read live data. In Project "Madeira", the **Web Services** window lists the web services that have been set up for you, including the following that are consumed by the content pack in Power BI:
- ItemSalesAndProfit
- ItemSalesByCustomer
- powerbifinance
- SalesDashboard
- SalesOpportunities
- SalesOrdersBySalesPerson
- TopCustomerOverview
>**Note**: If you change the name of any of these web services, the data will not show up in Power BI.  
If you want to add use other data in Power BI, you must find the tables in Project "Madeira", expose them as web services, and then add them to the content pack. This is an advanced scenario, and we recommend that you start with the data that is already available in Power BI.  

## Troubleshooting
The Power BI dashboard relies on the published web services that are listed above, and it will show data from the demonstration company or your own company if you import data from your current finance solution. However, if something goes wrong, this section provides a workaround for the most typical issues.  

**"Parameter validation failed, please make sure all parameters are valid"**
If you see this error after you enter your Project “Madeira” URL, make sure the following requirements are satisfied:
- The URL follows exactly this pattern 
https://*mycronusus*.projectmadeira.com:7048/NAV/OData/Company('*CRONUS%20US*')
- Delete any text after the company name in parenthesis 
- Make sure there are no trailing forward slash at the end of the URL.
- Make sure the URL is uses a secure connection as indicated by the URL starting with *https*.  

**"Login failed"**
If you get a "login failed" error when you log in to the dashboard, using your Project “Madeira” credentials, thenthis can be caused by one of the following issues:
- The account you are using does not have permissions to read the Project “Madeira” data from your account. Verify your user account in Project "Madeira", and make sure that you have used the right web service access key as the password, and then try again. 
- The Project "Madeira"  instance that you are trying to connect to does not have a valid SSL certificate. In this case you'll see a more detailed error message ("unable to establish trusted SSL relationship"). Note that self-signed certs are not supported.  

**"Oops"**  
If you see an "Oops" error dialog after you pass the authentication dialog, this is most frequently caused by a problem connecting to the data for the content pack. 
Verify that the URL follows the pattern that was specified earlier: https://*mycronusus*.projectmadeira.com:7048/NAV/OData/Company('*CRONUS%20US*')  
A common mistake is to specify the full URL for a specific web service:  
https://*mycronusus*.projectmadeira.com:7048/NAV/OData/Company('*CRONUS%20US*')/powerbifinance  
Or you might have forgotten to specify the company name: 
https://*mycronusus*.projectmadeira.com:7048/NAV/OData/  

 
## See Also
[Welcome to Project "Madeira"](madeira-get-started.md)  
[Import Data from Other Finance Systems](upload-data.md)  
  