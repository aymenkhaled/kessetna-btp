# Kessetna BTP — official Windows downloads

[Discover Kessetna BTP](https://kessetna.com/fr/btp/) · [Arabic product page](https://kessetna.com/ar/btp/)

Kessetna BTP is a local Windows application for businesses that rent construction equipment. Follow equipment availability, reservations, rental dispatch, partial returns, payments, refundable deposits, damage and repairs. Local staff PIN accounts, permissions and an attributed activity history help the depot organise its work.

## Download

Current stable release: **0.5.4**, published 2026-10-14.

[Download the latest stable installer](https://github.com/aymenkhaled/kessetna-btp/releases/latest) from the official Releases page. Select `Kessetna-BTP-Setup.exe` and the matching `.sha256.txt` file from the same release. Older versions and release notes remain in [Releases](https://github.com/aymenkhaled/kessetna-btp/releases).

Windows 10/11, x64. The application supports French, English and Arabic. The available business currencies are TND, EUR, USD, GBP and JPY; it does not convert exchange rates or use multiple currencies in one business database.

Normal rental operations continue without Internet, with business data stored locally on the depot's PC. Internet is used for downloads, updates and optional usage analytics, which can be disabled in Settings. This is not a multi-PC cloud synchronisation service.

## Installation and checksum

1. Download only through the official product page or this repository's Releases.
2. Compare the installer SHA-256 with its matching checksum file, for example with PowerShell `Get-FileHash -Algorithm SHA256 -LiteralPath '.\Kessetna-BTP-Setup.exe'`.
3. Back up existing business data before upgrading, then run the installer.
4. Create regular backups on another storage device. Local storage is not a substitute for backups.

The installer is unsigned and Windows may display an unknown-publisher warning. Contact support through the [official product page](https://kessetna.com/fr/btp/) if you need installation or demo assistance.

This public repository contains distribution information and installer assets, not private application source or licensing/signing materials.
