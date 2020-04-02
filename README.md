# Overview     [![Gitter](https://badges.gitter.im/Analogy-LogViewer/community.svg)](https://gitter.im/Analogy-LogViewer/community?utm_source=badge&utm_medium=badge&utm_campaign=pr-badge)  <img src="./Assets/logo128x128.jpg" align="right" width="155px" height="155px">
 Overview of projects and their repositories
 
# Analogy Log Viewer

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
- [Analogy Log Viewer (DevExpress 19.1.9 version)](https://github.com/Analogy-LogViewer/Analogy.LogViewer). [![Build Status](https://dev.azure.com/Analogy-LogViewer/Analogy%20Log%20Viewer/_apis/build/status/Analogy-LogViewer.Analogy.LogViewer?branchName=master)](https://dev.azure.com/Analogy-LogViewer/Analogy%20Log%20Viewer/_build/latest?definitionId=1&branchName=master)
- [Analogy Log Viewer (Syncfusion version)](https://github.com/Analogy-LogViewer/Analogy.LogViewer.Syncfusion).
- [Analogy Log Viewer (Winforms version - not ready for use)](https://github.com/Analogy-LogViewer/Analogy.LogViewer.Winforms). [![Build Status](https://dev.azure.com/Analogy-LogViewer/Analogy%20Log%20Viewer/_apis/build/status/Analogy-LogViewer.Analogy.LogViewer.Winforms?branchName=master)](https://dev.azure.com/Analogy-LogViewer/Analogy%20Log%20Viewer/_build/latest?definitionId=10&branchName=master)


# Data Providers
The following  custom data providers exists:
- [Plain Text Parser](https://github.com/Analogy-LogViewer/Analogy.LogViewer.PlainTextParser) [![Build Status](https://dev.azure.com/Analogy-LogViewer/Analogy%20Log%20Viewer/_apis/build/status/Analogy-LogViewer.Analogy.LogViewer.PlainTextParser?branchName=master)](https://dev.azure.com/Analogy-LogViewer/Analogy%20Log%20Viewer/_build/latest?definitionId=17&branchName=master)  [![Nuget](https://img.shields.io/nuget/v/Analogy.LogViewer.PlainTextParser)](https://www.nuget.org/packages/Analogy.LogViewer.PlainTextParser/)
- [NLog Parser](https://github.com/Analogy-LogViewer/Analogy.LogViewer.NLogProvider)[![Build Status](https://dev.azure.com/Analogy-LogViewer/Analogy%20Log%20Viewer/_apis/build/status/Analogy-LogViewer.Analogy.LogViewer.NLog?branchName=master)](https://dev.azure.com/Analogy-LogViewer/Analogy%20Log%20Viewer/_build/latest?definitionId=20&branchName=master)  [![Nuget](https://img.shields.io/nuget/v/Analogy.LogViewer.NLogProvider)](https://www.nuget.org/packages/Analogy.LogViewer.NLogProvider/) 
- [Serilog Parser](https://github.com/Analogy-LogViewer/Analogy.LogViewer.Serilog) [![Build Status](https://dev.azure.com/Analogy-LogViewer/Analogy%20Log%20Viewer/_apis/build/status/Analogy-LogViewer.Analogy.LogViewer.Serilog?branchName=master)](https://dev.azure.com/Analogy-LogViewer/Analogy%20Log%20Viewer/_build/latest?definitionId=15&branchName=master)  [![Nuget](https://img.shields.io/nuget/v/Analogy.LogViewer.Serilog)](https://www.nuget.org/packages/Analogy.LogViewer.Serilog/)
- [Confluent's Apache Kafka .NET Producer and consumer](https://github.com/Analogy-LogViewer/Analogy.LogViewer.KafkaProvider) [![Build Status](https://dev.azure.com/Analogy-LogViewer/Analogy%20Log%20Viewer/_apis/build/status/Analogy-LogViewer.Analogy.LogViewer.KafkaProvider?branchName=master)](https://dev.azure.com/Analogy-LogViewer/Analogy%20Log%20Viewer/_build/latest?definitionId=5&branchName=master)  [![Nuget](https://img.shields.io/nuget/v/Analogy.LogViewer.KafkaProvider)](https://www.nuget.org/packages/Analogy.LogViewer.KafkaProvider/)
- [Catel log Parser](https://github.com/Analogy-LogViewer/Analogy.LogViewer.CatelProject) [![Build Status](https://dev.azure.com/Analogy-LogViewer/Analogy%20Log%20Viewer/_apis/build/status/Analogy-LogViewer.Analogy.LogViewer.CatelProject?branchName=master)](https://dev.azure.com/Analogy-LogViewer/Analogy%20Log%20Viewer/_build/latest?definitionId=4&branchName=master)
- [IIS log Parser](https://github.com/Analogy-LogViewer/Analogy.LogViewer.IISLogParser) [![Build Status](https://dev.azure.com/Analogy-LogViewer/Analogy%20Log%20Viewer/_apis/build/status/Analogy-LogViewer.Analogy.LogViewer.IISLogsProvider?branchName=master)](https://dev.azure.com/Analogy-LogViewer/Analogy%20Log%20Viewer/_build/latest?definitionId=6&branchName=master)  [![Nuget](https://img.shields.io/nuget/v/Analogy.LogViewer.IISLogsProvider)](https://www.nuget.org/packages/Analogy.LogViewer.IISLogsProvider/)
- [RSS Reader](https://github.com/Analogy-LogViewer/Analogy.LogViewer.RSSReader) [![Build Status](https://dev.azure.com/Analogy-LogViewer/Analogy%20Log%20Viewer/_apis/build/status/Analogy-LogViewer.Analogy.LogViewer.RSSReader?branchName=master)](https://dev.azure.com/Analogy-LogViewer/Analogy%20Log%20Viewer/_build/latest?definitionId=7&branchName=master)   [![Nuget](https://img.shields.io/nuget/v/Analogy.LogViewer.RSSReader)](https://www.nuget.org/packages/Analogy.LogViewer.RSSReader/)
- [Kama Research and Development](https://github.com/Analogy-LogViewer/Analogy.LogViewer.KamaResearch) [![Build Status](https://dev.azure.com/Analogy-LogViewer/Analogy%20Log%20Viewer/_apis/build/status/Analogy-LogViewer.Analogy.LogViewer.KamaResearch?branchName=master)](https://dev.azure.com/Analogy-LogViewer/Analogy%20Log%20Viewer/_build/latest?definitionId=11&branchName=master)
- [Generic Json Log Parser](https://github.com/Analogy-LogViewer/Analogy.LogViewer.JsonParser) [![Build Status](https://dev.azure.com/Analogy-LogViewer/Analogy%20Log%20Viewer/_apis/build/status/Analogy-LogViewer.Analogy.LogViewer.JsonParser?branchName=master)](https://dev.azure.com/Analogy-LogViewer/Analogy%20Log%20Viewer/_build/latest?definitionId=12&branchName=master)
- [Plain XML Parser](https://github.com/Analogy-LogViewer/Analogy.LogViewer.XMLFileProvider)[![Build Status](https://dev.azure.com/Analogy-LogViewer/Analogy%20Log%20Viewer/_apis/build/status/Analogy-LogViewer.Analogy.LogViewer.XMLParser?branchName=master)](https://dev.azure.com/Analogy-LogViewer/Analogy%20Log%20Viewer/_build/latest?definitionId=19&branchName=master)
- [Git History](https://github.com/Analogy-LogViewer/Analogy.LogViewer.GitHistory)[![Build Status](https://dev.azure.com/Analogy-LogViewer/Analogy%20Log%20Viewer/_apis/build/status/Analogy-LogViewer.Analogy.LogViewer.GitHistory?branchName=master)](https://dev.azure.com/Analogy-LogViewer/Analogy%20Log%20Viewer/_build/latest?definitionId=24&branchName=master)
- [Philips I4 BU](https://github.com/Analogy-LogViewer/Analogy.LogViewer.Philips.I4) [![Build Status](https://dev.azure.com/Analogy-LogViewer/Analogy%20Log%20Viewer/_apis/build/status/Analogy-LogViewer.Analogy.LogViewer.Philips.I4?branchName=master)](https://dev.azure.com/Analogy-LogViewer/Analogy%20Log%20Viewer/_build/latest?definitionId=16&branchName=master)
- [MIrada XD logs Parser](https://github.com/Analogy-LogViewer/Analogy.LogViewer.MiradaXD) [![Build Status](https://dev.azure.com/Analogy-LogViewer/Analogy%20Log%20Viewer/_apis/build/status/Analogy-LogViewer.Analogy.LogViewer.MiradaXD?branchName=master)](https://dev.azure.com/Analogy-LogViewer/Analogy%20Log%20Viewer/_build/latest?definitionId=8&branchName=master)
- [Philips ICAP BU](https://github.com/Analogy-LogViewer/Analogy.LogViewer.Philips.ICAP)  [![Build Status](https://dev.azure.com/Analogy-LogViewer/Analogy%20Log%20Viewer/_apis/build/status/Analogy-LogViewer.Analogy.LogViewer.Philips.ICAP?branchName=master)](https://dev.azure.com/Analogy-LogViewer/Analogy%20Log%20Viewer/_build/latest?definitionId=21&branchName=master)
- (private repo) Philips CT BU
- Windows event logs

Data providers settings are managed in their own user setting window. Planned and existing data providers are:
![Data Providers settings screen](Assets/AnalogyDataProviders.jpg)

# Other Repositories

- [Analogy.DataProviders.Extensions](https://github.com/Analogy-LogViewer/Analogy.DataProviders.Extensions)  [![Nuget](https://img.shields.io/nuget/v/Analogy.DataProviders.Extensions)](https://www.nuget.org/packages/Analogy.DataProviders.Extensions/)  [![Nuget](https://img.shields.io/nuget/dt/Analogy.DataProviders.Extensions)](https://www.nuget.org/packages/Analogy.DataProviders.Extensions/)  [![Build Status](https://dev.azure.com/Analogy-LogViewer/Analogy%20Log%20Viewer/_apis/build/status/Analogy-LogViewer.Analogy.DataProviders.Extensions?branchName=master)](https://dev.azure.com/Analogy-LogViewer/Analogy%20Log%20Viewer/_build/latest?definitionId=9&branchName=master) - Add additional functionality (e.g UI controls) for .net framework/.net Core versions.

- [Analogy.LogViewer.Example](https://github.com/Analogy-LogViewer/Analogy.LogViewer.Example) [![Build Status](https://dev.azure.com/Analogy-LogViewer/Analogy%20Log%20Viewer/_apis/build/status/Analogy-LogViewer.Analogy.LogViewer.Example?branchName=master)](https://dev.azure.com/Analogy-LogViewer/Analogy%20Log%20Viewer/_build/latest?definitionId=14&branchName=master) [![Nuget](https://img.shields.io/nuget/v/Analogy.LogViewer.Example)](https://www.nuget.org/packages/Analogy.LogViewer.Example/) [![Nuget](https://img.shields.io/nuget/dt/Analogy.LogViewer.Example)](https://www.nuget.org/packages/Analogy.LogViewer.Example/) - Example project how to create new custom data provider.
# Dependencies & Build
- Main Application UI is complied to .Net Framework 4.7.2 and to .Net Core 3.0.
The projects targets .Net Framework 4.7.2/Core 3.0 . The supported version of Visual studio for this framework is Visual studio 2017 (or above).
After successfull build any custom data source assemblies should be placed at the same folder as the executable (Analogy.exe) with the folowing pattern naming: Analogy.LogViewer.*.dll
- Analogy Interfaces assembly is complied to .Net Standard 2.0.

Detailed Documentation will be added to the Wiki page.

- DevExpress User Controls:
in order to compile the DevExpress version  [DevExpress](https://www.devexpress.com/) assemblies are required (winforms package only).

- Syncfusion User Controls:
[Syncfusion](https://www.syncfusion.com/) has open source license.

# Usage

The primary usage of this application is to implement your own data source of logs of your own business domain by implementing small Interface but there are built in data providers (like NLog parser) that can be used without and additional coding.

To implement your own custom provider check the following repositories:
- [Example Parser Project](https://github.com/Analogy-LogViewer/Analogy.LogViewer.Example) [![Build Status](https://dev.azure.com/Analogy-LogViewer/Analogy%20Log%20Viewer/_apis/build/status/Analogy-LogViewer.Analogy.LogViewer.Example?branchName=master)](https://dev.azure.com/Analogy-LogViewer/Analogy%20Log%20Viewer/_build/latest?definitionId=14&branchName=master)
- [Example Template](https://github.com/Analogy-LogViewer/Analogy.LogViewer.Template)

The interface project located at:

- [Analogy Interface Project](https://github.com/Analogy-LogViewer/Analogy.Interfaces)
[![Build Status](https://dev.azure.com/Analogy-LogViewer/Analogy%20Log%20Viewer/_apis/build/status/Analogy-LogViewer.Analogy.Interfaces?branchName=master)](https://dev.azure.com/Analogy-LogViewer/Analogy%20Log%20Viewer/_build/latest?definitionId=2&branchName=master) [![Nuget](https://img.shields.io/nuget/dt/Analogy.LogViewer.Interfaces)](https://www.nuget.org/packages/Analogy.LogViewer.Interfaces/) 
<a name="contact"></a>
## Contact

### Owner
- [Lior Banai](mailto:liorbanai@gmail.com)

## Used by the following Organizations:

[<img src="./Assets/Kama.jpg">](https://www.linkedin.com/company/kama-research-ltd/about/)
[<img src="./Assets/PhilipsShield.jpg">](https://www.philips.com/global)
