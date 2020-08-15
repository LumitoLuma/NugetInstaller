**Attention! This documentation is currently outdated, so there are steps that may vary with the real result**
## About NuGet Installer
NuGet Installer is a command-line installer that installs the latest version of NuGet.exe into your system. You may notice while you use NuGet that you always need to move the `nuget.exe` file every time you want to use it. To solve this problem, I wrote this software, NuGet Installer, so nuget.exe installs directly to C:\Windows folder, so you do not need to copy it every time you want to run it.

## Building source code
### Requirements
-   Visual Studio or Microsoft .NET Framework

### Procedure
1.  `git clone` or download this repository.

2.  Open `cmd.exe` (or Developer Command Prompt if you are using Visual Studio) in the folder you have extracted the files.

3.  Run:

    ```batch
    msbuild.exe NuGetInstaller.sln /m /p:Configuration=Release /p:Platform="Any CPU"
    ```

4.  Check `bin\Release` folder and enjoy NuGet Installer!

## Badges
[![.NET Framework (Windows)](https://github.com/LumitoLuma/NuGetInstaller/workflows/.NET%20Framework%20(Windows)/badge.svg)](https://github.com/LumitoLuma/NuGetInstaller/actions?query=workflow%3A%22.NET+Framework+%28Windows%29%22) [![Build status](https://ci.appveyor.com/api/projects/status/bkdtonymj7ayhm2h?svg=true)](https://ci.appveyor.com/project/LumitoLuma/NuGetInstaller) [![Build Status](https://dev.azure.com/LumitoLuma/GitHub/_apis/build/status/LumitoLuma.NuGetInstaller?branchName=master)](https://dev.azure.com/LumitoLuma/GitHub/_build/latest?definitionId=14&branchName=master) [![Build Status](https://travis-ci.com/LumitoLuma/NuGetInstaller.svg?branch=master)](https://travis-ci.com/LumitoLuma/NuGetInstaller) [![Codacy Badge](https://app.codacy.com/project/badge/Grade/8dff8f4225114d29bc7d7c31c4a0ff42)](https://www.codacy.com/manual/LumitoLuma/NuGetInstaller?utm_source=github.com&amp;utm_medium=referral&amp;utm_content=LumitoLuma/NugetInstaller&amp;utm_campaign=Badge_Grade) [![.NET Framework (Mono)](https://github.com/LumitoLuma/NuGetInstaller/workflows/.NET%20Framework%20(Mono)/badge.svg)](https://github.com/LumitoLuma/NuGetInstaller/actions?query=workflow%3A%22.NET+Framework+%28Mono%29%22)

## Downloading compiled version of NuGet Installer
You can download a compiled version of NuGet Installer through Releases tab.

[![Download now!](https://img.shields.io/badge/Download-now-green.svg?style=flat-square)](https://github.com/LumitoLuma/NuGetInstaller/releases)

## Contributing to the project
If you want to contribute to the project, please contact me through [lumito.net/contact](https://lumito.net/contact) or open a Pull Request.

You can contribute with the following things:

-   Code improvements
-   Ideas for future programs / services.

Reporting bugs at the contact form is not allowed, unless you have reported them through [Issues](https://github.com/LumitoLuma/NuGetInstaller/issues) tab and you have not received any comments for a while (minimum a week).

## Acknowledgements
I would like to thank Microsoft for developing the amazing NuGet package manager, which is available through [www.nuget.org](https://www.nuget.org).

© 2010 - 2020, Microsoft Corporation
<br><br>
**© 2020, Lumito - [www.lumito.net](https://lumito.net)**
