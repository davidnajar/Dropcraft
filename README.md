
# Dropcraft
Forked from https://github.com/Dropcraft/Dropcraft
NuGet-based deployment and application composition framework for .NET and .NET Core. The main goal of the framework is to allow an application composition directly from the NuGet packages.

[![Build status](https://ci.appveyor.com/api/projects/status/ef7mmm0cj8tgasy9/branch/master?svg=true)](https://ci.appveyor.com/project/davidnajar/dropcraft/branch/master)


## Features

 - NuGet packages deployment from the remote and local sources to a target folder
 - Runtime application composition
 - Package based application extensibility model (i.e. NuGet packages as plugins)
 - Framework extensibility via the deployment and runtime hooks 

## Roadmap

 - v0.2 - Full support for .NET 4.6.2 WPF and console applications
 - v0.4 - Full support for ASP.NET Core
 - v0.6 - Full support for .NET Core applications on Linux
 - v1.0 - Stable deployment and runtime APIs for all supported platforms 

## Documentation

 - [Introduction](http://lunarfrog.com/blog/introducing-dropcraft-nuget)
 - [API documentation](http://dropcraft.net/api/index.html)

## Build

Cake is used to build the project. On Windows run:

```powershell
./build
```
