# CodeOfChaos.Extensions

`CodeOfChaos.Extensions` is a multi-package .NET repository with reusable extension libraries, Roslyn analyzers/generators, examples, tests, and benchmarks.

## Prerequisites

- [.NET SDK 11.0.100](https://dotnet.microsoft.com/download) (pinned in `global.json`; required to build)
- .NET 10 SDK/runtime (the test suite also runs against `net10.0`, so the 10.0 runtime must be installed alongside the 11.0 runtime)

Supported target frameworks for the shipped libraries and tests: `net10.0` (LTS) and `net11.0` (STS).
Benchmark, example and tooling projects single-target `net11.0`; the Roslyn analyzer/generator packages target `netstandard2.0`.

## Repository Layout

- `src/CodeOfChaos.Extensions`: Core extension utilities
- `src/CodeOfChaos.Extensions.Analyzers`: Roslyn analyzers
- `src/CodeOfChaos.Extensions.AspNetCore`: ASP.NET Core extensions
- `src/CodeOfChaos.Extensions.AspNetCore.Components`: Blazor/component extensions
- `src/CodeOfChaos.Extensions.DependencyInjection`: DI helpers
- `src/CodeOfChaos.Extensions.DependencyInjection.Generators`: Source generators for DI
- `src/CodeOfChaos.Extensions.EntityFrameworkCore`: Entity Framework Core extensions
- `src/CodeOfChaos.Extensions.FluentValidation`: FluentValidation extensions
- `src/CodeOfChaos.Extensions.MicrosoftLogging`: Microsoft.Extensions.Logging helpers
- `src/CodeOfChaos.Extensions.ObjectPool`: ObjectPool extensions
- `src/CodeOfChaos.Extensions.Serilog`: Serilog extensions
