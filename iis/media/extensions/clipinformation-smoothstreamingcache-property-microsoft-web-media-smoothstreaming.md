﻿---
title: ClipInformation.SmoothStreamingCache Property  (Microsoft.Web.Media.SmoothStreaming)
TOCTitle: SmoothStreamingCache Property
ms:assetid: P:Microsoft.Web.Media.SmoothStreaming.ClipInformation.SmoothStreamingCache
ms:mtpsurl: https://msdn.microsoft.com/en-us/library/microsoft.web.media.smoothstreaming.clipinformation.smoothstreamingcache(v=VS.90)
ms:contentKeyID: 31469261
ms.date: 05/02/2012
mtps_version: v=VS.90
f1_keywords:
- Microsoft.Web.Media.SmoothStreaming.ClipInformation.get_SmoothStreamingCache
- Microsoft.Web.Media.SmoothStreaming.ClipInformation.set_SmoothStreamingCache
- Microsoft.Web.Media.SmoothStreaming.ClipInformation.SmoothStreamingCache
dev_langs:
- CSharp
- JScript
- VB
- c++
api_location:
- Microsoft.Web.Media.SmoothStreaming.dll
api_name:
- Microsoft.Web.Media.SmoothStreaming.ClipInformation.get_SmoothStreamingCache
- Microsoft.Web.Media.SmoothStreaming.ClipInformation.SmoothStreamingCache
- Microsoft.Web.Media.SmoothStreaming.ClipInformation.set_SmoothStreamingCache
api_type:
- Managed
topic_type:
- apiref
- kbSyntax
product_family_name: VS
ROBOTS: INDEX,FOLLOW
---

# SmoothStreamingCache Property

Gets or sets the Smooth Streaming cache.

**Namespace:**  [Microsoft.Web.Media.SmoothStreaming](microsoft-web-media-smoothstreaming-namespace_1.md)  
**Assembly:**  Microsoft.Web.Media.SmoothStreaming (in Microsoft.Web.Media.SmoothStreaming.dll)

## Syntax

``` vb
'Declaration
PublicPropertySmoothStreamingCacheAsISmoothStreamingCache
'Usage
DiminstanceAsClipInformationDimvalueAsISmoothStreamingCachevalue = instance.SmoothStreamingCache
```

``` csharp
publicISmoothStreamingCacheSmoothStreamingCache { get; privateset; }
```

``` c++
public:
propertyISmoothStreamingCache^ SmoothStreamingCache {
    ISmoothStreamingCache^ get ();
    private: voidset (ISmoothStreamingCache^ value);
}
```

``` jscript
function getSmoothStreamingCache () : ISmoothStreamingCacheprivatefunction setSmoothStreamingCache (value : ISmoothStreamingCache)
```

#### Property Value

Type: [Microsoft.Web.Media.SmoothStreaming. . :: . .ISmoothStreamingCache](ismoothstreamingcache-interface-microsoft-web-media-smoothstreaming_1.md)  
An [ISmoothStreamingCache](ismoothstreamingcache-interface-microsoft-web-media-smoothstreaming_1.md) object.  

## Remarks

Allows the caller to specify a separate cache to use when playing this clip. This can enable offline ad scenarios. Note that setting this property implicitly sets [UseSmoothStreamingCache](clipinformation-usesmoothstreamingcache-property-microsoft-web-media-smoothstreaming_1.md) to true.

## Version Information

#### Silverlight

Supported in: 4  

## Permissions

  - Full trust for the immediate caller. This member cannot be used by partially trusted code. For more information, see [Using Libraries from Partially Trusted Code](https://msdn.microsoft.com/en-us/library/8skskf63\(v=vs.90\)).

## See Also

#### Reference

[ClipInformation Class](clipinformation-class-microsoft-web-media-smoothstreaming_1.md)

[Microsoft.Web.Media.SmoothStreaming Namespace](microsoft-web-media-smoothstreaming-namespace_1.md)
