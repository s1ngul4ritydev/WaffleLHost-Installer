# WaffleLHost Installer

WaffleLHost is a local Windows hosting manager for running bots and small apps directly from your own computer.

It is designed for local project control, process logs, runtime configuration, environment variables, ports, and basic hardware/resource visibility in one clean desktop panel.

## What It Does

- Import ZIP projects safely.
- Manage Node.js, Python, Java, and custom-command projects.
- Start, stop, restart, and force-kill local services.
- View live stdout/stderr logs.
- Configure environment variables per project.
- Monitor local CPU, memory, disk, and hardware information when available.
- Keep project data stored locally on your computer.

## Installation

Run the WaffleLHost installer and follow the setup wizard.

The installer may request administrator permission because WaffleLHost is installed as a Windows desktop application. Project files, logs, and user data are stored separately in the user profile so the app can work normally after installation.

## First Launch

After opening WaffleLHost:

1. Import a trusted ZIP project.
2. Review the detected project type and start command.
3. Configure environment variables if needed.
4. Start the project manually from the dashboard.

WaffleLHost does not automatically run uploaded projects.

## Privacy

WaffleLHost is local-first.

- No cloud account.
- No telemetry.
- No external dashboard.
- No analytics.
- No project upload to remote servers.
- No hidden data sharing.

Hosted projects may still access the internet if their own code requires it.

## Safety Notice

Only run projects you trust. Imported projects can execute code on your computer when started.

Review commands, environment variables, and project files before running anything important.

## Uninstall

Use Windows Settings or Control Panel to uninstall WaffleLHost.

Removing the application does not necessarily remove your saved projects and logs. Review your local WaffleLHost data folder if you want to delete stored project data manually.

## Developer

Developed by **WafflyCatt**.
