<properties
                pageTitle="How to: Set Up Fixed Asset Insurance| Financials"
                description="Describes how to set the system up for insurance of fixed assets."
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
    ms.date="09/29/2016"
    ms.author="SorenGP" />

# How to: Set Up Fixed Asset Insurance
To manage fixed asset insurance coverage, you must first set up some general insurance information and an insurance card per policy.

## To set up general insurance information  
To use the insurance features in Dynamics NAV, you must set up some general insurance information.  
1. In the top right corner, choose the **Search for Page or Report** icon, enter **FA Setups**, and then choose the related link.  
2. Fill in the fields as necessary. Choose a field to read a short description of the field or link to more information.  

## To set up insurance types  
You can group your insurance policies into categories, such as insurance against theft or fire insurance. The insurance types are used on the insurance card.
1. In the top right corner, choose the **Search for Page or Report** icon, enter **Insurance Types**, and then choose the related link.  
2. Fill in the fields as necessary.

## To set up insurance cards  
You may accumulate information about each insurance policy on the insurance card.  
1. In the top right corner, choose the **Search for Page or Report** icon, enter **Insurance**, and then choose the related link.  
2. In the **Insurance** window, choose the **New** action to create a  new insurance card.  
3. Fill in the fields as necessary.

## To set up insurance journal templates  
Dynamics NAV automatically creates an insurance journal template the first time that you open the **Insurance Journal** window, but you can set up additional journal templates. For more information, see [Work with General Journals](ui-work-general-journals.md).  
1. In the top right corner, choose the **Search for Page or Report** icon, enter **Insurance Journal Templates**, and then choose the related link.  
2. Fill in the fields as necessary.

## To set up insurance journal batches  
You can set up batches in an insurance journal template. The values in the journal batch are used as default values if the fields are not filled in on the journal lines. For more information, see [Work with General Journals](ui-work-general-journals.md)  
1. In the top right corner, choose the **Search for Page or Report** icon, enter **Insurance Journal Templates**, and then choose the related link.  
2. Select an insurance journal template, and then choose the **Batches** action.
3. In the **Insurance Journal Batches** window, fill in the fields as necessary.

**NOTE**: Numbers have a special function in journal names. If a journal template name or journal batch name contains a number, the number automatically advances by one every time that the journal is posted. For example, if HH1 is entered in the **Name** field, the journal name will change to HH2 after the journal named HH1 has been posted.

## See Also
[Set Up Fixed Assets](fa-setup.md)  
[Manage Fixed Assets](fa-manage.md)  
[Finance](finance.md)  
[Welcome to Dynamics NAV](madeira-get-started.md)
