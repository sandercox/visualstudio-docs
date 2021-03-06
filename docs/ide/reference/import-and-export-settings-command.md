---
title: "Import and Export Settings Command | Microsoft Docs"
ms.custom: ""
ms.date: "11/04/2016"
ms.reviewer: ""
ms.suite: ""
ms.technology: 
  - "vs-ide-general"
ms.tgt_pltfrm: ""
ms.topic: "article"
f1_keywords: 
  - "Tools.ImportandExportSettings"
helpviewer_keywords: 
  - "Tools.ImportandExportSettings"
  - "Import and Export Settings command"
ms.assetid: 94a06468-a44d-403d-a931-77bbc9d06e56
caps.latest.revision: 5
author: "gewarren"
ms.author: "gewarren"
manager: ghogen
---
# Import and Export Settings Command
Imports, exports, or resets [!INCLUDE[vsprvs](../../code-quality/includes/vsprvs_md.md)] settings.  
  
## Syntax  
  
```  
Tools.ImportandExportSettings [/export:filename | /import:filename | /reset]  
```  
  
## Switches  
 /export:`filename`  
 Optional. Exports the current settings to the specified file.  
  
 /import:`filename`  
 Optional. Imports the settings in the specified file.  
  
 /reset  
 Optional. Resets the current settings.  
  
## Remarks  
 Running this command with no switches opens the **Import and Export Settings** wizard. For more information, see [How to: Share Settings Between Computers or Visual Studio Versions](http://msdn.microsoft.com/en-us/1131fb10-35c1-42da-9cd8-91aa3235b882).  
  
## Example  
 The following command exports the curent settings to the file `MyFile.vssettings`.  
  
```  
Tools.ImportandExportSettings /export:"c:\Files\MyFile.vssettings"  
```  
  
## See Also  
 [Personalize the Visual Studio IDE](../../ide/personalizing-the-visual-studio-ide.md)   
 [Visual Studio Commands](../../ide/reference/visual-studio-commands.md)