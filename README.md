# ![logo][] PowerShell

Welcome to the PowerShell GitHub Community!
PowerShell Core is a cross-platform (Windows, Linux, and macOS) automation and configuration tool/framework that works well with your existing tools and is optimized
for dealing with structured data (e.g. JSON, CSV, XML, etc.), REST APIs, and object models.
It includes a command-line shell, an associated scripting language and a framework for processing cmdlets.

[logo]: https://raw.githubusercontent.com/PowerShell/PowerShell/master/assets/ps_black_64.svg?sanitize=true

## Windows PowerShell vs. PowerShell Core

Although this repository started as a fork of the Windows PowerShell code base, changes made in this repository do not make their way back to Windows PowerShell 5.1 automatically.
This also means that [issues tracked here][issues] are only for PowerShell Core 6 and higher.
Windows PowerShell specific issues should be reported with the [Feedback Hub app][feedback-hub], by choosing "Apps > PowerShell" in category.

[issues]: https://github.com/PowerShell/PowerShell/issues
[feedback-hub]: https://support.microsoft.com/windows/send-feedback-to-microsoft-with-the-feedback-hub-app-f59187f8-8739-22d6-ba93-f66612949332

## New to PowerShell?

If you are new to PowerShell and would like to learn more, we recommend reviewing the [getting started][] documentation.

[getting started]: https://github.com/PowerShell/PowerShell/tree/master/docs/learning-powershell

## Get PowerShell

You can download and install a PowerShell package for any of the following platforms.

| Supported Platform                         | Download (LTS)          | Downloads (stable)      | Downloads (preview)   | How to Install                |
| -------------------------------------------| ------------------------| ------------------------| ----------------------| ------------------------------|
| [Windows (x64)][corefx-win]                | [.msi][lts-windows-64]  | [.msi][rl-windows-64]   | [.msi][pv-windows-64] | [Instructions][in-windows]    |
| [Windows (x86)][corefx-win]                | [.msi][lts-windows-86]  | [.msi][rl-windows-86]   | [.msi][pv-windows-86] | [Instructions][in-windows]    |
| [Ubuntu 20.04][corefx-linux]               |                         | [.deb][rl-ubuntu20]     | [.deb][pv-deb]        | [Instructions][in-ubuntu20]   |
| [Ubuntu 18.04][corefx-linux]               | [.deb][lts-ubuntu18]    | [.deb][rl-ubuntu18]     | [.deb][pv-deb]        | [Instructions][in-ubuntu18]   |
| [Ubuntu 16.04][corefx-linux]               | [.deb][lts-ubuntu16]    | [.deb][rl-ubuntu16]     | [.deb][pv-deb]        | [Instructions][in-ubuntu16]   |
| [Debian 9][corefx-linux]                   | [.deb][lts-debian9]     | [.deb][rl-debian9]      | [.deb][pv-deb]        | [Instructions][in-deb9]       |
| [Debian 10][corefx-linux]                  | [.deb][lts-debian10]    | [.deb][rl-debian10]     | [.deb][pv-deb]        | [Instructions][in-deb9]       |
| [Debian 11][corefx-linux]                  |                         | [.deb][rl-debian11]     | [.deb][pv-deb]        |                               |
| [CentOS 7][corefx-linux]                   | [.rpm][lts-centos]      | [.rpm][rl-centos]       | [.rpm][pv-rpm]        | [Instructions][in-centos]     |
| [CentOS 8][corefx-linux]                   | [.rpm][lts-centos8]     | [.rpm][rl-centos8]      | [.rpm][pv-rpm]        |                               |
| [Red Hat Enterprise Linux 7][corefx-linux] | [.rpm][lts-centos]      | [.rpm][rl-centos]       | [.rpm][pv-rpm]        | [Instructions][in-rhel7]      |
| [openSUSE 42.3][corefx-linux]              | [.rpm][lts-centos]      | [.rpm][rl-centos]       | [.rpm][pv-rpm]        | [Instructions][in-opensuse]   |
| [Fedora 30][corefx-linux]                  | [.rpm][lts-centos]      | [.rpm][rl-centos]       | [.rpm][pv-rpm]        | [Instructions][in-fedora]     |
| [macOS 10.13+ (x64)][corefx-macos]         | [.pkg][lts-macos]       | [.pkg][rl-macos]        | [.pkg][pv-macos]      | [Instructions][in-macos]      |
| [macOS 10.13+ (arm64)][corefx-macos]       |                         |                         | [.pkg][pv-macos-arm64]| [Instructions][in-macos]      |
| Docker                                     |                         |                         |                       | [Instructions][in-docker]     |

You can download and install a PowerShell package for any of the following platforms, **which are supported by the community.**

| Platform                 | Downloads (stable)      | Downloads (preview)           | How to Install                |
| -------------------------| ------------------------| ----------------------------- | ------------------------------|
| Arch Linux               |                         |                               | [Instructions][in-archlinux]  |
| Kali Linux               | [.deb][rl-ubuntu16]     | [.deb][pv-deb]           | [Instructions][in-kali]       |
| Many Linux distributions | [Snapcraft][rl-snap]    | [Snapcraft][pv-snap]          |                               |

You can also download the PowerShell binary archives for Windows, macOS and Linux.

| Platform       | Downloads (stable)                                  | Downloads (preview)                             | How to Install                                 |
| ---------------| --------------------------------------------------- | ------------------------------------------------| -----------------------------------------------|
| Windows        | [32-bit][rl-winx86-zip]/[64-bit][rl-winx64-zip]     | [32-bit][pv-winx86-zip]/[64-bit][pv-winx64-zip] | [Instructions][in-windows-zip]                 |
| macOS          | [64-bit][rl-macos-tar]                              | [64-bit][pv-macos-tar]                          | [Instructions][in-tar-macos]                   |
| macOS          |                                                     | [64-bit][pv-macos-tar-arm64]                    | [Instructions][in-tar-macos]                   |
| Linux          | [64-bit][rl-linux-tar]                              | [64-bit][pv-linux-tar]                          | [Instructions][in-tar-linux]                   |
| Windows (Arm)  | [64-bit][rl-winarm64] (preview)                     | [64-bit][pv-winarm64]                           | [Instructions][in-arm]                         |
| Raspbian (Arm) | [32-bit][rl-arm32]/[64-bit][rl-arm64]               | [32-bit][pv-arm32]/[64-bit][pv-arm64]           | [Instructions][in-raspbian]                    |

[lts-windows-86]: https://github.com/PowerShell/PowerShell/releases/download/v7.0.7/PowerShell-7.0.7-win-x86.msi
[lts-windows-64]: https://github.com/PowerShell/PowerShell/releases/download/v7.0.7/PowerShell-7.0.7-win-x64.msi
[lts-ubuntu18]: https://github.com/PowerShell/PowerShell/releases/download/v7.0.7/powershell-lts_7.0.7-1.ubuntu.18.04_amd64.deb
[lts-ubuntu16]: https://github.com/PowerShell/PowerShell/releases/download/v7.0.7/powershell-lts_7.0.7-1.ubuntu.16.04_amd64.deb
[lts-debian9]: https://github.com/PowerShell/PowerShell/releases/download/v7.0.7/powershell-lts_7.0.7-1.debian.9_amd64.deb
[lts-debian10]: https://github.com/PowerShell/PowerShell/releases/download/v7.0.7/powershell-lts_7.0.7-1.debian.10_amd64.deb
[lts-centos]: https://github.com/PowerShell/PowerShell/releases/download/v7.0.7/powershell-lts-7.0.7-1.rhel.7.x86_64.rpm
[lts-centos8]: https://github.com/PowerShell/PowerShell/releases/download/v7.0.7/powershell-lts-7.0.7-1.centos.8.x86_64.rpm
[lts-macos]: https://github.com/PowerShell/PowerShell/releases/download/v7.0.7/powershell-lts-7.0.7-osx-x64.pkg

[rl-windows-64]: https://github.com/PowerShell/PowerShell/releases/download/v7.1.4/PowerShell-7.1.4-win-x64.msi
[rl-windows-86]: https://github.com/PowerShell/PowerShell/releases/download/v7.1.4/PowerShell-7.1.4-win-x86.msi
[rl-ubuntu20]: https://github.com/PowerShell/PowerShell/releases/download/v7.1.4/powershell_7.1.4-1.ubuntu.20.04_amd64.deb
[rl-ubuntu18]: https://github.com/PowerShell/PowerShell/releases/download/v7.1.4/powershell_7.1.4-1.ubuntu.18.04_amd64.deb
[rl-ubuntu16]: https://github.com/PowerShell/PowerShell/releases/download/v7.1.4/powershell_7.1.4-1.ubuntu.16.04_amd64.deb
[rl-debian9]: https://github.com/PowerShell/PowerShell/releases/download/v7.1.4/powershell_7.1.4-1.debian.9_amd64.deb
[rl-debian10]: https://github.com/PowerShell/PowerShell/releases/download/v7.1.4/powershell_7.1.4-1.debian.10_amd64.deb
[rl-debian11]: https://github.com/PowerShell/PowerShell/releases/download/v7.1.4/powershell_7.1.4-1.debian.11_amd64.deb
[rl-centos]: https://github.com/PowerShell/PowerShell/releases/download/v7.1.4/powershell-7.1.4-1.rhel.7.x86_64.rpm
[rl-centos8]: https://github.com/PowerShell/PowerShell/releases/download/v7.1.4/powershell-7.1.4-1.centos.8.x86_64.rpm
[rl-macos]: https://github.com/PowerShell/PowerShell/releases/download/v7.1.4/powershell-7.1.4-osx-x64.pkg
[rl-winarm64]: https://github.com/PowerShell/PowerShell/releases/download/v7.1.4/PowerShell-7.1.4-win-arm64.zip
[rl-winx86-zip]: https://github.com/PowerShell/PowerShell/releases/download/v7.1.4/PowerShell-7.1.4-win-x86.zip
[rl-winx64-zip]: https://github.com/PowerShell/PowerShell/releases/download/v7.1.4/PowerShell-7.1.4-win-x64.zip
[rl-macos-tar]: https://github.com/PowerShell/PowerShell/releases/download/v7.1.4/powershell-7.1.4-osx-x64.tar.gz
[rl-linux-tar]: https://github.com/PowerShell/PowerShell/releases/download/v7.1.4/powershell-7.1.4-linux-x64.tar.gz
[rl-arm32]: https://github.com/PowerShell/PowerShell/releases/download/v7.1.4/powershell-7.1.4-linux-arm32.tar.gz
[rl-arm64]: https://github.com/PowerShell/PowerShell/releases/download/v7.1.4/powershell-7.1.4-linux-arm64.tar.gz
[rl-snap]: https://snapcraft.io/powershell

[pv-windows-64]: https://github.com/PowerShell/PowerShell/releases/download/v7.2.0-preview.8/PowerShell-7.2.0-preview.8-win-x64.msi
[pv-windows-86]: https://github.com/PowerShell/PowerShell/releases/download/v7.2.0-preview.8/PowerShell-7.2.0-preview.8-win-x86.msi
[pv-deb]: https://github.com/PowerShell/PowerShell/releases/download/v7.2.0-preview.8/powershell-preview_7.2.0-preview.8-1.deb_amd64.deb
[pv-rpm]: https://github.com/PowerShell/PowerShell/releases/download/v7.2.0-preview.8/powershell-preview-7.2.0_preview.8-1.rh.x86_64.rpm
[pv-macos]: https://github.com/PowerShell/PowerShell/releases/download/v7.2.0-preview.8/powershell-7.2.0-preview.8-osx-x64.pkg
[pv-macos-arm64]: https://github.com/PowerShell/PowerShell/releases/download/v7.2.0-preview.8/powershell-7.2.0-preview.8-osx-arm64.pkg
[pv-winarm64]: https://github.com/PowerShell/PowerShell/releases/download/v7.2.0-preview.8/PowerShell-7.2.0-preview.8-win-arm64.zip
[pv-winx86-zip]: https://github.com/PowerShell/PowerShell/releases/download/v7.2.0-preview.8/PowerShell-7.2.0-preview.8-win-x86.zip
[pv-winx64-zip]: https://github.com/PowerShell/PowerShell/releases/download/v7.2.0-preview.8/PowerShell-7.2.0-preview.8-win-x64.zip
[pv-macos-tar]: https://github.com/PowerShell/PowerShell/releases/download/v7.2.0-preview.8/powershell-7.2.0-preview.8-osx-x64.tar.gz
[pv-macos-tar-arm64]: https://github.com/PowerShell/PowerShell/releases/download/v7.2.0-preview.8/powershell-7.2.0-preview.8-osx-arm64.tar.gz
[pv-linux-tar]: https://github.com/PowerShell/PowerShell/releases/download/v7.2.0-preview.8/powershell-7.2.0-preview.8-linux-x64.tar.gz
[pv-arm32]: https://github.com/PowerShell/PowerShell/releases/download/v7.2.0-preview.8/powershell-7.2.0-preview.8-linux-arm32.tar.gz
[pv-arm64]: https://github.com/PowerShell/PowerShell/releases/download/v7.2.0-preview.8/powershell-7.2.0-preview.8-linux-arm64.tar.gz
[pv-snap]: https://snapcraft.io/powershell-preview

[in-windows]: https://docs.microsoft.com/powershell/scripting/install/installing-powershell-core-on-windows
[in-ubuntu16]: https://docs.microsoft.com/powershell/scripting/install/installing-powershell-core-on-linux#ubuntu-1604
[in-ubuntu18]: https://docs.microsoft.com/powershell/scripting/install/installing-powershell-core-on-linux#ubuntu-1804
[in-ubuntu20]: https://docs.microsoft.com/powershell/scripting/install/installing-powershell-core-on-linux#ubuntu-2004
[in-deb9]: https://docs.microsoft.com/powershell/scripting/install/installing-powershell-core-on-linux#debian-9
[in-deb10]: https://docs.microsoft.com/powershell/scripting/install/installing-powershell-core-on-linux#debian-10
[in-centos]: https://docs.microsoft.com/powershell/scripting/install/installing-powershell-core-on-linux#centos-7
[in-rhel7]: https://docs.microsoft.com/powershell/scripting/install/installing-powershell-core-on-linux#red-hat-enterprise-linux-rhel-7
[in-opensuse]: https://docs.microsoft.com/powershell/scripting/install/installing-powershell-core-on-linux#opensuse
[in-fedora]: https://docs.microsoft.com/powershell/scripting/install/installing-powershell-core-on-linux#fedora
[in-archlinux]: https://docs.microsoft.com/powershell/scripting/install/installing-powershell-core-on-linux#arch-linux
[in-macos]: https://docs.microsoft.com/powershell/scripting/install/installing-powershell-core-on-macos
[in-docker]: https://github.com/PowerShell/PowerShell-Docker
[in-kali]: https://docs.microsoft.com/powershell/scripting/install/installing-powershell-core-on-linux#kali
[in-windows-zip]: https://docs.microsoft.com/powershell/scripting/install/installing-powershell-core-on-windows#zip
[in-tar-linux]: https://docs.microsoft.com/powershell/scripting/install/installing-powershell-core-on-linux#binary-archives
[in-tar-macos]: https://docs.microsoft.com/powershell/scripting/install/installing-powershell-core-on-macos#binary-archives
[in-raspbian]: https://docs.microsoft.com/powershell/scripting/install/installing-powershell-core-on-linux#raspbian
[in-arm]: https://docs.microsoft.com/powershell/scripting/install/powershell-core-on-arm
[corefx-win]:https://github.com/dotnet/core/blob/master/release-notes/3.0/3.0-supported-os.md#windows
[corefx-linux]:https://github.com/dotnet/core/blob/master/release-notes/3.0/3.0-supported-os.md#linux
[corefx-macos]:https://github.com/dotnet/core/blob/master/release-notes/3.0/3.0-supported-os.md#macos

To install a specific version, visit [releases](https://github.com/PowerShell/PowerShell/releases).

## Community Dashboard

[Dashboard](https://aka.ms/psgithubbi) with visualizations for community contributions and project status using PowerShell, Azure, and PowerBI.

For more information on how and why we built this dashboard, check out this [blog post](https://devblogs.microsoft.com/powershell/powershell-open-source-community-dashboard/).

## Discussions

[GitHub Discussions](https://docs.github.com/en/free-pro-team@latest/discussions/quickstart) is a feature to enable fluid and open discussions within the community
for topics that are not related to code, unlike issues.

This is an experiment we are trying in our repositories to see if it helps move discussions out of issues so that issues remain actionable by the team or members of the community.
There should be no expectation that PowerShell team members are regular participants in the discussions.
Individual PowerShell team members may choose to participate in discussions, but the expectation is that community members help drive discussions so that team members
can focus on issues.

Create or join a [discussion](https://github.com/PowerShell/PowerShell/discussions).

## Chat

Want to chat with other members of the PowerShell community?

There are dozens of topic specific channels on our community-driven PowerShell Virtual User Group, which you can join on:

* [Gitter](https://gitter.im/PowerShell/PowerShell)
* [Discord](https://discord.gg/PowerShell)
* [IRC](https://web.libera.chat/#powershell) on Libera.Chat
* [Slack](https://aka.ms/psslack)

## Add-ons and libraries

[Awesome PowerShell](https://github.com/janikvonrotz/awesome-powershell) has a great curated list of add-ons and resources.

## Building the Repository

| Linux                    | Windows                    | macOS                   |
|--------------------------|----------------------------|------------------------|
| [Instructions][bd-linux] | [Instructions][bd-windows] | [Instructions][bd-macOS] |

If you have any problems building, please consult the developer [FAQ][].

### Build status of nightly builds

| Azure CI (Windows)                       | Azure CI (Linux)                               | Azure CI (macOS)                               | Code Coverage Status     | CodeFactor Grade         |
|:-----------------------------------------|:-----------------------------------------------|:-----------------------------------------------|:-------------------------|:-------------------------|
| [![windows-nightly-image][]][windows-nightly-site] | [![linux-nightly-image][]][linux-nightly-site] | [![macOS-nightly-image][]][macos-nightly-site] | [![cc-image][]][cc-site] | [![cf-image][]][cf-site] |

[bd-linux]: https://github.com/PowerShell/PowerShell/tree/master/docs/building/linux.md
[bd-windows]: https://github.com/PowerShell/PowerShell/tree/master/docs/building/windows-core.md
[bd-macOS]: https://github.com/PowerShell/PowerShell/tree/master/docs/building/macos.md

[FAQ]: https://github.com/PowerShell/PowerShell/tree/master/docs/FAQ.md

[windows-nightly-site]: https://powershell.visualstudio.com/PowerShell/_build?definitionId=32
[linux-nightly-site]: https://powershell.visualstudio.com/PowerShell/_build?definitionId=23
[macos-nightly-site]: https://powershell.visualstudio.com/PowerShell/_build?definitionId=24
[windows-nightly-image]: https://powershell.visualstudio.com/PowerShell/_apis/build/status/PowerShell-CI-Windows-daily
[linux-nightly-image]: https://powershell.visualstudio.com/PowerShell/_apis/build/status/PowerShell-CI-linux-daily?branchName=master
[macOS-nightly-image]: https://powershell.visualstudio.com/PowerShell/_apis/build/status/PowerShell-CI-macos-daily?branchName=master
[cc-site]: https://codecov.io/gh/PowerShell/PowerShell
[cc-image]: https://codecov.io/gh/PowerShell/PowerShell/branch/master/graph/badge.svg
[cf-site]: https://www.codefactor.io/repository/github/powershell/powershell
[cf-image]: https://www.codefactor.io/repository/github/powershell/powershell/badge

## Downloading the Source Code

You can just clone the repository:

```sh
git clone https://github.com/PowerShell/PowerShell.git
```

See [working with the PowerShell repository](https://github.com/PowerShell/PowerShell/tree/master/docs/git) for more information.

## Developing and Contributing

Please see the [Contribution Guide][] for how to develop and contribute.
If you are developing .NET Core C# applications targeting PowerShell Core, please [check out our FAQ][] to learn more about the PowerShell SDK NuGet package.

Also, make sure to check out our [PowerShell-RFC repository](https://github.com/powershell/powershell-rfc) for request-for-comments (RFC) documents to submit and give comments on proposed and future designs.

[Contribution Guide]: https://github.com/PowerShell/PowerShell/blob/master/.github/CONTRIBUTING.md
[check out our FAQ]: https://github.com/PowerShell/PowerShell/tree/master/docs/FAQ.md#where-do-i-get-the-powershell-core-sdk-package

## Support

For support, please see the [Support Section][].

[Support Section]: https://github.com/PowerShell/PowerShell/tree/master/.github/SUPPORT.md

## Legal and Licensing

PowerShell is licensed under the [MIT license][].

[MIT license]: https://github.com/PowerShell/PowerShell/tree/master/LICENSE.txt

### Windows Docker Files and Images

License: By requesting and using the Container OS Image for Windows containers, you acknowledge, understand, and consent to the Supplemental License Terms available on Docker Hub:

- [Windows Server Core](https://hub.docker.com/r/microsoft/windowsservercore/)
- [Nano Server](https://hub.docker.com/r/microsoft/nanoserver/)

### Telemetry

By default, PowerShell collects the OS description and the version of PowerShell (equivalent to `$PSVersionTable.OS` and `$PSVersionTable.GitCommitId`) using [Application Insights](https://azure.microsoft.com/services/application-insights/).
To opt-out of sending telemetry, create an environment variable called `POWERSHELL_TELEMETRY_OPTOUT` set to a value of `1` before starting PowerShell from the installed location.
The telemetry we collect falls under the [Microsoft Privacy Statement](https://privacy.microsoft.com/privacystatement/).

## Governance

The governance policy for the PowerShell project is described [here][].

[here]: https://github.com/PowerShell/PowerShell/blob/master/docs/community/governance.md

## [Code of Conduct][conduct-md]

This project has adopted the [Microsoft Open Source Code of Conduct][conduct-code].
For more information see the [Code of Conduct FAQ][conduct-FAQ] or contact [opencode@microsoft.com][conduct-email] with any additional questions or comments.

[conduct-code]: https://opensource.microsoft.com/codeofconduct/
[conduct-FAQ]: https://opensource.microsoft.com/codeofconduct/faq/
[conduct-email]: mailto:opencode@microsoft.com
[conduct-md]: https://github.com/PowerShell/PowerShell/tree/master/CODE_OF_CONDUCT.md
