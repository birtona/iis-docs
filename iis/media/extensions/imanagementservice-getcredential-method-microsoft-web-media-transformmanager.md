﻿---
title: IManagementService.GetCredential Method  (Microsoft.Web.Media.TransformManager)
TOCTitle: GetCredential Method
ms:assetid: M:Microsoft.Web.Media.TransformManager.IManagementService.GetCredential(System.String)
ms:mtpsurl: https://msdn.microsoft.com/en-us/library/microsoft.web.media.transformmanager.imanagementservice.getcredential(v=VS.90)
ms:contentKeyID: 35521066
ms.date: 06/14/2012
mtps_version: v=VS.90
f1_keywords:
- Microsoft.Web.Media.TransformManager.IManagementService.GetCredential
dev_langs:
- CSharp
- JScript
- VB
- FSharp
- c++
api_location:
- Microsoft.Web.Media.TransformManager.ServiceLibrary.dll
api_name:
- Microsoft.Web.Media.TransformManager.IManagementService.GetCredential
api_type:
- Managed
topic_type:
- apiref
- kbSyntax
product_family_name: VS
ROBOTS: INDEX,FOLLOW
---

# GetCredential Method

Returns a [Credential](credential-class-microsoft-web-media-transformmanager.md) object for the service account from the Generic Credentials vault in Windows Credential Manager.

**Namespace:**  [Microsoft.Web.Media.TransformManager](microsoft-web-media-transformmanager-namespace.md)  
**Assembly:**  Microsoft.Web.Media.TransformManager.ServiceLibrary (in Microsoft.Web.Media.TransformManager.ServiceLibrary.dll)

## Syntax

``` vb
'Declaration
<OperationContractAttribute> _
FunctionGetCredential ( _
    credentialIdAsString _
) AsCredential
'Usage
DiminstanceAsIManagementServiceDimcredentialIdAsStringDimreturnValueAsCredentialreturnValue = instance.GetCredential(credentialId)
```

``` csharp
[OperationContractAttribute]
CredentialGetCredential(
    stringcredentialId
)
```

``` c++
[OperationContractAttribute]
Credential^ GetCredential(
    String^ credentialId
)
```

``` fsharp
[<OperationContractAttribute>]
abstractGetCredential : 
        credentialId:string->Credential
```

``` jscript
functionGetCredential(
    credentialId : String
) : Credential
```

#### Parameters

  - credentialId  
    Type: [System. . :: . .String](https://msdn.microsoft.com/en-us/library/s1wwdcbf\(v=vs.90\))  
    The ID of a [Credential](credential-class-microsoft-web-media-transformmanager.md) object to get.  

#### Return Value

Type: [Microsoft.Web.Media.TransformManager. . :: . .Credential](credential-class-microsoft-web-media-transformmanager.md)  
The [Credential](credential-class-microsoft-web-media-transformmanager.md) object.  

## See Also

#### Reference

[IManagementService Interface](imanagementservice-interface-microsoft-web-media-transformmanager.md)

[Microsoft.Web.Media.TransformManager Namespace](microsoft-web-media-transformmanager-namespace.md)
