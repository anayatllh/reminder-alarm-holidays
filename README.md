# Reminder Alarm — holiday data

Public holiday lists used by the Reminder Alarm Android app. This repository holds data only (no code, no keys).

- `v1/index.json` lists every file with its country, year and version.
- `v1/<CC>-<YEAR>.json` holds one country's holidays for one year.

The app checks `index.json` once a week and downloads a file only when its `version` is higher than the one it already has. To publish a correction, edit the holiday file and increase its `version` in both the file and `index.json`.

Holidays that are not confirmed by an official notification carry `"needsVerification": true`.

Source for Bangladesh 2026: Ministry of Public Administration holiday notification (9 November 2025).
