---
title: delete disk
description: "Windows Commands topic for **** - "
ms.custom: na
ms.prod: windows-server-threshold
ms.reviewer: na
ms.suite: na
ms.technology: manage-windows-commands
ms.tgt_pltfrm: na
ms.topic: article
ms.assetid: 44079900-e4ed-49d0-81e4-d652c38cd636
author: coreyp-at-msft
ms.author: coreyp
manager: dongill
ms.date: 10/12/2016
---
# delete disk

>Applies To: Windows Server 2016, Windows Server 2012 R2, Windows Server 2012

deletes a missing dynamic disk from the list of disks.  
  
for instructions regarding how to use this command, see [remove a Missing Dynamic Disk](http://go.microsoft.com/fwlink/?LinkId=207055) \(http:\/\/go.microsoft.com\/fwlink\/?LinkId\=207055\).  
  
## Syntax  
  
```  
delete disk [noerr] [override]  
```  
  
## Parameters  
  
|Parameter|Description|  
|-------|--------|  
|noerr|for scripting only. When an error is encountered, DiskPart continues to process commands as if the error did not occur. Without this parameter, an error causes DiskPart to exit with an error code.|  
|override|Enables DiskPart to delete all simple volumes on the disk. If the disk contains half of a mirrored volume, the half of the mirror on the disk is deleted. The delete disk override command fails if the disk is a member of a RAID\-5 volume.|  
  
## <a name="BKMK_examples"></a>Examples  
To delete a missing dynamic disk from the list of disks, type:  
  
```  
delete disk  
```  
  
#### additional references  
[Command-Line Syntax Key](command-line-syntax-key.md)  
  

  
