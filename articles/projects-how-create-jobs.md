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
    ms.date="10/24/2016"
    ms.author="SorenGP" />

# How to: Create Jobs
When you start a new project, you must create a job card with integrated job tasks and job planning lines, structured in twi layers.  

The first layer consists of job tasks. You must acreate at least one job task per job because all posting refers to a job task. Having at least one job task in your job enables you to set up job planning lines and to post consumption to the job.

The second layer consists of job planning lines, which specify the detailed use of resources, items and various general ledger expenses.

The layer structure enables you to divide the job into smaller tasks, and therefore use more specific details in budgeting, quotes, and registration. In addition, it gives you insight into how a job is progressing. For example, you can track whether you are meeting designated milestones or if lyou are on target to meet budget expectations.

**Note**: The **New Job** action on the **Project Manager** Role Center launches an assisted setup that guides you through the steps of creating a job with integrated tasks and planning lines. The following procedure describes how to perform the steps manually.

## To create a job card
You create a job card and then create job task lines and job planning lines for it.

1. In the top right corner, choose the **Search for Page or Report** icon, enter **Jobs**, and then choose the related link.  
2. Choose the **New** action, and then fill in the fields as necessary. Choose a field to read a short description of the field or link to more information.
3. To specify the job with information on other jobs, choose the **Copy Job** action, fill in the fields as necessary, and then choose the **OK** button.

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
6. To specify the job tasks with information on other job tasks, choose the **Copy Job Tasks from** action, fill in the fields as necessary, and then choose the **OK** button.

## To create planning lines for a job  
You can refine your new job tasks on job planning lines. A planning line can be used to capture any information that you want to track for a job. You can use planning lines to add information such as what resources are required or to capture what items are needed to perform the job. For example, if you have a task to obtain customer approval of a job, you can associate that task with planning lines for items such as meeting with the customer and creating a service contract.  

A job planning line can have one of the following types.  

|Type|Description|
|----|-----------|
|**Budget**|Provides estimated usage and costs for the job, typically in a time and materials type project. Planning lines of this type cannot be invoiced.|
|**Billable**|Provides estimated invoicing to the customer, typically in a fixed price project.|
|**Both Budget and Billable**|provides budgeted usage equal to what you want to invoice.|  
  
**Note**. As you enter information on job planning lines, cost information is automatically filled in. For example, the cost, price, and discount for resources and items are initially based on the information that is defined on the resource and item cards.

1. In the top right corner, choose the **Search for Page or Report** icon, enter **Jobs**, and then choose the related link.
2. Select a job, and then choose the **Job Task Lines** action.  
3. Select a job task for which the **Job Task Type** is **Posting**, and then choose the **Job Planning Lines** action.  
4. In the **Job Planning Lines** window, on a new line, fill in the fields as necessary.
5. Repeat step 4 for all planning lines that you need for the job task.

## See Also
[Manage Projects](projects-manage-projects.md)  
[Finance](finance.md)  
[Manage Purchasing](purchasing-manage-purchasing.md)         
[Manage Sales](sales-manage-sales.md)      
[Work With Dynamics 365 for Financials](ui-work-product.md)  
