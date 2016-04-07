<properties pageTitle="Processing Sales Opportunities | Project “Madeira”" 
    description="Describes the process for sales opportunities in Project “Madeira”" 
    services="" 
    documentationCenter="Madeira"
    authors="jswymer"/>
    
# Processing Sales Opportunities
After you create an opportunity, there are several features for managing the opportunity and moving it through to completion.

## View opportunities
The existing sale opportunities are available from the **Opportunity List** window. There are different ways to access this window for processing sales opportunities:

|To view opportunities for |Then |
|--------------------------|-----|
|All salespeople and contacts|In the **Search** box, enter **Opportunity List**, and then choose the related link.|
|A specific sales person|In the **Search** box, enter **Salespeople**, and then choose the related link. Select the salesperson, choose the **Opportunities** action, and then choose the **List** action.|
|A specific contact|In the **Search** box, enter **Contacts**, and then choose the related link. Select the contact from the list, and then choose the **Opportunities** action.|

Each of these tasks opens the **Opportunity List** window.

## Close opportunities
You can close opportunities when the negotiations are over. When closing an opportunity, you can specify whether it was won or lost, and the reasons for closing it. To specify a reason, you must set up closed opportunity codes.

1. In the **Opportunity List** window, select the opportunity, and the choose the **Close** action. 

  The **Close Opportunity** window opens.
2. Fill in the relevant fields, and then choose the **OK** button.

  The **Close Opportunity Code** and **Date Closed** fields are required fields and must be filled in before you can choose the **OK** button.
  
  In the **Close Opportunity Code** field, you can choose from one of the existing close opportunity codes or add a new code. To add a new code, from the dropdown list, choose **Select from full list**, and then choose **new**. On the new blank line, fill in the **Code**, **Type**, and **Description** fields, and then choose the **OK** button.
  
## Create quotes for opportunities
You can create sales quotes for contacts that are not recorded as customers.
 
1. In the **Opportunity List** window, select the opportunity, and then choose the **Assign Sales Quote** action. The **Sales Quote** window opens.
2. Fill in the relevant fields.

## Create sales orders for opportunities
You can make sales orders from the sales quotes that you have created for your opportunities. Before you can create sales orders for your contacts, you must create the contact as a customer. For more information, see [Create a Customer, Vendor, or Bank Account From a Contact](marketing-how-create-contacts-new-customers-vendors-bank-accounts.md).

1. In the **Opportunity List** window, find the opportunity that you have created a sales quote for.
2. Choose the Assign Sales Quote actions. The **Sales Quote** window opens to show the sales quote that you have assigned to the opportunity.
3. Fill in the additional fields, and then choose the **Make Order** action.

When handling sales opportunities, you may need to create a quote for the contact that the opportunity is linked to.

## Delete opportunities
You can delete opportunities, for example, after you have concluded a deal. However, you can only delete closed opportunities. There are two ways to delete closed opportunities. You can delete individual closed opportunities from the **Opportunity List** window or you can run the **Delete Closed Opportunities** batch job to delete multiple opportunities based on a specified criteria.

To delete closed opportunities from the **Opportunity List** window, select the opportunity, and then choose the **Delete** action. 

To delete closed opportunities by using the **Delete Closed Opportunities** batch job, follow these steps:

1. In the **Search** box, enter **Delete Opportunities, and then choose the related link.
2. In the **Opportunity** section, set up the filters that specify the closed opportunities to delete.
3. Choose the **OK** button.

After you have deleted an opportunity, it is removed it from the **Opportunity List** window.

## Move an opportunity through sales cycle stages
If an opportunity follows a sales cycle, you can move it forward or back through the different stages, such as moving the the next or pervious stage, and even skipping a stage.

1. In the **Opportunity List** window, choose the **Update** action. The **Update Opportunity** opens,
2. Use the **Action Type** field to move the opportunity through the sales cycle stages:
  * **Next** moves the oppurtunity forward one stage.
  * **Skip** moves rhe the opportunity forward one or several stages in the sales cycle, which you specify in the **Presentation** field. You can only skip stages that have been set up to allow skipping. 
  * **Previous** moves the oppurtunity back one stage.
  * **Jump** moves rhe the opportunity back one or several stages in the sales cycle, which you specify in the **Presentation** field.
  * **Update** enables you to change information (such as to modify your evaluation of their chances of success and estimated values) without moving to another stage.
3. Fill in the other fields as needed, and then choose the **OK** button.
 
##See Also  
[Manage Sales](sales-manage-sales.md)  
[Create and Manage Contacts](marketing-contacts.md)  
[Work with Project "Madeira"](ui-work-product.md)

