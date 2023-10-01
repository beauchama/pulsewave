# ![logo](./assets/icons/icon-32.png) Pulsewave

![.NET7.0-version](https://img.shields.io/badge/.NET-7.0-9431ff)
![.NET8.0-version](https://img.shields.io/badge/.NET-8.0-9431ff)

Pulsewave is an efficient, well-designed, simple, and intuitive NuGet packages to be used in any .NET project such as Blazor, ASP.NET Core, Console, etc. It is designed to be split in multiple nugets, allowing developers to include only specific NuGets they need for their project.

## Setup

### Requirements

1. Install [.Net 7.0] and [.Net 8.0] SDKs to install/develop nugets
2. Install the latest version of [Visual Studio] to develop and test

> [Visual Studio Preview] is needed for .Net 8.0 until it will be released in november 2023.

### Install nugets

* In your solution, open the NuGet Package Manager and install the desired nugets
* Or use the command line `dotnet add package Pulsewave.*`

### Develop/Test

1. Clone the repository
2. `dotnet tool restore` to install/restore tools
3. Open the solution `Pulsewave.sln`
4. Run unit tests using the exploirer in Visual Studio or the command line `dotnet test`

## How to contribute

If you want to contribute to this repo, please read the [contributing guide] first.

[.Net 7.0]: https://dotnet.microsoft.com/download/dotnet/7.0
[.Net 8.0]: https://dotnet.microsoft.com/download/dotnet/8.0
[Visual Studio]: https://visualstudio.microsoft.com/vs/community/
[Visual Studio Preview]: https://visualstudio.microsoft.com/vs/preview/
[contributing guide]: https://github.com/beauchama/pulsewave/blob/main/.github/contributing.md
