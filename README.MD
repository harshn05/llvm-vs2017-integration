 # LLVM 6.0.0 Visual Studio 2017 Integration

This is a forked version of llvm-vs2017-integration which is updated for LLVM 6.0.0 and provides better integration by providing include and library paths of LLVM/clang.

Thanks to Royi for realizing that the library paths should be updated from `5.0` to `6.0.0`.

### Automatic Installation

Open a command prompt with Administrator rights (DO NOT OPEN AutoSetup.bat with admin rights it won't load the files)

Go to the folder where AutoSetup.bat exists and type "AutoSetup"

### Manual Installation (If Automatic doesn't work)

Go to "[Your Visual Studio Installation Directory]\Common7\IDE\VC\VCTargets\Platforms"

##### Performing x86 Toolset installation
- Go to Win32\PlatformToolset
- Create 2 folders called LLVM-vs2017 and LLVM-vs2017_xp
- Go to LLVM-vs2017
- Copy all files that starts with Toolset-llvm-vs2017-x86
- Rename the name of all this files (not the extensions) into Toolset
- Now go to LLVM-vs2017_xp
- Copy all files that starts with Toolset-llvm-vs2017-xp-x86
- Rename the name of all this files (not the extensions) into Toolset

##### Performing x64 Toolset installation
- Go to x64\PlatformToolset
- Create 2 folders called LLVM-vs2017 and LLVM-vs2017_xp
- Go to LLVM-vs2017
- Copy all files that starts with Toolset-llvm-vs2017-x64
- Rename the name of all this files (not the extensions) into Toolset
- Now go to LLVM-vs2017_xp
- Copy all files that starts with Toolset-llvm-vs2017-xp-x64
- Rename the name of all this files (not the extensions) into Toolset

### LICENSE

Released under Uol-NCSA (Same license as LLVM)
