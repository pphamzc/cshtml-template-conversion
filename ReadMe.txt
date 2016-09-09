Objective
---------

Modify the templates (cshtml files) in template directory to match the sample pdf in Sample-Invoice-PDF directory after conversion process.  You will use a test harness written .NET 4.5 to convert, test your changes and compare the pdf generated with the sample pdf located in Sample-Invoice-PDF directory.


Tools
-----
Go to the Test-Harness folder and double click on the file : InvoiceTemplateTestHarness.exe.  You might need to install the .NET 4.5 redistributable.


Instructions
------------

First make sure all files are there.

- The templates have three parts in Template directory : *Header.cshtml, *Body.cshtml, *Footer.cshtml.  
- You have sample pdf named like your templates in Sample-Invoice-PDF directory : *Sample.pdf
- Test harness works by double clicking on InvoiceTemplateTestHarness.exe in Test-Harness directory.
- You have *_TemplateOptions.txt matching your templates.

1. Launch the InvoiceTemplateTestHarness.exe application.
2. Header : browse to the Template directory for the *Header.cshtml file and select it.
3. Body : browse to the Template directory for the *Body.cshtml file and select it.
4. Footer : browse to the Template directory for the *Footer.cshtml file and select it.
5. TemplateOptions :  Go into Template directory, open up the *_TemplateOptions.txt file.  Then copy content of file and paste into Template Options section.
5. Set the output directory and name of pdf file.
6. Click on Create Invoice Button.
7. Compare your generated PDF file to the sample pdf file in Sample-Invoice-PDF directory.
9. Repeat as many times as necessary to match generated pdf to sample pdf in format.  Note content are hard coded so you should not have to worry about that.  


NOTE
----

Standard_US_ConsolidateInvoice is the sample template that has been completed.  You will use this as a guide on how to update the following templates for this challenge : 

SAS_EMEA_BU_Sweden_ConsolidateInvoice
SAS_EMEA_BU_Norway_ConsolidateInvoice
SAS_EMEA_BU_Denmark_EUR_ConsolidateInvoice
SAS_EMEA_BU_Denmark_ConsolidateInvoice
PayWiseConsolidated_ConsolidateInvoice