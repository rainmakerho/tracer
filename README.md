Tracer 1.0.0
======

Tracing and logging rewriter using Fody. It adds trace enter and trace leave log entries for the methods specified. Such calls include incoming and outgoing parameters as well as time spent in the method. It also rewrites static log entries to properly configured log calls. Tracer is the rewriter core on which one of the specific adapters like Tracer.Log4Net is built uppon. Creating custom adapters for your specific needs is very easy. 
See [Wiki](https://github.com/csnemes/tracer/wiki) for details.

Should you have any question/problem send an email to csaba.nemes@outlook.com or add an issue/request.

Compatibility:
---
  - .NET Framework 4.0+

Current Release:
---
  - This is the initial production release 

To install:
---
  - using NuGet: Install-Package Tracer.Log4Net.Fody 
  - build and use the binaries

To build:
---
Use Visual Studio 2013

Version History:
---
*1.0.0 
    Initial release

Notes:
---
