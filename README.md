# WaffleLHost Installer

WaffleLHost is a local Windows hosting manager for bots, apps, and Minecraft servers.

It runs on your own computer and keeps projects, logs, settings, files, and server data local. The panel is made for managing local services with a clean dashboard, live logs, resource information, file management, and safe project imports.

## Features

- Local dashboard for managing hosted projects.
- Import ZIP projects and Minecraft server ZIPs.
- Manage Node.js, Python, Java, custom-command apps, and Minecraft servers.
- Start, stop, restart, and force-kill local processes.
- View live stdout and stderr logs.
- Configure environment variables per project.
- Edit setup commands and start commands.
- Monitor CPU, memory, disk, and hardware details when available.
- Store project data locally on the machine.
- Use a local login session to protect the panel.

## Minecraft Servers

WaffleLHost includes a dedicated Minecraft Servers section for creating, importing, and managing local servers.

Supported server options include:

- Vanilla
- Paper
- Fabric
- Manual server JAR mode for other loaders

Minecraft **26.2** is supported as an experimental version. Use backups before testing experimental versions or loaders, especially with existing worlds.

The Minecraft server panel includes:

- Server creation
- Existing server ZIP import
- Server properties management
- Console commands
- Live logs
- File manager
- Upload, download, edit, copy, move, rename, and delete file actions

## File Manager

The file manager lets you work with server files from the local panel.

You can open folders, edit text-based configuration files, upload plugins or mods, download files, create folders, rename items, copy items, move items, and delete selected files or folders.

Binary and large files are not opened in the text editor to avoid freezing the panel.

## First Launch

On first launch, WaffleLHost asks you to create a local profile with a case-sensitive username and password.

After login, the app keeps a local session on the same machine/browser so the dashboard does not ask for login every time. A different browser, user profile, or computer must log in again.

## Privacy

WaffleLHost is local-first.

- No cloud account
- No telemetry
- No analytics
- No remote dashboard
- No hidden data sharing
- No automatic project upload

Hosted projects may still access the internet if their own code requires it.

## Safety

Only run projects and server files you trust.

Imported projects can execute code on your computer when started. Review commands, environment variables, server files, plugins, and mods before running them.

WaffleLHost does not automatically start imported projects.

## Installation

Run the WaffleLHost installer and follow the setup wizard.

The installer may request administrator permission because WaffleLHost is installed as a Windows desktop application. Project files, logs, settings, and local data are stored separately in the user profile.

## Uninstall

Use Windows Settings or Control Panel to uninstall WaffleLHost.

Uninstalling the application may not remove saved projects, logs, and local data. Review your WaffleLHost data folder if you want to remove stored project files manually.

## Developer

Developed by **WafflyCatt**.
