# Azure VM Extension List - 01/17/2017

Reference this site which has a running script updating the list:
http://armtg.azurewebsites.net/extension_list.html

```
//az command
juluk@justins-mbp-2:~$ az vm extension image list

[
  {
    "name": "AcronisBackup",
    "publisher": "Acronis.Backup",
    "version": "1.0.33"
  },
  {
    "name": "AgentWinExt",
    "publisher": "bmc.ctm",
    "version": "9.0.0.1"
  },
  {
    "name": "AcronisBackupLinux",
    "publisher": "Acronis.Backup",
    "version": "1.0.33"
  },
  {
    "name": "AlertLogicLM",
    "publisher": "AlertLogic.Extension",
    "version": "1.3.0.0"
  },
  {
    "name": "AlertLogicLM",
    "publisher": "AlertLogic.Extension",
    "version": "1.4.0.0"
  },
  {
    "name": "AlertLogicLM",
    "publisher": "AlertLogic.Extension",
    "version": "1.9.0.0"
  },
  {
    "name": "AlertLogicLM",
    "publisher": "AlertLogic.Extension",
    "version": "1.9.1.0"
  },
  {
    "name": "CentosChefClient",
    "publisher": "Chef.Bootstrap.WindowsAzure",
    "version": "11.12.4.2"
  },
  {
    "name": "CentosChefClient",
    "publisher": "Chef.Bootstrap.WindowsAzure",
    "version": "11.14.6.1"
  },
  {
    "name": "CloudLinkSecureVMLinuxAgent",
    "publisher": "CloudLinkEMC.SecureVM",
    "version": "4.0.21165.21808"
  },
  {
    "name": "CloudLinkSecureVMLinuxAgent",
    "publisher": "CloudLinkEMC.SecureVM",
    "version": "5.0.22503.21808"
  },
  {
    "name": "CloudLinkSecureVMLinuxAgent",
    "publisher": "CloudLinkEMC.SecureVM",
    "version": "5.5.23389.23430"
  },
  {
    "name": "CloudLinkSecureVMLinuxAgent",
    "publisher": "CloudLinkEMC.SecureVM",
    "version": "6.0.62.0"
  },
  {
    "name": "ConferForAzure",
    "publisher": "Confer",
    "version": "1.0.5.38"
  },
  {
    "name": "ConferForAzure",
    "publisher": "Confer",
    "version": "1.0.5.39"
  },
  {
    "name": "ConferForAzure",
    "publisher": "Confer",
    "version": "1.0.5.40"
  },
  {
    "name": "ChefClient",
    "publisher": "Chef.Bootstrap.WindowsAzure",
    "version": "11.10.4"
  },
  {
    "name": "ChefClient",
    "publisher": "Chef.Bootstrap.WindowsAzure",
    "version": "11.12.0.0"
  },
  {
    "name": "ChefClient",
    "publisher": "Chef.Bootstrap.WindowsAzure",
    "version": "11.18.6.2"
  },
  {
    "name": "ChefClient",
    "publisher": "Chef.Bootstrap.WindowsAzure",
    "version": "1207.12.3.0"
  },
  {
    "name": "ChefClient",
    "publisher": "Chef.Bootstrap.WindowsAzure",
    "version": "1210.12.106.1000"
  },
  {
    "name": "ChefClient",
    "publisher": "Chef.Bootstrap.WindowsAzure",
    "version": "1210.12.107.1000"
  },
  {
    "name": "ChefClient",
    "publisher": "Chef.Bootstrap.WindowsAzure",
    "version": "1210.12.107.1001"
  },
  {
    "name": "BmcCtmAgentLinux",
    "publisher": "ctm.bmc.com",
    "version": "9.0.0.1"
  },
  {
    "name": "DatadogLinuxAgent",
    "publisher": "Datadog.Agent",
    "version": "0.4"
  },
  {
    "name": "CloudLinkSecureVMWindowsAgent",
    "publisher": "CloudLinkEMC.SecureVM",
    "version": "4.0.15.21835"
  },
  {
    "name": "CloudLinkSecureVMWindowsAgent",
    "publisher": "CloudLinkEMC.SecureVM",
    "version": "5.0.3.22576"
  },
  {
    "name": "CloudLinkSecureVMWindowsAgent",
    "publisher": "CloudLinkEMC.SecureVM",
    "version": "5.5.6.23416"
  },
  {
    "name": "CloudLinkSecureVMWindowsAgent",
    "publisher": "CloudLinkEMC.SecureVM",
    "version": "6.0.59.0"
  },
  {
    "name": "LinuxChefClient",
    "publisher": "Chef.Bootstrap.WindowsAzure",
    "version": "11.18.6.2"
  },
  {
    "name": "LinuxChefClient",
    "publisher": "Chef.Bootstrap.WindowsAzure",
    "version": "1207.12.3.0"
  },
  {
    "name": "LinuxChefClient",
    "publisher": "Chef.Bootstrap.WindowsAzure",
    "version": "1210.12.104.1000"
  },
  {
    "name": "LinuxChefClient",
    "publisher": "Chef.Bootstrap.WindowsAzure",
    "version": "1210.12.106.1000"
  },
  {
    "name": "dtmanaged",
    "publisher": "dynatrace.ruxit",
    "version": "1.4.0.7"
  },
  {
    "name": "DatadogWindowsAgent",
    "publisher": "Datadog.Agent",
    "version": "0.4.1"
  },
  {
    "name": "DatadogWindowsAgent",
    "publisher": "Datadog.Agent",
    "version": "0.5"
  },
  {
    "name": "FileSecurity",
    "publisher": "ESET",
    "version": "6.3.12010.1001"
  },
  {
    "name": "FileSecurity",
    "publisher": "ESET",
    "version": "6.4.12002.1000"
  },
  {
    "name": "FileSecurity",
    "publisher": "ESET",
    "version": "6.4.12004.1002"
  },
  {
    "name": "oneAgentLinux",
    "publisher": "dynatrace.ruxit",
    "version": "1.99.0.1"
  },
  {
    "name": "ProtectVClientLinuxExtension",
    "publisher": "Gemalto.SafeNet.ProtectV",
    "version": "3.0.0.205"
  },
  {
    "name": "ProtectVClientWindowsExtension",
    "publisher": "Gemalto.SafeNet.ProtectV",
    "version": "3.0.0.318"
  },
  {
    "name": "oneAgentWindows",
    "publisher": "dynatrace.ruxit",
    "version": "1.99.0.1"
  },
  {
    "name": "DotnetAgent",
    "publisher": "HPE.Security.ApplicationDefender",
    "version": "1.0.0.2"
  },
  {
    "name": "DotnetAgent",
    "publisher": "HPE.Security.ApplicationDefender",
    "version": "1.0.0.4"
  },
  {
    "name": "DotnetAgent",
    "publisher": "HPE.Security.ApplicationDefender",
    "version": "1.6.13.0"
  },
  {
    "name": "DotnetAgent",
    "publisher": "HPE.Security.ApplicationDefender",
    "version": "1.6.14.0"
  },
  {
    "name": "DotnetAgent",
    "publisher": "HPE.Security.ApplicationDefender",
    "version": "1.6.9.0"
  },
  {
    "name": "ruxitAgentLinux",
    "publisher": "dynatrace.ruxit",
    "version": "1.93.104.0"
  },
  {
    "name": "VMSnapshot",
    "publisher": "Microsoft.Azure.RecoveryServices",
    "version": "1.0.16.0"
  },
  {
    "name": "VMSnapshot",
    "publisher": "Microsoft.Azure.RecoveryServices",
    "version": "1.0.17.0"
  },
  {
    "name": "MyBackupTest",
    "publisher": "Microsoft.Azure.Backup.Test",
    "version": "1.0.78.0"
  },
  {
    "name": "MyBackupTest",
    "publisher": "Microsoft.Azure.Backup.Test",
    "version": "1.0.79.0"
  },
  {
    "name": "MyBackupTest",
    "publisher": "Microsoft.Azure.Backup.Test",
    "version": "1.0.80.0"
  },
  {
    "name": "MyBackupTest",
    "publisher": "Microsoft.Azure.Backup.Test",
    "version": "1.0.81.0"
  },
  {
    "name": "MyBackupTest",
    "publisher": "Microsoft.Azure.Backup.Test",
    "version": "1.0.82.0"
  },
  {
    "name": "IaaSDiagnostics",
    "publisher": "Microsoft.Azure.Diagnostics",
    "version": "1.1.0.0"
  },
  {
    "name": "IaaSDiagnostics",
    "publisher": "Microsoft.Azure.Diagnostics",
    "version": "1.2.0.0"
  },
  {
    "name": "IaaSDiagnostics",
    "publisher": "Microsoft.Azure.Diagnostics",
    "version": "1.3.1.6"
  },
  {
    "name": "IaaSDiagnostics",
    "publisher": "Microsoft.Azure.Diagnostics",
    "version": "1.4.2.1"
  },
  {
    "name": "IaaSDiagnostics",
    "publisher": "Microsoft.Azure.Diagnostics",
    "version": "1.5.9.0"
  },
  {
    "name": "IaaSDiagnostics",
    "publisher": "Microsoft.Azure.Diagnostics",
    "version": "1.6.2.0"
  },
  {
    "name": "IaaSDiagnostics",
    "publisher": "Microsoft.Azure.Diagnostics",
    "version": "1.6.3.0"
  },
  {
    "name": "IaaSDiagnostics",
    "publisher": "Microsoft.Azure.Diagnostics",
    "version": "1.6.4.0"
  },
  {
    "name": "IaaSDiagnostics",
    "publisher": "Microsoft.Azure.Diagnostics",
    "version": "1.7.1.0"
  },
  {
    "name": "IaaSDiagnostics",
    "publisher": "Microsoft.Azure.Diagnostics",
    "version": "1.7.3.0"
  },
  {
    "name": "IaaSDiagnostics",
    "publisher": "Microsoft.Azure.Diagnostics",
    "version": "1.7.4.0"
  },
  {
    "name": "ADETest",
    "publisher": "Microsoft.Azure.Security",
    "version": "1.4.0.2"
  },
  {
    "name": "ADETest",
    "publisher": "Microsoft.Azure.Security",
    "version": "1.4.0.3"
  },
  {
    "name": "ADETest",
    "publisher": "Microsoft.Azure.Security",
    "version": "1.4.0.4"
  },
  {
    "name": "McAfeeEndpointSecurity",
    "publisher": "McAfee.EndpointSecurity",
    "version": "6.0"
  },
  {
    "name": "CustomScript",
    "publisher": "Microsoft.Azure.Extensions",
    "version": "2.0.0"
  },
  {
    "name": "CustomScript",
    "publisher": "Microsoft.Azure.Extensions",
    "version": "2.0.1"
  },
  {
    "name": "CustomScript",
    "publisher": "Microsoft.Azure.Extensions",
    "version": "2.0.2"
  },
  {
    "name": "MicrosoftMonitoringAgent",
    "publisher": "Microsoft.EnterpriseCloud.Monitoring",
    "version": "1.0.10900.0"
  },
  {
    "name": "MicrosoftMonitoringAgent",
    "publisher": "Microsoft.EnterpriseCloud.Monitoring",
    "version": "1.0.10900.4"
  },
  {
    "name": "MicrosoftMonitoringAgent",
    "publisher": "Microsoft.EnterpriseCloud.Monitoring",
    "version": "1.0.11030.0"
  },
  {
    "name": "MicrosoftMonitoringAgent",
    "publisher": "Microsoft.EnterpriseCloud.Monitoring",
    "version": "1.0.11030.1"
  },
  {
    "name": "ruxitAgentWindows",
    "publisher": "dynatrace.ruxit",
    "version": "1.95.100.1"
  },
  {
    "name": "LinuxNodeAgent",
    "publisher": "Microsoft.HpcPack",
    "version": "1.5.1.0"
  },
  {
    "name": "LinuxNodeAgent",
    "publisher": "Microsoft.HpcPack",
    "version": "1.6.18.3"
  },
  {
    "name": "LinuxNodeAgent",
    "publisher": "Microsoft.HpcPack",
    "version": "1.7.11.2"
  },
  {
    "name": "LinuxNodeAgent",
    "publisher": "Microsoft.HpcPack",
    "version": "2.1.5.0"
  },
  {
    "name": "MicrosoftMonitoringAgent",
    "publisher": "Microsoft.EnterpriseCloud.Monitoring.Test",
    "version": "1.0.11030.0"
  },
  {
    "name": "IaaSAntimalware",
    "publisher": "Microsoft.Azure.Security.Test",
    "version": "1.5.2.0"
  },
  {
    "name": "SiteRecoveryTest",
    "publisher": "Microsoft.Azure.SiteRecovery.Test",
    "version": "1.0.0.8"
  },
  {
    "name": "SiteRecoveryTest",
    "publisher": "Microsoft.Azure.SiteRecovery.Test",
    "version": "1.1.0.0"
  },
  {
    "name": "SiteRecoveryTest",
    "publisher": "Microsoft.Azure.SiteRecovery.Test",
    "version": "1.1.0.1"
  },
  {
    "name": "SiteRecoveryTest",
    "publisher": "Microsoft.Azure.SiteRecovery.Test",
    "version": "1.1.0.2"
  },
  {
    "name": "SiteRecoveryTest",
    "publisher": "Microsoft.Azure.SiteRecovery.Test",
    "version": "1.1.0.3"
  },
  {
    "name": "SiteRecoveryTest",
    "publisher": "Microsoft.Azure.SiteRecovery.Test",
    "version": "1.1.0.4"
  },
  {
    "name": "SiteRecoveryTest",
    "publisher": "Microsoft.Azure.SiteRecovery.Test",
    "version": "1.1.0.5"
  },
  {
    "name": "SiteRecoveryTest",
    "publisher": "Microsoft.Azure.SiteRecovery.Test",
    "version": "1.1.0.6"
  },
  {
    "name": "SiteRecoveryTest",
    "publisher": "Microsoft.Azure.SiteRecovery.Test",
    "version": "1.1.0.7"
  },
  {
    "name": "IaaS47C6E03DTest",
    "publisher": "Microsoft.Azure.Applications",
    "version": "1.0.0.3"
  },
  {
    "name": "DSC",
    "publisher": "Microsoft.Powershell",
    "version": "2.10.0.0"
  },
  {
    "name": "DSC",
    "publisher": "Microsoft.Powershell",
    "version": "2.13.2.0"
  },
  {
    "name": "DSC",
    "publisher": "Microsoft.Powershell",
    "version": "2.14.0.0"
  },
  {
    "name": "DSC",
    "publisher": "Microsoft.Powershell",
    "version": "2.15.0.0"
  },
  {
    "name": "DSC",
    "publisher": "Microsoft.Powershell",
    "version": "2.16.0.0"
  },
  {
    "name": "DSC",
    "publisher": "Microsoft.Powershell",
    "version": "2.17.0.0"
  },
  {
    "name": "DSC",
    "publisher": "Microsoft.Powershell",
    "version": "2.18.0.0"
  },
  {
    "name": "DSC",
    "publisher": "Microsoft.Powershell",
    "version": "2.19.0.0"
  },
  {
    "name": "DSC",
    "publisher": "Microsoft.Powershell",
    "version": "2.20.0.0"
  },
  {
    "name": "DSC",
    "publisher": "Microsoft.Powershell",
    "version": "2.21.0.0"
  },
  {
    "name": "DSC",
    "publisher": "Microsoft.Powershell",
    "version": "2.4.0.0"
  },
  {
    "name": "DSC",
    "publisher": "Microsoft.Powershell",
    "version": "2.5.0.0"
  },
  {
    "name": "DSC",
    "publisher": "Microsoft.Powershell",
    "version": "2.6.0.0"
  },
  {
    "name": "DSC",
    "publisher": "Microsoft.Powershell",
    "version": "2.7.0.0"
  },
  {
    "name": "DSC",
    "publisher": "Microsoft.Powershell",
    "version": "2.8.0.0"
  },
  {
    "name": "DSC",
    "publisher": "Microsoft.Powershell",
    "version": "2.9.1.0"
  },
  {
    "name": "SiteRecovery",
    "publisher": "Microsoft.Azure.RecoveryServices.SiteRecovery",
    "version": "0.0.0.0"
  },
  {
    "name": "TestMSILinuxExtension",
    "publisher": "Microsoft.Azure.Test.Identity",
    "version": "1.0.0.0"
  },
  {
    "name": "TestMSILinuxExtension",
    "publisher": "Microsoft.Azure.Test.Identity",
    "version": "1.0.0.1"
  },
  {
    "name": "TestMSILinuxExtension",
    "publisher": "Microsoft.Azure.Test.Identity",
    "version": "1.0.0.2"
  },
  {
    "name": "TestMSILinuxExtension",
    "publisher": "Microsoft.Azure.Test.Identity",
    "version": "1.0.0.3"
  },
  {
    "name": "TestMSILinuxExtension",
    "publisher": "Microsoft.Azure.Test.Identity",
    "version": "1.0.0.4"
  },
  {
    "name": "TestMSILinuxExtension",
    "publisher": "Microsoft.Azure.Test.Identity",
    "version": "1.0.0.5"
  },
  {
    "name": "TestMSILinuxExtension",
    "publisher": "Microsoft.Azure.Test.Identity",
    "version": "1.0.0.6"
  },
  {
    "name": "TestMSILinuxExtension",
    "publisher": "Microsoft.Azure.Test.Identity",
    "version": "1.0.0.7"
  },
  {
    "name": "HpcVmDrivers",
    "publisher": "Microsoft.HpcCompute",
    "version": "1.1.0.0"
  },
  {
    "name": "HpcVmDrivers",
    "publisher": "Microsoft.HpcCompute",
    "version": "1.1.1.1"
  },
  {
    "name": "HpcVmDrivers",
    "publisher": "Microsoft.HpcCompute",
    "version": "1.1.2.0"
  },
  {
    "name": "HpcVmDrivers",
    "publisher": "Microsoft.HpcCompute",
    "version": "1.1.3.0"
  },
  {
    "name": "BGInfo",
    "publisher": "Microsoft.Compute",
    "version": "2.1"
  },
  {
    "name": "SqlIaaSAgent",
    "publisher": "Microsoft.SqlServer.Management",
    "version": "1.2.10.0"
  },
  {
    "name": "SqlIaaSAgent",
    "publisher": "Microsoft.SqlServer.Management",
    "version": "1.2.11.0"
  },
  {
    "name": "SqlIaaSAgent",
    "publisher": "Microsoft.SqlServer.Management",
    "version": "1.2.12.0"
  },
  {
    "name": "SqlIaaSAgent",
    "publisher": "Microsoft.SqlServer.Management",
    "version": "1.2.13.0"
  },
  {
    "name": "SqlIaaSAgent",
    "publisher": "Microsoft.SqlServer.Management",
    "version": "1.2.14.0"
  },
  {
    "name": "SqlIaaSAgent",
    "publisher": "Microsoft.SqlServer.Management",
    "version": "1.2.15.0"
  },
  {
    "name": "SqlIaaSAgent",
    "publisher": "Microsoft.SqlServer.Management",
    "version": "1.2.9.0"
  },
  {
    "name": "DSC",
    "publisher": "Microsoft.Powershell.Install",
    "version": "1.0.0.0"
  },
  {
    "name": "DSC",
    "publisher": "Microsoft.Powershell.Test",
    "version": "2.20.6.0"
  },
  {
    "name": "DSC",
    "publisher": "Microsoft.Powershell.Nano",
    "version": "2.21.4.0"
  },
  {
    "name": "DSC",
    "publisher": "Microsoft.Powershell.Nano",
    "version": "2.21.5.0"
  },
  {
    "name": "AzureDiskEncryptionForLinux",
    "publisher": "Microsoft.OSTCExtensions",
    "version": "0.1.0.999105"
  },
  {
    "name": "VSETWTraceListenerService",
    "publisher": "Microsoft.VisualStudio.Azure.ETWTraceListenerService",
    "version": "0.1.0.0"
  },
  {
    "name": "VSETWTraceListenerService",
    "publisher": "Microsoft.VisualStudio.Azure.ETWTraceListenerService",
    "version": "0.1.0.1"
  },
  {
    "name": "VSETWTraceListenerService",
    "publisher": "Microsoft.VisualStudio.Azure.ETWTraceListenerService",
    "version": "0.2.0.0"
  },
  {
    "name": "VSETWTraceListenerService",
    "publisher": "Microsoft.VisualStudio.Azure.ETWTraceListenerService",
    "version": "0.3.0.0"
  },
  {
    "name": "VSETWTraceListenerService",
    "publisher": "Microsoft.VisualStudio.Azure.ETWTraceListenerService",
    "version": "0.4.0.0"
  },
  {
    "name": "VSETWTraceListenerService",
    "publisher": "Microsoft.VisualStudio.Azure.ETWTraceListenerService",
    "version": "0.5.0.0"
  },
  {
    "name": "VSETWTraceListenerService",
    "publisher": "Microsoft.VisualStudio.Azure.ETWTraceListenerService",
    "version": "0.6.0.0"
  },
  {
    "name": "VSETWTraceListenerService",
    "publisher": "Microsoft.VisualStudio.Azure.ETWTraceListenerService",
    "version": "0.7.0.0"
  },
  {
    "name": "VSETWTraceListenerService",
    "publisher": "Microsoft.VisualStudio.Azure.ETWTraceListenerService",
    "version": "0.7.1.0"
  },
  {
    "name": "VSETWTraceListenerService",
    "publisher": "Microsoft.VisualStudio.Azure.ETWTraceListenerService",
    "version": "0.7.2.0"
  },
  {
    "name": "VSETWTraceListenerService",
    "publisher": "Microsoft.VisualStudio.Azure.ETWTraceListenerService",
    "version": "0.7.3.0"
  },
  {
    "name": "VSETWTraceListenerService",
    "publisher": "Microsoft.VisualStudio.Azure.ETWTraceListenerService",
    "version": "0.8.0.0"
  },
  {
    "name": "VSETWTraceListenerService",
    "publisher": "Microsoft.VisualStudio.Azure.ETWTraceListenerService",
    "version": "1.0.0.0"
  },
  {
    "name": "MSEnterpriseApplication",
    "publisher": "Microsoft.SystemCenter",
    "version": "1.0.5.0"
  },
  {
    "name": "ADETestWire",
    "publisher": "Microsoft.Azure.Security",
    "version": "1.0.0.0"
  },
  {
    "name": "VSRemoteDebugger",
    "publisher": "Microsoft.VisualStudio.Azure.RemoteDebug",
    "version": "1.1.1.0"
  },
  {
    "name": "VSRemoteDebugger",
    "publisher": "Microsoft.VisualStudio.Azure.RemoteDebug",
    "version": "1.1.2.0"
  },
  {
    "name": "VSRemoteDebugger",
    "publisher": "Microsoft.VisualStudio.Azure.RemoteDebug",
    "version": "1.1.3.0"
  },
  {
    "name": "AzureDiagnosticsLinuxExtIaaS7.Test",
    "publisher": "Microsoft.OSTCExtensions.Test",
    "version": "1.0.0.0"
  },
  {
    "name": "DockerExtension",
    "publisher": "Microsoft.Azure.Extensions",
    "version": "1.0.1512030601"
  },
  {
    "name": "DockerExtension",
    "publisher": "Microsoft.Azure.Extensions",
    "version": "1.1.1512090359"
  },
  {
    "name": "DockerExtension",
    "publisher": "Microsoft.Azure.Extensions",
    "version": "1.1.1512180541"
  },
  {
    "name": "DockerExtension",
    "publisher": "Microsoft.Azure.Extensions",
    "version": "1.1.1601070410"
  },
  {
    "name": "DockerExtension",
    "publisher": "Microsoft.Azure.Extensions",
    "version": "1.1.1601140348"
  },
  {
    "name": "DockerExtension",
    "publisher": "Microsoft.Azure.Extensions",
    "version": "1.1.1602270800"
  },
  {
    "name": "DockerExtension",
    "publisher": "Microsoft.Azure.Extensions",
    "version": "1.1.1604142300"
  },
  {
    "name": "DockerExtension",
    "publisher": "Microsoft.Azure.Extensions",
    "version": "1.1.1606092330"
  },
  {
    "name": "DockerExtension",
    "publisher": "Microsoft.Azure.Extensions",
    "version": "1.2.0"
  },
  {
    "name": "LinuxNodeAgent2016",
    "publisher": "Microsoft.HpcPack",
    "version": "2.1.6.0"
  },
  {
    "name": "AzureCATExtensionHandler",
    "publisher": "Microsoft.AzureCAT.AzureEnhancedMonitoring",
    "version": "2.2.0.48"
  },
  {
    "name": "AzureCATExtensionHandler",
    "publisher": "Microsoft.AzureCAT.AzureEnhancedMonitoring",
    "version": "2.2.0.68"
  },
  {
    "name": "ServiceProfilerAgent",
    "publisher": "Microsoft.VisualStudio.ServiceProfiler",
    "version": "0.1.0.24"
  },
  {
    "name": "ServiceProfilerAgent",
    "publisher": "Microsoft.VisualStudio.ServiceProfiler",
    "version": "0.1.0.25"
  },
  {
    "name": "SiteRecoveryTestLinux",
    "publisher": "Microsoft.Azure.SiteRecovery.Test",
    "version": "0.0.0.0"
  },
  {
    "name": "SiteRecoveryTestLinux",
    "publisher": "Microsoft.Azure.SiteRecovery.Test",
    "version": "1.0.0.0"
  },
  {
    "name": "SiteRecoveryTestLinux",
    "publisher": "Microsoft.Azure.SiteRecovery.Test",
    "version": "1.0.0.1"
  },
  {
    "name": "SiteRecoveryTestLinux",
    "publisher": "Microsoft.Azure.SiteRecovery.Test",
    "version": "1.0.0.2"
  },
  {
    "name": "SiteRecoveryTestLinux",
    "publisher": "Microsoft.Azure.SiteRecovery.Test",
    "version": "1.0.0.3"
  },
  {
    "name": "SiteRecoveryTestLinux",
    "publisher": "Microsoft.Azure.SiteRecovery.Test",
    "version": "1.0.0.4"
  },
  {
    "name": "OmsAgentForLinux",
    "publisher": "Microsoft.EnterpriseCloud.Monitoring",
    "version": "1.0.0.2"
  },
  {
    "name": "OmsAgentForLinux",
    "publisher": "Microsoft.EnterpriseCloud.Monitoring",
    "version": "1.0.0.3"
  },
  {
    "name": "OmsAgentForLinux",
    "publisher": "Microsoft.EnterpriseCloud.Monitoring",
    "version": "1.0.0.4"
  },
  {
    "name": "OmsAgentForLinux",
    "publisher": "Microsoft.EnterpriseCloud.Monitoring",
    "version": "1.0.0.5"
  },
  {
    "name": "OmsAgentForLinux",
    "publisher": "Microsoft.EnterpriseCloud.Monitoring",
    "version": "1.0.217.0"
  },
  {
    "name": "OmsAgentForLinux",
    "publisher": "Microsoft.EnterpriseCloud.Monitoring",
    "version": "1.2.148.0"
  },
  {
    "name": "OmsAgentForLinux",
    "publisher": "Microsoft.EnterpriseCloud.Monitoring",
    "version": "1.2.25.0"
  },
  {
    "name": "OmsAgentForLinux",
    "publisher": "Microsoft.EnterpriseCloud.Monitoring",
    "version": "1.2.75.0"
  },
  {
    "name": "CustomScriptExtension",
    "publisher": "Microsoft.Compute",
    "version": "1.0.1"
  },
  {
    "name": "CustomScriptExtension",
    "publisher": "Microsoft.Compute",
    "version": "1.0.3"
  },
  {
    "name": "CustomScriptExtension",
    "publisher": "Microsoft.Compute",
    "version": "1.1"
  },
  {
    "name": "CustomScriptExtension",
    "publisher": "Microsoft.Compute",
    "version": "1.2"
  },
  {
    "name": "CustomScriptExtension",
    "publisher": "Microsoft.Compute",
    "version": "1.3"
  },
  {
    "name": "CustomScriptExtension",
    "publisher": "Microsoft.Compute",
    "version": "1.4"
  },
  {
    "name": "CustomScriptExtension",
    "publisher": "Microsoft.Compute",
    "version": "1.7"
  },
  {
    "name": "CustomScriptExtension",
    "publisher": "Microsoft.Compute",
    "version": "1.8"
  },
  {
    "name": "SiteRecoveryLinux",
    "publisher": "Microsoft.Azure.RecoveryServices.SiteRecovery",
    "version": "0.0.0.1"
  },
  {
    "name": "AzureRemoteAppTestAgentV2",
    "publisher": "Microsoft.Windows.AzureRemoteApp.Test",
    "version": "1.0"
  },
  {
    "name": "TeamServicesAgent",
    "publisher": "Microsoft.VisualStudio.Services",
    "version": "1.0.0.0"
  },
  {
    "name": "TeamServicesAgent",
    "publisher": "Microsoft.VisualStudio.Services",
    "version": "1.3.0.0"
  },
  {
    "name": "TeamServicesAgent",
    "publisher": "Microsoft.VisualStudio.Services",
    "version": "1.4.0.0"
  },
  {
    "name": "TeamServicesAgent",
    "publisher": "Microsoft.VisualStudio.Services",
    "version": "1.5.0.0"
  },
  {
    "name": "AzureEnhancedMonitorForLinux",
    "publisher": "Microsoft.OSTCExtensions",
    "version": "2.0.0.2"
  },
  {
    "name": "AzureEnhancedMonitorForLinux",
    "publisher": "Microsoft.OSTCExtensions",
    "version": "3.0.0.1"
  },
  {
    "name": "AzureEnhancedMonitorForLinux",
    "publisher": "Microsoft.OSTCExtensions",
    "version": "3.0.0.5"
  },
  {
    "name": "AzureEnhancedMonitorForLinux",
    "publisher": "Microsoft.OSTCExtensions",
    "version": "3.0.0.97"
  },
  {
    "name": "AzureEnhancedMonitorForLinux",
    "publisher": "Microsoft.OSTCExtensions",
    "version": "3.0.0.98"
  },
  {
    "name": "AzureEnhancedMonitorForLinux",
    "publisher": "Microsoft.OSTCExtensions",
    "version": "3.0.0.99"
  },
  {
    "name": "AzureEnhancedMonitorForLinux",
    "publisher": "Microsoft.OSTCExtensions",
    "version": "3.0.1.0"
  },
  {
    "name": "AzureDiskEncryption",
    "publisher": "Microsoft.Azure.Security",
    "version": "1.0.0.0"
  },
  {
    "name": "AzureDiskEncryption",
    "publisher": "Microsoft.Azure.Security",
    "version": "1.1.0.0"
  },
  {
    "name": "AzureDiskEncryption",
    "publisher": "Microsoft.Azure.Security",
    "version": "1.1.0.1"
  },
  {
    "name": "AzureLogCollector",
    "publisher": "Microsoft.WindowsAzure.Compute",
    "version": "1.0.0.7"
  },
  {
    "name": "AzureLogCollector",
    "publisher": "Microsoft.WindowsAzure.Compute",
    "version": "1.0.0.8"
  },
  {
    "name": "AzureLogCollector",
    "publisher": "Microsoft.WindowsAzure.Compute",
    "version": "1.0.0.9"
  },
  {
    "name": "LinuxAsm",
    "publisher": "Microsoft.Azure.Extensions",
    "version": "2.0.1"
  },
  {
    "name": "LinuxAsm",
    "publisher": "Microsoft.Azure.Extensions",
    "version": "2.1.0"
  },
  {
    "name": "LinuxAsm",
    "publisher": "Microsoft.Azure.Extensions",
    "version": "2.1.1"
  },
  {
    "name": "LinuxAsm",
    "publisher": "Microsoft.Azure.Extensions",
    "version": "2.2.0"
  },
  {
    "name": "LinuxAsm",
    "publisher": "Microsoft.Azure.Extensions",
    "version": "2.2.1"
  },
  {
    "name": "JsonADDomainExtension",
    "publisher": "Microsoft.Compute",
    "version": "1.0"
  },
  {
    "name": "JsonADDomainExtension",
    "publisher": "Microsoft.Compute",
    "version": "1.3"
  },
  {
    "name": "VMSnapshotLinux",
    "publisher": "Microsoft.Azure.RecoveryServices",
    "version": "1.0.9102.0"
  },
  {
    "name": "VMSnapshotLinux",
    "publisher": "Microsoft.Azure.RecoveryServices",
    "version": "1.0.9103.0"
  },
  {
    "name": "VMSnapshotLinux",
    "publisher": "Microsoft.Azure.RecoveryServices",
    "version": "1.0.9104.0"
  },
  {
    "name": "MyBackupTestInt",
    "publisher": "Microsoft.Azure.Backup.Test",
    "version": "1.0.11.0"
  },
  {
    "name": "MyBackupTestInt",
    "publisher": "Microsoft.Azure.Backup.Test",
    "version": "1.0.12.0"
  },
  {
    "name": "TeamServicesAgentLinux",
    "publisher": "Microsoft.VisualStudio.Services",
    "version": "1.0.0.0"
  },
  {
    "name": "TeamServicesAgentLinux",
    "publisher": "Microsoft.VisualStudio.Services",
    "version": "1.2.0.0"
  },
  {
    "name": "TeamServicesAgentLinux",
    "publisher": "Microsoft.VisualStudio.Services",
    "version": "1.3.0.0"
  },
  {
    "name": "TeamServicesAgentLinux",
    "publisher": "Microsoft.VisualStudio.Services",
    "version": "1.4.0.0"
  },
  {
    "name": "TeamServicesAgentLinux",
    "publisher": "Microsoft.VisualStudio.Services",
    "version": "1.5.0.0"
  },
  {
    "name": "AzureDiskEncryptionForLinux",
    "publisher": "Microsoft.Azure.Security",
    "version": "0.1.0.999242"
  },
  {
    "name": "AzureDiskEncryptionForLinux",
    "publisher": "Microsoft.Azure.Security",
    "version": "0.1.0.999249"
  },
  {
    "name": "CustomScriptForLinux",
    "publisher": "Microsoft.OSTCExtensions",
    "version": "1.0"
  },
  {
    "name": "CustomScriptForLinux",
    "publisher": "Microsoft.OSTCExtensions",
    "version": "1.1"
  },
  {
    "name": "CustomScriptForLinux",
    "publisher": "Microsoft.OSTCExtensions",
    "version": "1.2.1.0"
  },
  {
    "name": "CustomScriptForLinux",
    "publisher": "Microsoft.OSTCExtensions",
    "version": "1.2.2.0"
  },
  {
    "name": "CustomScriptForLinux",
    "publisher": "Microsoft.OSTCExtensions",
    "version": "1.3.0.0"
  },
  {
    "name": "CustomScriptForLinux",
    "publisher": "Microsoft.OSTCExtensions",
    "version": "1.3.0.1"
  },
  {
    "name": "CustomScriptForLinux",
    "publisher": "Microsoft.OSTCExtensions",
    "version": "1.3.0.2"
  },
  {
    "name": "CustomScriptForLinux",
    "publisher": "Microsoft.OSTCExtensions",
    "version": "1.4.0.0"
  },
  {
    "name": "CustomScriptForLinux",
    "publisher": "Microsoft.OSTCExtensions",
    "version": "1.4.1.0"
  },
  {
    "name": "CustomScriptForLinux",
    "publisher": "Microsoft.OSTCExtensions",
    "version": "1.5.2.0"
  },
  {
    "name": "CustomScriptForLinux",
    "publisher": "Microsoft.OSTCExtensions",
    "version": "1.5.2.1"
  },
  {
    "name": "VMAccessAgent",
    "publisher": "Microsoft.Compute",
    "version": "2.0"
  },
  {
    "name": "VMAccessAgent",
    "publisher": "Microsoft.Compute",
    "version": "2.0.1"
  },
  {
    "name": "VMAccessAgent",
    "publisher": "Microsoft.Compute",
    "version": "2.0.2"
  },
  {
    "name": "VMAccessAgent",
    "publisher": "Microsoft.Compute",
    "version": "2.3"
  },
  {
    "name": "AzureDiskEncryptionForLinuxTest",
    "publisher": "Microsoft.Azure.Security",
    "version": "0.1.0.999266"
  },
  {
    "name": "DSCForLinux",
    "publisher": "Microsoft.OSTCExtensions",
    "version": "1.0.0.0"
  },
  {
    "name": "DSCForLinux",
    "publisher": "Microsoft.OSTCExtensions",
    "version": "2.0.0.0"
  },
  {
    "name": "IaaSAntimalware",
    "publisher": "Microsoft.Azure.Security",
    "version": "1.0.0.0"
  },
  {
    "name": "IaaSAntimalware",
    "publisher": "Microsoft.Azure.Security",
    "version": "1.1.0.0"
  },
  {
    "name": "IaaSAntimalware",
    "publisher": "Microsoft.Azure.Security",
    "version": "1.2.0.0"
  },
  {
    "name": "IaaSAntimalware",
    "publisher": "Microsoft.Azure.Security",
    "version": "1.3.0.2"
  },
  {
    "name": "IaaSAntimalware",
    "publisher": "Microsoft.Azure.Security",
    "version": "1.4.0.0"
  },
  {
    "name": "IaaSAntimalware",
    "publisher": "Microsoft.Azure.Security",
    "version": "1.5.0.0"
  },
  {
    "name": "IaaSAntimalware",
    "publisher": "Microsoft.Azure.Security",
    "version": "1.5.2.0"
  },
  {
    "name": "IaaSAntimalware",
    "publisher": "Microsoft.Azure.Security",
    "version": "1.5.4.2"
  },
  {
    "name": "MyBackupTestLinux",
    "publisher": "Microsoft.Azure.Backup.Test",
    "version": "1.0.6.0"
  },
  {
    "name": "MyBackupTestLinux",
    "publisher": "Microsoft.Azure.Backup.Test",
    "version": "1.0.7.0"
  },
  {
    "name": "LinuxDiagnostic",
    "publisher": "Microsoft.OSTCExtensions",
    "version": "2.0.9005"
  },
  {
    "name": "LinuxDiagnostic",
    "publisher": "Microsoft.OSTCExtensions",
    "version": "2.1.9005"
  },
  {
    "name": "LinuxDiagnostic",
    "publisher": "Microsoft.OSTCExtensions",
    "version": "2.2.9005"
  },
  {
    "name": "LinuxDiagnostic",
    "publisher": "Microsoft.OSTCExtensions",
    "version": "2.3.9013"
  },
  {
    "name": "LinuxDiagnostic",
    "publisher": "Microsoft.OSTCExtensions",
    "version": "2.3.9015"
  },
  {
    "name": "LinuxDiagnostic",
    "publisher": "Microsoft.OSTCExtensions",
    "version": "2.3.9017"
  },
  {
    "name": "PuppetAgent",
    "publisher": "puppet",
    "version": "1.4.2"
  },
  {
    "name": "PuppetAgent",
    "publisher": "puppet",
    "version": "1.5.2"
  },
  {
    "name": "MyBackupTestLinuxInt",
    "publisher": "Microsoft.Azure.Backup.Test",
    "version": "1.0.1630.0"
  },
  {
    "name": "MyBackupTestLinuxInt",
    "publisher": "Microsoft.Azure.Backup.Test",
    "version": "1.0.1631.0"
  },
  {
    "name": "MyBackupTestLinuxInt",
    "publisher": "Microsoft.Azure.Backup.Test",
    "version": "1.0.1632.0"
  },
  {
    "name": "MyBackupTestLinuxInt",
    "publisher": "Microsoft.Azure.Backup.Test",
    "version": "1.0.1633.0"
  },
  {
    "name": "PuppetEnterpriseAgent",
    "publisher": "PuppetLabs",
    "version": "2015.2.3"
  },
  {
    "name": "PuppetEnterpriseAgent",
    "publisher": "PuppetLabs",
    "version": "2015.3.3"
  },
  {
    "name": "PuppetEnterpriseAgent",
    "publisher": "PuppetLabs",
    "version": "3.2.1"
  },
  {
    "name": "PuppetEnterpriseAgent",
    "publisher": "PuppetLabs",
    "version": "3.2.2"
  },
  {
    "name": "PuppetEnterpriseAgent",
    "publisher": "PuppetLabs",
    "version": "3.2.3"
  },
  {
    "name": "PuppetEnterpriseAgent",
    "publisher": "PuppetLabs",
    "version": "3.7.2"
  },
  {
    "name": "PuppetEnterpriseAgent",
    "publisher": "PuppetLabs",
    "version": "3.8.4"
  },
  {
    "name": "VMBackupForLinuxExtension",
    "publisher": "Microsoft.Azure.Security",
    "version": "0.1.0.995"
  },
  {
    "name": "PuppetEnterpriseAgent",
    "publisher": "PuppetLabs.Test",
    "version": "3.8.4"
  },
  {
    "name": "QualysAgent",
    "publisher": "Qualys",
    "version": "0.0.0.1"
  },
  {
    "name": "QualysAgent",
    "publisher": "Qualys",
    "version": "0.0.0.3"
  },
  {
    "name": "QualysAgent",
    "publisher": "Qualys",
    "version": "0.0.0.4"
  },
  {
    "name": "QualysAgent",
    "publisher": "Qualys",
    "version": "0.0.0.5"
  },
  {
    "name": "QualysAgent",
    "publisher": "Qualys",
    "version": "0.0.0.7"
  },
  {
    "name": "Null",
    "publisher": "Microsoft.OSTCExtensions",
    "version": "1.0.0.3"
  },
  {
    "name": "QualysAgentLinux",
    "publisher": "Qualys",
    "version": "1.5.0.72"
  },
  {
    "name": "QualysAgentLinux",
    "publisher": "Qualys",
    "version": "1.5.0.73"
  },
  {
    "name": "OSPatchingForLinux",
    "publisher": "Microsoft.OSTCExtensions",
    "version": "1.0"
  },
  {
    "name": "OSPatchingForLinux",
    "publisher": "Microsoft.OSTCExtensions",
    "version": "1.0.1.1"
  },
  {
    "name": "OSPatchingForLinux",
    "publisher": "Microsoft.OSTCExtensions",
    "version": "2.0.0.0"
  },
  {
    "name": "OSPatchingForLinux",
    "publisher": "Microsoft.OSTCExtensions",
    "version": "2.0.0.1"
  },
  {
    "name": "OSPatchingForLinux",
    "publisher": "Microsoft.OSTCExtensions",
    "version": "2.0.0.2"
  },
  {
    "name": "OSPatchingForLinux",
    "publisher": "Microsoft.OSTCExtensions",
    "version": "2.0.0.5"
  },
  {
    "name": "OSPatchingForLinux",
    "publisher": "Microsoft.OSTCExtensions",
    "version": "2.1.0.0"
  },
  {
    "name": "OSPatchingForLinux",
    "publisher": "Microsoft.OSTCExtensions",
    "version": "2.2.0.0"
  },
  {
    "name": "OSPatchingForLinux",
    "publisher": "Microsoft.OSTCExtensions",
    "version": "2.3.0.1"
  },
  {
    "name": "Site24x7ApmInsightExtn",
    "publisher": "Site24x7",
    "version": "1.2.1.1"
  },
  {
    "name": "Site24x7ApmInsightExtn",
    "publisher": "Site24x7",
    "version": "1.3.0.0"
  },
  {
    "name": "RDMAUpdateForLinux",
    "publisher": "Microsoft.OSTCExtensions",
    "version": "0.1.0.9"
  },
  {
    "name": "IaaSDiagnostics",
    "publisher": "StatusReport.Diagnostics.Test",
    "version": "0.25.0.0"
  },
  {
    "name": "IaaSDiagnostics",
    "publisher": "StatusReport.Diagnostics.Test",
    "version": "0.26.0.0"
  },
  {
    "name": "IaaSDiagnostics",
    "publisher": "StatusReport.Diagnostics.Test",
    "version": "0.27.0.0"
  },
  {
    "name": "Site24x7LinuxServerExtn",
    "publisher": "Site24x7",
    "version": "1.2.0.1"
  },
  {
    "name": "Site24x7LinuxServerExtn",
    "publisher": "Site24x7",
    "version": "1.3.0.0"
  },
  {
    "name": "SymantecEndpointProtection",
    "publisher": "Symantec",
    "version": "12.1.4100.2"
  },
  {
    "name": "SymantecEndpointProtection",
    "publisher": "Symantec",
    "version": "12.1.7007.6505"
  },
  {
    "name": "VMAccessForLinux",
    "publisher": "Microsoft.OSTCExtensions",
    "version": "1.0"
  },
  {
    "name": "VMAccessForLinux",
    "publisher": "Microsoft.OSTCExtensions",
    "version": "1.1"
  },
  {
    "name": "VMAccessForLinux",
    "publisher": "Microsoft.OSTCExtensions",
    "version": "1.2"
  },
  {
    "name": "VMAccessForLinux",
    "publisher": "Microsoft.OSTCExtensions",
    "version": "1.3.0.1"
  },
  {
    "name": "VMAccessForLinux",
    "publisher": "Microsoft.OSTCExtensions",
    "version": "1.4.0.0"
  },
  {
    "name": "VMAccessForLinux",
    "publisher": "Microsoft.OSTCExtensions",
    "version": "1.4.1.0"
  },
  {
    "name": "VMAccessForLinux",
    "publisher": "Microsoft.OSTCExtensions",
    "version": "1.4.2.0"
  },
  {
    "name": "VMAccessForLinux",
    "publisher": "Microsoft.OSTCExtensions",
    "version": "1.4.3.0"
  },
  {
    "name": "VMAccessForLinux",
    "publisher": "Microsoft.OSTCExtensions",
    "version": "1.4.4.0"
  },
  {
    "name": "VMAccessForLinux",
    "publisher": "Microsoft.OSTCExtensions",
    "version": "1.4.5.0"
  },
  {
    "name": "VMAccessForLinux",
    "publisher": "Microsoft.OSTCExtensions",
    "version": "1.4.6.0"
  },
  {
    "name": "Site24x7WindowsServerExtn",
    "publisher": "Site24x7",
    "version": "1.2.1.1"
  },
  {
    "name": "Site24x7WindowsServerExtn",
    "publisher": "Site24x7",
    "version": "1.3.0.0"
  },
  {
    "name": "TrendMicroDSA",
    "publisher": "Test.TrendMicro.DeepSecurity",
    "version": "9.6.2.10701"
  },
  {
    "name": "TrendMicroDSA",
    "publisher": "Test.TrendMicro.DeepSecurity",
    "version": "9.6.2.10801"
  },
  {
    "name": "PortalProtectExtension",
    "publisher": "TrendMicro.PortalProtect",
    "version": "2.1"
  },
  {
    "name": "TrendMicroDSA",
    "publisher": "TrendMicro.DeepSecurity",
    "version": "9.6.2.107"
  },
  {
    "name": "TrendMicroDSA",
    "publisher": "TrendMicro.DeepSecurity",
    "version": "9.6.2.108"
  },
  {
    "name": "VMBackupForLinuxExtension",
    "publisher": "Microsoft.OSTCExtensions",
    "version": "0.1.0.993"
  },
  {
    "name": "TrendMicroDSALinux",
    "publisher": "Test.TrendMicro.DeepSecurity",
    "version": "9.6.2.10802"
  },
  {
    "name": "TrendMicroDSALinux",
    "publisher": "Test.TrendMicro.DeepSecurity",
    "version": "9.6.2.10901"
  },
  {
    "name": "TeamServicesAgentLinux1",
    "publisher": "Test.Microsoft.VisualStudio.Services",
    "version": "1.0.0.0"
  },
  {
    "name": "TrendMicroDSALinux",
    "publisher": "TrendMicro.DeepSecurity",
    "version": "9.6.2.108"
  },
  {
    "name": "TrendMicroDSALinux",
    "publisher": "TrendMicro.DeepSecurity",
    "version": "9.6.2.109"
  },
  {
    "name": "IaaSDiagnostics",
    "publisher": "WAD2EventHub.Diagnostics.Test",
    "version": "0.1.0.0"
  },
  {
    "name": "IaaSDiagnostics",
    "publisher": "WAD2AI.Diagnostics.Test",
    "version": "0.19.0.0"
  },
  {
    "name": "IaaSDiagnostics",
    "publisher": "WAD2AI.Diagnostics.Test",
    "version": "0.21.0.0"
  },
  {
    "name": "IaaSDiagnostics",
    "publisher": "WAD2AI.Diagnostics.Test",
    "version": "0.22.0.0"
  },
  {
    "name": "IaaSDiagnostics",
    "publisher": "WAD2AI.Diagnostics.Test",
    "version": "0.23.0.0"
  },
  {
    "name": "VormetricTransparentEncryptionAgent",
    "publisher": "Vormetric",
    "version": "5.2.339.0"
  },
  {
    "name": "AlertLogicLM",
    "publisher": "alertlogic",
    "version": "1.3.0.1"
  }
]
```