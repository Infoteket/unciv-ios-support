---
layout: default
title: Privacy Policy
description: Privacy policy for the Unciv iOS app
---

# Privacy Policy

Last updated: November 2, 2025

This privacy policy describes how the Unciv iOS app (the "App") collects and processes data. The App is an iOS client for the open-source game Unciv. The App is maintained by Infoteket.

## What personal data does the app collect and transmit?

The Unciv iOS app collects the following personal data **when you use multiplayer features or link accounts**:

### Account Information
- Username and User ID (GUID)
- Password (only transmitted during login/registration and stored locally on-device)
- Session tokens/cookies (stored locally and used for subsequent API calls)
- Account profile data (display name, account creation/deletion requests)

### Multiplayer Game Data
- Saved game files (including game state, player IDs, civilization names, city names, map data)
- Game preview data (reduced game metadata for quick previews)
- Game IDs and Player IDs (UUIDs)
- User-generated content within saves (custom text, settings, civilization names, city names)

### Social Features
- Chat messages and metadata (message text, civilization name, game ID, join/leave events)
- Friend lists and friend actions (friend UUIDs, friend invitations)
- Lobby data (lobby name, optional password, lobby UUID, maximum players)

### Technical Data
- HTTP headers (User-Agent, Content-Type, Accept)
- IP address (visible to all contacted servers for network routing and server operations)

### Mod Discovery
- Mod metadata and search requests
- Mod preview images and asset downloads

## Where is this data sent?

When you use multiplayer features, the app transmits this data to:

- **Unciv Multiplayer API v2 servers** (default: uncivserver.xyz) — for game uploads, account management, friend lists, lobbies, and chat
- **Legacy Unciv file servers** (if configured) — for alternative game file storage using Basic authentication
- **Chat WebSocket server** — for real-time in-game messaging
- **Dropbox** (developer-controlled account via content.dropboxapi.com) — for alternate multiplayer game file storage
- **GitHub API** (api.github.com, raw.githubusercontent.com) — for mod discovery and downloads (does not require user authentication by default)

Infoteket does not collect, store, or retain this data. The third-party servers listed above handle data according to their own privacy policies.

## Data linking and identity

All data transmitted to third-party servers is linked to your user identity via the User ID (GUID). This allows:
- Other players to identify you in multiplayer games
- Servers to associate your saved games and chat history with your account
- Cross-device session continuity

## Local data storage

The following data is stored locally on your device (not transmitted to Infoteket):
- Your passwords (in encrypted app settings)
- Your session tokens/cookies
- Your saved game files (before transmission to servers)
- Your mod files and cache

## Data not collected

The app **does not** collect:
- Analytics or crash reports (no Sentry, Firebase, or similar SDKs)
- Advertising identifiers
- Device contacts, photos, or other device data
- Location data
- Biometric data

## Your choices

- **Multiplayer opt-out:** You can play single-player games without creating an account or transmitting personal data.
- **Custom servers:** You can configure the app to use alternative multiplayer servers under your control.
- **Data removal:** To request removal of data from the Unciv project servers, contact the Unciv project maintainers at [https://github.com/yairm210/Unciv/](https://github.com/yairm210/Unciv/)
- **Questions:** For questions about this iOS app's privacy practices, open an issue on the project issue tracker: [https://github.com/Infoteket/unciv-support/issues](https://github.com/Infoteket/unciv-support/issues)

## Third-party server privacy

For privacy practices of the Unciv project's multiplayer servers, GitHub, Dropbox, or other third-party services, please consult their respective privacy policies.

## Changes to this policy

We may update this policy from time to time. When we do, we will update the "Last updated" date above.
