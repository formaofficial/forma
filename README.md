# Forma

Windows launcher for the Forma integration in Qwen Desktop.

**Closed source · Official binary releases only.** Forma’s original code is proprietary under the [Forma license](LICENSE). This repository distributes releases and documentation; it does not publish Forma source code. Third-party components retain their own licenses.

[Download](https://github.com/formaofficial/forma/releases/latest) · [Quick-start guide](GUIDE.md) · [Discord](https://discord.gg/MqwFSTEdkF)

Download the Windows installer from [Releases](https://github.com/formaofficial/forma/releases/latest). Forma downloads and verifies compatible Qwen Desktop 1.0.3 automatically if needed, then installs the integration.

## Access

A valid, installation-bound Forma key is required. Keys expire after 10 hours and are rechecked automatically. Qwen launched directly is also gated while the Forma integration is installed. A brief verified lease covers temporary connection problems; expiration locks access without deleting chats.

To get a key, open **Get key inside Forma**, continue to Linkvertise, complete the checkpoint and paste the complete returned key into the app. Always start in Forma: the secure browser session binds the key to your installation. Keys last 10 hours. Invalid or missing checkpoint verification never issues a key.

## Updates

Forma checks GitHub at startup and every 30 minutes. Update manifests have an Ed25519 signature; the installer size and SHA256 are verified before installation. An available update is downloaded and offers a restart.

## Data

Mailboxes and Qwen account sessions are created on each Windows user profile. Private state uses Windows encryption. Personal accounts, license keys, chats and mailbox passwords are not included in the release.

Read, Confirm and Full access control the integrated local tools. Select the mode appropriate to the task. Qwen server quotas still apply.

## Status

This is an independent, unofficial modification. Windows publisher code signing is not configured; Windows may show an unverified-publisher warning. Cryptographic update signing and archive integrity are separate protections. No desktop software is guaranteed uncrackable or bug-free.

## Community and support

Join the [Forma Discord](https://discord.gg/MqwFSTEdkF) for official downloads, key instructions, announcements and support. Read the rules and select Verify with Discord in the verify channel to unlock downloads, key instructions, community chat and voice. Discord requests your basic profile and permission to add you to servers; Forma uses this only for the Forma server. Update notifications are optional through the Updates reaction role. Carl-bot posts welcome messages when members join. Never post license keys, mailbox passwords or verification codes.

