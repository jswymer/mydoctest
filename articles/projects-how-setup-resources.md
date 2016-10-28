<properties
                pageTitle="How to: Set Up Resources| Financials"
                description="Describes how to prepare the system to use resources in projects."
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
    ms.date="10/24/2016"
    ms.author="SorenGP" />

# How to: Set Up Resources
To correctly manage resource activities, you must set up your resources and the related costs and prices. The job-related prices, discounts, and cost factor rules are set up on the job card. You can specify the costs and prices for individual resources, resource groups, or all available resources of the company.

When resources are used or sold in a job, the prices and costs associated with them are retrieved from the information that you set up.

You specify the default amount per hour when the resource is created. For example, if you use a specific machine on a job for five hours, the job would be calculated based on the amount per hour.

## To set up a resource
Create a card for each resource that you want to use in projects.

1. In the top right corner, choose the **Search for Page or Report** icon, enter **Resources**, and then choose the related link.
2. Choose the **New** action.
3. Fill in the fields as necessary. Choose a field to read a short description of the field or link to more information.  

## To set up a resource group
You can combine several resources in one resource group. All capacities and budgets of resource groups are accumulated from the individual resources. It is also possible to enter capacities for resource groups either independently of the accumulated values or in addition to them.

1. In the top right corner, choose the **Search for Page or Report** icon, enter **Resource groups**, and then choose the related link.
2. Choose the **New** action.
3. Fill in the fields as necessary.

## To allocate a resource to a job  
You can allocate a resource or resource group’s capacity to one or more jobs to be used in project planning.  

1. In the top right corner, choose the **Search for Page or Report** icon, enter **Resources**, and then choose the related link. 
2. Open the relevant resource card, and then choose the **Resource Capacity** action.  
3. Fill in the filters to specify the resource and view options, and then choose the **Show Matrix** action.  
4. Select the line of the job that you want to allocate resources to.  

To allocate resource groups to jobs, perform steps 2 and 3 by choosing the **Resource Group Capacity** action.

## To set up alternate resource costs
In addition to the cost specified on the resource card, you can set up alternate costs for each resource. For example, if you pay an employee a higher hourly rate for overtime, you can set up a resource cost for the overtime rate. The alternate cost that you set up for the resource will override the cost on the resource card when you use the resource in the resource journal.

1. In the top right corner, choose the **Search for Page or Report** icon, enter **Resources**, and then choose the related link.  
2. Select the resource for that you want to set up one or more alternate costs for, and then choose the **Costs** action.  
3. In the **Resource Costs** window, fill in the fields on a line as necessary.  
4. Repeat step 3 for each alternate resource cost that you want to set up.

**Note**. To set up resource costs that will apply to all resources and resource groups, open the **Resource Costs** window and fill in the fields. 

## To set up alternate resource prices  
In addition to price specified on the resource card, you can set up alternate prices for each resource. These alternate prices can be conditional. They can depend on whether the resource is used with a specific job or work type.
  
1. In the top right corner, choose the **Search for Page or Report** icon, enter **Resources**, and then choose the related link.
2. Select the resource for that you want to set up one or more alternate prices for, and then choose the **Prices** action. 
3. In the **Resource Prices** window, fill in the fields on a line as necessary. 
4. Repeat step 3 for each alternate resource price that you want to set up.

## See Also
[Set Up Project Management](projects-setup-projects.md)  
[Manage Projects](projects-manage-projects.md)  
[Finance](finance.md)  
[Manage Purchasing](purchasing-manage-purchasing.md)         
[Manage Sales](sales-manage-sales.md)      
[Work With Dynamics 365 for Financials](ui-work-product.md)  
