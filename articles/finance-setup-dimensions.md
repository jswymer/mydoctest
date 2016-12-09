<properties
                pageTitle="Set Up Dimensions| Financials"
                description="You can define the dimensions and dimension values you want to use to categorize journals and documents, such as sales orders and purchase orders."
                services="project-madeira"
                documentationCenter=""
                authors="bholtorf"/>

<tags
    ms.service="project-madeira"
    ms.topic="article"
    ms.devlang="na"
    ms.tgt_pltfrm="na"
    ms.workload="na"
    ms.date="12/08/2016"
    ms.author="bholtorf" />

# Set Up Dimensions
You can define the dimensions and dimension values you want to use to categorize journals and documents, such as sales orders and purchase orders. You set up dimensions in the **Dimensions** window, where you create one line for each dimension, such as *Project*, *Department*, *Area*, and *Salesperson*.

You also set up values for dimension. For example, these might be departments in your company. Dimension values can be set up in a hierarchical structure similar to the chart of accounts, so that data can be broken down into various levels of granularity, and subsets of dimension values can be totaled. You can define as many dimensions and dimension values as you need in your company, and everyone in your company can use them.

You can also set up some global and shortcut dimensions:  

- **Global dimensions** are used as filters, for example, on reports and batch jobs. You can use only two global dimensions, so choose dimensions you will use often.
- **Shortcut dimensions** are available as a field on journal and document lines. You can create up to six of these.  

**Note**: This functionality requires that your experience is set to **Suite**. For more information, see [Customizing the Dynamics 365 for Financials Experience](ui-experiences.md).

## Set up default dimensions for Customers, Vendors, and other accounts  
You can assign a default dimension for a specific account. The dimension will be copied to the journal or document when you enter the account number on a line, but you can delete or change the code on the line if appropriate. You can also make a dimension required for posting an entry with a specific type of account.  

## Translate the names of dimensions
When you create a dimension, and especially a shortcut dimension, what you're actually creating a custom field or column heading. If your business is international, you can provide translations for the name of the dimension. Documents that include the dimension will use the translated name, where applicable.   

## Example
Let us say that your company wants to be able to track transactions based on organizational structure and geographic locations. You then set up two dimensions in the **Dimensions** window:

- **AREA**  
- **DEPARTMENT**  

|Code |Name |Code Caption |Filter Caption|
|-----|-----|-------------|--------------|
|AREA |Area |Area Code    |Area Filter   |
|DEPARTMENT |Department |Department Code |Department Filter |


For **AREA**, you add the following dimension values:

|Code |Name |Dimension Value Type |
|-----|-----|---------------------|
|10   |Americas |Begin-Total |
|20   |  North America |Standard |
|30   |  Pacific |Standard |
|40   |  South America |Standard |
|50   |Americas, Total |End-Total |
|60   |Europe |Begin-Total |
|70   |  EU |Standard |
|80   |  Non-EU |Standard |
|90   |Europe, Total |End-Total |

For the two main geographies, Americas and Europe, you add subcategories by indenting the dimension values. With this setup, you'll be able to report on sales or expenses in regions, and to get totals for the main geographies. you could also choose to use countries/regions and your dimension values, or counties or cities, depending on your business.  
**Note**: If you want to set up a hierarchy you must make sure that the codes are in alphabetical order. This includes the codes of the dimension values that are standard.  

For **DEPARTMENT**, you add the following dimension values:

|Code |Name |Dimension Value Type |
|-----|-----|---------------------|
|ADMIN |Administration |Standard |
|PROD  |Production |Standard |
|SALES  |Sales |Standard |

With this set up, you then add your two dimensions as the two global dimensions in the **General Ledger Setup** window. This means that you can use AREA and DEPARTMENT as filters for general ledger entries, as well as on all reports and account schedules. Both global dimensions are also automatically made available for use on entry lines and document headers as shortcut dimensions.  

With this set up, you can start adding dimensions to documents and journals. For more information, see [Dimensions](finance-dimensions.md).  

## See Also  
[Dimensions](finance-dimensions.md)  
[Set Up Core Financial Processes](finance-setup-finance.md)  
[Work With Dynamics 365 for Financials](ui-work-product.md)
