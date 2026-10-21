# Binary
Binary is a tool for editing Black Box Need for Speed games binary files, powered by Nikki and Endscript.

Binercover fixes some issues with the NFS Undercover support butchered in Binary v2.9.0+ and adds a few more, previously uneditable data types.


## Requirements
Binercover requires [the .NET Core 3.1 Desktop Runtime](dotnet.microsoft.com/download/dotnet/3.1). Make sure to install both x86 and x64 versions.


## Features
- UI to edit collection data of databases built using Nikki & Endscript libraries.
- Ability to use various commands, create and restore backups, import and export collections.
- Endscript support: special .end files that are imported to edit databases.
- Built-in tools, such as:
  - NFS-Hasher
  - NFS-Raider
  - Swatch Picker
  - Texture Editor
  - String Editor
  - CarPart Editor
  - Career Editor
  - FEng Editor (WIP)
- User configuration settings that can be changed and applied any time

## Motivation
- Lack of tools with UI to edit Need for Speed binary (.BIN, .BUN, .LZC) files
- Desire to build a universal tool for the reason stated above
- Desire to build a tool similar to process BIN data, similar to those that process VLT data
