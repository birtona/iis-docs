---
title: "IHttpContext::GetScriptTranslated Method | Microsoft Docs"
ms.custom: ""
ms.date: "10/07/2016"
ms.reviewer: ""
ms.suite: ""
ms.tgt_pltfrm: ""
ms.topic: "article"
ms.assetid: 80a1063c-b33b-7af1-b445-1a49922cd728
caps.latest.revision: 22
author: "shirhatti"
manager: "wpickett"
---
# IHttpContext::GetScriptTranslated Method
Retrieves the physical path of the current request.  
  
## Syntax  
  
```cpp  
virtual PCWSTR GetScriptTranslated(  
   DWORD* pcchScriptName = NULL  
) = 0;  
```  
  
#### Parameters  
 `pcchScriptName`  
 A pointer to a `DWORD` that receives the length of the returned string.  
  
## Return Value  
 A pointer to a string that contains the translated path for the current script.  
  
## Remarks  
 The `GetScriptTranslated` method is used to retrieve a pointer to a buffer that contains the physical path of the current URL.  
  
> [!NOTE]
>  The server owns the lifetime of this pointer.  
  
## Example  
 The following code example demonstrates how to use the `GetScriptTranslated` method to create an HTTP module that retrieves the physical path of the current script. The example returns that information to a Web client and then exits.  
  
<!-- TODO: review snippet reference  [!CODE [IHttpContextGetScriptTranslated#1](IHttpContextGetScriptTranslated#1)]  -->  
  
 Your module must export the [RegisterModule](../../../webdevelopment-reference\native-code-api\webdev-native-api-reference/pfn-registermodule-function.md) function. You can export this function by creating a module definition (.def) file for your project, or you can compile the module by using the `/EXPORT:RegisterModule` switch. For more information, see [Walkthrough: Creating a Request-Level HTTP Module By Using Native Code](../../../webdevelopment-reference\native-code-development-overview\native-code-dev-overview/walkthrough-creating-a-request-level-http-module-by-using-native-code.md).  
  
 You can optionally compile the code by using the `__stdcall (/Gz)` calling convention instead of explicitly declaring the calling convention for each function.  
  
## Requirements  
  
|Type|Description|  
|----------|-----------------|  
|Client|-   [!INCLUDE[iis70](../../../wmi-provider/includes/iis70-md.md)] on [!INCLUDE[winvista](../../../wmi-provider/includes/winvista-md.md)]<br />-   [!INCLUDE[iis75](../../../wmi-provider/includes/iis75-md.md)] on [!INCLUDE[win7](../../../wmi-provider/includes/win7-md.md)]<br />-   [!INCLUDE[iis80](../../../wmi-provider/includes/iis80-md.md)] on [!INCLUDE[win8](../../../wmi-provider/includes/win8-md.md)]<br />-   [!INCLUDE[iis100](../../../wmi-provider/includes/iis100-md.md)] on [!INCLUDE[win10](../../../wmi-provider/includes/win10-md.md)]|  
|Server|-   [!INCLUDE[iis70](../../../wmi-provider/includes/iis70-md.md)] on [!INCLUDE[winsrv2008](../../../wmi-provider/includes/winsrv2008-md.md)]<br />-   [!INCLUDE[iis75](../../../wmi-provider/includes/iis75-md.md)] on [!INCLUDE[winsrv2008r2](../../../wmi-provider/includes/winsrv2008r2-md.md)]<br />-   [!INCLUDE[iis80](../../../wmi-provider/includes/iis80-md.md)] on [!INCLUDE[winsrv2012](../../../wmi-provider/includes/winsrv2012-md.md)]<br />-   [!INCLUDE[iis85](../../../wmi-provider/includes/iis85-md.md)] on [!INCLUDE[winsrv2012r2](../../../wmi-provider/includes/winsrv2012r2-md.md)]<br />-   [!INCLUDE[iis100](../../../wmi-provider/includes/iis100-md.md)] on [!INCLUDE[winsrv2016](../../../wmi-provider/includes/winsrv2016-md.md)]|  
|Product|-   [!INCLUDE[iis70](../../../wmi-provider/includes/iis70-md.md)], [!INCLUDE[iis75](../../../wmi-provider/includes/iis75-md.md)], [!INCLUDE[iis80](../../../wmi-provider/includes/iis80-md.md)], [!INCLUDE[iis85](../../../wmi-provider/includes/iis85-md.md)], [!INCLUDE[iis100](../../../wmi-provider/includes/iis100-md.md)]<br />-   [!INCLUDE[iisexp75](../../../webdevelopment-reference\native-code-api\webdev-native-api-reference/includes/iisexp75-md.md)], [!INCLUDE[iisexp80](../../../webdevelopment-reference\native-code-api\webdev-native-api-reference/includes/iisexp80-md.md)], [!INCLUDE[iisexp100](../../../webdevelopment-reference\native-code-api\webdev-native-api-reference/includes/iisexp100-md.md)]|  
|Header|Httpserv.h|  
  
## See Also  
 [IHttpContext Interface](../../../webdevelopment-reference\native-code-api\webdev-native-api-reference/ihttpcontext-interface.md)   
 [IHttpContext::GetScriptMap Method](../../../webdevelopment-reference\native-code-api\webdev-native-api-reference/ihttpcontext-getscriptmap-method.md)   
 [IHttpContext::GetScriptName Method](../../../webdevelopment-reference\native-code-api\webdev-native-api-reference/ihttpcontext-getscriptname-method.md)   
 [IHttpContext::MapPath Method](../../../webdevelopment-reference\native-code-api\webdev-native-api-reference/ihttpcontext-mappath-method.md)