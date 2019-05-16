SpineOMatic is a Windows application that works with Ex Libris' Alma to print spine labels, pocket labels, flag slips and other custom labels to a variety of desktop or networked printers, singly or in batches.

* Operation is simple--scan or type an item number, and SpineOMatic gets the label record from Alma and prints a label.
* SpineOMatic is flexible--print to any printer with a Windows print driver, singly or in batches.
* Let Ex Libris parse the label, or let SpineOMatic parse your LC, NLM, SuDoc or other label formats.
* Add holdings info to the label, as well as any other field in the Alma label record.
* Add Label Prefixes (REFERENCE, MEDIA, OVERSIZE, etc.) based on library and shelving location.
* Create spine labels, flag slips, pocket labels or custom labels using any data in the Alma label record.
* View reports of labeling activity for each workstation.
* Updates are easy--SpineOMatic will let you know if a new version is available, and install it automatically.

## System Requirements
An installation of Ex Libris' Alma
Credentials to access the Alma Label Print Web Service, including the path to the Alma server, an authorized user name, password and Ex Libris Institution Code
* A PC running Windows 7(preferred), Vista or XP.
* An up-to-date version of the .Net Framework (4 or higher)
* An up-to-date version of Java (1.7.xx or higher) is required to use the deprecated "SOAP" access method.
* An API key from Ex Libris

## Installation Instructions

Download [`SpineLabeler.exe`](https://github.com/BCLibraries/SpineOMatic/releases/tag/v7.0.0) into an empty directory. Click the application to launch.

The User's Manual can also be downloaded and viewed from SpineOMatic's "About" box. It contains a Quick Start guide that will help you get SpineOMatic installed quickly and easily.

### The following are installation steps provided by an Ex Libris LSP Project Consultant

1. API Key: Login to the ExLibris Developer network: https://developers.exlibrisgroup.com 
1. Generate your API Key: Login to the ExLibris Developer network: https://developers.exlibrisgroup.com 
1. Click on Applications> Add Application
1. Enter a name (e.g. SpineOmatic) and select Multi-purpose.
1. Choose Bibs
1. Accept the Terms and Conditions
1. Click Save.
1. Click the gear icon next to the API Key 
1. Click Edit
1. Choose the API Management tab
1. From the Plan Change drop-down, select Prod Read/Write or Prod Read-Only
1. Open Spine-O-Matic
1. Select Use RESTful API
1. Make the following selections/entries:
  * ALMA URL = https://api-na.hosted.exlibrisgroup.com 
  * Method – leave as is.
  * API key – Paste the key 

ExLibris Developer Network username and password were provided to you in the email accompanying your delivered test load.

## Disclaimer

SpineOMatic is provided free of charge to the Ex Libris Alma user community. It is offered without warranty of any kind. Use it at your own risk. Neither the Trustees of Boston College, nor the agents or employees of Boston College, are liable for damages of any kind resulting from the running of this software or using the information it produces.
