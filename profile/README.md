# KHEA Members Internal Documentation
### _Welcome to Knowledge Hub for E-invoicing APIs (KHEA)_

## What is KHEA?
As E-Invoicing is being mandated across the world, we believe APIs have a critical role to play in in enabling small solution providers and startups to create custom solutions cheaply and efficiently. Consequently, Knowledge Hub for E-invoicing APIs (KHEA) is a community-driven initiative whose goal is consolidating important information and knowledge in this space. In doing so, KHEA will play a key role in bringing API creators and users together and make information on all existing e-Invoicing APIs available to developers and solution providers

## Public Available APIs
Our KHEA Repository classifies the E-invoicing APIs into four basice E-invoicing operations: Invoice Creation, Invoice Transformation, Invoice Validation and Invoice Communication. Below is the classification of APIs in specific E-Invoicing categories with their details and business parameters.

### _Invoice Transformation APIs_
Invoice Transformation APIs are APIs that enable businesses to automate their invoice creation and processing by facilitating the creation and transformation of invoices from PDFs, images, databases or unstructured formats into structured digital format. Below lists some of the popular invoice transformation APIs with all the business parameters and details.
|Business Name|Sub Category|Source|Description|URL Endpoint|Authentication|Input Format|Output Format|Client|How to access|
|---|---|---|---|---|---|---|---|---|---|
|UpBrains Xtract||Web Search|Extracts key data from documents, emails and tickets with a high accuracy. It uses prebuilt extractor or create custom extractors in minutes. The URL for UpBrains Xtract is https://upbrains.ai/|API URL: https://workspace.upbrainsai.com/agents|Access Token|PDF|JSON|REST|Within the UpBrains UI, (scroll down) Document Extraction ->Sign up->Automate document OCR workflows|
|ESS Transform||Project Sponser|Seamlessly transform a vast array of standardised (regulatory or industry) e-invoice formats. The URL for ESS Transform is https://www.ebsoftwareservices.com.au|API URL: Contact ESS|OAuth 2.0 Token|EDIFACT INVOIC D96A, CII XML and SAP INVOIC IDOC|EDIFACT INVOIC D96A, CII XML and SAP INVOIC IDOC|REST|Within the ESS UI, Products-> APIs->ESS Transform (Demo)|
|Ezzy Bills||Australian Accredited Provider|EzzyBills API creates a perfect AP automation solution for your business. Its EzzyBills OCR+ Invoice Capture technology is optimised to process invoices & receipts. The URL for Ezzybills is https://www.ezzybills.com/|API URL: https://app.ezzydoc.com/restapi.html?_gl=1*4cdvzi*_gcl_au*NzMzNDY2ODUuMTcxMzE1NDUxOA..#tag/IEzzyRest/paths/~1Login/get    EzzyService: https://app.ezzydoc.com/EzzyService.svc?_gl=1*1e0g4pp*_gcl_au*MTQxNzc0Nzg0Mi4xNzEyNTM5MDc1|API Key|PDF files, scans, email in-body receipts, Images|JSON|SOAP & REST|Within the Ezzybills UI, Integrations->EzzyBills API->(Scroll down) SOAP and REST API links|

### _Invoice Communication APIs_
Invoice Communication APIs are specialized Application Programming Interfaces (APIs) that facilitate the automated and seamless exchange of invoice data, enabling businesses to send and receive e-invoices between organizations over various network 
