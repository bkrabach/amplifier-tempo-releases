# Amplifier Tempo for Mac

Tempo puts your Amplifier chats within reach: a desktop avatar, menu-bar status,
notifications and quick replies. It connects to an existing Amplifier Unified
server; it does not install a server or change your server's version.

## Install

[**Download Tempo for Mac**](https://github.com/bkrabach/amplifier-tempo-releases/releases/latest/download/Amplifier-Tempo-macOS.dmg)

1. Open the downloaded disk image.
2. Drag **Amplifier Tempo** onto **Applications**.
3. Eject the disk image, then open Tempo from Applications. Confirm **Open** if macOS asks.
4. Enter your Amplifier server address in **Settings → Connection** and choose
   **Connect in browser**. Sign in, check that the code matches Tempo, and approve this Mac.

Ask the person sharing Tempo for your server address and access. Your server must
support browser device approval. You don't need a GitHub account or access to the
private source repository. Never send account passwords or host control tokens to
someone helping you install Tempo.

Requires macOS 13 or later, on Apple silicon or Intel. Native Liquid Glass is
available on macOS 26 or later; older systems use native material controls.
The app and disk image are Developer ID signed and Apple-notarized.

## Find your way around

Tempo lives in the **menu bar** and as a desktop avatar; it has no Dock icon.
Use its menu-bar menu for **Settings**, **New message**, **Check for Updates** or **Quit Tempo**.
Hover over the avatar to reveal its controls, drag it to move, or click an update
to open that chat. Blue means updates to review, red an error, teal ongoing work,
gray idle and amber disconnected. Visiting the latest response in your focused
Amplifier chat clears its update on Tempo's next refresh.

Allow notifications when macOS asks if you want desktop alerts. Notification
settings also control which chats appear and whether Tempo opens at login.
The six avatar shapes, eight colors and Clear/Dark finishes are in Appearance.

Updates use Sparkle's standard signed installer. Choose **Check for Updates**;
automatic checks are optional. Existing installations retain their settings,
connection and saved messages across signed updates.

## Connection and saved messages

**Disconnect** pauses your connection across relaunches; **Resume** reconnects.
**Forget…** confirms removal of this host's local credential. It keeps your saved
messages and preferences. Use **Manage connected devices** to revoke server access too.

If a message has uncertain delivery, inspect **Saved messages** in the menu bar,
review its full text, and check the chat before choosing **Retry message**. Tempo
keeps the original message identity and never automatically replays an uncertain reply.

## Remove Tempo

Turn off **Open Tempo at login**, disconnect or forget the credential if desired,
choose **Quit Tempo**, and move the app to Trash. Saved preferences and messages
remain on your Mac; uninstalling does not delete your Amplifier chats or revoke
server access. Saved-message recovery data is in
`~/Library/Application Support/Amplifier Companion`.

## Help and release details

[Release notes, checksums and ZIP downloads](https://github.com/bkrabach/amplifier-tempo-releases/releases/latest)

If something goes wrong, report the Tempo version, macOS version and what you
were doing through [Issues](https://github.com/bkrabach/amplifier-tempo-releases/issues).
Do not post credentials, private chat contents or unredacted logs. This is an early
release: full VoiceOver, sleep/wake, multi-display and physical Intel acceptance
are still in progress. Safari web-app discovery and Windows are not included.

This repository contains public downloads and documentation. Source code remains private.
