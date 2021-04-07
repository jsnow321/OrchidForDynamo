![logo](img/logo.png)
# &nbsp; Orchid  
  
![maintained](https://img.shields.io/maintenance/yes/2021)
![commit](https://img.shields.io/github/last-commit/erfajo/orchidfordynamo)
[![license](https://img.shields.io/badge/License-CC%20BY--ND%204.0-brightgreen)](http://creativecommons.org/licenses/by-nd/4.0/)  
Orchid is a solution designed for use in the [Dynamo](http://dynamobim.org) environment. The solution is designed to support practical, technical, logical, and mathematical issues. In particular, is some solutions designed to handle nD-list issues. In addition, are solutions for applications included that not necessarily are Autodesk products.  
  
**Software environment:**  
Built for Dynamo 2.10 (Revit 2022), Dynamo 2.6 (Revit 2021), 2.3 (Revit 2020), and 2.0 (Revit 2019, 2018).  
  
**Orchid Samples:**  
In the [samples](Samples) folder are examples using the Orchid package placed. For further informations read the [Readme](Samples/readme.md) file!  
  
**History/Change Log:**  
[![orchid](https://img.shields.io/badge/Orchid-210-lightgrey)](Orchid_210.md)
[![orchid](https://img.shields.io/badge/Orchid-206-lightgrey)](Orchid_206.md)
[![orchid](https://img.shields.io/badge/Orchid-203-lightgrey)](Orchid_203.md)
[![orchid](https://img.shields.io/badge/Orchid-200-lightgrey)](Orchid_200.md)
  
---
## Install or Update the package for Dynamo  
Use the executable installer in the **[Builds](Builds)** folder to install the Orchid package. Please note the vertical versions of Orchid are coded for a specific version of Dynamo and Revit to ensure code is applicable for that exact combination, and not least due to the enormous scope of Orchid.  
  
Select the executable according to your dynamo version!  
[![orchid](https://img.shields.io/badge/Orchid-210-brightgreen) &nbsp;&nbsp;&nbsp; ![dynamo](https://img.shields.io/badge/Dynamo-2.10-blue) &nbsp;&nbsp;&nbsp; ![revit](https://img.shields.io/badge/Revit-2022-blue)](Builds/OrchidForDynamo_210.exe)  
[![orchid](https://img.shields.io/badge/Orchid-206-brightgreen) &nbsp;&nbsp;&nbsp; ![dynamo](https://img.shields.io/badge/Dynamo-2.6-blue) &nbsp;&nbsp;&nbsp;&nbsp;&nbsp; ![revit](https://img.shields.io/badge/Revit-2021-blue)](Builds/OrchidForDynamo_206.exe)  
[![orchid](https://img.shields.io/badge/Orchid-203-brightgreen) &nbsp;&nbsp;&nbsp; ![dynamo](https://img.shields.io/badge/Dynamo-2.3-blue) &nbsp;&nbsp;&nbsp;&nbsp;&nbsp; ![revit](https://img.shields.io/badge/Revit-2020-blue)](Builds/OrchidForDynamo_203.exe)  
[![orchid](https://img.shields.io/badge/Orchid-200-brightgreen) &nbsp;&nbsp;&nbsp; ![dynamo](https://img.shields.io/badge/Dynamo-2.0-blue) &nbsp;&nbsp;&nbsp;&nbsp;&nbsp; ![revit](https://img.shields.io/badge/Revit-2019%20&verbar;%202018-blue)](Builds/OrchidForDynamo_200.exe)  
  
<span style="color:red">**REVIT AND DYNAMO MUST BE CLOSED DURING INSTALLATION!**</span>  
</br>

### Manually installation
The Orchid package may also be installed by manually copying files from the **[Zipped](Zipped)** folder. This is only recommendable for experienced users! To install/update this way, please unzip the zip-file of the chosen version into your dynamo package folder, into a folder named **Orchid**. Download may be handled either by downloading a single file, or by cloning or zipping the repository. The package folder path can be found in Dynamo via the menu item 'Settings' -> 'Manage Node and Package Paths'.  
  
Select the zip-file according to your dynamo version!  
Orchid_210_? &nbsp;&nbsp;&nbsp; (for the dynamo 2.10.x branch)  
Orchid_206_? &nbsp;&nbsp;&nbsp; (for the dynamo 2.6.x branch)  
Orchid_203_? &nbsp;&nbsp;&nbsp; (for the dynamo 2.3.x branch)  
Orchid_200_? &nbsp;&nbsp;&nbsp; (for the dynamo 2.0.x branch)  
  
The individual version is avalible both for the sandbox version and for the version used Inside revit.  
?_Revit &nbsp;&nbsp;&nbsp; (the Revit version)  
?_Core &nbsp;&nbsp;&nbsp; (the Sandbox version)  
  
### Error handling
If Orchid dosnt work after installation, then try to see if you have one of these <a href="error.md">errors</a>!  
  
---
## Node description and organization  
Nodes are generally arranged in four node assemblies depending the version. Two assemblies cover the Revit version and two assemblies cover the Core (Sandbox) version. Each of the two sets of assemblies has an assembly for base/standard nodes and an assembly for extensible nodes, mainly dropdown nodes. Besides these four, are assemblies covering external applications outside Revit and icons for the nodes present.  
The nodes may also be used as textual scripted functions in code blocks and custom nodes, example when using design script in code blocks as the Dynamo functions.  
  
Inside Dynamo is the Orchid package nodes arranged into different main branches: Common, RevitFamily, RevitMaterial, RevitProject, About, and Applications. The last branch covers functions for external applications outside Revit. The first four branches covers functions to be used inside Revit. the About branch cover nodes for information about the Orchid package.  
  
Nodes in the four Revit driven branches can be recognized by their icon ribbon color:  
Common -> yellow &nbsp;|&nbsp; RevitFamily -> blue &nbsp;|&nbsp; RevitMaterial -> green &nbsp;|&nbsp; RevitProject -> red  
  
---
## License  
Copyright(c) 2014  
Erik Falck Jørgensen  
  
All content in this repository is part of the Orchid package.  
  
[![license](https://i.creativecommons.org/l/by-nd/4.0/88x31.png)](http://creativecommons.org/licenses/by-nd/4.0/)  
  
This work is licensed under the [Creative Commons Attribution-NoDerivatives 4.0 International](http://creativecommons.org/licenses/by-nd/4.0/) license (CC BY-ND 4.0).  
  
In short terms does the CC BY-ND license state: This license allows for redistribution, commercial and non-commercial, as long as it is passed along unchanged and in whole, with credit to the author.  
