# Biomimetic Human Hand

Apache-2.0 mostly 3D-printable 21-DOF robotic hand prototype with many printable files and PCB BOM artifacts; strong robotics BOM candidate but complex.
## Documentation download

Download the complete build documentation/source package from this GitHub repository:

- **Download ZIP:** use GitHub's **Code → Download ZIP** button.
- **Start here:** `README.md` for the build/install guide.
- **Documentation pointer:** `download-documentation/README.md`.
- **Mirrored upstream source/assets:** `source/upstream/`.

## Installation / quick start

## Project

Biomimetic Human Hand

Apache-2.0 mostly 3D-printable 21-DOF robotic hand prototype with many printable files and PCB BOM artifacts; strong robotics BOM candidate but complex.

## Quick start

1. Download the printable files from Printables: https://www.printables.com/model/1776622-biomimetic-human-hand
2. Download this GitHub repository as a ZIP, or clone it:

   ```bash
   git clone https://github.com/ToolKnox/hawkridge-biomimetic-human-hand.git
   ```

3. Use `source/upstream/` for the mirrored software, firmware, PCB, CAD-source, and upstream documentation.
4. Use the Bill of Material PDF attached to the Printables Documentation section for parts planning.
5. Read the project-specific notes below before powering electronics or uploading firmware.

## Software / firmware setup

- Open the `.ino` sketch from `source/upstream/` in Arduino IDE, install libraries listed in the upstream README/source, select the target board/port, then upload.
- PCB/Gerber/electronics design files are mirrored under `source/upstream/`; open them with the original toolchain noted by the file type, such as KiCad, Altium, or CAM/Gerber viewers.

## Main software/config files

- `source/upstream/Software/Concurrent/DC_Motor_PID_Controller/DC_Motor_PID_Controller.ino`
- `source/upstream/Software/Concurrent/DC_Motor_PID_Controller/PID_Test/PID_Test.ino`
- `source/upstream/Software/Concurrent/Serial Command Assembler/.vs/DC_Motor_Controller_Serial_Command_Test/v17/DocumentLayout.json`
- `source/upstream/Software/Concurrent/Serial Command Assembler/DC_Motor_Controller_SPI_Command_Test/Form1.Designer.cs`
- `source/upstream/Software/Concurrent/Serial Command Assembler/DC_Motor_Controller_SPI_Command_Test/Form1.cs`
- `source/upstream/Software/Concurrent/Serial Command Assembler/DC_Motor_Controller_SPI_Command_Test/Program.cs`
- `source/upstream/Software/Concurrent/Serial Command Assembler/DC_Motor_Controller_SPI_Command_Test/bin/Debug/net8.0-windows/DC_Motor_Controller_SPI_Command_Test.deps.json`
- `source/upstream/Software/Concurrent/Serial Command Assembler/DC_Motor_Controller_SPI_Command_Test/bin/Debug/net8.0-windows/DC_Motor_Controller_SPI_Command_Test.runtimeconfig.json`
- `source/upstream/Software/Concurrent/Serial Command Assembler/DC_Motor_Controller_SPI_Command_Test/bin/Debug/net8.0-windows8.0/DC_Motor_Controller_SPI_Command_Test.deps.json`
- `source/upstream/Software/Concurrent/Serial Command Assembler/DC_Motor_Controller_SPI_Command_Test/bin/Debug/net8.0-windows8.0/DC_Motor_Controller_SPI_Command_Test.runtimeconfig.json`
- `source/upstream/Software/Concurrent/Serial Command Assembler/DC_Motor_Controller_SPI_Command_Test/bin/Debug/net8.0-windows8.0/DC_Motor_Controller_Serial_Command_Test.deps.json`
- `source/upstream/Software/Concurrent/Serial Command Assembler/DC_Motor_Controller_SPI_Command_Test/bin/Debug/net8.0-windows8.0/DC_Motor_Controller_Serial_Command_Test.runtimeconfig.json`
- `source/upstream/Software/Concurrent/Serial Command Assembler/DC_Motor_Controller_SPI_Command_Test/bin/Release/net8.0-windows8.0/DC_Motor_Controller_SPI_Command_Test.deps.json`
- `source/upstream/Software/Concurrent/Serial Command Assembler/DC_Motor_Controller_SPI_Command_Test/bin/Release/net8.0-windows8.0/DC_Motor_Controller_SPI_Command_Test.runtimeconfig.json`
- `source/upstream/Software/Concurrent/Serial Command Assembler/DC_Motor_Controller_SPI_Command_Test/bin/Release/net8.0-windows8.0/DC_Motor_Controller_Serial_Command_Test.deps.json`
- `source/upstream/Software/Concurrent/Serial Command Assembler/DC_Motor_Controller_SPI_Command_Test/bin/Release/net8.0-windows8.0/DC_Motor_Controller_Serial_Command_Test.runtimeconfig.json`
- `source/upstream/Software/Concurrent/Serial Command Assembler/DC_Motor_Controller_SPI_Command_Test/obj/DC_Motor_Controller_SPI_Command_Test.csproj.nuget.dgspec.json`
- `source/upstream/Software/Concurrent/Serial Command Assembler/DC_Motor_Controller_SPI_Command_Test/obj/DC_Motor_Controller_Serial_Command_Test.csproj.nuget.dgspec.json`
- `source/upstream/Software/Concurrent/Serial Command Assembler/DC_Motor_Controller_SPI_Command_Test/obj/Debug/net8.0-windows/.NETCoreApp,Version=v8.0.AssemblyAttributes.cs`
- `source/upstream/Software/Concurrent/Serial Command Assembler/DC_Motor_Controller_SPI_Command_Test/obj/Debug/net8.0-windows/DC_Motor_Controller_SPI_Command_Test.AssemblyInfo.cs`
- … 40 more software/config files under `source/upstream/`.

## PCB / electronics design files

- `source/upstream/Designs/Concurrent/DC Motor Controller/Mk1/Assembly/DC Motor Controller v45.csv`
- `source/upstream/Designs/Concurrent/DC Motor Controller/Mk1/DC Motor Controller PCB.zip`
- `source/upstream/Designs/Concurrent/DC Motor Controller/Mk1/Gerber Files.zip`
- `source/upstream/Designs/Concurrent/DC Motor Controller/Mk1/GerberFiles/copper_bottom.gbr`
- `source/upstream/Designs/Concurrent/DC Motor Controller/Mk1/GerberFiles/copper_top.gbr`
- `source/upstream/Designs/Concurrent/DC Motor Controller/Mk1/GerberFiles/gerber_job.gbrjob`
- `source/upstream/Designs/Concurrent/DC Motor Controller/Mk1/GerberFiles/profile.gbr`
- `source/upstream/Designs/Concurrent/DC Motor Controller/Mk1/GerberFiles/silkscreen_bottom.gbr`
- `source/upstream/Designs/Concurrent/DC Motor Controller/Mk1/GerberFiles/silkscreen_top.gbr`
- `source/upstream/Designs/Concurrent/DC Motor Controller/Mk1/GerberFiles/soldermask_bottom.gbr`
- `source/upstream/Designs/Concurrent/DC Motor Controller/Mk1/GerberFiles/soldermask_top.gbr`
- `source/upstream/Designs/Concurrent/DC Motor Controller/Mk1/GerberFiles/solderpaste_bottom.gbr`
- `source/upstream/Designs/Concurrent/DC Motor Controller/Mk1/GerberFiles/solderpaste_top.gbr`
- `source/upstream/Designs/Concurrent/DC Motor Controller/Mk1/T-I10W761085A-5sets-Bill+of+Materials(2024-05-20).xls`
- `source/upstream/Designs/Concurrent/DC Motor Controller/Mk2/Assembly/DC Motor Controller Mk2 v22.csv`
- `source/upstream/Designs/Concurrent/DC Motor Controller/Mk2/DC Motor Controller PCB.rar`
- `source/upstream/Designs/Concurrent/DC Motor Controller/Mk2/Gerber Files.zip`
- `source/upstream/Designs/Concurrent/DC Motor Controller/Mk2/GerberFiles/copper_bottom.gbr`
- `source/upstream/Designs/Concurrent/DC Motor Controller/Mk2/GerberFiles/copper_top.gbr`
- `source/upstream/Designs/Concurrent/DC Motor Controller/Mk2/GerberFiles/gerber_job.gbrjob`
- … 49 more PCB/manufacturing files under `source/upstream/`.

## Upstream documentation mirrored here

- `source/upstream/Designs/Concurrent/Phalanx Assemblies/Index Finger/Index Finger Assembly.3mf`
- `source/upstream/Designs/Concurrent/Phalanx Assemblies/Little Finger/Little Finger Assembly.3mf`
- `source/upstream/Designs/Concurrent/Phalanx Assemblies/Middle Finger/Middle Finger Assembly.3mf`
- `source/upstream/Designs/Concurrent/Phalanx Assemblies/Palm and Wrist Assembly/Palm and Wrist Assembly.3mf`
- `source/upstream/Designs/Concurrent/Phalanx Assemblies/Palm and Wrist Assembly/Wrist Assembly.stl`
- `source/upstream/Designs/Concurrent/Phalanx Assemblies/Ring Finger/Ring Finger Assembly.3mf`
- `source/upstream/Designs/Concurrent/Phalanx Assemblies/Thumb/Thumb Assembly.3mf`
- `source/upstream/README.md`
- `source/upstream/Renders/Phalanx Assembly Mk1.png`
- `source/upstream/Renders/Phalanx_Assembly_2024-Jun-23_05-39-12PM-000_CustomizedView3688566158_png.png`
- `source/upstream/Renders/Phalanx_Assembly_2024-Jun-24_08-13-17PM-000_CustomizedView18257921723_png.png`
- `source/upstream/Renders/Phalanx_Assembly_2024-Jun-28_02-02-48AM-000_CustomizedView21154948335_png.png`

## Original source

https://github.com/JCarroll-OU/Biomimetic-Human-Hand


## Where to find things

- Printables model and printable files: https://www.printables.com/model/1776622-biomimetic-human-hand
- Bill of Material: `Biomimetic Human Hand Bill of Material.pdf` in the Printables Documentation section
- Full mirrored upstream source/software/PCB files: `source/upstream/`
- Source asset index: `docs/source-assets.md`
- Standalone install/build guide: `docs/INSTALLATION.md`
