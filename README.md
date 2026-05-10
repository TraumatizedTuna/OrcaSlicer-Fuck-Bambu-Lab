<div align="center">

## About this fork

### Bambu Lab and the user

First of all, I'd like to clarify that I don't judge anyone for using a Bambu printer. I'm on your side, against the company that wants to screw you over. If you're fine with their recent behavior, I firmly but respectfully disagree with you.

### Resisting Bambu Lab's attack on FOSS

This fork is for preservation rather than development. [The original fork](https://github.com/jarczakpawel/OrcaSlicer-bambulab) has been voluntarily taken down by the author, following Bambu Lab's false accusations and unjustified legal threats. By forking this repo, you show Bambu Lab that the community whose work they built their success upon does not quietly accept this kind of abuse. [Your fork should still be available whatever happens upstream](https://docs.github.com/en/pull-requests/collaborating-with-pull-requests/working-with-forks/what-happens-to-forks-when-a-repository-is-deleted-or-changes-visibility#deleting-a-public-repository). They'll have to attack each one separately.<br>
I also strongly encourage you not to buy anything brand new from Bambu Lab. There are plenty of 3D printer manufacturers out there that don't actively disrespect their users and the FOSS community.

### Another measure of preservation
I've archived the repo [here](https://archive.org/details/OrcaSlicer-Fuck-Bambu-Lab) in case GitHub plays along with Bambu Lab's bullshit.


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
