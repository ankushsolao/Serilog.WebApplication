# Serilog.WebApplication
   Serilog is a third-party logging library that plugs into the default ILogger of our application with its own implementations.It is easy to set up, has a clean API, and runs on all recent .NET platforms. While it's useful even in the simplest applications, Serilog's support for structured logging shines when instrumenting complex, distributed, and asynchronous applications and systems. It enables the developers to log the events into various destinations like console, file, database, and more.

   ### Install these following packages to your web application project via the Package Manager Console.

* Install-Package Serilog.AspNetCore
* Install-Package Serilog.Settings.Configuration
* Install-Package Serilog.Enrichers.Environment
* Install-Package Serilog.Enrichers.Process
* Install-Package Serilog.Enrichers.Thread
* Install-Package Serilog.Sinks.MSSqlServer
