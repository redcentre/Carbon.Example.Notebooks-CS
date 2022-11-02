## Overview

This repository contains C# interactive notebooks that demonstrate how to use the Carbon cross-tabulation library API. The notebooks can be opened by [Visual Studio Code][vscode] and they provide a rich interactive experience using a mixture of code and formatted commentary text.

C# interactive notebooks can be used for educational purposes, and they can used to compose and run production quality data processing scripts.

Many [introductory Videos][vsintro] about Visual Studio Code are available online.

The numbered prefixes on the file names are a hint to the order in which they should be used as tutorials about the Carbon API.

---

## Tutorial Notebooks

### :blue_book: 01 Simple Reports

Shows the minimum code required to generate a simple cross-tabulation report in comma separated format. It explains the *boilerplate* code that is normally at the start and end of Carbon library processing.

### :blue_book: 02 Report to DataFrame and Bar Chart
 
Generates a report as a [DataFrame][msdf] which is input to the [Plotly.NET][plotly] library to create a bar chart.

### :blue_book: 03 Report to DataFrame and Line Chart
 
A more sophisticated example similar to example 02. A larger report is passed through a DataFrame into [Plotly.NET][plotly] to create a line chart.

### :blue_book: 10 Simple Web Service Report

Generates a cross-tabulation report through calls to the [Carbon web service][carbsrv] ![PDF icon][pdf16]. This demonstrates how the Carbon libraries can be hosted in a web service that provides job management and cross-tabulation reporting facilities to remote clients.

## Other Notebooks

### :blue_book: Carbon Scripting Document Samples

This stand-alone notebook contains the sets of sample code in the [Carbon Scripting][scriptpdf] ![PDF icon][pdf16] PDF which is distributed as part of the Red Centre Software [standard installation folders][rcsinst] ![PDF icon][pdf16].


[vscode]: https://code.visualstudio.com/
[vsintro]: https://code.visualstudio.com/docs/getstarted/introvideos
[msdf]: https://learn.microsoft.com/en-us/dotnet/api/microsoft.data.analysis.dataframe
[plotly]: https://plotly.net/
[scriptpdf]: https://rcsapps.azurewebsites.net/doc/carbon/Carbon%20Scripting.pdf
[rcsinst]: https://rcsapps.azurewebsites.net/doc/carbon/Introduction%20to%20the%20RedCentre%20Carbon%20Libraries%20and%20Applications.pdf
[pdf16]: https://systemrcs.blob.core.windows.net/wiki-images/pdf16.png
[carbsrv]: https://rcsapps.azurewebsites.net/doc/carbon/articles/carbon-webapi.htm