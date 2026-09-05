# AgroMarket Releases

Public APK downloads for **AgroMarket** (Digital Agro Platform).

Source code lives in the private repo [`NexIT-Africa/nexit-digital-agro-platform`](https://github.com/NexIT-Africa/nexit-digital-agro-platform).

## Install

1. Open the latest [Release](https://github.com/DreuDavids/agro-market-releases/releases/latest)
2. Download `app-release.apk`
3. On Android, allow install from this source if prompted
4. Open the APK and install

## How releases are published

GitHub Actions in the private source repo builds a release APK when a version tag (e.g. `v1.0.0`) is pushed, then uploads it here.

In-app update checks read version metadata from Supabase (`app_releases`) and open the APK URL from these releases.

> Prefer transferring this repo to `NexIT-Africa` when an org admin is available; update `RELEASES_REPO` in the source workflow accordingly.
