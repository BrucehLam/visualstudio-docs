---
title: "DUMPTYPE | Microsoft Docs"
ms.custom: ""
ms.date: "11/04/2016"
ms.reviewer: ""
ms.suite: ""
ms.technology: 
  - "vs-ide-sdk"
ms.tgt_pltfrm: ""
ms.topic: "article"
f1_keywords: 
  - "DUMPTYPE"
helpviewer_keywords: 
  - "DUMPTYPE enumeration"
ms.assetid: ea8160db-8732-4056-a1d7-892ef72da71e
caps.latest.revision: 10
author: "gregvanl"
ms.author: "gregvanl"
manager: ghogen
---
# DUMPTYPE
Specifies how much of a program's state (such as running threads, stack frames, and current instruction address) to dump.  
  
## Syntax  
  
```cpp  
enum enum_DUMPTYPE {   
   DUMP_MINIDUMP = 0,  
   DUMP_FULLDUMP = 1  
};  
typedef DWORD DUMPTYPE;  
```  
  
```csharp  
public enum enum_DUMPTYPE {   
   DUMP_MINIDUMP = 0,  
   DUMP_FULLDUMP = 1  
};  
```  
  
## Members  
 DUMP_MINIDUMP  
 Specifies a small, compact dump.  
  
 DUMP_FULLDUMP  
 Specifies a large, complete dump.  
  
## Remarks  
 Passed as an argument to the [WriteDump](../../../extensibility/debugger/reference/idebugprogram2-writedump.md) method.  
  
## Requirements  
 Header: msdbg.h  
  
 Namespace: Microsoft.VisualStudio.Debugger.Interop  
  
 Assembly: Microsoft.VisualStudio.Debugger.Interop.dll  
  
## See Also  
 [Enumerations](../../../extensibility/debugger/reference/enumerations-visual-studio-debugging.md)   
 [WriteDump](../../../extensibility/debugger/reference/idebugprogram2-writedump.md)