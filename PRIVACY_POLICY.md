# Velrix Privacy Policy

_Last updated: 4 November 2026. Contact: supportvelrix@gmail.com._

Bug reports are optional and user-initiated: "Report a Bug" opens your email app with a draft (app/device versions, Tor status, last crash trace; no messages, contacts or keys) that you can read and edit before sending.

## Summary
Velrix is a peer-to-peer encrypted messenger. There is no Velrix account server and no Velrix cloud. We do not collect, store, sell or share your personal data, because we never receive it.

## What stays on your device
- Your identity keys, contacts, messages, media, group data and call history are stored only on your device, encrypted with a key derived from your password.
- There is **no backup and no account recovery**. If you forget your password, lose your device or uninstall the app, your identity and chats are permanently lost. Nobody, including the developer, can restore them.
- Android's cloud backup is disabled for the app data.

## What leaves your device
- **Messages and calls** are end-to-end encrypted and sent directly to your contact through the Tor network (onion services). Tor relays can see that Tor is being used, but not the content or the real endpoints.
- **Voice/video calls** try a direct peer connection. If that is impossible, the encrypted media may pass through a TURN relay operated for the app. The relay sees IP addresses and encrypted traffic, not call content.
- **Time:** the app may check network time to keep clocks consistent for the protocol.

## What we do not do
- No advertising, no analytics SDKs, no tracking, no profiling.
- No contact-list upload. Contacts are added by you, in person (QR/Bluetooth) or by invitation.
- No automatic crash upload. If the app crashes it writes a small local report containing only exception class names, code locations and the app version, never messages, keys or addresses. It never leaves the device unless you choose to share it.

## Permissions and why
- Microphone / Camera: calls and video.
- Notifications and full-screen intent: incoming messages and calls.
- Bluetooth: finding and adding nearby contacts.
- Foreground service, boot completed, battery-optimization exemption: keeping your node reachable so you receive messages and calls.
- Media access: sending and saving pictures.

## Children
Velrix is not directed at children under 13.

## Changes
Changes to this policy will be published with a new date in this file.
