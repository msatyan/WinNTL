# WinNTL
Visual Studio 2017 Project file to build NTL library from its IDE

### Why 
NTL is a nice Library for doing Number Theory. If you try to build it on Windows you may face difficulty. Most of the information you find it on internet (and also the NTL documentation) may guide you to install Cygwin or MinGW. Though these approaches certainly work. If you are a developer on Windows platform chances are you may be using modern tool like Visual Studio etc and you prefer to use it for building and debugging your C/C++ code. 


### Setup
Download the source ZIP file of NTL (say WinNTL-10_5_0.zip) from http://www.shoup.net/ntl/
Extract the ZIP on your local folder. 
Copy WinNTL.sln,  WinNTL.vcxproj and README.md to the folder you have extracted the source. 
You are ready to use Visual Studio 2017 IDE for building it as static library x64. 
If you prefer to build it as any other option make required change by going through the project settings. 

#### FYI
```
FYI: The VS Project Setting applied the following flag on top of default: 
Additional FLAGS
#pragma warning (disable : 4146)

/wd4146 /D_CRT_SECURE_NO_WARNINGS
```

FYI: HElib uses NTL Library

