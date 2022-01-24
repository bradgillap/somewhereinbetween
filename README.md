
![S.I.B Logo](Images/SplashV2large.png)


# Somewhere In Between (S.I.B) 
A SkyrimSE Modding Automation for [Wabbajack](https://www.wabbajack.org/#/).

## Latest Release

| S.I.B Version | SkyrimSE Version | Release Date | Download Modlist |New Save Required?                                                                         |
|:-------------:|:----------------:|:------------:|:----------------:|:-----------------------------------------------------------------------------------------:|
| v0.0.8        | 1.6.353.0        | 2022/22/01   | [SIB_0.0.8.7z](https://github.com/bradgillap/somewhereinbetween/releases/download/v0.0.9/SIB_0.0.9.7z) | Yes |
| v0.0.8        | 1.6.353.0        | 2022/22/01   | [SIB_0.0.8.7z](https://github.com/bradgillap/somewhereinbetween/releases/download/v0.0.8/SIB_0.0.8.7z) | No  |
| v0.0.7        | 1.6.353.0        | 2022/22/01   | [SIB_0.0.7.7z](https://github.com/bradgillap/somewhereinbetween/releases/download/v0.0.7/SIB_0.0.7.7z) | Yes |

# Table of Contents

- [Somewhere In Between (S.I.B)](#somewhere-in-between--sib-)
  * [Latest Release](#latest-release)
  * [Overview](#overview)
    + [Pros](#pros)
    + [Cons](#cons)
  * [Requirements](#requirements)
    + [System Specifications](#system-specifications)
    + [Website Accounts Required](#website-accounts-required)
  * [Installation Instructions](#installation-instructions)
    + [Install SkyrimSE. (Step 1)](#install-skyrimse--step-1-)
    + [Dot Net 6.0 Requirements. (Step 2)](#dot-net-60-requirements--step-2-)
    + [Wabbajack Mod installer (Step 3)](#wabbajack-mod-installer--step-3-)
    + [Latest S.I.B Release (Step 4)](#latest-sib-release--step-4-)
    + [Open Wabbajack and prepare to install the S.I.B List. (Step 5)](#open-wabbajack-and-prepare-to-install-the-sib-list--step-5-)
    + [Post installation Instructions](#post-installation-instructions)
  * [Important Mods You should Know About](#important-mods-you-should-know-about)
  * [MCM Recommendations](#mcm-recommendations)
  * [Changelog](#changelog)


## Overview

While looking at popular modlists I noticed a few issues:

* Modlists are built for extremely powerful computers or extremely low performance computers. 
* Nearly all the major overhauls run their own Nexus mod pages with custom edits designed for their particular modlists. This creates incompatibilities if you wish to add or change their lists.

This will make customization difficult for the amateur modder and has lead me to building this modlist. I followed a set a of rules for myself to avoid bugs, add content, and improve on the vanilla experience based on Reddit & Nexus community sentiment. This is based on my modding experiences over 10 years of Skyrim and general I.T knowledge.

The following are rules I followed while building this:

### Pros
* All mods must work together using patches available on the  Nexusmods site. No extenuating custom edits. Nothing an amateur couldn't do themselves by reading.
* All texture mods should be aware of middle grade graphics cards and systems. Textures right in front of your face should be 1-2k while everything else should look passable to play.
* Read at least the first few pages worth of comments on each mod  page to determine compatibility, issues, and community sentiment. 
* Testing by teleporting into cells affected by mods and test interactions where possible. Stress test by setting movement speed high and traversing the world.
* Build for the latest 1.6xxx edition binary only as this is the future.
* I will focus on the experience based on community sentiment rather than number of mods, or comparison to the big mod lists.
* I will maintain appropriate documentation and mark if it's safe to upgrade or if a new save is required on release pages along with a changelog.

### Cons
* I do not have the time to do entire play through bug testing between versions. Please provide feedback through issues.

## Requirements

Requirements for storage and machine specifications.

### System Specifications

Size Installed: **88 Gigabytes**. This is in addition to your vanilla 14GB SkyrimSE install.

My Specs: 
* **CPU**: Intel Core i7 3770 3.4ghz overlcoked to 4.2ghz (Ivy Bridge 22nm).
* **RAM**: Memory 800mhz DDR3 32GB. (16gb is probably fine).
* **Video**: Geforce 1060 6GB Edition (16nm). This is similar to a Geforce 1660.

### Website Accounts Required

1. [NexusMods](https://www.nexusmods.com/modrewards#/store/item/35) premium account. **Paid Membership**.
2. [Vectorplus](https://vectorplexus.com/) **Free Account**.

(Note: Do not use oauth style sign-ins. A regular account works best). 

## Installation Instructions

This is basic installation to just get up and running. For additional features like hair physics, please see the wiki pages on this github. I provide step by step screenshots and gifs that will getyou up and running in a few minutes.

### Install SkyrimSE. (Step 1)

Make sure you open SkyrimSE at least once to allow for configuration files to update with your default video settings. 

### MS Framework Requirements. (Step 2)

1. Some mods require Dot Net frameworks. [Download Here](https://dotnet.microsoft.com/en-us/download/dotnet/6.0/runtime)
2. Some mods require Visual C++.         [Download x64 Version Here](https://docs.microsoft.com/en-US/cpp/windows/latest-supported-vc-redist?view=msvc-170)

[![https://dotnet.microsoft.com/en-us/download/dotnet/6.0/runtime](Images/dotnet.png "Dot Net 6 Required")](https://dotnet.microsoft.com/en-us/download/dotnet/6.0/runtime)

### Wabbajack Mod installer (Step 3)

Wabbajack is the program that will install all of the mods based on my list and complete the automation. 

[Download WabbaJack](https://www.wabbajack.org/#/) and save it to an empty folder on your computer. 

### Latest S.I.B Release (Step 4)

1. Download the latest release from: https://github.com/bradgillap/somewhereinbetween/releases
2. Extract with 7zip to your WabbaJack folder or a subfolder within your wabbajack folder.  Example C:\Wabbajack\SIB\releasefiles.example

### Open Wabbajack and prepare to install the S.I.B List. (Step 5)

Wabbajack png with marked paths and descriptions by number for the user.

1. Install folder description
2. Downloads folder description
3. Skyrim location description
4. Website button description
5. Manifest button description
6. Readme button description

### Post installation Instructions

The game is installed and will work but be missing some features. If you wish to add your own mods. These post install steps should be run everytime you make an addition or change to the modlist.

Features that won't work until post install steps are completed:
* Hair Physics.
* Correct items won't be in some chests.
* Misc items will have weight.

Click here for Post Install Steps on Wiki

## Important Mods You should Know About

Please see wiki page XXX

## MCM Recommendations 

Please See wiki page XXX

## Changelog

Please see Changelog page XXX

