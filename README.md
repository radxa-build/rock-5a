# ROCK 5A
[![Build image for Release channel](https://github.com/radxa-build/rock-5a/actions/workflows/build.yml/badge.svg)](https://github.com/radxa-build/rock-5a/actions/workflows/build.yml)[![Build image for Test channel](https://github.com/radxa-build/rock-5a/actions/workflows/test.yml/badge.svg)](https://github.com/radxa-build/rock-5a/actions/workflows/test.yml)

## What is this?

This repo is the central location for Radxa-built system images for ROCK 5A.

## What images are provided?

Currently 4 flavors are provided:

- Debian KDE: This flavor is officially supported, tested, and recommended for all users.
- Debian CLI: This flavor is officially supported. This flavor is quite minimal and is intended for headless usage. We do not support desktop usage on top of this flavor.
- Ubuntu KDE: This flavor is provided as-is except for critical issues. Users should look at Debian KDE as an alternative.
- Ubuntu CLI: This flavor is provided as-is except for critical issues. Users should look at Debian CLI as an alternative.

Please also always use [the latest release](https://github.com/radxa-build/rock-5a/releases/latest) instead of any pre-release / test builds. Those will not be supported.

## Is there any other options?

- [Armbian](https://www.armbian.com/rock-5a/)

## Where can I download the Radxa image?

Every month new images are [built](https://github.com/radxa-build/rock-5a/actions/workflows/build.yml) and [published](https://github.com/radxa-build/rock-5a/releases) as pre-releases, which serve as release candidates (RC). Radxa will periodically select an RC for additional testing, and once it passes those tests, promote it as an officially supported release. This is why you are always recommended to use [the latest release](https://github.com/radxa-build/rock-5a/releases/latest).

## Help! Something doesn't work!

For other questions, please first take a look at [our Wiki](https://wiki.radxa.com/Rock5), which covers the most basic usages.

Should you have any additional questions, please visit [our forum](https://forum.radxa.com/) or [our Discord](https://rock.sh/go), and we are willing to help.
