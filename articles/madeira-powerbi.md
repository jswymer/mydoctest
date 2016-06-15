<properties
	pageTitle="Using the Project “Madeira” Content Pack for Power BI | Project “Madeira”"
    description="Using the Project “Madeira” content pack for Power BI"
	services="project-madeira"
	documentationCenter=""
	authors="edupont04"/>
<tags
    ms.service="project-madeira"
    ms.topic="get-started-article"
    ms.devlang="na"
    ms.tgt_pltfrm="na"
    ms.workload="na"
    ms.date="06/03/2016"
    ms.author="edupont04" />

# Using the Project "Madeira" Content Pack for Power BI
Getting insights into your Project "Madeira" data is easy with Power BI and the Project "Madeira" content pack. Power BI retrieves your data and then builds an out-of-the-box dashboard and reports based on that data.  

The content pack is preconfigured to work with sales data and financial data from the demonstration company that you get when you sign up for the Project "Madeira" preview.  

- Choose any visual on the dashboard to bring up one of seven underlying reports.  
- Filter the report or add fields that you want to monitor.  
- Pin this customized view to the dashboard to continue tracking.  
The dashboard and underlying reports refresh daily. You can control the refresh schedule and modify the frequency on the dataset.  

## Accessing Project "Madeira" in Power BI
To see your Project "Madeira" data in Power BI, you must have the following:  

- Access to Project "Madeira". For more information, see [Project "Madeira"](http://go.microsoft.com/fwlink/?LinkID=759714).  
- Access to Power BI. For more information, see [Power BI](https://powerbi.microsoft.com).

On the Power BI site, you can find additional information about [adding the Project "Madeira" content pack to Power BI](http://go.microsoft.com/fwlink/?LinkID=760850).  

To access the Project "Madeira" content pack in Power BI, on the connection page, you must specify the following information:

| Field       | Description              |
|-------------|--------------------------|
|**OData Feed URL**|The OData URL so Power BI can access data from your company, such as https://mybusiness.projectmadeira.com:7048/MS/OData/Company('CRONUS%20US').|
|**Authentication method**|Choose **Basic**.|
|**User name**|The email account that you used to sign up for Project "Madeira", such as *me@mybusiness.com*.|
|**Password**|This is the web service access key for your user account in Project "Madeira".|

This means that you must get two pieces of information from Project "Madeira": The OData URL and the web service access key for your user account.  
**Getting the URL**  
When you add Project "Madeira" to Power BI, you must specify a URL so Power BI can access data from your company. On the connection page, the URL is referred to as the **OData Feed URL**, and it must have the following format:

         https://mybusiness.projectmadeira.com:7048/MS/OData/Company('CRONUS%20US')  
In this example, *mybusiness* is the name of your Project "Madeira" service, and *CRONUS US* is the name of the demonstration company with *%20* representing the space in the name.   
To get the URL, in Project "Madeira", search for and open the **Web Services** window. This window lists the web services that are currently available, and you can copy the link from the **OData URL** field for one of the default OData web services.  
**Getting the web service access key**  
In order to use data from Project "Madeira", in Power BI, in the **Connect to Project "Madeira"** window, you must specify your user name, which is your email account, and a password. The password is the web service access key that is set up for your user account in Project "Madeira".  
To get a web service access key, in Project “Madeira”, search for the **Users** window, and then open the card for your user account. On the **Web Service Access** FastTab, copy the contents of the **Web Service Access Key** field. If the field is blank, in the ribbon, choose **Change Web Service Access Key**, choose the **Key Never Expires** field, and then choose the OK button. You can then copy the key.  

## Getting Data from Project "Madeira"
The Project "Madeira" dashboard shows the most typical reports that you will want to use to track your business. The data is extracted from your Project "Madeira" company using web services to read live data. In Project "Madeira", the **Web Services** window lists the web services that have been set up for you, including the following that are consumed by the content pack in Power BI:  

- ItemSalesAndProfit  
- ItemSalesByCustomer  
- powerbifinance  
- SalesDashboard  
- SalesOpportunities  
- SalesOrdersBySalesPerson  
- TopCustomerOverview  

**Note**: If you change the name of any of these web services, the data will not show up in Power BI.  
If you want to add use other data in Power BI, you must find the tables in Project "Madeira", expose them as web services, and then add them to the content pack. This is an advanced scenario, and we recommend that you start with the data that is already available in Power BI.  

## Troubleshooting
The Power BI dashboard relies on the published web services that are listed above, and it will show data from the demonstration company or your own company if you import data from your current finance solution. However, if something goes wrong, this section provides a workaround for the most typical issues.  

**"Parameter validation failed, please make sure all parameters are valid"**  
If you see this error after you enter your Project “Madeira” URL, make sure the following requirements are satisfied:  

- The URL follows exactly this pattern:

    https://mybusiness.projectmadeira.com:7048/MS/OData/Company('CRONUS%20US')  
- Delete any text after the company name in parenthesis  
- Make sure there are no trailing forward slash at the end of the URL.  
- Make sure that it is a secure connection as indicated by the URL starting with *https*.  


**"Login failed"**  
If you get a "login failed" error when you log in to the dashboard, using your Project “Madeira” credentials, then this can be caused by one of the following issues:

* The account you are using does not have permissions to read the Project “Madeira” data from your account.

    Verify your user account in Project "Madeira", and make sure that you have used the right web service access key as the password, and then try again.  
* The Project "Madeira"  instance that you are trying to connect to does not have a valid SSL certificate. In this case you'll see a more detailed error message ("unable to establish trusted SSL relationship").

    **Note**: Self-signed certificates are not supported.  


**"Oops"**  
If you see an "Oops" error dialog after you pass the authentication dialog, this is most frequently caused by a problem connecting to the data for the content pack.

* Verify that the URL follows the pattern that was specified earlier:

    https://mybusiness.projectmadeira.com:7048/MS/OData/Company('CRONUS%20US')  
* A common mistake is to specify the full URL for a specific web service:

    https://mybusiness.projectmadeira.com:7048/MS/OData/Company('CRONUS%20US')/powerbifinance  
* Or you might have forgotten to specify the company name:

    https://mybusiness.projectmadeira.com:7048/MS/OData/  


## See Also
[Welcome to Project "Madeira"](madeira-get-started.md)  
[Import Data from Other Finance Systems](upload-data.md)  
