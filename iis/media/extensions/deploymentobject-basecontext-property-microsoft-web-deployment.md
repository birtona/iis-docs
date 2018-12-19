﻿---
title: DeploymentObject.BaseContext Property  (Microsoft.Web.Deployment)
TOCTitle: BaseContext Property
ms:assetid: P:Microsoft.Web.Deployment.DeploymentObject.BaseContext
ms:mtpsurl: https://msdn.microsoft.com/en-us/library/microsoft.web.deployment.deploymentobject.basecontext(v=VS.90)
ms:contentKeyID: 20209225
ms.date: 05/02/2012
mtps_version: v=VS.90
f1_keywords:
- Microsoft.Web.Deployment.DeploymentObject.BaseContext
- Microsoft.Web.Deployment.DeploymentObject.get_BaseContext
dev_langs:
- CSharp
- JScript
- VB
- c++
api_location:
- Microsoft.Web.Deployment.dll
api_name:
- Microsoft.Web.Deployment.DeploymentObject.BaseContext
- Microsoft.Web.Deployment.DeploymentObject.get_BaseContext
api_type:
- Managed
topic_type:
- apiref
- kbSyntax
product_family_name: VS
ROBOTS: INDEX,FOLLOW
---

# BaseContext Property

Gets the [DeploymentBaseContext](deploymentbasecontext-class-microsoft-web-deployment.md) associated with the current object.

**Namespace:**  [Microsoft.Web.Deployment](microsoft-web-deployment-namespace.md)  
**Assembly:**  Microsoft.Web.Deployment (in Microsoft.Web.Deployment.dll)

## Syntax

``` vb
'Declaration
PublicReadOnlyPropertyBaseContextAsDeploymentBaseContext
'Usage
DiminstanceAsDeploymentObjectDimvalueAsDeploymentBaseContextvalue = instance.BaseContext
```

``` csharp
publicDeploymentBaseContextBaseContext { get; }
```

``` c++
public:
propertyDeploymentBaseContext^ BaseContext {
    DeploymentBaseContext^ get ();
}
```

``` jscript
function getBaseContext () : DeploymentBaseContext
```

#### Property Value

Type: [Microsoft.Web.Deployment. . :: . .DeploymentBaseContext](deploymentbasecontext-class-microsoft-web-deployment.md)  

## Permissions

  - Full trust for the immediate caller. This member cannot be used by partially trusted code. For more information, see [Using Libraries from Partially Trusted Code](https://msdn.microsoft.com/en-us/library/8skskf63\(v=vs.90\)).

## See Also

#### Reference

[DeploymentObject Class](deploymentobject-class-microsoft-web-deployment.md)

[Microsoft.Web.Deployment Namespace](microsoft-web-deployment-namespace.md)
