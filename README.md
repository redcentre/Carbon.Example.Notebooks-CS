## Overview

This repository contains C# interactive notebooks that demonstrate how to use the Carbon cross-tabulation library API. The notebooks can be opened by [Visual Studio Code][vscode] and they provide a rich interactive experience using a mixture of code and formatted commentary text.

C# interactive notebooks can be used for educational purposes, and they can used to compose and run production quality data processing scripts.

Many [introductory Videos][vsintro] are available online.

The notebook file names have numbered prefixes as a hint to the order in which they should be used as tutorials about the Carbon API.

---

## Sample Notebooks

### 01 Simple Reports

Shows the minimum code required to generate a simple cross-tabulation report in comma separated format. It explains the *boilerplate* code that is normally at the start and end of Carbon library processing.

### 02 Report to DataFrames and Chart
 
Generates a report as a [DataFrame][msdf] which is input to the [Plotly.NET][plotly] library to generate attractive charts.

### 10 Simple Plutonium Report

Generates a cross-tabulation report through calls to the [Plutonium web service][plutswag]. This demonstrates how the Carbon libraries can be hosted in a web service that provides job management and cross-tabulation reporting facilities to remote clients.

[vscode]: https://code.visualstudio.com/
[vsintro]: https://code.visualstudio.com/docs/getstarted/introvideos
[msdf]: https://learn.microsoft.com/en-us/dotnet/api/microsoft.data.analysis.dataframe
[plotly]: https://plotly.net/
[plutswag]: https://rcsapps.azurewebsites.net/plutonium/swagger/