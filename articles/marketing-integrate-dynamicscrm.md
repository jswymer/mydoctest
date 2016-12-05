<properties
                pageTitle="Manage your customer relationships using Dynamics 365 for Sales from inside Dynamics 365 for Financials | Financials"
                description="If you use Dynamics 365 for Sales for customer engagement, you can use Dynamics 365 for Financials for order processing and finances and have seamless integration in the lead-to-cash process"
                services="project-madeira"
                documentationCenter=""
                authors="edupont04"
/>
<tags
    ms.service="project-madeira"
    ms.topic="article"
    ms.devlang="na"
    ms.tgt_pltfrm="na"
    ms.workload="na"
    ms.date="11/28/2016"
    ms.author="edupont" />

# Manage Your Customer Relationships using Dynamics 365 for Sales from inside Dynamics 365 for Financials
If you use Dynamics 365 for Sales for customer engagement, you can use Financials for order processing and finances and have seamless integration in the lead-to-cash process.

When your application is set up to integrate with Dynamics 365 for Sales, you have access to Sales data from Financials and vice versa in some cases. This integration enables you to work with and synchronize data types that are common to both services, such as customers, contacts, and sales information, and keep the data up\-to\-date in both locations.  

**Note**: In Financials, Dynamics 365 for Sales is referred to as Dynamics CRM. For simplicity, the remainder of this article will use the terminology that is used in Financials.  

For example, the sales person in Dynamics CRM can use the price lists from Financials when they create a sales order. When they add the item to the sales order line in Dynamics CRM, they are also able to see the inventory level (availability) of the item from Financials. This data is published as part of the assisted setup guide, **Dynamics CRM Connection Setup**.  

**Note**: You'll have to set the experience to *Suite* in the **Company Information** window to get access to integration to the Dynamics CRM functionality.  

## Setting up the connection
From Home, you can access the **Dynamics CRM Connection Setup** guide that helps you set up the connection. Once that's done, you'll have a seamless coupling of Dynamics CRM records with Financials records.  

In the setup guide, you can choose which data to synchronize between the two services. You can also specify that you want to import your existing Dynamics CRM solution. In that case, you must specify an administrative user account.  

### Set up the user account for importing the solution
To import an existing Dynamics CRM solution, the setup guide uses an administrative account. This account must be a valid user in Dynamics CRM with the following security roles:

- System Administrator  
- Solution Customizer  

For more information, see [Create users and assign Microsoft Dynamics 365 (online) security roles](https://technet.microsoft.com/library/jj191623.aspx).  

This account is only used during the setup. Once the solution is imported into Financials, the account is no longer needed.

### Set up the user account for synchronization
The integration relies on a shared user account. So in your Office 365 subscription, you must create a dedicated user that will be used for synchronization between the two services. This account must already be a valid user in Dynamics CRM, but you do not have to assign security roles to the account because the setup guide will do that for you. You must specify this user account one or more times in the setup guide, depending how much synchronization you want to enable. For more information, see [Create a user account](https://technet.microsoft.com/library/jj191623.aspx#BKMK_create_users).

If you choose to enable *item availability*, the integration user account must have a web services access key. This is a two-step thing - in the Financials page for that user account, you must choose the **Change Web Service Key** button; and in the CRM connection setup guide, you must specify that user as the OData web service user.

If you choose to enable *sales order integration*, you must specify a user that can handle this synchronization - the integration user or another user account.

### Coupling records
In the setup guide, you can choose the synchronize between the two services. But later, you can also set up synchronization of specific types of data. This is referred to as *coupling*, and this section provides recommendations for what you must take into consideration.

For example, if you want to see Dynamics CRM accounts as customers in Financials, you must couple the two types of records. It is not very complicated - you open the Customer list in Financials, and there is an action in the ribbon to couple this data with Dynamics CRM. Then you specify which Financials customers match which accounts in Dynamics CRM.

In certain areas, the functionality relies on you couple certain sets of data before other sets of data as shown in the following list:

- Customers and accounts  
    - Couple salespeople with Dynamics CRM users first  
- Items and resources  
    - Couple units of measure with Dynamics CRM unit groups first  
- Items and resource prices  
    - Couple customer price groups with Dynamics CRM prices first  

**Note**: If you are using prices in foreign currencies, make sure that you couple currencies to Dynamics CRM transaction currencies.

Dynamics CRM Sales Orders depends on additional information like customers, units of measure, currencies, customer price groups, items and/or resources. In order for Dynamics CRM Sales Order to work seamlessly, you must couple customers, units of measure, currencies, customer price groups, items and/or resources first.

## See Also
[Relationship Management](marketing-relationship-management.md)  
[Work With Dynamics 365 for Financials](ui-work-product.md)  
