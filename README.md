<h2 align="center">FiveM Axon Body 3 OBS</h2>

<p align="center">
<a href="https://patreon.com/yeen"><img alt="Patreon" src="https://img.shields.io/badge/patreon-donate?color=F77F6F&labelColor=F96854&logo=patreon&logoColor=ffffff"></a>
<a href="https://discord.gg/xHaPKfSDtu"><img alt="Discord" src="https://img.shields.io/discord/463778631551025187?color=7389D8&labelColor=6A7EC2&logo=discord&logoColor=ffffff"></a>
</p>

## Table of Contents

- [About](#about)
- [Installation](#installation)
- [Usage](#usage)
- [Configuration](#configuration)

## About

A fork of [TFNRP's Axon Body Camera 3](https://github.com/TFNRP/axonbody3) made to work with [OBS](https://obsproject.com).  
[Axon Body 3 OBS](https://github.com/MrGriefs/axonbody3-obs) is out of the box and requires no dependencies.  
This software was created by and for [The Furry Nexus Roleplay](https://forum.cfx.re/t/4712777/40).  

## Installation

No special installation or dependencies required.  
Clone from Git or [download manually](https://github.com/MrGriefs/axonbody3-obs/archive/refs/heads/main.zip).  

```bash
$ git clone https://github.com/MrGriefs/axonbody3-obs.git
```

## Usage

1. Create a new Browser Source Component (Right Click in Preview -> `Add` -> `Browser`).  
1. Check `Local file`, click `Browse` and locate `index.html` from the directory you donwloaded [Axon Body 3 OBS](https://github.com/MrGriefs/axonbody3-obs).  
1. Set `Width` and `Height` to your Canvas resolution (usually 1920 by 1080).  
1. Click `OK`. Now you should have a functioning AB3 overlay in OBS.  

## Configuration

We also supply a `config.js` for further ehancement:  

- `CustomCameraId`: If you'd like to use a custom id for the overlay. It will replace the randomly generated id.  
- `ForceUTCTimeZoneOffset`: Can be `false` or a numebr. Setting this to a number will override the UTC offset instead of using your current UTC offset.  
- `CalculateDaylightSavingsTime`: Can be `true` or `false`. Setting this to `true` will make the overlay advance an hour ahead during [Daylight Saving Time](https://en.wikipedia.org/wiki/Daylight_saving_time).  
- `BeepVolume`: Can be a number. This will determine the volume of interval beeps, which occur every two minutes. Set this to `0` if you do not want beeping.  
