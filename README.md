
This fork has been updated to target dotnet 5 and the Microsoft.Data.SqlClient dependency:

Build instructions
```
cd src\System.Windows.Forms.DataVisualization
dotnet build -c Release ChartWin.csproj
nuget pack ./ChartWin.nuspec -Properties Configuration=Release -version 1.0.0
```


# ⚠️ **This repo is read-only** ⚠️
We consider the `System.Windows.Forms.DataVisualization` deprecated and we only provide it to ease porting to .NET Core 3. We're not going to innovate in this component and subsequently will not accept any issues and/or PRs.
You're welcome to fork the source, and update it as you see fit.


# Data Visualization

This repository contains partial source code of the `System.Windows.Forms.DataVisualization` namespace that provides charting for WinForms. We ported and open sourced those components to enable charting features for WinForms applications that are developed on .NET Core 3.


## Getting started with Chart Controls

The best way to learn about Chart Controls is by looking at the [sample solution](https://github.com/dotnet/winforms-datavisualization/tree/master/sample) where via interactive experience with the app you can learn about every chart type and every major feature. While modifying the control parameters and instantly seeing how that affects the look of the control, you can also get the generated C# or Visual Basic code to use in your apps.

![Chart Controls](sample-screenshot.png)

There is also a [.NET Framework version](https://code.msdn.microsoft.com/Windows-Forms-Samples-26bf2a53) of this sample available on Microsoft samples portal.

Pre-release version of this package is available from [NuGet Gallery](https://www.nuget.org/packages/System.Windows.Forms.DataVisualization)
