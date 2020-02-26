---
title: "Setup foot switch keyboard pedal"
series: "tools"
summary: "Note to setup foot switch keyboard pedal"
date: 2020-02-22T21:00:00+01:00
draft: true
tags:
- gadgets
- setup
- keyboard
---

## Foot switch keyboard pedal

It's a pedal that's used as keyboard to control your PC/Mac.

In this post, I will use [Olympus Foot Switch RS28H](https://www.olympus.co.uk/site/en/a/audio_accessories/accessories_professional_dictation/hand_foot_controls/rs28h_footswitch/index.html)

### Olympus Foot Switch RS28H

Two main reasons I choose it because:

 - Easy to buy from Sweden
 - Support MacOS officially 
 - Can setup pedals to shortcuts

## How can setup it

### Strategy

 - I setup Olympus Foot Switch RS28H pedal to map with a keyword, e.g. Ctrl+Shift+B
 - I setup vim/sublime or any application accept keyword Ctrl+Shift+B to a function
 - I setup vim/sublime or any application to write snipet code if Ctrl+Shift+B

```
                                    ┌──────────────────┐
                                    │ VIM              │
┌────────┐                          │                  │
│        │                          ├──────┐  ┌──────┐ │
│ Pedal  │────Ctrl + Shift + B─────▶│Plugin│─▶│action│ │
│        │                          ├──────┘  └──────┘ │
└────────┘                          │                  │
                                    │                  │
                                    └──────────────────┘
                                    ┌──────────────────┐
                                    │ Sublime          │
 ┌────────┐                         │                  │
 │ Pedal  │                         ├──────┐  ┌──────┐ │
 │        │──Ctrl + Shift + B──────▶│Plugin│─▶│action│ │
 │        │                         ├──────┘  └──────┘ │
 └────────┘                         │                  │
                                    │                  │
                                    └──────────────────┘
                                    ┌──────────────────┐
                                    │ Browser/Document │
 ┌────────┐                         │                  │
 │ Pedal  │                         │         ▲        │
 │        │────Page Up/Down────────▶│         │        │
 │        │                         │         │        │
 └────────┘                         │         ▼        │
                                    │                  │
                                    └──────────────────┘
```

### Step 1: Install Foot Switch Configuration Tool

The Foot Switch Configuration Tool is management tool that allows you manage your pedal or configuration it.

In time I write this note, it's v100 Windows and v101 MacOS, you can download it from following links:
 - [Download](https://dl-support.olympus-imaging.com/odms_download/ftsw_configuration_tool/en/)
 - [Backup Windows](/files/foot-switch-keyboard-pedal/FTSW_tool_win_V100.zip)
 - [Backup MacOS](/files/foot-switch-keyboard-pedal/FTSW_tool_mac_V101.zip)

### Step 2: Setup keywords for pedals

Plug Olympus Foot Switch RS28H to your machine, open FTSW toll, that you download and install in step 1 

![FTSW tool](/images/foot-switch-keyboard-pedal/ftsw.png)

## Scrolling, page up, page down
