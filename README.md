# SpektorRF updates (Sparkle)

**Public feed + release zips only. No SpektorRF source code lives here.**

The application source stays in the private `oakentek/cursor-projects` repository.

| Asset | URL |
| --- | --- |
| Appcast (Sparkle feed) | https://raw.githubusercontent.com/oakentek/spektorrf-updates/main/appcast.xml |
| Release zip | `https://github.com/oakentek/spektorrf-updates/releases/download/vVERSION/SpektorRF.zip` |

Publish a new build from the private SpektorRF tree:

```bash
RFExplorerMac/tools/publish_sparkle_github_release.sh /path/to/SpektorRF.app 0.9 1
```

That script zips the app, creates a GitHub Release here, and updates `appcast.xml`.
