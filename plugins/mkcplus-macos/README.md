# MKC+ for Claude Code on a Mac

See and use the devices of your MKC+ group from Claude Code: their screens, pointer, keyboard, clipboard and files. MKC+ is a free beta app for using one mouse and keyboard across your Windows PCs, Macs, Linux machines and Android devices on your local network. With this plugin, Claude can use those devices too, this Mac included.

## Install

Install MKC+ from [mkcplus.com](https://mkcplus.com) first. Then, in Claude Code (2.1.275 or later):

    /plugin install mkcplus-macos --marketplace arxidaki/mkcplus-releases

Or in a terminal:

    claude plugin marketplace add arxidaki/mkcplus-releases
    claude plugin install mkcplus-macos@mkcplus

## What it runs

The plugin adds one MCP server and has no code of its own. It starts the MKC+ engine that is already installed on this Mac, over stdio:

    /Applications/MKC+.app/Contents/MacOS/mkcplusd mcp

[The Agents page](https://mkcplus.com/agents.html) has the same setup for other agents.

## Asking first

The first time Claude uses MKC+, the MKC+ window on this Mac asks you to allow it. Each device then asks before Claude first uses it, and, where the device can tell which app is in front, before it first uses each app there.

## Data

MKC+ sends nothing about agents anywhere: there is no account, relay or telemetry, and each device keeps its own record of what agents did there. What Claude sees, it sends to its own service, as with anything else you show it. See [Privacy](https://mkcplus.com/privacy.html).

## Examples

- "Look at my PC's screen and tell me which windows are open."
- "Open Notes on this Mac and write down the list we just made."
- "Send report.pdf from this Mac to the Downloads folder of my PC."
