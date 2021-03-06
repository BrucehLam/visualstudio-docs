---
title: "The connection property in the Application Settings file is missing or incorrect | Microsoft Docs"
ms.custom: ""
ms.date: "11/04/2016"
ms.reviewer: ""
ms.suite: ""
ms.tgt_pltfrm: ""
ms.topic: "article"
ms.assetid: 77724510-ff59-4d43-b933-a0434e1ac597
caps.latest.revision: 4
author: "gewarren"
ms.author: "gewarren"
manager: ghogen
ms.technology: "vs-data-tools"
---
# The connection property in the Application Settings file is missing or incorrect
The connection property in the Application Settings file is missing or incorrect. The connection string from the .dbml file has been used in its place.  
  
 The .dbml file contains a reference to a connection string in the application settings file that cannot be found. This message is informational; the connection string setting will be created when **OK** is clicked.  
  
### To respond to this message  
  
-   Click **OK**. The connection information that is contained in the .dbml file is added to application settings.  
  
## See Also  
 [LINQ to SQL Tools in Visual Studio](../data-tools/linq-to-sql-tools-in-visual-studio2.md)   
 [Walkthrough: Creating LINQ to SQL Classes (O-R Designer)](how-to-create-linq-to-sql-classes-mapped-to-tables-and-views-o-r-designer.md)   
 [Managing Application Settings (.NET)](../ide/managing-application-settings-dotnet.md)   
 [LINQ to SQL](/dotnet/framework/data/adonet/sql/linq/index)