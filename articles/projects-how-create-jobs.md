<properties
                pageTitle="How to: Create Jobs| Financials"
                description="Describes how to create a job."
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
    ms.date="10/21/2016"
    ms.author="SorenGP" />

# How to: Create Jobs
When you start a new project, a job card with integrated job planning lines must be created. Job planning has two layers:

The first layer consists of job task lines. It is necessary to set up at least one job task because all posting needs to refer to a job task. Having at least one job task in your project enables you to set up planning lines and to post consumption to the job.

The second layer consists of planning lines, which specify the detailed use of resources, items and various general ledger expenses.

All jobs that you create can be separated into task lines and planning lines. This enables you to divide the job into smaller tasks, and therefore use more specific details in budgeting, quotes and registration.

## To create a job card
You create a job card and then create job task lines and job planning lines for it. Each step in job creation is designed to give you an overview of and insight into how a job is progressing. For example, you can track whether you are meeting designated milestones, or are on target for meeting budget expectations.  
  
1. In the top right corner, choose the **Search for Page or Report** icon, enter **Jobs**, and then choose the related link.  
2. Choose the **New** action, and then fill in the fields as necessary. Choose a field to read a short description of the field or link to more information.

**NOTE**: If you are using time sheets with your job, you must also designate a person responsible. This person can approve time sheets for the employee tasks associated with the job. For more information, see [How to: Set Up Timesheets](projects-how-setup-time-sheets.md). 
  
## To create tasks for a job  
A key part of creating a job is to specify the various tasks involved in the job. You do this by adding new lines in the **Job Task Lines** window, one task per line. Every job must have at least one task. 
  
1. In the top right corner, choose the **Search for Page or Report** icon, enter **Jobs**, and then choose the related link.
2. Select a job, and then choose the **Job Task Lines** action.  
3. In the **Job Task Lines** window, on a new line, fill in the fields as necessary.  
4. In the **WIP-Total** field, specify if WIP (the value of work in process) should be calculated for the task and all previous tasks in the task group. Select one of the following options.

|Option|Description|
|------|-----------|
|**Total**|Includes the group of tasks in WIP calculation for the task.|
|**Excluded**|Excludes the task from WIP calculation. This option can be useful if you are still planning the task for a job and you have not posted any usage or invoices.|  

5. Repeat steps 3 and 4 for all the tasks that you need for the job. 
  
## To create planning lines for jobs  
You can refine your new job tasks on job planning lines. A planning line can be used to capture any information that you want to track for a job. You can use planning lines to add information such as what resources are required or to capture what items are needed to perform the job. For example, if you have a task to obtain customer approval of a job, you can associate that task with planning lines for items such as meeting with the customer and creating a service contract.  
  
Job planning line can be of the following type.  
  
|Type|Description|
|----|-----------|
|**Schedule**|Provides estimated usage and costs for the job, typically in a time and materials type contract. Planning lines of this type cannot be invoiced.|
|**Contract**|Provides estimated invoicing to the customer, typically in a fixed price contract.|
|**Both Schedule and Contract**|provides scheduled usage equal to what you want to invoice.|  
  
**Note**. As you enter information on job planning lines, cost information is automatically filled in. For example, the cost, price, and discount for resources and items are initially based on the information that is defined on the resource and item cards.
   
1. In the top right corner, choose the **Search for Page or Report** icon, enter **Jobs**, and then choose the related link. 
2. Select a job, and then choose the **Job Task Lines** action.  
3. Select a job task for which the **Job Task Type** is **Posting**, and then choose the **Job Planning Lines** action.  
4. In the **Job Planning Lines** window, on a new line, fill in the fields as necessary.
5. Repeat step 4 for all planning lines that you need for the job task. 

In [!INCLUDE[navnow](../Token/navnow_md.md)], you can create a template to use when you are creating a new job. You can reuse phases and estimates from previous jobs as the template for future projects. You can then create and customize a library of job templates as needed.  
  
## To copy a job
You can create a new job by copying an existing job and saving the copy as a template.   

1. In the top right corner, choose the **Search for Page or Report** icon, enter **Jobs**, and then choose the related link.
2. Choose the **New** action, and then fill in the fields ass necessary.

    **Note**: This is a normal job card, but to use it as a template, fill in generic information that makes it useful as a template going forward.
    
3. Set the **Blocked** field to **All** to make sure it cannot be used as a real job.  
4. Choose the **Copy Job** actions.  
5. In the **Copy Job** window, fill in the fields as necessary. The existing job that you are copying from is specified on the **Copy From** FastTab. You can choose to copy both job tasks and job planning lines from the selected the job and task lines that you want to copy from.  

    If you set the **Source** field to **Job Planning Lines**, then estimates for the job are based on the planned values from the job that you are copying from. If you set the **Source** field to **Job Ledger Entry**, then estimates for the job are based on the actual values from the job you are copying from.  
  
6. Choose the **OK** button to copy the specified job.
  
## See Also
[Manage Projects](projects-manage-projects.md)  
[Finance](finance.md)  
[Manage Purchasing](purchasing-manage-purchasing.md)         
[Manage Sales](sales-manage-sales.md)      
[Work With Dynamics 365 for Financials](ui-work-product.md)  
