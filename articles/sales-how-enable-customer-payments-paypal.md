<properties
                pageTitle="How to: Enable Customer Payments Through PayPal| Project “Madeira”"
                description="How to: Enable Customer Payments Through PayPal"
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
    ms.date="05/12/2016"
    ms.author="europe\sgroespe" />

# How to: Enable Customer Payments Through PayPal#
As an alternative to collecting payments through bank transfer or credit cards, you can offer your customers to pay you through their PayPal account.

When a customer chooses the PayPal link on a sales invoice or sales order document, the service page for their PayPal account appears showing the payment details for the sale. The customer can then pay the invoice as any other PayPal payment.

To enable customer payments through PayPal, you must do the following:

1. Set up PayPal Payments Standard as a payment service in the **Payments Services** window.
2. Select PayPal Payments Standard in the **Payment Service** field on the sales document in question.

The PayPal Payments Standard service is installed as an extension to Project "Madeira" and ready to enabled. For more information, see [Customizing Project "Madeira" Using Extensions ](ui-extensions.md).

## To enable the PayPal Payments Standard service
1. In the top right corner, choose the **Search for Page or Report** icon, **Payment Services**, and then choose the related link.  
2. In the **Payment Services** window, choose the **New** action.
3. Select **PayPal Standard**, and then choose the **OK** button.
4. In the **Payment Services** window, choose the **Setup** action.
5. Fill the fields as necessary. Choose a field to read a short description of the field or link to more information.

    **Note**: Select the **Always Include on Documents** check box if the hyperlink for the PayPal payment service should always be visible on sales documents where payment through PayPal is enabled.

6. Choose the **OK** button.

## To select PayPal Payments Standard on a customer card
1. On the Home page, choose **Sales Invoices**.
2. Open the sales invoice that you want to enable PayPal payments for.
3. In the **Payment Service** field, choose PayPal Payments Standard.

**Note**: The **Payment Service** field is only visible if the PayPal Payments Standard service is enabled.   

## See Also  
[Set Up Sales](sales-setup-sales.md)  
[Manage Sales](sales-manage-sales.md)
