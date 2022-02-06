
![S.I.B Logo](Images/SplashV2large.png)


# Somewhere In Between (S.I.B) AE
A SkyrimSE Modding Automation for [Wabbajack](https://www.wabbajack.org/#/).

## Latest Release

* S.I.B is without world edits, new items, quests. This is designed for the user to build upon.
* Authors cut has my hand selected gameplay, quest, and recommendations already installed.

| Variant                                                                                          | S.I.B Version | SkyrimAE Version | Release Date | Download Modlist |
|:------------------------------------------------------------------------------------------------:|:-------------:|:----------------:|:------------:|:----------------:|
| Somewhere In Between                                                                             | v1.0.0        | 1.6.353.0        | Soon         |                  |
| Authors Cut [(More Info)](https://github.com/bradgillap/somewhereinbetween/wiki/SIB-Authors-Cut) | v0.1.0        | 1.6.353.0        | Soon         |                  |

# Table of Contents

## Overview

While looking at popular mod lists I noticed a few issues:

* Mod lists are built for extremely powerful computers or extremely low performance computers.
* Nearly all the major overhauls run their own Nexus mod pages with custom edits designed for their particular mod lists. This creates incompatibilities if you wish to add or change their lists.

The intention of S.I.B is to provide a Wabbajack list to build upon. Stripped down of mods that often conflict focusing mostly on bug fixes, meshes and textures.

### Included

* Mesh,Bug,Quest Fixes.
* User Interface Improvements.
* Mesh & Texture Replacers.
* Lighting and FX Replacers.
* New Animations.
* Performance Optimizations.
* Self Documented Mod Organizer.

### Purposefully Not Included

* Gameplay and Game System Changes.
* New Quests.
* New Items, Weapons, or Armour.
* Interrior or Exterior World Edits.



## System Specifications

S.I.B AE Install Size: **101'ish Gigabytes**.

My Specs:
* **CPU**: Intel Core i7 3770 3.4ghz overclocked to 4.2ghz (Ivy Bridge 22nm).
* **RAM**: Memory DDR3 32GB. (12GB-16gb is probably fine).
* **Video**: GeForce 1060 6GB Edition (Tested). This is similar to a GeForce 1660. A GeForce 770 was tested with ENB Performance Option (See Wiki for Recommendations).

## Requirements

Software: Skyrim Anniversary Edition from Steam.

### Website User Accounts

1. [NexusMods](https://www.nexusmods.com/modrewards#/store/item/35)  **Free or Premium**.
2. [Vectorplus](https://vectorplexus.com/) **Free Account**.

(Note: **Do not use OAuth style sign-ins.** A regular account works best with Wabbajack).

## Installation Instructions

Follow along for installation instructions.

Post Installation instructions available on the [wiki](https://github.com/bradgillap/somewhereinbetween/wiki).

### Install Skyrim AE Via Steam. (Step 1)

Make sure you open SkyrimSE at least once to allow for configuration files to update with your default video settings. Allow creation club content to download. Then close the game.

### MS Framework Requirements. (Step 2)

1. Dot Net frameworks. [Download Here](https://dotnet.microsoft.com/en-us/download/dotnet/6.0/runtime).

**Get both CLI and Desktop Versions of DOTNET 6.**
[![https://dotnet.microsoft.com/en-us/download/dotnet/6.0/runtime](Images/dotnet.png "Dot Net 6 Required")](https://dotnet.microsoft.com/en-us/download/dotnet/6.0/runtime).

3. Visual C++.         [Download x64 Version](https://docs.microsoft.com/en-US/cpp/windows/latest-supported-vc-redist?view=msvc-170).
4. DOTNET SDK          [Download x64 Version](https://dotnet.microsoft.com/en-us/download).
5. DOTNET 3.5 (Available Ondemand for Windows 10 Users) [Instructions](https://docs.microsoft.com/en-us/dotnet/framework/install/dotnet-35-windows).

### Wabbajack Mod installer (Step 3)

Wabbajack is the program that will retrieve and install all of then complete the automated installation.

[Download WabbaJack](https://www.wabbajack.org/#/) and save it to an empty folder on your computer.

### Latest S.I.B Release (Step 4)

1. Download the latest S.I.B release from: https://github.com/bradgillap/somewhereinbetween/releases
2. Extract with 7zip to your WabbaJack folder.

Example:

```
C:\Wabbajack\SIB\releases\S.I.B AE.wabbajack
```

### Open Wabbajack and prepare to install the S.I.B List. (Step 5)

![Wabba Install Window](Images/icon48.png "Logo Title Text 1")

Wabbajack png with marked paths and descriptions by number for the user.

1. Install folder description
2. Downloads folder description
3. Skyrim location description
4. Website button description
5. Manifest button description
6. Readme button description

## Post installation Instructions

1. Run Open ModOrganizer.exe and run the SKSE exe. Make sure the game starts.
2. Add your own mods or see the Wiki on this github to walk through my recommendations.
