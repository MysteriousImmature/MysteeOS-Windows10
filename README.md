# Mystee OS Windows 10 Customization

This repository contains a custom configuration file for optimizing a Windows 10 Professional installation. The customization removes unnecessary components to enhance system performance and reduce the installation footprint.

## Table of Contents

- [Overview](#overview)
- [Prerequisites](#prerequisites)
- [Usage](#usage)
- [Components Removed](#components-removed)
- [License](#license)

## Overview

Mystee OS is a custom Windows 10 image tailored for users who prefer a minimalist setup. The project focuses on removing bloatware and unnecessary system components from Windows 10 Professional (22H2) x64.

## Prerequisites

Before using this configuration, ensure you have:

- A legal copy of Windows 10 Professional (22H2) x64
- [NTLite](https://www.ntlite.com/) or any similar tool to apply the XML configuration
- A backup of your data

## Usage

1. **Clone this repository** to your local machine:
   ```bash
   git clone (https://github.com/MysteriousImmature/MysteeOS-Windows10.git)
    ```
   Open the XML file in NTLite or another customization tool.

2.Load your Windows 10 ISO into the tool.

3.Apply the configuration to remove the specified components.

4.Create a bootable USB or burn the customized ISO to a DVD.

5.Install Windows 10 using your customized image.

## Components Removed
The following components are removed in this customization:

### Windows Components:

- Cortana: The digital assistant service.
- Edge: The default web browser.
- OneDrive: The cloud storage service.
- Xbox Services: Gaming-related services, including Game DVR.
- Windows Media Player: The default media player.
- Windows Defender: The default antivirus software.

### Apps and Features:

- Photos: The default photo viewer.
- Groove Music: The default music player.
- Movies & TV: The default video player.
- Maps: The default maps app.
- People: The default contacts app.
- Alarms & Clock: The default alarm and clock app.
