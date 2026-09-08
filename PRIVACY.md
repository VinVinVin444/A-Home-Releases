# A-Home Privacy Notice

Last updated: 2026-09-08

## Overview

A-Home stores its business data locally in the user's Obsidian Vault. It does not include client telemetry, usage analytics, advertising trackers, or automatic crash-reporting services.

## License service

The plugin connects to the A-Home licensing service when the user activates a license, when an offline license requires renewal or recovery, when local trusted time requires verification, or when the user manually requests online validation.

Depending on the request, the licensing service may receive:

- The activation code during activation.
- The A-Home product code.
- An anonymous randomly generated device identifier.
- A human-readable device name and platform category.
- The existing offline license during online validation.

The activation code is not persisted in plugin settings and is not written to client logs. License verification failures log only a non-sensitive reason code.

## Weather and location services

A-Home does not ship with a fixed weather provider. Weather and location requests occur only after the user supplies compatible API endpoint URLs. Data sent to those services depends on the user's endpoint configuration and may include a place name, coordinates, locale, date range, or weather query parameters. Those services have their own privacy policies.

## User-opened external content

The plugin can open author pages, user-created task links, and user-configured external Banner images. These requests occur only through visible links or user configuration and are governed by the destination service.

## Local storage

- Business data is stored in Markdown or JSON files within the Vault.
- Plugin settings and the offline license are stored in the plugin's Vault-specific configuration data.
- The anonymous device identifier is stored under the current Vault configuration directory in `a-license/device.json`.

The user's own sync or backup provider may copy these files according to that provider's settings.

## Data deletion

Users can remove local A-Home data by deleting the corresponding Vault data folders and plugin configuration after disabling the plugin. Deleting local data does not automatically revoke a server-side device activation; contact the author if a device needs to be released.

## Contact

For privacy or licensing questions, contact the author through the channels listed in [README.md](./README.md).
