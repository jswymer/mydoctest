<properties
	pageTitle="How to: Post Year-End Closing Entry | Project "Madeira""
	description="Explains how to post year-end closing entry."
	services="SMB"
	documentationCenter=""
	authors="jswymer"
	manager="edupont"
	editor=""/>
	
<tags
	ms.service="SMB"
	ms.workload=""
	ms.tgt_pltfrm="na"
	ms.devlang="na"
	ms.topic="article"
	ms.date="02/08/2016"
	ms.author="jswymer" />
	
# How to: Post Year-End Closing Entry
After you use the Close Income Statement batch job to generate the year-end closing entry or entries, you must open the journal you specified in the batch job, and then review and post the entries.

## To post the year end closing entry
1. In the **Search** box, enter **General Journal**, and then choose the related link.
2. In the **General Journal** window, in the **Batch Name** field, select the batch that contains the closing entries.
3. Review the entries.
4. To post the journal, choose the Post action.

>**Note:** If an error is detected, an error message is displayed. If the posting is successful, the posted entries are removed from the journal. After posting is complete, an entry is posted to each income statement account so that its balance becomes zero and the year's result is transferred to the balance sheet.

## See Also
[How to: Close Accounting Periods](year-close-account-periods.md)  
[Close Books](year-close-books.md)  
[Close Income Statement](year-close-income-statement.md)






