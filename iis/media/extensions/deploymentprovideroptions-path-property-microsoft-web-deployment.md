﻿---
title: DeploymentProviderOptions.Path Property  (Microsoft.Web.Deployment)
TOCTitle: Path Property
ms:assetid: P:Microsoft.Web.Deployment.DeploymentProviderOptions.Path
ms:mtpsurl: https://msdn.microsoft.com/en-us/library/microsoft.web.deployment.deploymentprovideroptions.path(v=VS.90)
ms:contentKeyID: 20209079
ms.date: 05/02/2012
mtps_version: v=VS.90
f1_keywords:
- Microsoft.Web.Deployment.DeploymentProviderOptions.Path
- Microsoft.Web.Deployment.DeploymentProviderOptions.get_Path
- Microsoft.Web.Deployment.DeploymentProviderOptions.set_Path
dev_langs:
- CSharp
- JScript
- VB
- c++
api_location:
- Microsoft.Web.Deployment.dll
api_name:
- Microsoft.Web.Deployment.DeploymentProviderOptions.get_Path
- Microsoft.Web.Deployment.DeploymentProviderOptions.Path
- Microsoft.Web.Deployment.DeploymentProviderOptions.set_Path
api_type:
- Managed
topic_type:
- apiref
- kbSyntax
product_family_name: VS
ROBOTS: INDEX,FOLLOW
---

# Path Property

Gets the path of the current object.

**Namespace:**  [Microsoft.Web.Deployment](microsoft-web-deployment-namespace.md)  
**Assembly:**  Microsoft.Web.Deployment (in Microsoft.Web.Deployment.dll)

## Syntax

``` vb
'Declaration
PublicPropertyPathAsString
'Usage
DiminstanceAsDeploymentProviderOptionsDimvalueAsStringvalue = instance.Path

instance.Path = value
```

``` csharp
publicstringPath { get; set; }
```

``` c++
public:
propertyString^ Path {
    String^ get ();
    voidset (String^ value);
}
```

``` jscript
function getPath () : Stringfunction setPath (value : String)
```

#### Property Value

Type: [System. . :: . .String](https://msdn.microsoft.com/en-us/library/s1wwdcbf\(v=vs.90\))  
The path of the current object.  

## Permissions

  - Full trust for the immediate caller. This member cannot be used by partially trusted code. For more information, see [Using Libraries from Partially Trusted Code](https://msdn.microsoft.com/en-us/library/8skskf63\(v=vs.90\)).

## See Also

#### Reference

[DeploymentProviderOptions Class](deploymentprovideroptions-class-microsoft-web-deployment.md)

[Microsoft.Web.Deployment Namespace](microsoft-web-deployment-namespace.md)
