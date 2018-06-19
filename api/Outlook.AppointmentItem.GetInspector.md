---
title: AppointmentItem.GetInspector Property (Outlook)
keywords: vbaol11.chm853
f1_keywords:
- vbaol11.chm853
ms.prod: outlook
api_name:
- Outlook.AppointmentItem.GetInspector
ms.assetid: 6d0dc447-80f3-ab00-4bb9-7bbda34745aa
ms.date: 06/08/2017
---


# AppointmentItem.GetInspector Property (Outlook)

Returns an  **[Inspector](Outlook.Inspector.md)** object that represents an inspector initialized to contain the specified item. Read-only.


## Syntax

 _expression_. 'GetInspector'

 _expression_ A variable that represents an **AppointmentItem** object.


## Remarks

This property is useful for returning an  **Inspector** object in which to display the item, as opposed to using the **[Application.ActiveInspector](Outlook.Application.ActiveInspector.md)** method and setting the **[Inspector.CurrentItem](Outlook.Inspector.CurrentItem.md)** property. If an **Inspector** object already exists for the item, the **GetInspector** property will return that **Inspector** object instead of creating a new one.


## See also


[AppointmentItem Object](Outlook.AppointmentItem.md)
