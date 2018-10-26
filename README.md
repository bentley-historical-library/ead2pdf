ArchivesSpace EAD2PDF
--------------------


This is a basic little script to convert EAD files into PDFs. 
It uses a slightly tweaked XSLT developed by Winona Salesky, using the Apache FO library
to convert XML into PDF.

It requires Java.

To run, simply use java -jar ead2pdf.jar EAD_INPUT_FILE PDF_OUTPUT_FILE [ XSLT_FILE ( option ) ]

To develop, make your edits, have warbler installed, and then "warble compiled jar" or simply "warble".

## Bentley Historical Library Modifications
This fork of ead2pdf replaces lib/as-ead-pdf.xsl with the [BHL's modified stylesheet](https://github.com/bentley-historical-library/bhl_aspace_pdf_stylesheet) and includes the Bentley's logo (bhl-fa-smlogo.gif)
