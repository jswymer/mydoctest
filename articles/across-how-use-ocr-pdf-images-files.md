<properties
                pageTitle="How to: Use OCR to Turn PDF and Image Files into Electronic Documents| Project “Madeira”"
                description="Describes how to use OCR to turn PDF and image files into electronic documents"
                services=""
                documentationCenter="Madeira"
                authors="edupont" />

# How to: Use OCR to Turn PDF and Image Files into Electronic Documents
From PDF or image files that you receive from your trading partners, you can have an external OCR service (Optical Character Recognition) generate electronic documents that can be converted to document records in Project "Madeira". For example, when you receive an invoice in PDF format from your vendor, you can send it to the OCR service from the **Incoming Documents** window. This is described in the first procedure.

As an alternative to sending the file from the **Incoming Documents** window, you can send the file to the OCR service by email. Then, when you receive the electronic document back, a related incoming document record is created automatically. This is described in the second procedure.

After some seconds, you receive the file back from the OCR service as an electronic invoice that can be converted to a purchase invoice for the vendor. This is described in the third procedure.

Because OCR is based on optical recognition, it is likely that the OCR service will interpret characters in your PDF or image files wrongly when it first processes a certain vendor’s documents, for example. It may not interpret the company logo as the vendor’s name or it may misinterpret the total amount on a receipt because of its layout. To avoid these errors going forward, you can correct the errors in a separate version of the **Incoming Document** window. Then you send the corrections back to the OCR service to train it to interpret the specific characters correctly next time it processes a PDF or image document for the same vendor. For more information, see the "To train the OCR service to avoid errors# section.

The traffic of files to and from the OCR service is processed by a dedicated job queue entry, which are created automatically when you enable the related service connection. For more information, see [How to: Set Up an OCR Service](across-how-setup-income-documents.md).

## To send a PDF or image file to the OCR service from the **Incoming Documents** window
1. In the **Search** box, enter **Incoming Documents**, and then choose the related link.
2. Create a new incoming document record and attach the file. For more information, see [How to: Create Incoming Document Records](across-how-create-income-document-records.md).  
3. In the **Incoming Documents** window, select one or more lines, and then choose the **Send to Job Queue** action.

    The value in the **OCR Status** field changes to **Ready**. The attached PDF or image file is sent to the OCR service by the job queue according to the schedule, provided that no errors exist.
5. Alternatively, in the **Incoming Documents** window, select one or more lines, and then choose the **Send to OCR Service** action.

The value in the **OCR Status** field changes to Sent, provided that no errors exist.

## To send a PDF or image file to the OCR service by email
From your email application, you can send an email to the OCR service provider with the PDF or image file attached. For information about the email address to send to, see the OCR service provider’s web site.

Because no incoming document record exists for the file, a new record will be created automatically in the **Incoming Documents** window when you receive the resulting electronic document from the OCR service. For more information, see [How to: Create Incoming Document Records](across-how-create-income-document-records.md).

**Note**: If you work on a tablet or phone, you can send the file to the OCR service as soon as you have taken a photo of the document, or you can create an incoming document directly. For more information, see the "To create incoming document records by taking a photo" section in [How to: Create Incoming Document Records](across-how-create-income-document-records.md).

## To train the OCR service to avoid errors
Because OCR is based on optical recognition, it is likely that the OCR service will interpret characters in your PDF or image files wrongly when it first processes documents from a certain vendor, for example. It may not interpret the company logo as the vendor’s name or it may misinterpret the total amount on an expense receipt because of its layout. To avoid such errors going forward, you can correct data received by the OCR service and then send the feedback to the service.

The **OCR Data Correction** window, which you open from the **Incoming Document** window, shows the fields from the **Financial Information** FastTab in two columns, one with the OCR data editable and one with the OCR data read-only. When you choose the **Send OCR Feedback** button, the content of the **OCR Data Correction** window is sent to the OCR service. Next time the service processes PDF or image files that contain the data in question, your corrections will be incorporated to avoid the same errors.

1. In the **Search** box, enter **Incoming Documents**, and then choose the related link.
2. Open an incoming document record that contains data received from OCR service, which you want to correct.
3. In the **Incoming Document** window, choose the **Correct OCR Data** action.
4. In the **OCR Data Correction** window, overwrite the data in the editable column for each field that has an incorrect value.
5. To undo corrections that you have made since you opened the **OCR Data Correction** window, choose the **Reset OCR Data** action.
6. To send the corrections to the OCR service, choose the **Send OCR Feedback** action.
7. To save the corrections, close the **OCR Data Correction** window.

The fields on the **Financial Information** FastTab in the **Incoming Document** window are updated with any new values that you entered in step 4.

## See Also  
[Process Incoming Documents](across-process-income-documents.md)  
[Incoming Documents](across-income-documents.md)  
[Manage Purchasing](purchasing-manage-purchasing.md)  
[Work With Project "Madeira"](ui-work-product.md)
