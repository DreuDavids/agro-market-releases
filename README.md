# AgroMarket Releases

Public APK downloads for **AgroMarket** (Digital Agro Platform).

Source code: private [`NexIT-Africa/nexit-digital-agro-platform`](https://github.com/NexIT-Africa/nexit-digital-agro-platform).

## Install

1. Open the latest [Release](https://github.com/DreuDavids/agro-market-releases/releases/latest)
2. Download `app-release.apk`
3. On Android, allow install from this source if prompted
4. Open the APK and install

## How releases are published

Use **Actions’ Release Android APK** in *this* repo (workflow_dispatch). It checks out the private source with `SOURCE_REPO_TOKEN`, builds the APK, and publishes a GitHub Release here.

Secrets for that workflow live in **this** repo™s Settings (not the NexIT org repo).
