# Overview     [![Gitter](https://badges.gitter.im/Analogy-LogViewer/community.svg)](https://gitter.im/Analogy-LogViewer/community?utm_source=badge&utm_medium=badge&utm_campaign=pr-badge)  <img src="./Assets/logo128x128.jpg" align="right" width="155px" height="155px">
 Overview of projects and its repositories
 
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
- [Analogy Log Viewer (DevExpress 19.1.8 version)](https://github.com/Analogy-LogViewer/Analogy.LogViewer).
- [Analogy Log Viewer (Syncfusion version)](https://github.com/Analogy-LogViewer/Analogy.LogViewer.Syncfusion).
- [Analogy Log Viewer (Winforms version - not ready for use)](https://github.com/Analogy-LogViewer/Analogy.LogViewer.Winforms).


# Data Providers
The following  custom data providers exists:
- [Confluent's Apache Kafka .NET Producer and consumer](https://github.com/Analogy-LogViewer/Analogy.LogViewer.KafkaProvider) 
- [NLog Parser with layout customization](https://github.com/Analogy-LogViewer/Analogy.LogViewer.KafkaProvider)
- Windows event logs
- [Catel log Parser](https://github.com/Analogy-LogViewer/Analogy.LogViewer.CatelProject)
- [IIS log Parser](https://github.com/Analogy-LogViewer/Analogy.LogViewer.IISLogParser)
- [RSS Reader](https://github.com/Analogy-LogViewer/Analogy.LogViewer.RSSReader)
- and many more to follow

Data providers settings are managed in their own user setting window. Planned and existing data providers are:
![Data Providers settings screen](Assets/AnalogyDataProviders.jpg)

# Dependencies & Build
- Main Application UI is complied to .Net Framework 4.7.2 and to .Net Core 3.0.
The projects targets .Net Framework 4.7.2/Core 3.0 . The supported version of Visual studio for this framework is Visual studio 2017 (or above).
After successfull build any custom data source assemblies should be placed at the same folder as the executable (Analogy.exe) with the folowing pattern naming: Analogy.LogViewer.*.dll
- Analogy Interfaces assembly is complied to .Net Standard 2.0.

Detailed Documentation will be added to the Wiki page.

- DevExpress User Controls:
in order to compile this code [DevExpress](https://www.devexpress.com/) assemblies are required (winforms package only).


# Usage

The primary usage of this application is to implement your own data source of logs of your own business domain by implementing small Interface but there are built in data providers (like NLog parser) that can be used without and additional coding.

To implement your own custom provider check the following repositories:
- [Example Parser Project](https://github.com/Analogy-LogViewer/Analogy.LogViewer.Example)
- [Example Tamplate](https://github.com/Analogy-LogViewer/Analogy.LogViewer.Template)

The interface project located at:

- [Analogy Interface Project](https://github.com/Analogy-LogViewer/Analogy.Interfaces)
[![Build Status](https://dev.azure.com/Analogy-LogViewer/Analogy%20Log%20Viewer/_apis/build/status/Analogy-LogViewer.Analogy.Interfaces?branchName=master)](https://dev.azure.com/Analogy-LogViewer/Analogy%20Log%20Viewer/_build/latest?definitionId=2&branchName=master)
<a name="contact"></a>
## Contact

### Owner
- [Lior Banai](mailto:liorbanai@gmail.com)

