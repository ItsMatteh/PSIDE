# PSIDE

PSIDE (PowerShell IDE) is a custom version of Windows PowerShell with 300+ additional commands and quality-of-life improvements.

PSIDE adds tools for file management, system information, networking, processes, text manipulation, and more while keeping the familiar PowerShell experience.

## Features
300+ commands
File and folder tools
System tools
Networking tools
Process and service tools
Text and file tools
Custom packs
Built-in updater
Quality-of-life improvements
Packs

PSIDE supports .pack files that add custom commands.

Packs are stored in:

%LOCALAPPDATA%\PSIDE\Packs
### Install a Pack

Use:

installpack <link>

You can also place a .pack file directly into the Packs folder.

### Make a Pack

Create a file ending in .pack and add PowerShell functions to it.

Example:

function hello {
    Write-Host "Hello!" -ForegroundColor Green
}

Multiple commands can be added to the same pack.

Place the pack in:

%LOCALAPPDATA%\PSIDE\Packs

PSIDE will automatically detect it.

### Pack Commands

View installed packs:

viewpacks

View commands from packs:

packcommands

### Reload packs:

reloadpacks

### View pack information:

packinfo <pack>

Pack commands are also included in:

custom-help

PSIDE checks the Packs folder automatically and detects new or changed packs while running.

## Updating

PSIDE includes a built-in update system.

Check for updates with:

checkupd

If an update fails, DM:

`matteh_is_z6`
## Development

PSIDE is still in development. More commands and features will be added over time.
