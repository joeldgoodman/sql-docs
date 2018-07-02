---
title: "LOCALDB_ERROR_INSTANCE_ALREADY_SHARED | Microsoft Docs"
ms.custom: ""
ms.date: "06/13/2017"
ms.prod: "sql-server-2014"
ms.reviewer: ""
ms.suite: ""
ms.technology: 
  - "database-engine"
  - "docset-sql-devref"
ms.tgt_pltfrm: ""
ms.topic: "reference"
ms.assetid: 35b4d6fa-ebb9-49d3-aaab-d4e37b6f3760
caps.latest.revision: 6
author: stevestein
ms.author: sstein
manager: craigg
---
# LOCALDB_ERROR_INSTANCE_ALREADY_SHARED
    
## Details  
  
|||  
|-|-|  
|Product Name|SQL Server|  
|Event ID|284|  
|Event Source|SQL Server Local Database Runtime 12.0|  
|Component|Local Database Runtime API|  
|Message Text|The specified Local Database Instance is already shared.|  
  
## Explanation  
 The specified Local Database Instance is already shared with a different shared name.  
  
## User Action  
 Unshare the shared instance before sharing it again with a different shared name.  
  
  