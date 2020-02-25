# RegexTestBench
Cross-platform regex testing tool in .NET Core
![](https://github.com/CommonLoon102/RegexTestBench/blob/master/image/screenshot.png?raw=true)
# Running
## Windows
 - Start the app with `RegexTestBench.Wpf.exe`
## Linux
 - Install the .NET Core Runtime
 - Start the app from the terminal with `dotnet RegexTestBench.Gtk.dll`
# Compiling
## Windows
 - Download and open the repo in Visual Studio 2019
 - Publish `RegexTestBench.Wpf`
## Linux
- Install the .NET Core SDK
- You need to have GTK3 installed too
- Git clone
- Publish with `dotnet publish RegexTestBench/RegexTestBench.Gtk/RegexTestBench.Gtk.csproj --configuration Release --output publish --self-contained false --runtime linux-x64 --framework netcoreapp3.1`
