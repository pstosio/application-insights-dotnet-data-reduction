---
services: application-insights
platforms: dotnet
author: SergeyKanzhelev
---

# Optimize Telemetry with Application Insights

This is a demo application for the different data reduction techniques used in Application Insights. It gives overview of 
the Application Insights domain model, how telemetry is collected, and what coding techniques are available to decrease 
the amount of telemetry while preserving monitoring capabilities, analytical accuracy, and diagnosing depth.

## Features

This demo applicaiton is a script for the MSDN magazine article [DevOps - Optimize Telemetry with Application Insights](https://msdn.microsoft.com/magazine/mt808502).

This project framework provides the following features:

* Sampling (static and adaptive)
* Metrics preaggregation
* Telemetry examplification

## Getting Started

### Prerequisites

Visual Studio 2017+

### Quickstart
Open solution in Visual Studio. Uncomment the demo you'd like to run in `Program.cs`. To view the data use Visual Studio 
Application Insights search tool.

If you want to see the data in Azure portal - change the instrumentation key in the demo code in the line: 
`configuration.InstrumentationKey = "fb8a0b03-235a-4b52-b491-307e9fd6b209";`.

## Demo

This demo applicaiton is a script for the MSDN magazine article [DevOps - Optimize Telemetry with Application Insights](https://msdn.microsoft.com/magazine/mt808502).

## Resources

- [Filtering and preprocessing telemetry in the Application Insights SDK](https://docs.microsoft.com/azure/application-insights/app-insights-api-filtering-sampling)
- [Application Insights API for custom events and metrics](https://docs.microsoft.com/azure/application-insights/app-insights-api-custom-events-metrics)
