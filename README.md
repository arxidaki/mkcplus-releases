# MKC+

Use one mouse and keyboard across your Windows PCs, Macs and Android devices on your local network, and copy & paste between them. Free beta, unlimited devices.

Download it for Windows, Windows ARM, macOS (Apple silicon) or Android (Android 10 or later) from [mkcplus.com](https://mkcplus.com).

- Control any device from any device
- Arrange devices to match your desk
- Unlimited devices
- Copy & paste text, media, files, complex data
- One-click pairing
- Automatic reconnection, any kind of local network

## Questions

**What is MKC+?**
MKC+ is a free beta app for using one mouse and keyboard across your Windows PCs, Apple silicon Macs and Android phones and tablets on the same local network. Move the pointer past the edge of one screen and it appears on the next device, and the keyboard follows it. No device is the server: the mouse and keyboard of any PC or Mac can control any other device. An Android phone or tablet is controlled, but its touchscreen does not control the other devices.

**Is it free?**
Yes. MKC+ is a free beta: there is no paid version and no charge per device. It is not open source, and as a beta it comes as-is, without warranty.

**Which systems does it work on?**
Windows PCs (Intel or AMD, and ARM), Macs with Apple silicon, and Android phones and tablets with Android 10 or later. Typing on an Android device from your keyboard needs Android 13 or later. It does not run on Intel Macs or on Linux.

**Do I need an account or an internet connection?**
No. MKC+ has no account, and nothing you type, copy or move goes through a server: your devices talk directly to each other on your local network. The internet is used only to download updates, which install automatically (Android asks you to confirm), and to send feedback when you choose to.

**Is the connection encrypted?**
Yes. You pair two devices by comparing a six-digit code on both screens. After that, the keystrokes, pointer movement, clipboard and files they send each other are encrypted and authenticated. MKC+ is a beta and has not had an independent security audit.

**How do I set it up?**
Install MKC+ on each device and open it. On a Mac, grant Input Monitoring and Accessibility when the window asks. On Android, turn on Accessibility for MKC+: its Permissions window shows the steps. With both devices on the same network, the new device appears in the MKC+ window of the other one: press Pair, check that both screens show the same six-digit code, and press Pair again. Then drag the devices in the window so they match how they sit on your desk.

**Does it work over Wi-Fi?**
MKC+ works over Wi-Fi, Ethernet, or both at once. It tests every connection all the time, uses the best one, and switches by itself if one drops. Your devices must be on the same local network; MKC+ does not work across the internet.

**Can I copy and paste between Windows, Mac and Android?**
Yes. Copy on one device, move the pointer to another device, and paste. Between PCs and Macs, text, formatted text, images and PDFs cross, and so do files and folders, which you can also drag across. With an Android phone or tablet, text and images cross both ways. To send files from it, share them to MKC+ and paste on a PC or Mac. A file copied on a PC or Mac shows on it in a notification with Save to Downloads. File copy is the newest part and still has limits in the beta.

**Why do Windows, macOS and Android show a warning when I install it?**
The MKC+ installers are not signed with a commercial certificate, so Windows SmartScreen warns once (More info, then Run anyway), and on a Mac you approve the installer once under System Settings, Privacy & Security, Open Anyway. The Android app is an APK file from mkcplus.com, not from an app store, so Android asks you to allow installing from your browser or file app, and Google Play Protect may warn about an app it does not know. MKC+ needs Android's Accessibility permission to move the pointer and type; on Android 13 and later you first allow restricted settings for MKC+, and its Permissions window shows the steps. This is expected during the beta. Download MKC+ only from mkcplus.com. After that, MKC+ updates itself and checks every update against its own signing key.

**Does it collect any data?**
MKC+ has no account and does not track you. Once a day its update check adds one to an anonymous count of the system and processor type (for example Windows on ARM) and the country; no IP address or device identifier is kept. Feedback is sent only when you press Submit: your message, the app and system versions and the device name, plus the screenshots and logs you tick.

This repository holds the installers, the Android app (`MKC+.apk`) and the update files, which the app verifies by signature before installing. Each [release](https://github.com/arxidaki/mkcplus-releases/releases) says what it changed. The source lives in a private repository.
