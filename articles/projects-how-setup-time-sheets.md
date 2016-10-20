<properties
                pageTitle="How to: Set Up Time Sheets| Financials"
                description="Describes how to prepare the system to use time sheets to manage projects."
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
    ms.date="10/11/2016"
    ms.author="SorenGP" />

# How to: Set Up Time Sheets
Time sheets in Financials handle time registration in weekly increments of seven days. You use them to track the time used on job, service orders, and assembly orders. In addition, you can use them to record simple resource time registration and employee absences. Before you can use time sheets, you must specify how you want them to be set up and configured.

After you have set up how your organization will use time sheets, the next step is to specify approves time sheets. Depending on the needs of your organization, you have options about how you set up a time sheet approver. You can designate: 

- One or more users as the time sheet administrator for all time sheets.
- A time sheet approver for each resource. 

## To set up general information for time sheets  
  
1. In the top right corner, choose the **Search for Page or Report** icon, enter **Resources Setup**, and then choose the related link.  
2. Fill in the fields as necessary. Choose a field to read a short description of the field or link to more information.

**Note**: The default weekday is Monday.  

## To specify a time sheet administrator  
  
1. In the top right corner, choose the **Search for Page or Report** icon, enter **User Setup**, and then choose the related link.  
2.  Add a new user, if the user list does not include the person who you want to be the time sheet administrator. For more information, see the "Creating Users" section in [Get Ready for Business](ui-get-ready-business.md).  
3. Select a user to be a time sheet administrator, and then select the **Time Sheet Admin.** check box.  

**Tip**: We recommend that you designate only one user to be the time sheet administrator for a company. In the next procedure, you set up a time sheet owner and approver. In this case, the time sheet approver is specified for each resource.  
  
## To specify a time sheet owner and approver  
  
1. In the top right corner, choose the **Search for Page or Report** icon, enter **Resources**, and then choose the related link. 
2. Select the resource for which you want to set up the ability to use time sheets, and then select the **Use Time Sheet** check box.  
3. In the **Time Sheet Owner User ID** field, enter the ID of the owner of the time sheet. The owner can enter time usage on a time sheet and submit it for approval. In general, when the resource is a person, that person is also the owner.  
4. In the **Time Sheet Approver User ID** field, enter the ID of the approver of the time sheet. The approver can approve, reject, or reopen a time sheet.  

**Note**: You cannot change the ID of the time sheet approver if there are time sheets that have not yet been processed and have the status of **Submitted** or **Open**. 



## See Also
[Set Up Project Management](projects-setup-projects.md)  
[Manage Projects](projects-manage-projects.md)  
[Finance](finance.md)  
[Manage Purchasing](purchasing-manage-purchasing.md)         
[Manage Sales](sales-manage-sales.md)      
[Work With Dynamics 365 for Financials](ui-work-product.md)  
