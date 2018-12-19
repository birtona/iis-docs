﻿---
title: DeploymentObjectProvider.Add Method  (Microsoft.Web.Deployment)
TOCTitle: Add Method
ms:assetid: M:Microsoft.Web.Deployment.DeploymentObjectProvider.Add(Microsoft.Web.Deployment.DeploymentObject,System.Boolean)
ms:mtpsurl: https://msdn.microsoft.com/en-us/library/microsoft.web.deployment.deploymentobjectprovider.add(v=VS.90)
ms:contentKeyID: 20209052
ms.date: 05/02/2012
mtps_version: v=VS.90
f1_keywords:
- Microsoft.Web.Deployment.DeploymentObjectProvider.Add
dev_langs:
- CSharp
- JScript
- VB
- c++
api_location:
- Microsoft.Web.Deployment.dll
api_name:
- Microsoft.Web.Deployment.DeploymentObjectProvider.Add
api_type:
- Managed
topic_type:
- apiref
- kbSyntax
product_family_name: VS
ROBOTS: INDEX,FOLLOW
---

# Add Method

**Namespace:**  [Microsoft.Web.Deployment](microsoft-web-deployment-namespace.md)  
**Assembly:**  Microsoft.Web.Deployment (in Microsoft.Web.Deployment.dll)

## Syntax

``` vb
'Declaration
PublicOverridableSubAdd ( _
    sourceAsDeploymentObject, _
    whatIfAsBoolean _
)
'Usage
DiminstanceAsDeploymentObjectProviderDimsourceAsDeploymentObjectDimwhatIfAsBoolean

instance.Add(source, whatIf)
```

``` csharp
publicvirtualvoidAdd(
    DeploymentObjectsource,
    boolwhatIf
)
```

``` c++
public:
virtualvoidAdd(
    DeploymentObject^ source, 
    boolwhatIf
)
```

``` jscript
publicfunctionAdd(
    source : DeploymentObject, 
    whatIf : boolean
)
```

#### Parameters

  - source  
    Type: [Microsoft.Web.Deployment. . :: . .DeploymentObject](deploymentobject-class-microsoft-web-deployment.md)  

<!-- end list -->

  - whatIf  
    Type: [System. . :: . .Boolean](https://msdn.microsoft.com/en-us/library/a28wyd50\(v=vs.90\))  

## Permissions

  - Full trust for the immediate caller. This member cannot be used by partially trusted code. For more information, see [Using Libraries from Partially Trusted Code](https://msdn.microsoft.com/en-us/library/8skskf63\(v=vs.90\)).

## See Also

#### Reference

[DeploymentObjectProvider Class](deploymentobjectprovider-class-microsoft-web-deployment.md)

[Microsoft.Web.Deployment Namespace](microsoft-web-deployment-namespace.md)
