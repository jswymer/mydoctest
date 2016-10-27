<properties
                pageTitle="Set Up Dimensions| Financials"
                description="Describes how to set up dimensions."
                services="project-madeira"
                documentationCenter=""
                authors="bholtorf"/>

<tags
    ms.service="project-madeira"
    ms.topic="article"
    ms.devlang="na"
    ms.tgt_pltfrm="na"
    ms.workload="na"
    ms.date="10/24/2016"
    ms.author="bholtorf" />

#Set Up Dimensions
You can define the dimensions and dimension values you want to use to categorize journals and documents, such as sales orders and purchase orders. You set up dimensions in the **Dimensions** window, where you create one line for each dimension, such as *Project*, *Department*, *Area*, and *Salesperson*.

You also set up values for dimension. For example, these might be departments in your company. Dimension values can be set up in a hierarchical structure similar to the chart of accounts, so that data can be broken down into various levels of granularity, and subsets of dimension values can be totaled. You can define as many dimensions and dimension values as you need in your company, and everyone in your company can use them.

You can also set up some global and shortcut dimensions:  
  
- **Global dimensions** are used as filters, for example, on reports and batch jobs. You can use only two global dimensions, so choose dimensions you will use often. 
- **Shortcut dimensions** are available as a field on journal and document lines. You can create up to six of these.  
  
## Set Up Default Dimensions for Customers, Vendors, and Other Accounts  
You can assign a default dimension for a specific account. The dimension will be copied to the journal or document when you enter the account number on a line, but uou can delete or change the code on the line if appropriate. You can also make a dimension required for posting an entry with a specific type of account.  

## Translate the Names of Dimensions
When you create a dimension, and especially a shortcut dimension, what you're actually creating a custom field or column heading. If your business is international, you can provide translations for the name of the dimension. Documents that include the dimension will use the translated name, where applicable.   
  
## See Also  
[Dimensions](finance-dimensions.md)  
[Set Up Core Financial Processes](finance-setup-finance.md)
