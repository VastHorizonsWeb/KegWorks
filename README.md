# KegWorks
Run Windows games and apps directly on Mac hardware!
A wrapper project that's the successor to Wineskin\
This project supports *macOS 10.15.4* or later.

<br>

> [!NOTE]
> Download the executable here - [Latest Build](https://github.com/VastHorizonsWeb/KegWorks/blob/main/KegWorks.exe?raw=true)

<br>

> [!IMPORTANT]
> DirectX support
> - WineD3D (default) Supports DirectX 11 and below.
> - VKD3D (default) Limited DirectX 12 support.
> - D3DMetal (toggle) 64Bit Direct3D 11 & 12 via Metal (Apple Silicon Macs).
> - DXMT (toggle) DirectX 11 via Metal (Apple Silicon Macs).
> - DXVK (toggle) DirectX 10 & 11 via Vulkan.
> - D9VK (winetricks) DirectX 9 via Vulkan (experimental and no longer being developed).
>
> <br>
>
> Apples D3DMetal commonly refered to as GPTK is closed source and has a restrictive license\
> it can not be used for commerial ports, that's not the case for all over renders.\
> You can review the license for [D3DMetal-v1.1](/D3DMetal/1.1/License.pdf), [D3DMetal-v2.0](/D3DMetal/2.0/License.pdf) and [D3DMetal-v2.1](/D3DMetal/2.1/License.pdf)

<br>

> [!CAUTION]
> My Antivirus says it's a VIRUS!!!\
> You need to contact your Antivirus/Anti-malware vendor to report these as false positives.\
> This started once wine moved to using *Mingw-gcc* to compile PE binaries.
> 
> __See the following examples:__
> - [CrossOver 19 and antivirus programs](https://www.codeweavers.com/support/forums/general/?t=27;msg=222870)
> - [Windows Defender detects Occamy.c trojan in steam proton 5.0 folder](https://github.com/ValveSoftware/Proton/issues/3593)

<br>

## Components that fall under LGPL-2.1 license
- `Configure.app` (modified version of  `Wineskin.app`)
- `Creator.app` (modified version of `Wineskin Winery.app`)

Sources can be found https://github.com/Sikarugir-App/Sikarugir-foss-sources

<br>

## Components that don't fall under LGPL-2.1 license
_master wrappers Template-1.0/Wineskin-3.0.6-1 or greater_
- `Sikarugir Launcher` (Running in wineskin compatibility mode)

<br>
