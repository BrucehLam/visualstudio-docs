---
title: "Properties of elements on UML activity diagrams | Microsoft Docs"
ms.custom: ""
ms.date: "11/04/2016"
ms.prod: "visual-studio-tfs-dev14"
ms.reviewer: ""
ms.suite: ""
ms.tgt_pltfrm: ""
ms.topic: "article"
f1_keywords: 
  - "vs.teamarch.activitydiagram.shapes.properties"
helpviewer_keywords: 
  - "UML, element properties"
  - "activity diagrams, properties"
ms.assetid: 9849d45e-65d5-46bd-a319-757e90b7c748
caps.latest.revision: 17
author: "alexhomer1"
ms.author: "ahomer"
manager: "douge"
translation.priority.ht: 
  - "cs-cz"
  - "de-de"
  - "es-es"
  - "fr-fr"
  - "it-it"
  - "ja-jp"
  - "ko-kr"
  - "pl-pl"
  - "pt-br"
  - "ru-ru"
  - "tr-tr"
  - "zh-cn"
  - "zh-tw"
---
# Properties of elements on UML activity diagrams
On a UML activity diagram, each element on the diagram has properties. To see the properties of an element, right-click the element on the diagram or in **UML Model Explorer** and then click **Properties**. The properties appear in the **Properties** window.  
  
> [!NOTE]
>  This topic is about the properties of elements on UML activity diagrams. For information about how to read UML activity diagrams, see [UML Activity Diagrams: Reference](../modeling/uml-activity-diagrams-reference.md). For more information about how to draw UML activity diagrams, see [UML Activity Diagrams: Guidelines](../modeling/uml-activity-diagrams-guidelines.md).  
  
## Properties of Elements  
  
|Property|Default|Element|Description|  
|--------------|-------------|-------------|-----------------|  
|**Name**|A default name|All|Identifies the element.|  
|**Qualified Name**|Package :: Name|All|Identifies the element uniquely. Prefixed with the qualified name of the package that contains it.|  
|**Work Items**|0 associated|All|The number of work items associated with this element. To associate work items, see [Link model elements and work items](../modeling/link-model-elements-and-work-items.md).|  
|**Description**|(none)|All|You can make general notes about the element here.|  
|**Color**|(default for the type)|All|The color of the shape.|  
|**Body**|(none)|Action|Specifies the action in detail.|  
|**Language**|(none)|Action|The language of the expression in Body.|  
|**Local Postconditions**|(none)|Action, Send, Accept, Call Behavior, Call Operation|Constraints that must be satisfied when execution ends. The goal achieved by the action.|  
|**Local Preconditions**|(none)|Action, Send, Accept, Call Behavior, Call Operation|Constraints that must be satisfied before execution begins.|  
|**Is Synchronous**|True|Call Behavior, Call Operation|-   If true, the action waits until the activity terminates.|  
|**Behavior**|(none)|Call Behavior|-   The activity invoked.|  
|**Operation**|(none)|Call Operation|-   The operation invoked.|  
|**Is Unmarshall**|False|Accept Event|-   If true, there can be several typed output pins, and data is unmarshaled onto them. If false, all data appear on one pin.|  
|**Upper Bound**|**\***|Object Node, Activity Parameter|**0** indicates that data must pass directly along the flow.<br /><br /> **\*** indicates that data can be stored in the flow.|  
|**Selection**|(none)|Object Node, Activity Parameter, Input Pin, Output Pin, Object Flow|Invokes a process that filters the data. This process can be defined in another diagram.|  
|**Ordering**|(none)|Object Node, Activity Parameter, Input Pin, Output Pin|-   How multiple tokens are stored.|  
|**Is Control**|False|Input Pin, Output Pin|-   If true, the flow on this pin is a control flow. If false, it is an object flow.|  
|**Type**|(none)|Input Pin, Output Pin, Object Node, Activity Parameter|-   The type of objects transmitted.<br />-   The type can be a primitive type such as Integer, or a classifier defined elsewhere in the model. If you enter the name of a type that is not defined, it will appear in the **Unspecified Types** section of UML Model Explorer.|  
|**Multiplicity**|1|Input Pin, Output Pin|-   Can be a single value, or a range `[n..m]`.<br />-   Lower bound `n` - the action cannot start (for an input pin) or stop (for an output pin) until there are `n` objects waiting on the pin.<br />-   Upper bound `m` - The action cannot consume or produce more than `m` objects in one execution. * means that there is no limit.|  
|**Transformation**|(none)|Object Flow|-   Invokes a process that transforms the data. This process can be defined in another diagram.|  
|**Is Multicast**|False|Object Flow|-   Indicates that there might be several recipient objects or components.|  
|**Is MultiReceive**|False|Object Flow|-   Indicates that there might be several recipient objects or components.|  
|**Is Single Execution**|False|Activity Diagram|-   If set, there is at most one execution of this diagram at a time.|  
  
## See Also  
 [UML Activity Diagrams: Reference](../modeling/uml-activity-diagrams-reference.md)   
 [UML Activity Diagrams: Guidelines](../modeling/uml-activity-diagrams-guidelines.md)