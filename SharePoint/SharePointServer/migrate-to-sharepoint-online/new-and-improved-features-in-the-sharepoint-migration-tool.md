---
title: "New and improved features in the SharePoint Migration Tool"
ms.author: jhendr
author: JoanneHendrickson
manager: pamgreen
ms.date: 2/13/2018
ms.audience: ITPro
ms.topic: article
ms.prod: sharepoint-server-itpro
localization_priority: Normal
ms.assetid: f3f3e548-196f-44b9-b630-645d781bc096
description: "Learn about the new features and updates to existing features in SharePoint Migration Tool, Version 0.2.78.0."
---

# New and improved features in the SharePoint Migration Tool

Learn about the new features and updates to existing features in SharePoint Migration Tool, Version 0.2.78.0.
  
> [!NOTE]
> To download the SharePoint Migration Tool, go here: [ SharePoint Migration Tool ](http://technet.microsoft.com/library/http://spmtreleasescus.blob.core.windows.net/install/default.md.aspx)
  
## New features

The following features have been added to this update.
  
|**Feature**|**Description**|
|:-----|:-----|
|Allow migration of 0 bytes files  <br/> |Files will be migrated even if they are of zero bytes.  <br/> |
|Computer names column  <br/> |A column containing the name of the computers running the migration job has been added to the report.  <br/> |
|Support of incremental check on target environment  <br/> |In SharePoint Online, an incremental check of the target environment will be performed. If the modified time of the source file is earlier than the modified time of the target file, the file will not be migrated.  <br/> |
   
## Improvements

In addition to a number of minor fixes, here are the primary improvements made in this release:
  
|**Issue**|**Fix**|
|:-----|:-----|
|Stability  <br/> |General improvements have been made to remove some errors in tool.  <br/> |
|Permissions fixes  <br/> |We have made several improvements to better preserve the permission when requested and not removing existing permission in the destination.  <br/> |
|Warnings when files are checked out  <br/> |Users will now have warning messages appear in the tool when attempting to migrate a file that was checked out.  <br/> |
|Report when performing only a scan  <br/> |The **FilesReport.csv** file will now show the correct results when only scanning option is turned on.  <br/> |
   
## See also

#### Other Resources

[Download the SharePoint Migration Tool](http://spmtreleasescus.blob.core.windows.net/install/default.md)
  
[How to use the SharePoint Migration Tool](how-to-use-the-sharepoint-migration-tool.md)

