# MapIt Pro updates

`updates.json` lists the newest TestFlight build of MapIt Pro (`mac`) and its iOS companion (`companion`). MapIt Pro's Check for Updates reads it from `https://raw.githubusercontent.com/chuckycastle/mapit-pro-updates/main/updates.json` and compares the `build` number with its own.

`release.sh` in the MapIt Pro repository updates the file through `tools/publish-update.py` once App Store Connect has processed a build. Do not edit it by hand.

Each entry holds `version`, `build` (`yyyyMMddHHmm`), `published` (ISO 8601), `url` (the app's TestFlight page), and optional `notes`.

## License

[CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/)
