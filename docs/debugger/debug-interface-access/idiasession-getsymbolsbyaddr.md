---
description: "Retrieves an enumerator that finds symbols in the order of their addresses."
title: "IDiaSession::getSymbolsByAddr | Microsoft Docs"
ms.date: "11/04/2016"
ms.topic: "reference"
dev_langs:
  - "C++"
helpviewer_keywords:
  - "IDiaSession::getSymbolsByAddr method"
ms.assetid: eafcc757-b488-487d-a063-ad3703ff42e8
author: "mikejo5000"
ms.author: "mikejo"
manager: jmartens
ms.technology: vs-ide-debug
ms.workload:
  - "multiple"
---
# IDiaSession::getSymbolsByAddr

 [!INCLUDE [Visual Studio](~/includes/applies-to-version/vs-windows-only.md)]
Retrieves an enumerator that finds symbols in the order of their addresses.

## Syntax

```C++
HRESULT getSymbolsByAddr( 
   IDiaEnumSymbolsByAddr** ppEnumbyAddr
);
```

#### Parameters
 `ppEnumbyAddr`

[out] Returns an [IDiaEnumSymbolsByAddr](../../debugger/debug-interface-access/idiaenumsymbolsbyaddr.md) object. Use this interface to search for symbols in the symbol store by memory location.

## Return Value
 If successful, returns `S_OK`; otherwise, returns an error code.

## See also
- [IDiaSession](../../debugger/debug-interface-access/idiasession.md)
- [IDiaEnumSymbolsByAddr](../../debugger/debug-interface-access/idiaenumsymbolsbyaddr.md)
