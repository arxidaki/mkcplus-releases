# MKC+

Use one mouse and keyboard across your Windows PCs and Macs on your local network, and copy & paste between them. Free beta, unlimited devices.

Download it for Windows, Windows ARM or macOS (Apple silicon) from [mkcplus.com](https://mkcplus.com).

- Control any device from any device
- Arrange devices to match your desk
- Unlimited devices
- Copy & paste text, media, files, complex data
- One-click pairing
- Automatic reconnection, any kind of local network

## Questions

**What is MKC+?**
MKC+ is a free beta app for using one mouse and keyboard across your Windows PCs and Apple silicon Macs on the same local network. Move the pointer past the edge of one screen and it appears on the next device, and the keyboard follows it. No device is the server: any device's mouse and keyboard can control any other device.

**Is it free?**
Yes. MKC+ is a free beta: there is no paid version and no charge per device. It is not open source, and as a beta it comes as-is, without warranty.

**Which systems does it work on?**
Windows PCs (Intel or AMD, and ARM) and Macs with Apple silicon. It does not run on Intel Macs or on Linux.

**Do I need an account or an internet connection?**
No. MKC+ has no account, and nothing you type, copy or move goes through a server: your devices talk directly to each other on your local network. The internet is used only to download updates, which install automatically, and to send feedback when you choose to.

**Is the connection encrypted?**
Yes. You pair two devices by comparing a six-digit code on both screens. After that, the keystrokes, pointer movement, clipboard and files they send each other are encrypted and authenticated. MKC+ is a beta and has not had an independent security audit.

**How do I set it up?**
Install MKC+ on each device and open it. On a Mac, grant Input Monitoring and Accessibility when the window asks. With both devices on the same network, the new device appears in the MKC+ window of the other one: press Pair, check that both screens show the same six-digit code, and press Pair again. Then drag the devices in the window so they match how they sit on your desk.

**Does it work over Wi-Fi?**
MKC+ works over Wi-Fi, Ethernet, or both at once. It tests every connection all the time, uses the best one, and switches by itself if one drops. Your devices must be on the same local network; MKC+ does not work across the internet.

**Can I copy and paste between Windows and Mac?**
Yes. Copy on one device, move the pointer to another device, and paste: text, formatted text, images and PDFs cross, and so do files and folders, which you can also drag across. File copy is the newest part and still has limits in the beta.

**Why do Windows and macOS show a warning when I install it?**
The MKC+ installers are not signed with a commercial certificate, so Windows SmartScreen warns once (More info, then Run anyway), and on a Mac you approve the installer once under System Settings, Privacy & Security, Open Anyway. This is expected during the beta. Download MKC+ only from mkcplus.com. After that, MKC+ updates itself and checks every update against its own signing key.

**Does it collect any data?**
MKC+ has no account and does not track you. Once a day its update check adds one to an anonymous count of the system and processor type (for example Windows on ARM) and the country; no IP address or device identifier is kept. Feedback is sent only when you press Submit: your message, the app and system versions and the device name, plus the screenshots and logs you tick.

This repository holds the installers and the update files, which the app verifies by signature before installing. Each [release](https://github.com/arxidaki/mkcplus-releases/releases) says what it changed. The source lives in a private repository.
