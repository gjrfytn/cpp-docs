---
title: "CDataConnection::operator CDataSource* | Microsoft Docs"
ms.custom: ""
ms.date: "11/04/2016"
ms.technology: ["cpp-data"]
ms.topic: "reference"
f1_keywords: ["CDataSource*", "CDataConnection::operatorCDataSource*", "CDataConnection.operatorCDataSource*", "operatorCDataSource*"]
dev_langs: ["C++"]
helpviewer_keywords: ["CDataSource* operator", "operator * (CDataSource)"]
ms.assetid: 9118e324-e68d-45c5-a791-03f041d420ed
author: "mikeblome"
ms.author: "mblome"
ms.workload: ["cplusplus", "data-storage"]
---
# CDataConnection::operator CDataSource*
Returns a pointer to the contained `CDataSource` object.  
  
## Syntax  
  
```cpp
operator const CDataSource*() throw();  
  
```  
  
## Remarks  
 This operator returns a pointer to the contained `CDataSource` object, allowing you to pass a `CDataConnection` object where a `CDataSource` pointer is expected.  
  
 See [operator CDataSource&](../../data/oledb/cdataconnection-operator-cdatasource-amp.md) for a usage example.  
  
## Requirements  
 **Header:** atldbcli.h  
  
## See Also  
 [CDataConnection Class](../../data/oledb/cdataconnection-class.md)   
 [CDataConnection::operator CDataSource&](../../data/oledb/cdataconnection-operator-cdatasource-amp.md)