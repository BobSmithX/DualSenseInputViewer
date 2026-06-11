DualSense Input Viewer

A simple Windows controller input display built with C# / .NET / WPF.

This tool is designed to visually display DualSense controller button presses and stick movement for streaming, recording, or input demonstration purposes.

Features
Displays DualSense controller input on screen
Shows button presses visually
Shows analog stick movement
Uses a custom controller image and layout
Built with C# / .NET / WPF
Uses local HID controller input only
What this tool does

This application only reads local controller input and displays it visually.

It is intended to work like a controller input viewer or input overlay for streaming.

What this tool does NOT do

This tool does not:

Inject into any game
Read or modify game memory
Modify controller input
Simulate keyboard, mouse, or controller input
Remap controls
Use macros
Provide recoil control
Provide aim assist
Provide wallhack, ESP, or any gameplay advantage
Install drivers
Create a virtual controller
Use ViGEmBus, HidHide, DS4Windows, reWASD, or similar input modification tools
Fair Play Notice

This tool is only a visual input display.

It is not designed to provide any competitive advantage in games. However, every game and anti-cheat system has its own rules and detection behavior.

Use this tool responsibly and make sure it is allowed under the rules of the game or platform you are using.

The developer is not responsible for account penalties, bans, or restrictions caused by using third-party software while playing online games.

Requirements

For the normal release version:

Windows 10 / Windows 11
.NET 8 Desktop Runtime may be required if using the framework-dependent build
DualSense controller

For the self-contained release version:

Windows 10 / Windows 11
No separate .NET installation required
How to use
Download the latest release ZIP file.
Extract the ZIP file.
Open the extracted folder.
Run the .exe file.
Connect a DualSense controller.
The controller input display should appear on screen.

Do not move the .exe file out of the folder by itself.
The Assets folder and related .dll files must stay next to the .exe.

Expected release folder structure:

DualSenseInputViewer
├─ Assets
│  ├─ controller_sheet.png
│  └─ controller_preset.json
├─ DualSenseInputViewer.exe
├─ HidSharp.dll
├─ Microsoft.Windows.SDK.NET.dll
├─ WinRT.Runtime.dll
├─ DualSenseInputViewer.dll
├─ DualSenseInputViewer.deps.json
└─ DualSenseInputViewer.runtimeconfig.json
Build from source

This project was built with:

Visual Studio 2022
C#
.NET 8
WPF
HidSharp

To build:

Open the solution in Visual Studio 2022.
Restore NuGet packages.
Build the project in Release mode.
Publish or run the generated executable.
Project purpose

The purpose of this project is to provide a simple, transparent controller input display for content creation, streaming, testing, and demonstration.

It is not a cheat tool and does not interact with game processes.

Disclaimer

This project is not affiliated with Sony, PlayStation, Electronic Arts, Respawn Entertainment, Apex Legends, or any other game company.

Use at your own risk.
