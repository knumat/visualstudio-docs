---
description: "Requests that all programs being debugged by this debug engine (DE) to stop execution the next time one of their threads attempts to run."
title: IDebugEngine2::CauseBreak | Microsoft Docs
ms.date: 11/04/2016
ms.topic: reference
f1_keywords:
- IDebugEngine2::CauseBreak
helpviewer_keywords:
- IDebugEngine2::CauseBreak
ms.assetid: 17fe4698-b04e-4798-8412-80e0da60c387
author: maiak
ms.author: maiak
manager: jmartens
ms.technology: vs-ide-debug
ms.workload:
- vssdk
dev_langs:
- CPP
- CSharp
---
# IDebugEngine2::CauseBreak

 [!INCLUDE [Visual Studio](~/includes/applies-to-version/vs-windows-only.md)]
Requests that all programs being debugged by this debug engine (DE) to stop execution the next time one of their threads attempts to run.

## Syntax

### [C#](#tab/csharp)
```csharp
int CauseBreak();
```
### [C++](#tab/cpp)
```cpp
HRESULT CauseBreak( 
   void 
);
```
---

## Return Value
 If successful, returns `S_OK`; otherwise, returns an error code.

## Remarks
 This method is asynchronous: an [IDebugBreakEvent2](../../../extensibility/debugger/reference/idebugbreakevent2.md) event is sent when the program next attempts to execute after this method is called.

## See also
- [CauseBreak](../../../extensibility/debugger/reference/idebugprogram2-causebreak.md)
- [IDebugEngine2](../../../extensibility/debugger/reference/idebugengine2.md)
