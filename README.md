# Smart Campus Device Management System

A console-based C++ application for managing smart devices across a university campus, built using Object-Oriented Programming principles.

## About

This system lets campus administrators register, monitor, and control IoT devices — security cameras, air conditioners, projectors, room lights, and door locks — through an interactive text menu. It demonstrates inheritance, polymorphism, encapsulation, and dynamic memory management in C++.

## Device Types

| Type | Key Attributes |
|---|---|
| Security Camera | Quality (720p/1080p/4k), Power source (mains/battery/solar) |
| Air Conditioning | Target temperature (0–36 °C) |
| Projector | Input (VGA/HDMI/Wireless), Brightness (0–100) |
| Room Lighting | Brightness (0–100) |
| Door Lock | Lock state, Last opened by |

## Getting Started

**Requirements:** Visual Studio 2019/2022 and C++17 or later.

```bash
git clone https://github.com/Hyzen-collab/SmartCampusDeviceSystem.git
```

Open `Smart_Campus.sln` in Visual Studio, build with `Ctrl + Shift + B`, and run with `Ctrl + F5`.

**Linux/macOS (g++):**
```bash
cd Smart_Campus
g++ -std=c++17 -o SmartCampus *.cpp
./SmartCampus
```

## Menu Options

```
1.  Add Device              6.  Delete Device
2.  View All Devices        7.  Activate Single Device
3.  Activate All Devices    8.  Deactivate Single Device
4.  Deactivate All Devices  9.  View Single Device's Info
5.  Interact All Devices    10. Interact Single Device
0.  Exit
```

## Author

**Idusha Piumika** — G21328023  
[github.com/Hyzen-collab](https://github.com/Hyzen-collab)

> Developed as part of a C++ Object-Oriented Programming module.
