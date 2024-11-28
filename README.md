# TinyNvidiaUpdateChecker

![TNUC Logo](image.png)

TinyNvidiaUpdateChecker (TNUC for short) is a lightweight tool that checks for NVIDIA GPU drivers for Windows.

## Features

- Lightweight and modernized open sourced project
- Fully customizable driver install, allowing installing the components that are important to you, and keeping bloatware away
- [Automated update notifications](https://github.com/ElPumpo/TinyNvidiaUpdateChecker/wiki/Quiet-runs-on-user-login) with semi automatic installation
- Supports most NVIDIA GPUs (even if you don't have any drivers installed)
- Supports multi-GPU setups and eGPUs

## Dependencies

- Windows 10 or higher
- [.NET Desktop Runtime 8 x64](https://dotnet.microsoft.com/en-us/download/dotnet/8.0), it will be prompted to install if missing
- Internet connection
- (optional) WinRAR, 7-Zip or NanaZip for minimal install feature

## Installation

1. [Download the latest version](https://github.com/ElPumpo/TinyNvidiaUpdateChecker/releases)
2. Start TinyNvidiaUpdateChecker.exe
3. (Optional) Configure [execute when logging in](https://github.com/ElPumpo/TinyNvidiaUpdateChecker/wiki/Quiet-runs-on-user-login)

### Install with [Scoop](https://scoop.sh/#/apps?s=2&d=1&o=true&p=1&q=tinynvidiaupdatechecker)

```bash
scoop bucket add extras
scoop install tinynvidiaupdatechecker
```

## How to use

Be sure to [check out the wiki](https://github.com/ElPumpo/TinyNvidiaUpdateChecker/wiki) to learn more about how to use TNUC.

## Legal

### License

TinyNvidiaUpdateChecker - Check for NVIDIA GPU driver updates!

Copyright (C) 2016-present Hawaii_Beach

This program is free software: you can redistribute it And/Or modify it under the terms Of the GNU General Public License As published by the Free Software Foundation, either version 3 Of the License, Or (at your option) any later version.

This program is distributed In the hope that it will be useful, but WITHOUT ANY WARRANTY; without even the implied warranty Of MERCHANTABILITY Or FITNESS FOR A PARTICULAR PURPOSE. See the GNU General Public License For more details.

You should have received a copy Of the GNU General Public License along with this program. If Not, see <http://www.gnu.org/licenses/>.
