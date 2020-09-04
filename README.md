# Overview     [![Gitter](https://badges.gitter.im/Analogy-LogViewer/community.svg)](https://gitter.im/Analogy-LogViewer/community?utm_source=badge&utm_medium=badge&utm_campaign=pr-badge)  <img src="./Assets/logo128x128.jpg" align="right" width="155px" height="155px">
 Overview of projects and their repositories
 
# Analogy Log Viewer
![Supported extensions](Assets/Analogy512x512.jpg)

Analogy Log Viewer is multi purpose Log Viewer for Windows Operating systems (with built-in Parser for most commonly used log frameworks).

The application has many standard operations for analysis logs (like filtering, excluding) but its strength is in the ability to add additional custom data sources by implementing few interfaces.
This allows adding any logs formats and/or custom modification of logs before presenting the data in the UI Layer.
Some features of this tool are:
1.	Windows event log support (evtx files)
2.	Logs aggregation into single view.
3.	Search in multiple files
4.	Combine multiple files
5.	Compare logs 
6.	Themes support
7.	64 bit support
8.	Personalization (users settings per user) 
9.	Columns extension to add more columns specific to the data source implementation
10.	Exporting to Excel/CSV files

# Log Viewer Application
The main Analogy Log Viewer app resides at the following repositories:
- [Analogy Log Viewer (DevExpress 19.1.10 version)](https://github.com/Analogy-LogViewer/Analogy.LogViewer). [![Build Status](https://dev.azure.com/Analogy-LogViewer/Analogy%20Log%20Viewer/_apis/build/status/Analogy-LogViewer.Analogy.LogViewer?branchName=master)](https://dev.azure.com/Analogy-LogViewer/Analogy%20Log%20Viewer/_build/latest?definitionId=1&branchName=master)
- [Analogy Log Viewer (Syncfusion version - developement paused for now)](https://github.com/Analogy-LogViewer/Analogy.LogViewer.Syncfusion).
- [Analogy Log Viewer (Winforms version - not ready for use)](https://github.com/Analogy-LogViewer/Analogy.LogViewer.Winforms). [![Build Status](https://dev.azure.com/Analogy-LogViewer/Analogy%20Log%20Viewer/_apis/build/status/Analogy-LogViewer.Analogy.LogViewer.Winforms?branchName=master)](https://dev.azure.com/Analogy-LogViewer/Analogy%20Log%20Viewer/_build/latest?definitionId=10&branchName=master)

# Real Time Data Providers

Analogy Log Viewer has a Real time gRPC Data provider:

| Data Provider   |      CI Status      |  Nuget Version |
|----------|:---------------:|------|
| [gRPC Real Time Data Provider](https://github.com/Analogy-LogViewer/Analogy.LogViewer.gRPC) |![.NET Core Desktop](https://github.com/Analogy-LogViewer/Analogy.LogViewer.gRPC/workflows/.NET%20Core%20Desktop/badge.svg) [![Build Status](https://dev.azure.com/Analogy-LogViewer/Analogy%20Log%20Viewer/_apis/build/status/Analogy-LogViewer.Analogy.LogViewer.gRPC?branchName=master)](https://dev.azure.com/Analogy-LogViewer/Analogy%20Log%20Viewer/_build/latest?definitionId=34&branchName=master) | [![Nuget](https://img.shields.io/nuget/v/Analogy.LogViewer.gRPC)](https://www.nuget.org/packages/Analogy.LogViewer.gRPC/)

## gRPC Real Time Data Provider

| Nuget   |      Version      |  Description |
|----------|:-------------:|------|
| [Analogy.LogViewer.gRPC](https://www.nuget.org/packages/Analogy.LogViewer.gRPC/) |   [![Nuget](https://img.shields.io/nuget/v/Analogy.LogViewer.gRPC)](https://www.nuget.org/packages/Analogy.LogViewer.gRPC/) | Primary Analogy Log Viewer grRPC providers |
| [Analogy.LogServer](https://www.nuget.org/packages/Analogy.LogServer/) |   [![Nuget](https://img.shields.io/nuget/v/Analogy.LogServer)](https://www.nuget.org/packages/Analogy.LogServer/) | A windows Service for receiving logs |
| [Analogy.LogServer.Clients](https://www.nuget.org/packages/Analogy.LogServer.Clients/) |   [![Nuget](https://img.shields.io/nuget/v/Analogy.LogServer.Clients)](https://www.nuget.org/packages/Analogy.LogServer.Clients) | gRPC client to pull back messages from Analogy Service |



# Data Providers
The following custom data providers exists:
### Common Data providers:
| Data Provider   |      CI Status      |  Nuget Version |
|----------|:---------------:|------|
| [Plain Text Parser](https://github.com/Analogy-LogViewer/Analogy.LogViewer.PlainTextParser) | ![.NET Core Desktop](https://github.com/Analogy-LogViewer/Analogy.LogViewer.PlainTextParser/workflows/.NET%20Core%20Desktop/badge.svg) [![Build Status](https://dev.azure.com/Analogy-LogViewer/Analogy%20Log%20Viewer/_apis/build/status/Analogy-LogViewer.Analogy.LogViewer.PlainTextParser?branchName=master)](https://dev.azure.com/Analogy-LogViewer/Analogy%20Log%20Viewer/_build/latest?definitionId=17&branchName=master) | [![Nuget](https://img.shields.io/nuget/v/Analogy.LogViewer.PlainTextParser)](https://www.nuget.org/packages/Analogy.LogViewer.PlainTextParser/)
| [NLog Parser](https://github.com/Analogy-LogViewer/Analogy.LogViewer.NLogProvider)|  ![.NET Core Desktop](https://github.com/Analogy-LogViewer/Analogy.LogViewer.NLog/workflows/.NET%20Core%20Desktop/badge.svg) [![Build Status](https://dev.azure.com/Analogy-LogViewer/Analogy%20Log%20Viewer/_apis/build/status/Analogy-LogViewer.Analogy.LogViewer.NLog?branchName=master)](https://dev.azure.com/Analogy-LogViewer/Analogy%20Log%20Viewer/_build/latest?definitionId=20&branchName=master) | [![Nuget](https://img.shields.io/nuget/v/Analogy.LogViewer.NLogProvider)](https://www.nuget.org/packages/Analogy.LogViewer.NLogProvider/) 
| [Serilog Parser](https://github.com/Analogy-LogViewer/Analogy.LogViewer.Serilog) |  ![.NET Core Desktop](https://github.com/Analogy-LogViewer/Analogy.LogViewer.Serilog/workflows/.NET%20Core%20Desktop/badge.svg) [![Build Status](https://dev.azure.com/Analogy-LogViewer/Analogy%20Log%20Viewer/_apis/build/status/Analogy-LogViewer.Analogy.LogViewer.Serilog?branchName=master)](https://dev.azure.com/Analogy-LogViewer/Analogy%20Log%20Viewer/_build/latest?definitionId=15&branchName=master) | [![Nuget](https://img.shields.io/nuget/v/Analogy.LogViewer.Serilog)](https://www.nuget.org/packages/Analogy.LogViewer.Serilog/)
| [Log4Net Parser](https://github.com/Analogy-LogViewer/Analogy.LogViewer.Log4Net) |  ![.NET Core Desktop](https://github.com/Analogy-LogViewer/Analogy.LogViewer.Log4Net/workflows/.NET%20Core%20Desktop/badge.svg)  [![Build Status](https://dev.azure.com/Analogy-LogViewer/Analogy%20Log%20Viewer/_apis/build/status/Analogy-LogViewer.Analogy.LogViewer.Log4Net?branchName=master)](https://dev.azure.com/Analogy-LogViewer/Analogy%20Log%20Viewer/_build/latest?definitionId=26&branchName=master) | [![Nuget](https://img.shields.io/nuget/v/Analogy.LogViewer.Log4Net)](https://www.nuget.org/packages/Analogy.LogViewer.Log4Net/)
| [Regular Expression Parser](https://github.com/Analogy-LogViewer/Analogy.LogViewer.RegexParser)| ![.NET Core Desktop](https://github.com/Analogy-LogViewer/Analogy.LogViewer.RegexParser/workflows/.NET%20Core%20Desktop/badge.svg) [![Build Status](https://dev.azure.com/Analogy-LogViewer/Analogy%20Log%20Viewer/_apis/build/status/Analogy-LogViewer.Analogy.LogViewer.RegexParser?branchName=master)](https://dev.azure.com/Analogy-LogViewer/Analogy%20Log%20Viewer/_build/latest?definitionId=30&branchName=master) | [![Nuget](https://img.shields.io/nuget/v/Analogy.LogViewer.RegexParser)](https://www.nuget.org/packages/Analogy.LogViewer.RegexParser/)
| [Kafka Producer/ consumer](https://github.com/Analogy-LogViewer/Analogy.LogViewer.KafkaProvider)| ![.NET Core Desktop](https://github.com/Analogy-LogViewer/Analogy.LogViewer.KafkaProvider/workflows/.NET%20Core%20Desktop/badge.svg) [![Build Status](https://dev.azure.com/Analogy-LogViewer/Analogy%20Log%20Viewer/_apis/build/status/Analogy-LogViewer.Analogy.LogViewer.KafkaProvider?branchName=master)](https://dev.azure.com/Analogy-LogViewer/Analogy%20Log%20Viewer/_build/latest?definitionId=5&branchName=master) |[![Nuget](https://img.shields.io/nuget/v/Analogy.LogViewer.KafkaProvider)](https://www.nuget.org/packages/Analogy.LogViewer.KafkaProvider/)
| [IIS log Parser](https://github.com/Analogy-LogViewer/Analogy.LogViewer.IISLogParser)| ![.NET Core Desktop](https://github.com/Analogy-LogViewer/Analogy.LogViewer.IISLogsProvider/workflows/.NET%20Core%20Desktop/badge.svg) [![Build Status](https://dev.azure.com/Analogy-LogViewer/Analogy%20Log%20Viewer/_apis/build/status/Analogy-LogViewer.Analogy.LogViewer.IISLogsProvider?branchName=master)](https://dev.azure.com/Analogy-LogViewer/Analogy%20Log%20Viewer/_build/latest?definitionId=6&branchName=master) | [![Nuget](https://img.shields.io/nuget/v/Analogy.LogViewer.IISLogsProvider)](https://www.nuget.org/packages/Analogy.LogViewer.IISLogsProvider/)
| [RSS Reader](https://github.com/Analogy-LogViewer/Analogy.LogViewer.RSSReader) | ![.NET Core Desktop](https://github.com/Analogy-LogViewer/Analogy.LogViewer.RSSReader/workflows/.NET%20Core%20Desktop/badge.svg) [![Build Status](https://dev.azure.com/Analogy-LogViewer/Analogy%20Log%20Viewer/_apis/build/status/Analogy-LogViewer.Analogy.LogViewer.RSSReader?branchName=master)](https://dev.azure.com/Analogy-LogViewer/Analogy%20Log%20Viewer/_build/latest?definitionId=7&branchName=master) | [![Nuget](https://img.shields.io/nuget/v/Analogy.LogViewer.RSSReader)](https://www.nuget.org/packages/Analogy.LogViewer.RSSReader/)
| [Generic Json Log Parser](https://github.com/Analogy-LogViewer/Analogy.LogViewer.JsonParser)| ![.NET Core Desktop](https://github.com/Analogy-LogViewer/Analogy.LogViewer.JsonParser/workflows/.NET%20Core%20Desktop/badge.svg) [![Build Status](https://dev.azure.com/Analogy-LogViewer/Analogy%20Log%20Viewer/_apis/build/status/Analogy-LogViewer.Analogy.LogViewer.JsonParser?branchName=master)](https://dev.azure.com/Analogy-LogViewer/Analogy%20Log%20Viewer/_build/latest?definitionId=12&branchName=master) |[![Nuget](https://img.shields.io/nuget/v/Analogy.LogViewer.JsonParser)](https://www.nuget.org/packages/Analogy.LogViewer.JsonParser/)
| [XML Parser](https://github.com/Analogy-LogViewer/Analogy.LogViewer.XMLFileProvider)| ![.NET Core Desktop](https://github.com/Analogy-LogViewer/Analogy.LogViewer.XMLParser/workflows/.NET%20Core%20Desktop/badge.svg) [![Build Status](https://dev.azure.com/Analogy-LogViewer/Analogy%20Log%20Viewer/_apis/build/status/Analogy-LogViewer.Analogy.LogViewer.XMLParser?branchName=master)](https://dev.azure.com/Analogy-LogViewer/Analogy%20Log%20Viewer/_build/latest?definitionId=19&branchName=master)| [![Nuget](https://img.shields.io/nuget/v/Analogy.LogViewer.XMLParser)](https://www.nuget.org/packages/Analogy.LogViewer.XMLParser/)
| [Windows event logs](https://github.com/Analogy-LogViewer/Analogy.LogViewer.WindowsEventLogs)| ![.NET Core Desktop](https://github.com/Analogy-LogViewer/Analogy.LogViewer.WindowsEventLogs/workflows/.NET%20Core%20Desktop/badge.svg) [![Build Status](https://dev.azure.com/Analogy-LogViewer/Analogy%20Log%20Viewer/_apis/build/status/Analogy-LogViewer.Analogy.LogViewer.WindowsEventLogs?branchName=master)](https://dev.azure.com/Analogy-LogViewer/Analogy%20Log%20Viewer/_build/latest?definitionId=25&branchName=master)| [![Nuget](https://img.shields.io/nuget/v/Analogy.LogViewer.WindowsEventLogs)](https://www.nuget.org/packages/Analogy.LogViewer.WindowsEventLogs/)
| [Catel log Parser](https://github.com/Analogy-LogViewer/Analogy.LogViewer.CatelProject) |[![Build Status](https://dev.azure.com/Analogy-LogViewer/Analogy%20Log%20Viewer/_apis/build/status/Analogy-LogViewer.Analogy.LogViewer.CatelProject?branchName=master)](https://dev.azure.com/Analogy-LogViewer/Analogy%20Log%20Viewer/_build/latest?definitionId=4&branchName=master)

### Special Purpose Data providers:
| Data Provider   |      CI Status      |  Nuget Version |
|----------|:---------------:|------|
| [Git History](https://github.com/Analogy-LogViewer/Analogy.LogViewer.GitHistory) | ![.NET Core Desktop](https://github.com/Analogy-LogViewer/Analogy.LogViewer.GitHistory/workflows/.NET%20Core%20Desktop/badge.svg) [![Build Status](https://dev.azure.com/Analogy-LogViewer/Analogy%20Log%20Viewer/_apis/build/status/Analogy-LogViewer.Analogy.LogViewer.GitHistory?branchName=master)](https://dev.azure.com/Analogy-LogViewer/Analogy%20Log%20Viewer/_build/latest?definitionId=24&branchName=master) | [![Nuget](https://img.shields.io/nuget/v/Analogy.LogViewer.GitHistory)](https://www.nuget.org/packages/Analogy.LogViewer.GitHistory/)
| [WCF Sender/Receiver](https://github.com/Analogy-LogViewer/Analogy.LogViewer.WCF) | ![.NET Core Desktop](https://github.com/Analogy-LogViewer/Analogy.LogViewer.WCF/workflows/.NET%20Core%20Desktop/badge.svg) [![Build Status](https://dev.azure.com/Analogy-LogViewer/Analogy%20Log%20Viewer/_apis/build/status/Analogy-LogViewer.Analogy.LogViewer.WCF?branchName=master)](https://dev.azure.com/Analogy-LogViewer/Analogy%20Log%20Viewer/_build/latest?definitionId=22&branchName=master) | [![Nuget](https://img.shields.io/nuget/v/Analogy.LogViewer.WCF)](https://www.nuget.org/packages/Analogy.LogViewer.WCF/)
| [WhatsApp Chat Log Parser](https://github.com/Analogy-LogViewer/Analogy.LogViewer.WhatsApp) | ![.NET Core Desktop](https://github.com/Analogy-LogViewer/Analogy.LogViewer.WhatsApp/workflows/.NET%20Core%20Desktop/badge.svg) [![Build Status](https://dev.azure.com/Analogy-LogViewer/Analogy%20Log%20Viewer/_apis/build/status/Analogy-LogViewer.Analogy.LogViewer.WhatsApp?branchName=master)](https://dev.azure.com/Analogy-LogViewer/Analogy%20Log%20Viewer/_build/latest?definitionId=31&branchName=master) | [![Nuget](https://img.shields.io/nuget/v/Analogy.LogViewer.WhatsApp)](https://www.nuget.org/packages/Analogy.LogViewer.WhatsApp/)
| [Visual Studio Activity Log Parser](https://github.com/Analogy-LogViewer/Analogy.LogViewer.VisualStudioLogParser) | ![.NET Core Desktop](https://github.com/Analogy-LogViewer/Analogy.LogViewer.VisualStudioLogParser/workflows/.NET%20Core%20Desktop/badge.svg) [![Build Status](https://dev.azure.com/Analogy-LogViewer/Analogy%20Log%20Viewer/_apis/build/status/Analogy-LogViewer.Analogy.LogViewer.VisualStudioLogParser?branchName=master)](https://dev.azure.com/Analogy-LogViewer/Analogy%20Log%20Viewer/_build/latest?definitionId=33&branchName=master) | [![Nuget](https://img.shields.io/nuget/v/Analogy.LogViewer.VisualStudioLogParser)](https://www.nuget.org/packages/Analogy.LogViewer.VisualStudioLogParser/)


### Organizations/Companies Data providers:
| Data Provider   |      CI Status      |
|----------|:---------------:|
| [Kama Research and Development](https://github.com/Analogy-LogViewer/Analogy.LogViewer.KamaResearch) | [![Build Status](https://dev.azure.com/Analogy-LogViewer/Analogy%20Log%20Viewer/_apis/build/status/Analogy-LogViewer.Analogy.LogViewer.KamaResearch?branchName=master)](https://dev.azure.com/Analogy-LogViewer/Analogy%20Log%20Viewer/_build/latest?definitionId=11&branchName=master)
| [Philips I4 BU](https://github.com/Analogy-LogViewer/Analogy.LogViewer.Philips.I4) | [![Build Status](https://dev.azure.com/Analogy-LogViewer/Analogy%20Log%20Viewer/_apis/build/status/Analogy-LogViewer.Analogy.LogViewer.Philips.I4?branchName=master)](https://dev.azure.com/Analogy-LogViewer/Analogy%20Log%20Viewer/_build/latest?definitionId=16&branchName=master)
| [Philips ICAP BU](https://github.com/Analogy-LogViewer/Analogy.LogViewer.Philips.ICAP)  | [![Build Status](https://dev.azure.com/Analogy-LogViewer/Analogy%20Log%20Viewer/_apis/build/status/Analogy-LogViewer.Analogy.LogViewer.Philips.ICAP?branchName=master)](https://dev.azure.com/Analogy-LogViewer/Analogy%20Log%20Viewer/_build/latest?definitionId=21&branchName=master)
| [MIrada XD logs Parser](https://github.com/Analogy-LogViewer/Analogy.LogViewer.MiradaXD) | [![Build Status](https://dev.azure.com/Analogy-LogViewer/Analogy%20Log%20Viewer/_apis/build/status/Analogy-LogViewer.Analogy.LogViewer.MiradaXD?branchName=master)](https://dev.azure.com/Analogy-LogViewer/Analogy%20Log%20Viewer/_build/latest?definitionId=8&branchName=master)


# Other Repositories


| Data Provider   |      CI Status      |  Nuget Version |
|----------|:---------------:|------|
| [Analogy.DataProviders.Extensions](https://github.com/Analogy-LogViewer/Analogy.DataProviders.Extensions) |  ![.NET Core Desktop](https://github.com/Analogy-LogViewer/Analogy.DataProviders.Extensions/workflows/.NET%20Core%20Desktop/badge.svg)  [![Build Status](https://dev.azure.com/Analogy-LogViewer/Analogy%20Log%20Viewer/_apis/build/status/Analogy-LogViewer.Analogy.DataProviders.Extensions?branchName=master)](https://dev.azure.com/Analogy-LogViewer/Analogy%20Log%20Viewer/_build/latest?definitionId=9&branchName=master) | [![Nuget](https://img.shields.io/nuget/v/Analogy.DataProviders.Extensions)](https://www.nuget.org/packages/Analogy.DataProviders.Extensions/)  
| [Analogy.LogViewer.Example](https://github.com/Analogy-LogViewer/Analogy.LogViewer.Example) | ![.NET Core Desktop](https://github.com/Analogy-LogViewer/Analogy.LogViewer.Example/workflows/.NET%20Core%20Desktop/badge.svg) [![Build Status](https://dev.azure.com/Analogy-LogViewer/Analogy%20Log%20Viewer/_apis/build/status/Analogy-LogViewer.Analogy.LogViewer.Example?branchName=master)](https://dev.azure.com/Analogy-LogViewer/Analogy%20Log%20Viewer/_build/latest?definitionId=14&branchName=master) | [![Nuget](https://img.shields.io/nuget/v/Analogy.LogViewer.Example)](https://www.nuget.org/packages/Analogy.LogViewer.Example/) 
| [Analogy Interface Project](https://github.com/Analogy-LogViewer/Analogy.Interfaces) | ![.NET Core Desktop](https://github.com/Analogy-LogViewer/Analogy.Interfaces/workflows/.NET%20Core%20Desktop/badge.svg) [![Build Status](https://dev.azure.com/Analogy-LogViewer/Analogy%20Log%20Viewer/_apis/build/status/Analogy-LogViewer.Analogy.Interfaces?branchName=master)](https://dev.azure.com/Analogy-LogViewer/Analogy%20Log%20Viewer/_build/latest?definitionId=2&branchName=master) | [![Nuget](https://img.shields.io/nuget/v/Analogy.LogViewer.Interfaces)](https://www.nuget.org/packages/Analogy.LogViewer.Interfaces/) 
# Dependencies & Build
- Main Application UI is complied to .Net Framework 4.7.2 and to .Net Core 3.1. The supported version of Visual studio for this framework is Visual studio 2017 (or above).
After successfull build any custom data source assemblies should be placed at the same folder as the executable (Analogy.exe) with the folowing pattern naming: Analogy.LogViewer.*.dll
- Analogy Interfaces assembly is complied to .Net Standard 2.0.

- DevExpress User Controls:
in order to compile the DevExpress version  [DevExpress](https://www.devexpress.com/) assemblies are required (winforms package only).

- Syncfusion User Controls:
[Syncfusion](https://www.syncfusion.com/) has open source license.


<a name="contact"></a>
## Contact

### Owner
- [Lior Banai](mailto:liorbanai@gmail.com)

## Used by the following Organizations:

[<img src="./Assets/Kama.jpg">](https://www.linkedin.com/company/kama-research-ltd/about/)
[<img src="./Assets/PhilipsShield.jpg">](https://www.philips.com/global)
