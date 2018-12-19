﻿---
title: DeploymentBaseContext.IncludeAcls Property  (Microsoft.Web.Deployment)
TOCTitle: IncludeAcls Property
ms:assetid: P:Microsoft.Web.Deployment.DeploymentBaseContext.IncludeAcls
ms:mtpsurl: https://msdn.microsoft.com/en-us/library/microsoft.web.deployment.deploymentbasecontext.includeacls(v=VS.90)
ms:contentKeyID: 20208798
ms.date: 05/02/2012
mtps_version: v=VS.90
f1_keywords:
- Microsoft.Web.Deployment.DeploymentBaseContext.IncludeAcls
- Microsoft.Web.Deployment.DeploymentBaseContext.get_IncludeAcls
dev_langs:
- CSharp
- JScript
- VB
- c++
api_location:
- Microsoft.Web.Deployment.dll
api_name:
- Microsoft.Web.Deployment.DeploymentBaseContext.get_IncludeAcls
- Microsoft.Web.Deployment.DeploymentBaseContext.IncludeAcls
api_type:
- Managed
topic_type:
- apiref
- kbSyntax
product_family_name: VS
ROBOTS: INDEX,FOLLOW
---

# IncludeAcls Property

Gets a value that indicates whether security descriptors will be added to the deployment context.

**Namespace:**  [Microsoft.Web.Deployment](microsoft-web-deployment-namespace.md)  
**Assembly:**  Microsoft.Web.Deployment (in Microsoft.Web.Deployment.dll)

## Syntax

``` vb
'Declaration
PublicReadOnlyPropertyIncludeAclsAsBoolean
'Usage
DiminstanceAsDeploymentBaseContextDimvalueAsBooleanvalue = instance.IncludeAcls
```

``` csharp
publicboolIncludeAcls { get; }
```

``` c++
public:
propertyboolIncludeAcls {
    boolget ();
}
```

``` jscript
function getIncludeAcls () : boolean
```

#### Property Value

Type: [System. . :: . .Boolean](https://msdn.microsoft.com/en-us/library/a28wyd50\(v=vs.90\))  
true if security descriptors will be added to the deployment context, otherwise false.  

## Permissions

  - Full trust for the immediate caller. This member cannot be used by partially trusted code. For more information, see [Using Libraries from Partially Trusted Code](https://msdn.microsoft.com/en-us/library/8skskf63\(v=vs.90\)).

## See Also

#### Reference

[DeploymentBaseContext Class](deploymentbasecontext-class-microsoft-web-deployment.md)

[Microsoft.Web.Deployment Namespace](microsoft-web-deployment-namespace.md)
