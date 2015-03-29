# IW4LAN

[![Build status](https://ci.appveyor.com/api/projects/status/qfcle1nxvwmpbq9i?svg=true)](https://ci.appveyor.com/project/win32re/iw4lan)

Open source IW4 modification project which brings an offline mode to the game.

## Build instructions

> Building with Visual Studio versions older than Visual Studio 2013 is not supported.

### Requirements

* Git
* Microsoft Visual Studio 2013

### Clone the repository

```
git clone https://github.com/twizre/iw4lan.git
cd iw4lan
```

### Set up Premake

1. Download the latest Premake nightly build from [here](http://www.mirrorservice.org/sites/ftp.sourceforge.net/pub/sourceforge/p/pr/premake/Premake/nightlies/premake-dev-windows.zip).
2. Extract `premake5.exe` to the directory you cloned this repository to.

### Generate project files

```
cd iw4lan
premake5 vs2013
```

### Build the project

1. Open the project folder and open `iw4cli.sln`.
2. Build the project using Visual Studio 2013.
