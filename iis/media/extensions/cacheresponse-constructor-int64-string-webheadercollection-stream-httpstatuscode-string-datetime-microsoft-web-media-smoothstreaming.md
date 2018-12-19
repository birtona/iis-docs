﻿---
title: CacheResponse Constructor (Int64, String, WebHeaderCollection, Stream, HttpStatusCode, String, DateTime) (Microsoft.Web.Media.SmoothStreaming)
TOCTitle: CacheResponse Constructor (Int64, String, WebHeaderCollection, Stream, HttpStatusCode, String, DateTime)
ms:assetid: M:Microsoft.Web.Media.SmoothStreaming.CacheResponse.#ctor(System.Int64,System.String,System.Net.WebHeaderCollection,System.IO.Stream,System.Net.HttpStatusCode,System.String,System.DateTime)
ms:mtpsurl: https://msdn.microsoft.com/en-us/library/microsoft.web.media.smoothstreaming.cacheresponse.cacheresponse(v=VS.90)
ms:contentKeyID: 31469223
ms.date: 05/02/2012
mtps_version: v=VS.90
dev_langs:
- vb
- csharp
- c++
- jscript
api_location:
- Microsoft.Web.Media.SmoothStreaming.dll
api_name:
- Microsoft.Web.Media.SmoothStreaming.CacheResponse..ctor
api_type:
- Managed
topic_type:
- apiref
- kbSyntax
product_family_name: VS
ROBOTS: INDEX,FOLLOW
---

# CacheResponse Constructor (Int64, String, WebHeaderCollection, Stream, HttpStatusCode, String, DateTime)

Initializes a new instance of the [CacheResponse](cacheresponse-class-microsoft-web-media-smoothstreaming_1.md) class from the parameters.

**Namespace:**  [Microsoft.Web.Media.SmoothStreaming](microsoft-web-media-smoothstreaming-namespace_1.md)  
**Assembly:**  Microsoft.Web.Media.SmoothStreaming (in Microsoft.Web.Media.SmoothStreaming.dll)

## Syntax

``` vb
'Declaration
PublicSubNew ( _
    contentLengthAsLong, _
    contentTypeAsString, _
    headersAsWebHeaderCollection, _
    responseAsStream, _
    statusCodeAsHttpStatusCode, _
    statusDescriptionAsString, _
    downloadTimeAsDateTime _
)
'Usage
DimcontentLengthAsLongDimcontentTypeAsStringDimheadersAsWebHeaderCollectionDimresponseAsStreamDimstatusCodeAsHttpStatusCodeDimstatusDescriptionAsStringDimdownloadTimeAsDateTimeDiminstanceAs NewCacheResponse(contentLength, _
    contentType, headers, response, statusCode, _
    statusDescription, downloadTime)
```

``` csharp
publicCacheResponse(
    longcontentLength,
    stringcontentType,
    WebHeaderCollectionheaders,
    Streamresponse,
    HttpStatusCodestatusCode,
    stringstatusDescription,
    DateTimedownloadTime
)
```

``` c++
public:
CacheResponse(
    long longcontentLength, 
    String^ contentType, 
    WebHeaderCollection^ headers, 
    Stream^ response, 
    HttpStatusCodestatusCode, 
    String^ statusDescription, 
    DateTimedownloadTime
)
```

``` jscript
publicfunctionCacheResponse(
    contentLength : long, 
    contentType : String, 
    headers : WebHeaderCollection, 
    response : Stream, 
    statusCode : HttpStatusCode, 
    statusDescription : String, 
    downloadTime : DateTime
)
```

#### Parameters

  - contentLength  
    Type: [System. . :: . .Int64](https://msdn.microsoft.com/en-us/library/6yy583ek\(v=vs.90\))  
    A long integer that contains the length of the response in bytes.  

<!-- end list -->

  - contentType  
    Type: [System. . :: . .String](https://msdn.microsoft.com/en-us/library/s1wwdcbf\(v=vs.90\))  
    A string object that identifies the content type.  

<!-- end list -->

  - headers  
    Type: [System.Net. . :: . .WebHeaderCollection](https://msdn.microsoft.com/en-us/library/1beth6ct\(v=vs.90\))  
    A NetWebHeaderCollection.  

<!-- end list -->

  - response  
    Type: [System.IO. . :: . .Stream](https://msdn.microsoft.com/en-us/library/8f86tw9e\(v=vs.90\))  
    A [Stream](https://msdn.microsoft.com/en-us/library/8f86tw9e\(v=vs.90\)) object that contains the response.  

<!-- end list -->

  - statusCode  
    Type: [System.Net. . :: . .HttpStatusCode](https://msdn.microsoft.com/en-us/library/f92ssyy1\(v=vs.90\))  
    An HTTPStatusCode enumeration object.  

<!-- end list -->

  - statusDescription  
    Type: [System. . :: . .String](https://msdn.microsoft.com/en-us/library/s1wwdcbf\(v=vs.90\))  
    A string that contains the status description.  

<!-- end list -->

  - downloadTime  
    Type: [System. . :: . .DateTime](https://msdn.microsoft.com/en-us/library/03ybds8y\(v=vs.90\))  
    A [DateTime](https://msdn.microsoft.com/en-us/library/03ybds8y\(v=vs.90\)) object.  

## Version Information

#### Silverlight

Supported in: 4  

#### Silverlight for Windows Phone

Supported in: Windows Phone OS 7.0  

## Permissions

  - Full trust for the immediate caller. This member cannot be used by partially trusted code. For more information, see [Using Libraries from Partially Trusted Code](https://msdn.microsoft.com/en-us/library/8skskf63\(v=vs.90\)).

## See Also

#### Reference

[CacheResponse Class](cacheresponse-class-microsoft-web-media-smoothstreaming_1.md)

[CacheResponse Overload](cacheresponse-constructor-microsoft-web-media-smoothstreaming_1.md)

[Microsoft.Web.Media.SmoothStreaming Namespace](microsoft-web-media-smoothstreaming-namespace_1.md)
