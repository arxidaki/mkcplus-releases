# MKC+ for Claude Code on Linux

See and use the devices of your MKC+ group from Claude Code: their screens, pointer, keyboard, clipboard and files. MKC+ is a free beta app for using one mouse and keyboard across your Windows PCs, Macs, Linux machines and Android devices on your local network. With this plugin, Claude can use those devices too, this machine included.

## Install

Install MKC+ from [mkcplus.com](https://mkcplus.com) first. Then, in Claude Code (2.1.275 or later):

    /plugin install mkcplus-linux --marketplace arxidaki/mkcplus-releases

Or in a terminal:

    claude plugin marketplace add arxidaki/mkcplus-releases
    claude plugin install mkcplus-linux@mkcplus

## What it runs

The plugin adds one MCP server and has no code of its own. It starts the MKC+ engine that is already installed on this machine, over stdio:

    /usr/libexec/mkcplus/mkcplusd mcp

The plugin is for the .deb and .rpm packages. With the AppImage, the Agents page gives the line that starts the AppImage's own file with `--engine mcp` instead. [The Agents page](https://mkcplus.com/agents.html) has the same setup for other agents.

## Asking first

The first time Claude uses MKC+, the MKC+ window on this machine asks you to allow it. Each device then asks before Claude first uses it, and, where the device can tell which app is in front, before it first uses each app there.

## Data

MKC+ sends nothing about agents anywhere: there is no account, relay or telemetry, and each device keeps its own record of what agents did there. What Claude sees, it sends to its own service, as with anything else you show it. See [Privacy](https://mkcplus.com/privacy.html).

## Examples

- "Look at my PC's screen and tell me which windows are open."
- "Open the Text Editor on this machine and write down the list we just made."
- "Send report.pdf from this machine to the Downloads folder of my Mac."
