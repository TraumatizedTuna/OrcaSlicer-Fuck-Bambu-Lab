<div align="center">

## About this fork

This fork is for preservation rather than development. <a href= https://github.com/jarczakpawel/OrcaSlicer-bambulab>The original repo</a> has been voluntarily taken down by the author, following false accusations and legal threats made by Bambu Lab. I encourage you to make your own fork, in order to show Bambu Lab that the community that they built their success upon does not quietly accept this kind of behavior. I also strongly encourage you not to buy anything brand new from Bambu Lab. There are plenty of 3D printer manufacturers out there that don't actively disrespect their users and the FOSS community.


## Original README

<picture>
  <img alt="OrcaSlicer logo" src="resources/images/OrcaSlicer.png" width="15%" height="15%">
</picture>

## This version of OrcaSlicer restores full BambuNetwork support for Bambu Lab printers.

You are not limited to LAN only.  
It works over the internet just like before, through BambuNetwork, with full functionality for normal use and printing.

## Installation

### Windows

Windows requires WSL 2.

Before first launch, open Command Prompt or PowerShell as Administrator and run:

```bat
dism.exe /online /enable-feature /featurename:Microsoft-Windows-Subsystem-Linux /all /norestart
dism.exe /online /enable-feature /featurename:VirtualMachinePlatform /all /norestart
```

Restart Windows, then launch Orca Studio.

### Linux

On Linux, a normal installation is enough.

### macOS

Work in progress.


## BMCU

I also encourage you to use BMCU.

You can find BMCU firmware in my repositories.

</div>
