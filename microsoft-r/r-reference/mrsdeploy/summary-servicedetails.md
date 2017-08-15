--- 
 
# required metadata 
title: "The summary generic for serviceDetails." 
description: " Defines the R summary generic for serviceDetails during a  listServices(). " 
keywords: "mrsdeploy, summary.serviceDetails" 
author: "HeidiSteen"
ms.author: "heidist" 
manager: "jhubbard" 
ms.date: "04/17/2017" 
ms.topic: "reference" 
ms.prod: "microsoft-r" 
ms.service: "" 
ms.assetid: "" 
 
# optional metadata 
#ROBOTS: "" 
#audience: "" 
#ms.devlang: "" 
#ms.reviewer: "" 
#ms.suite: "" 
#ms.tgt_pltfrm: "" 
ms.technology: "r-server" 
#ms.custom: "" 
 
--- 
 
 
 
 
 #summary.serviceDetails: The summary generic for `serviceDetails`.

 Applies to version 1.1.0 of package mrsdeploy.
 
 ##Description
 
Defines the R summary generic for `serviceDetails` during a 
`listServices()`.
 
 
 ##Usage

```   
 ## S3 method for class `serviceDetails':
summary  (o)
 
```
 
 ##Arguments

   
  
 ### o
 The `serviceDetails` list of S3 objects. 
  
 
 
 ##See Also
 
Other service methods: [deleteService](deleteservice.md),
[getService](getservice.md), [listServices](listservices.md),
[print.serviceDetails](print-servicedetails.md),
[publishService](publishservice.md),
[serviceOption](serviceoption.md), [updateService](updateservice.md)
   
 ##Examples

 ```
   
  ## Not run:
 
# --- print all ---
summary(listServices())
 ## End(Not run) 
  
 
```
 
 