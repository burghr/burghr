# About me

I am an automation engineer with 18+ years of experience. I turn manual IT processes into reliable, self-service workflows. My day job is ServiceNow platform engineering. After hours, I build native macOS apps, self-hosted tools for my homelab, and MCP servers for AI agents. I also tinker with gaming handhelds.

I write about these projects and other thoughts at **[burghrbytes.com](https://burghrbytes.com)**.

## Featured

| Project | What it is |
|---|---|
| [**MacMixer**](https://github.com/burghr/MacMixer) | A macOS menu bar volume mixer for each app. It uses Core Audio process taps, so there is no audio driver to install and no microphone indicator. Swift. |
| [**TerminalSpace**](https://github.com/burghr/TerminalSpace) | A native macOS terminal with project workspaces. Each terminal can be a shell, a Claude Code session, an opencode session, or a custom command. Swift + SwiftTerm. |
| [**Xodus Nexus on ArmadaOS**](https://github.com/burghr/xodus-nexus-arm-port) | An unofficial port that brings the Xodus Nexus launcher (Microsoft Store and PC Game Pass games on Linux) to ARM64 handhelds. One install script sets up everything. |
| [**ServiceNow Catalog Intake**](https://github.com/burghr/ServiceNow-Catalog-Intake) | Two Service Portal widgets: a wizard to request a new catalog item in plain words, and an admin builder that creates the item, its variables, and its choices. |

## macOS apps

I built these Mac apps to make my own daily use of macOS better.

| Repo | Description |
|---|---|
| [MacMixer](https://github.com/burghr/MacMixer) | Volume for each app, a volume boost, master volume, and a switch for the output device, all from the menu bar. Swift/SwiftUI. |
| [TerminalSpace](https://github.com/burghr/TerminalSpace) | A terminal that groups sessions into workspaces, with themes. Swift + SwiftTerm. |
| [SpaceHog](https://github.com/burghr/SpaceHog) | A visual disk usage analyzer: a sorted folder tree next to a treemap of every file. It scans hundreds of thousands of files in seconds. SwiftUI. |
| [LANScan](https://github.com/burghr/LANScan) | A LAN scanner with ping sweep, ARP discovery, reverse DNS, and a device type from the MAC vendor. SwiftUI. |
| [Macro-Deck](https://github.com/burghr/Macro-Deck) | A Stream Deck-style grid of macros in the menu bar: key sequences, text snippets, and shell commands. Swift/SwiftUI. |
| [MacroPort](https://github.com/burghr/MacroPort) | Imports Windows 8BitDo macro files (`.ini`) into the sandboxed macOS 8BitDo Ultimate Software. Swift. |
| [Hop](https://github.com/burghr/Hop) | A keyboard address bar for Finder. Type a path, push Enter, and Finder goes there. Tab completion, history, and favorites. Python + rumps. |

## Handheld gaming on Linux

| Repo | Description |
|---|---|
| [xodus-nexus-arm-port](https://github.com/burghr/xodus-nexus-arm-port) | The install script for Xodus Nexus on ArmadaOS. Tested on an AYN Odin 3 in Desktop Mode and Game Mode. Shell. |
| [xodus-nexus-arm](https://github.com/burghr/xodus-nexus-arm) | A fork that builds the Xodus Nexus launcher as a native arm64 AppImage. The games run through the FEX x86 translation layer. TypeScript. |
| [decky-xodus-chat](https://github.com/burghr/decky-xodus-chat) | A Decky Loader plugin that shows Xbox friends and Xbox text chat in the Steam Quick Access menu. Python + TypeScript. |

## AI and MCP tools

| Repo | Description |
|---|---|
| [cal-mcp](https://github.com/burghr/cal-mcp) | A read-only MCP server for the local Apple Calendar, through EventKit. Python. |
| [reminders-mcp](https://github.com/burghr/reminders-mcp) | An MCP server that reads, creates, updates, and completes Apple Reminders. Python. |
| [AI-Bench](https://github.com/burghr/AI-Bench) | A benchmark harness for local AI coding agents against local LLM backends (Ollama, LM Studio, oMLX). It measures wall time, TTFT, and throughput, and makes an HTML report. Python. |

## ServiceNow

| Repo | Description |
|---|---|
| [ServiceNow-Catalog-Intake](https://github.com/burghr/ServiceNow-Catalog-Intake) | A requester wizard and an admin builder for new catalog items. The request is stored on a story as JSON. |
| [ServiceNow-AutoWatchlist](https://github.com/burghr/ServiceNow-AutoWatchlist) | A scoped app that adds users to task watch lists from condition rules that an admin defines. |
| [ServiceNow-BatchPluginUpdater](https://github.com/burghr/ServiceNow-BatchPluginUpdaterWidget) | A Service Portal widget that updates many plugins in one batch through the CICD REST API, with live progress. |
| [ServiceNow-CWM-Space-Gantt](https://github.com/burghr/ServiceNow-CWM-Space-Gantt) | An interactive Gantt chart for CWM tasks, with zoom levels and filters for users and spaces. |
| [ServiceNow-Copy-CWM-Automations](https://github.com/burghr/ServiceNow-Copy-CWM-Automations) | A widget that copies CWM automation rules from one board to another. |
| [ServiceNow-Catalog-Create-Script](https://github.com/burghr/ServiceNow-Catalog-Create-Script) | A scripted catalog item that creates new catalog items with role-based access and variable templates. |

## Self-hosted apps and homelab

These apps run in Docker on my home NAS.

| Repo | Description |
|---|---|
| [Bill-Tracker](https://github.com/burghr/Bill-Tracker) | Bills grouped by paycheck, recurring bills, debt tracking, monthly budgets for each category with pace tracking, and a budget that a household can share. React + Express + SQLite. |
| [game-tracker](https://github.com/burghr/game-tracker) | A game library and backlog tracker with IGDB metadata. FastAPI + SQLite. |
| [chess-review](https://github.com/burghr/chess-review) | Pulls Chess.com games into SQLite, runs Stockfish on every position, and shows accuracy trends. CLI + web dashboard. Python. |
| [MyCalPal](https://github.com/burghr/MyCalPal) | A calorie and macro tracker with meal logs, barcode scans, weight trends, and PWA install. FastAPI + React + PostgreSQL. |
| [Sticky-Kanban](https://github.com/burghr/Sticky-Kanban) | A kanban board of sticky notes with Apple Pencil drawing. Node/Express + SQLite. |
| [Pi-Monitor](https://github.com/burghr/Pi-Monitor) | A dashboard for Raspberry Pi CPU, memory, disk, temperature, and Docker status. FastAPI + vanilla JS. |
| [nas-deploy](https://github.com/burghr/nas-deploy) | A cron script that keeps the app folders on the NAS equal to their GitHub branch. Shell. |

## What I work with

- **Languages:** Swift, JavaScript, TypeScript, Python, PowerShell, Bash, SQL
- **Platforms:** ServiceNow, macOS (SwiftUI, Core Audio, EventKit), Linux, Docker, VMware vSphere, Active Directory, Azure DevOps
- **Frameworks:** SwiftUI, React, FastAPI, Express, MCP
- **Practices:** CI/CD, infrastructure as code, ITSM/ITIL, monitoring
