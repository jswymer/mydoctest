<properties
                pageTitle="How to: Use Time Sheets| Financials"
                description="Describes how to use time sheets to manage projects."
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

# How to: Use Time Sheets
You use the **Create Time Sheets** batch job to set up time sheets for a specified number of time periods or weeks. You must have permissions to be able to create time sheets.

You can copy and use your job planning lines in a time sheet. In that way, you must only enter the information in one place and the line information is always correct.

After you have approved time sheet entries for a job, you can post them to the relevant job journal or resource journal. 

Before you can use time sheets, you must set up general information and specify an administrator and one or more approvers of time sheets. For more information, see [How to: Set Up Time Sheets](projects-how-setup-time-sheets.md). 

## To create a time sheet  
You can use the **Create Time Sheets** batch job to set up time sheets for a specified number of time periods or weeks. Then, the time sheet owner can open it and record time that has been spent on a task.
  
1. In the top right corner, choose the **Search for Page or Report** icon, enter **Time Sheets**, and then choose the related link.
2. In the **Time Sheet List** window, choose the **Create Time Sheets** action. 
3. Fill in the fields as necessary, and then choose the **OK** button.

**Note**: The **Use Time Sheet** and **Time Sheet Owner User ID** fields must be filled in on the card the resource of the time sheet.  
  
You can view the time sheets that you have created in the **Time Sheet list** window.

## To copy job planning lines to a time sheet  
The following procedure describes how to quickly add job planning lines to a time sheet.
  
1. In the top right corner, choose the **Search for Page or Report** icon, enter **Time Sheets**, and then choose the related link.  
2. In the **Time Sheet List** window, select a time sheet for the relevant time period, and then choose the **Edit Time Sheet** action.  
3. Choose the **Create lines from job planning** action. Any job planning lines in the time sheet time period are copied to the time sheet for the person or machine in the **Resource No.** field on the time sheet.

## To define work types and add one to a time sheet  
You can define the work type for all time sheet lines for jobs. In this way, you can add information that you need to bill the customer for different types of work.

1. In the top right corner, choose the **Search for Page or Report** icon, enter **Time Sheets**, and then choose the related link.   
2. Open the relevant time sheet.
3. Choose the **Description** field.  
4. In the **Time Sheet Line Res. Detail ** window, choose the **Work Type Code** field, and select a work type from the list.  
5. If no work types exist, chose the **New** action.
6. In the **Work Types** window, fill the fields as necessary.
7. Repeat step 4 to assign a work type to the time sheet.

## To reuse time sheet lines in other time sheets  
If your time sheet information remains the same from time period to time period, you can save time by copying the lines from the previous time period. Then, you just enter your time usage for the new period.

1. In the top right corner, choose the **Search for Page or Report** icon, enter **Time Sheets**, and then choose the related link.  
2. Open the time sheet for a period later than the period for an existing time sheet with lines.  
3. Choose the **Copy Lines from Previous Time Sheet** action.

The lines are copied, including details such as type and description. For example, if the line is related to a job, the **Job No.** is copied. All copied lines have the status **Open**. You can now modify the lines as needed. 

## To approve or reject a time sheet  
A time sheet must be submitted for approval before it can be used. You can approve and reject individual lines on a time sheet or send them back to the submitter for additional action. A time sheet can be approved in two ways:  
  
- A time sheet administrator may approve any time sheet.
- The person who is specified in the **Time Sheet Approver User ID $** field on a resource card may approve that resource's time sheets. For more information, see [How to: Set Up Time Sheets](projects-how-setup-time-sheets.md).    
  
 In addition, if you are the project manager on a job, you can approve lines in the **Manager Time Sheet by Job** window.
     
1. In the top right corner, choose the **Search for Page or Report** icon, enter **Manager Time Sheets**, and then choose the related link.
2. Select a time sheet from the list, and then choose the **Edit Time Sheet** action.  
3. Choose the **Approve** action, and then choose the **All submitted lines** action to approve all lines or the **Selected lines** action to approve only the lines that are selected in the **Time Sheets** window.
4. Choose the **OK** button.  
5. Alternatively, choose the **Reject** action and follow steps 4 through 5.  

**Tip**: Use the **Time Sheet Status** and **Actual/Scheduled Summary** FactBoxes to get an overview of time sheet information.
 
After you have approved or rejected a time sheet, it cannot be reopened or modified in the **Manager Time Sheet** window. The following procedure shows how to reopen an approved or rejected time sheet.
  
## To reopen a time sheet  

1. In the top right corner, choose the **Search for Page or Report** icon, enter **Manager Time Sheets**, and then choose the related link.  
  
    **Note**. You can only reopen lines that have the status **Approved**. You cannot reopen lines that have the status **Rejected**. You cannot reopen a time sheet if it has been posted.  
  
2. Choose the **Reopen** action, and then choose the **All submitted lines** action to reopen all lines or the **Selected lines** action to reopen only the lines that are selected in the **Time Sheets** window. 
3. Choose the **OK** button. The status of the time sheets line or lines is changes to **Submitted**.  



## See Also
[Manage Projects](projects-manage-projects.md)  
[Set Up Project Management](projects-setup-projects.md)    
[Finance](finance.md)  
[Manage Purchasing](purchasing-manage-purchasing.md)         
[Manage Sales](sales-manage-sales.md)     
[Work With Dynamics 365 for Financials](ui-work-product.md)  
