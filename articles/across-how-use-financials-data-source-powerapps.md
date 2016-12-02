<properties
	pageTitle="Using Dynamics 365 for Financials as a PowerApps Data Source | Financials"
    description="You can make your Financials data available as a data source in Power Apps."
	services="project-madeira"
	documentationCenter=""
	authors="edupont04"/>
<tags
    ms.service="project-madeira"
    ms.topic="article"
    ms.devlang="na"
    ms.tgt_pltfrm="na"
    ms.workload="na"
    ms.date="12/02/2016"
    ms.author="edupont" />

# Using Dynamics 365 for Financials as a PowerApps Data Source
You can make your Financials data available as a data source in PowerApps.  

**Note**: You must have a valid account with Financials and with PowerApps.  

## To add Financials as a data source in PowerApps
1.	In your browser, navigate to [powerapps.microsoft.com](https://powerapps.microsoft.com/en-us/), and then sign in.
2.  In the left navigation pane, choose **New App**.
3.  Choose your editor, PowerApps Studio for Windows or PowerApps Studio for Web.

	PowerApps Studio for Windows is a desktop application used to create and publish PowerApps. The PowerApps Studio for Web is the online solution used to create and publish PowerApps.

4.	The next step to create a PowerApp is to select your data. Choose the Arrow icon then choose the **New connection** option in the upper left side of the page.
5. In the list of available connections, choose **Dynamics 365 for Financials**.
6.	PowerApps will display a connection page that prompts you for the information that is required to connect to your Financials data. To connect, you must specify an OData URL, username, password, and company name.

	For the *OData URL*, you can copy the OData V4 URL of any of the web services that are listed in the **Web Services** page in Financials, such as `https://mycompany.financials.dynamics.com:7048/MS/ODataV4/`.  

	For the *Company Name*, use the name that is shown in the **Name** field in the **Company Information** window in Financials. If your Financials contains multiple companies, choose the relevant company name from the list in the **Companies** window. In both cases, make sure that the name that you specify in the PowerApps wizard matches exactly the text shown in Financials, such as `My Company`.

	For the username and password, use the name and web service access key that are specified for your account in the **Users** window in Financials. For example, your username is *ADMIN*, and the web service access key that serves as your password is *EgzeUFQ9Uv0o5O0lUMyqCzo1ueUW9yRF3SsLU=*.

7.  Choose the **Connection** button to continue. PowerApps will display a default dataset for Financials. Choose the **Default** dataset.

	PowerApps will display a list of tables that are available from Financials. These tables, or end points,  represent all the web services you have published from Financials.

    Alternatively, create a new web service URL in Financials by using the **Create Data Set** action in the **Web Services** page, using the **Set Up Reporting** Assisted Setup guide, or by choosing the **Edit in Excel** action in any lists.

8.	Choose the table that you want to use for your PowerApp, and then choose the **Connect** button.
7.  Repeat the previous steps to add additional Financials data to your Power BI data model.

    **Note**:  Once you have successfully connected to Financials, you will not be prompted again for the OData URL, username, or password.

At this point, you have successfully connected to your Dynamics 365 data and are ready to begin building your PowerApp. For more information, see the [PowerApps documentation](https://powerapps.microsoft.com/tutorials/getting-started/).

## See Also
[Welcome to Dynamics 365 for Financials](madeira-get-started.md)  
[Migrate Business Data from Other Finance Systems](upload-data.md)  
[Set Up Dynamics 365 for Financials](madeira-setup.md)  
[Finance](finance.md)  
