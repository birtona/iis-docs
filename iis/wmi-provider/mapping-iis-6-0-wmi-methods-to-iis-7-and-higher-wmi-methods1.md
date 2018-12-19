---
title: "Mapping IIS 6.0 WMI Methods to IIS 7 and higher WMI Methods1 | Microsoft Docs"
ms.custom: ""
ms.date: "10/07/2016"
ms.reviewer: ""
ms.suite: ""
ms.tgt_pltfrm: ""
ms.topic: "article"
ms.assetid: de857e8a-fb15-42b0-8806-da635e7c806f
caps.latest.revision: 9
author: "shirhatti"
manager: "wpickett"
---
# Mapping IIS 6.0 WMI Methods to IIS 7 and higher WMI Methods1
The table below shows the IIS 6.0 WMI provider class methods mapped to the [!INCLUDE[iisver](../wmi-provider/includes/iisver-md.md)] WMI provider class methods. Most of the IIS 6.0 WMI class methods do not map to [!INCLUDE[iisver](../wmi-provider/includes/iisver-md.md)] WMI provider class methods because of the significant architectural changes that were implemented in [!INCLUDE[iisver](../wmi-provider/includes/iisver-md.md)] to improve processes and provide additional features. Use this table to help you convert your IIS 6.0 programmatic administration to use [!INCLUDE[iisver](../wmi-provider/includes/iisver-md.md)] WMI provider classes and methods.  
  
 IIS 6.0 WMI provider classes that do not have methods do not appear in this table. For information about how those classes are mapped to [!INCLUDE[iisver](../wmi-provider/includes/iisver-md.md)] WMI classes and schema elements, see [Converting Metabase Properties to Configuration Settings](http://msdn.microsoft.com/library/f483d50d-ed22-4114-a5c2-212ec11526a2).  
  
|IIS 6.0 WMI class|IIS 6.0 method|[!INCLUDE[iisver](../wmi-provider/includes/iisver-md.md)] WMI class or method|  
|-----------------------|--------------------|--------------------------------------------------------------------------------|  
|IIsApplicationPool|IIsApplicationPool.EnumAppsInPool|[ApplicationPoolContainsApplication](../wmi-provider/applicationpoolcontainsapplication-class1.md) class|  
|IIsApplicationPool|IIsApplicationPool.Recycle|[ApplicationPool.Recycle](../wmi-provider/applicationpool-recycle-method2.md) method|  
|IIsApplicationPool|IIsApplicationPool.Start<br /><br /> IIsApplicationPool.Stop|[ApplicationPool.Start](../wmi-provider/applicationpool-start-method1.md) method<br /><br /> [ApplicationPool.Stop](../wmi-provider/applicationpool-stop-method1.md) method|  
|IIsCertMapper|IIsCertMapper.CreateMapping|Deprecated|  
|IIsCertMapper|IIsCertMapper.DeleteMapping|Deprecated|  
|IIsCertMapper|IIsCertMapper.GetMapping|Deprecated|  
|IIsCertMapper|IIsCertMapper.SetAcct|Deprecated|  
|IIsCertMapper|IIsCertMapper.SetEnabled|Deprecated|  
|IIsCertMapper|IIsCertMapper.SetName|Deprecated|  
|IIsCertMapper|IIsCertMapper.SetPwd|Deprecated|  
|IIsComputer|IIsComputer.BackupWithPassword|Deprecated|  
|IIsComputer|IIsComputer.DeleteBackup|Deprecated|  
|IIsComputer|IIsComputer.EnumBackup|Deprecated|  
|IIsComputer|IIsComputer.EnumHistory|Deprecated|  
|IIsComputer|IIsComputer.ExportHistory|Deprecated|  
|IIsComputer|IIsComputer.Export|Deprecated|  
|IIsComputer|IIsComputer.Import|Deprecated|  
|IIsComputer|IIsComputer.RestoreHistory|Deprecated|  
|IIsComputer|IIsComputer.RestoreWithPassword|Deprecated|  
|IIsComputer|IIsComputer.SaveData|Deprecated; see the [ConfigurationHistorySection](../wmi-provider/configurationhistorysection-class.md) class for the configuration of related functionality in [!INCLUDE[iisver](../wmi-provider/includes/iisver-md.md)].|  
|IIsFTPServer|IIsFTPServer.Continue|Use IIS 6.0 WMI classes and methods.|  
|IIsFTPServer|IIsFTPServer.Pause|Use IIS 6.0 WMI classes and methods.|  
|IIsFTPServer|IIsFTPServer.Start|Use IIS 6.0 WMI classes and methods.|  
|IIsFTPServer|IIsFTPServer.Stop|Use IIS 6.0 WMI classes and methods.|  
|IIsWebDirectory|IIsWebDirectory.AppCreate|Deprecated; use the [Application.Create](../wmi-provider/application-create-method1.md) method.|  
|IIsWebDirectory|IISWebDirectory.AppCreate2|Deprecated; use the [Application.Create](../wmi-provider/application-create-method1.md) method.|  
|IIsWebDirectory|IIsWebDirectory.AppCreate3|Deprecated; use the [Application.Create](../wmi-provider/application-create-method1.md) method.|  
|IIsWebDirectory|IIsWebDirectory.AppDelete|Deprecated; use the `Delete_` method inherited by the [Application](../wmi-provider/application-class1.md) class.|  
|IIsWebDirectory|IIsWebDirectory.AppDisable|Deprecated|  
|IIsWebDirectory|IIsWebDirectory.AppEnable|Deprecated|  
|IIsWebDirectory|IIsWebDirectory.AppGetStatus|Deprecated; use the [Site.GetState](../wmi-provider/site-getstate-method1.md), [WorkerProcess.GetState](../wmi-provider/workerprocess-getstate-method2.md), or [ApplicationPool.GetState](../wmi-provider/applicationpool-getstate-method2.md) method for similar functionality.|  
|IIsWebDirectory|IISWebDirectory.AppUnload|Deprecated; use the [AppDomain.Unload](../wmi-provider/appdomain-unload-method.md) method.|  
|IIsWebDirectory|IISWebDirectory.AspAppRestart|Deprecated|  
|IIsWebServer|IIsWebServer.Start|Deprecated; use the [ApplicationPool.Start](../wmi-provider/applicationpool-start-method1.md) or [Site.Start](../wmi-provider/site-start-method1.md) method.|  
|IIsWebServer|IIsWebServer.Stop|Deprecated; use the [ApplicationPool.Stop](../wmi-provider/applicationpool-stop-method1.md) or [Site.Stop](../wmi-provider/site-stop-method1.md) method.|  
|IIsWebServer|IIsWebServer.Continue|Deprecated|  
|IIsWebServer|IIsWebServer.Pause|Deprecated|  
|IIsWebService|IIsWebService.AddDependency|Deprecated|  
|IIsWebService|IIsWebService.AddExtension|Deprecated; see the [IsapiCgiRestrictionSection](../wmi-provider/isapicgirestrictionsection-class.md) class for related configuration.|  
|IIsWebService|IIsWebService.CreateNewSite|Deprecated; use the [Site.Create](../wmi-provider/site-create-method1.md) method.|  
|IIsWebService|IIsWebService.DisableExtensionFileRecord|Deprecated|  
|IIsWebService|IIsWebService.DisableExtensionFile|Deprecated|  
|IIsWebService|IIsWebService.DisableWebServiceExtension|Deprecated|  
|IIsWebService|IIsWebService.EnableApplication|Deprecated|  
|IIsWebService|IIsWebService.EnableExtensionFile|Deprecated|  
|IIsWebService|IIsWebService.EnableWebServiceExtension|Deprecated|  
|IIsWebService|IIsWebService.GetCurrentMode|Deprecated|  
|IIsWebService|IIsWebService.ListApplications|Deprecated; list instances of the [Application](../wmi-provider/application-class1.md) class instead.|  
|IIsWebService|IIsWebService.ListExtensionFiles|Deprecated|  
|IIsWebService|IIsWebService.ListWebServiceExtensions|Deprecated|  
|IIsWebService|IIsWebService.QueryGroupIDStatus|Deprecated|  
|IIsWebService|IIsWebService.RemoveApplication|Deprecated; use the `Delete_` method inherited by the [Application](../wmi-provider/application-class1.md) class.|  
|IIsWebService|IIsWebService.RemoveDependency|Deprecated|  
|IIsWebVirtualDir|IIsWebVirtualDir.AppCreate|[Application.Create](../wmi-provider/application-create-method1.md) method; [VirtualDirectory.Create](../wmi-provider/virtualdirectory-create-method1.md) method|  
|IIsWebVirtualDir|IIsWebVirtualDir.AppCreate2|[Application.Create](../wmi-provider/application-create-method1.md) method; [VirtualDirectory.Create](../wmi-provider/virtualdirectory-create-method1.md) method|  
|IIsWebVirtualDir|IIsWebVirtualDir.AppCreate3|[Application.Create](../wmi-provider/application-create-method1.md) method; [VirtualDirectory.Create](../wmi-provider/virtualdirectory-create-method1.md) method|  
|IIsWebVirtualDir|IIsWebVirtualDir.AppDelete|Deprecated; use the `Delete_` method inherited by the [Application](../wmi-provider/application-class1.md) class for applications; use the `Delete_` method inherited by the [VirtualDirectory](../wmi-provider/virtualdirectory-class2.md) class for virtual directories.|  
|IIsWebVirtualDir|IIsWebVirtualDir.AppDisable|Deprecated|  
|IIsWebVirtualDir|IIsWebVirtualDir.AppEnable|Deprecated|  
|IIsWebVirtualDir|IIsWebVirtualDir.AppGetStatus|Deprecated; use the [ApplicationPool.GetState](../wmi-provider/applicationpool-getstate-method2.md) or [Site.GetState](../wmi-provider/site-getstate-method1.md) method.|  
|IIsWebVirtualDir|IIsWebVirtualDir.AppUnload|Deprecated; use the [AppDomain.Unload](../wmi-provider/appdomain-unload-method.md) method.|  
|IIsWebVirtualDir|IIsWebVirtualDir.AspAppRestart|Deprecated; use the [ApplicationPool.Recycle](../wmi-provider/applicationpool-recycle-method2.md) method.|