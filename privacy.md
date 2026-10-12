---
layout: page
title: Privacy Policy
permalink: /privacy/
---

Last updated: 12 October 2026

## Summary

My Garden Plants has no account, no ads, no analytics and no tracking. Your garden data stays on your device and in your own private iCloud, which the developer cannot access.

Data leaves your device only for features you turn on or use:

| Feature | What is sent | Sent to | When |
| --- | --- | --- | --- |
| Plant identification | The photo you choose, resized, with location data removed | Pl@ntNet (France) | Only when you tap Identify, using your own API key |
| Plant info and translation | Plant names, species and plant descriptions | Anthropic (USA) | Only when you fetch info or translate, using your own API key |
| Frost and rain alerts | The approximate centre of your garden | Apple WeatherKit | When the app checks the forecast for a garden with a mapped boundary |
| iCloud sync | All your garden data | Your private iCloud account (Apple) | When iCloud is enabled on your device |

## Data stored on your device and in iCloud

Everything you enter stays in the app's storage on your device: plants, gardens and garden maps, care tasks and history, illnesses, and photos with their journal notes.

If iCloud is turned on for the app, this data syncs through Apple's CloudKit to the private database of your own iCloud account, so it appears on your other devices. Apple stores it under the [Apple Privacy Policy](https://www.apple.com/legal/privacy/). The developer has no access to your private iCloud data.

The developer runs no servers and receives none of your data.

## Plant identification with Pl@ntNet

Photo identification is optional and uses your own Pl@ntNet API key. It is off until you add a key in Settings and accept a disclosure explaining what is shared.

- A photo is sent only when you tap Identify, and only the photo you chose.
- Before upload the app resizes the photo to 1024 pixels and re-encodes it, which removes all metadata, including GPS location.
- The photo goes directly from your device to Pl@ntNet (France). It never passes through the developer.
- Pl@ntNet processes it under its own terms, which apply to your API account. See [my.plantnet.org](https://my.plantnet.org).

To stop sharing, remove your Pl@ntNet key in Settings.

## Plant information and translation with Claude (Anthropic)

Automatic plant information and translation are optional and use your own Anthropic API key. They are off until you add a key in Settings and accept a disclosure.

- Sent: the plant name or species you look up, and the descriptions and care notes you ask to translate.
- Never sent: photos, garden maps, locations or anything else about you.
- Requests go directly from your device to Anthropic (USA), never through the developer. Anthropic processes them under the terms of your own API account; see the [Anthropic Privacy Policy](https://www.anthropic.com/legal/privacy).

AI-generated plant information can be wrong. Check toxicity and safety details with a reliable source before relying on them.

To stop sharing, remove your Anthropic key in Settings.

## Location and weather

The app uses your location only while it is open, and only when you walk a garden's boundary to map it. The boundary coordinates are stored with that garden on your device and in your private iCloud.

For gardens with a mapped boundary, the app sends the boundary's centre point to Apple WeatherKit to get the daily forecast. It uses the forecast to warn you about frost and to count rain as watering. Apple handles these requests under the [Apple Privacy Policy](https://www.apple.com/legal/privacy/).

The app never tracks your location in the background. You can withdraw location access at any time in iOS Settings.

## Camera, photos, notifications, Siri and backups

| Feature | Permission | What happens |
| --- | --- | --- |
| Camera | Camera | Takes plant photos, stored in the app. |
| Photo library | Photos | Lets you pick photos for your plants. The app reads only the photos you select. |
| Reminders | Notifications | Watering and care reminders are scheduled on your device. No push server is involved. |
| Siri and Shortcuts | None | Requests such as "which plants need water" run inside the app. Apple processes the voice request under its own policy. |
| Backup and CSV export | None | Files are created only when you export them, and saved wherever you choose. |

You can change these permissions at any time in iOS Settings.

## Your API keys

Your Pl@ntNet and Anthropic API keys are stored in the iOS Keychain on this device only. They are not synced to iCloud, not included in backups, and never sent to the developer. They are sent only to the service they belong to, with each request. Usage is billed to your own accounts with those services.

## What the app does not do

- No user accounts or sign-in.
- No advertising and no ad identifiers.
- No analytics, crash-reporting or tracking SDKs.
- No selling or sharing of your data with data brokers.

The app is not directed at children under 13 (16 in some EU countries) and knowingly collects no data about them.

## Keeping and deleting your data

Your data is kept until you delete it. You control all of it:

- Delete plants, gardens, tasks or photos in the app. With iCloud on, deletions sync to your other devices.
- Delete the app's iCloud data in iOS Settings > [your name] > iCloud > Manage Storage.
- Uninstalling the app removes its data from the device. It also removes your API keys.
- Remove an API key in Settings to stop all sharing with that service.

Data already sent to Pl@ntNet, Anthropic or Apple is kept under their own policies.

## Your rights

If you are in the EU or EEA, the GDPR gives you the right to access, correct, delete and export your data, to object to processing, and to withdraw consent. Because the developer holds none of your data, you can use most of these rights directly in the app and in iOS Settings.

Sharing with Pl@ntNet and Anthropic is based on your consent (Art. 6(1)(a) GDPR), which you give when you save a key and withdraw by removing it. Weather requests are part of the feature you choose to use (Art. 6(1)(b) GDPR).

For requests about data a third party holds, contact that service directly. You can also complain to your local data protection authority; in Austria that is the [Datenschutzbehörde](https://www.dsb.gv.at).

## Changes and contact

If this policy changes, the new version is published at this address with a new date. Material changes, such as a new service that receives data, will also be shown in the app.

Developer: Alexander Peither, Austria  
Contact: [haarknoten_rauch.6z@icloud.com](mailto:haarknoten_rauch.6z@icloud.com)
