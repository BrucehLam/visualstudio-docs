---
title: "IDiaSectionContrib::get_relativeVirtualAddress | Microsoft Docs"
ms.custom: ""
ms.date: "11/04/2016"
ms.reviewer: ""
ms.suite: ""
ms.technology: 
  - "vs-ide-debug"
ms.tgt_pltfrm: ""
ms.topic: "article"
dev_langs: 
  - "C++"
helpviewer_keywords: 
  - "IDiaSectionContrib::get_relativeVirtualAddress method"
ms.assetid: 32f9674d-94f1-4590-99de-a2eb60da4af8
caps.latest.revision: 9
author: "mikejo5000"
ms.author: "mikejo"
manager: ghogen
---
# IDiaSectionContrib::get_relativeVirtualAddress
Retrieves the image relative virtual address (RVA) of the contribution.  
  
## Syntax  
  
```C++  
HRESULT get_relativeVirtualAddress (   
   DWORD* pRetVal  
);  
```  
  
#### Parameters  
 `pRetVal`  
 [out] Returns the image RVA of the contribution.  
  
## Return Value  
 If successful, returns `S_OK`. Returns `S_FALSE` if this property is not supported. Otherwise, returns an error code.  
  
## See Also  
 [IDiaSectionContrib](../../debugger/debug-interface-access/idiasectioncontrib.md)