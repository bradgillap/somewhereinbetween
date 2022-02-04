
![S.I.B Logo](Images/SplashV2large.png)


# Somewhere In Between (S.I.B) AE 
A SkyrimSE Modding Automation for [Wabbajack](https://www.wabbajack.org/#/).

## Latest Release

* S.I.B is without world edits, new items, quests. This is designed for the user build upon. 
* Authors cut has my hand selected gameplay, quest, recommendations already installed. 

| Variant                                                   | S.I.B Version | SkyrimAE Version | Release Date | Download Modlist |
|:---------------------------------------------------------:|:-------------:|:----------------:|:------------:|:----------------:|
| S.I.B                                                     | v0.1.0        | 1.6.353.0        | Soon         |                  |
| Authors Cut [(More Info)]()                               | v0.1.0        | 1.6.353.0        | Soon         |                  |

# Table of Contents

## Overview

While looking at popular modlists I noticed a few issues:

* Modlists are built for extremely powerful computers or extremely low performance computers. 
* Nearly all the major overhauls run their own Nexus mod pages with custom edits designed for their particular modlists. This creates incompatibilities if you wish to add or change their lists.

This will make customization difficult for the amateur modder and has lead me to building this modlist. I followed a set a of rules for myself to avoid bugs, add content, and improve on the vanilla experience based on Reddit & Nexus community sentiment. This is based on my modding experiences over 10 years of Skyrim and general I.T knowledge.

### Included

* Vanilla Mesh,Bug, Quest Fixes.
* User Interface Improvements and Minor Quality of Life Adjustments.
* Mesh & Texture Replacers.
* Lighting and FX Replacers.
* First Person Animations.
* Performance Optimizations.
* Documentation in Mod Oragnizer and Github.

### Purposefully Not Included

* Gameplay and Game System Changes.
* New Quests.
* New Items, Weapons, or Armour.
* Interrior or Exterior World Edits.

## Requirements

Software: Skyrim Anniversery Edition from Steam.

### System Specifications

Size Installed: **100ish Gigabytes**. This is in addition to your vanilla 14GB SkyrimSE install.

My Specs: 
* **CPU**: Intel Core i7 3770 3.4ghz overlcoked to 4.2ghz (Ivy Bridge 22nm).
* **RAM**: Memory 800mhz DDR3 32GB. (12GB-16gb is probably fine).
* **Video**: Geforce 1060 6GB Edition (Tested). This is similar to a Geforce 1660. A Geforce 770 was tessted with ENB Performance Option (See Wiki for Recommendations).

### Website Accounts Required

1. [NexusMods](https://www.nexusmods.com/modrewards#/store/item/35) premium account. **Paid Membership**.
2. [Vectorplus](https://vectorplexus.com/) **Free Account**.

(Note: **Do not use OAuth style sign-ins.** A regular account works best with Wabbajack). 

## Installation Instructions

This is basic installation to just get up and running. For additional features please see the Wiki pages on this github. I provide step by step screenshots and gifs that will get you closer to your desired results.

### Install Skyrim AE Via Steam. (Step 1)

Make sure you open SkyrimSE at least once to allow for configuration files to update with your default video settings. Allow creation club content to download. Then close the game.

### MS Framework Requirements. (Step 2)

1. Some mods require Dot Net frameworks. [Download Here](https://dotnet.microsoft.com/en-us/download/dotnet/6.0/runtime)
2. Some mods require Visual C++.         [Download x64 Version Here](https://docs.microsoft.com/en-US/cpp/windows/latest-supported-vc-redist?view=msvc-170)

Get both CLI and Desktop Versions of DOTNET 6.
[![https://dotnet.microsoft.com/en-us/download/dotnet/6.0/runtime](Images/dotnet.png "Dot Net 6 Required")](https://dotnet.microsoft.com/en-us/download/dotnet/6.0/runtime)

### Wabbajack Mod installer (Step 3)

Wabbajack is the program that will install all of the mods based on my list and complete the automation. 

[Download WabbaJack](https://www.wabbajack.org/#/) and save it to an empty folder on your computer. 

### Latest S.I.B Release (Step 4)

1. Download the latest release from: https://github.com/bradgillap/somewhereinbetween/releases
2. Extract with 7zip to your WabbaJack folder or a subfolder within your wabbajack folder.  

Example: 

``` 
C:\Wabbajack\SIB\release\S.I.B AE.wabbajack
```

### Open Wabbajack and prepare to install the S.I.B List. (Step 5)

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

