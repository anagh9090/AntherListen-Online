<h1 align="center">
  <img src="logo.png" width="128" height="128" alt="AntherListen Logo">
  <br>
  AntherListen
</h2>


AntherListen is a clean, lightweight, ad-free online music streaming player built for Android. Powered by YouTube and YouTube Music backends, it lets you stream, search, and manage your music library without interruptions or track limits.

---

## Features

- **Ad-Free Streaming:** Pure playback experience with zero ad interruptions.
- **Smart Search:** Search across songs, albums, playlists, and artists.
- **Background Playback:** Full audio playback support with system media notification integration.
- **Offline Library Management:** Save playlists, favorite tracks, and organize your music history locally.
- **Customizable UI:** Clean interface built with modern Material styling and dark theme support.
- **Privacy First:** No extra trackers, telemetry, or Google Play Services required.

---

## Downloads

Grab the latest compiled **FOSS Release APK** from the official releases page:

<table>
  <tr>
    <td align="center">
      <a href="https://github.com/anagh9090/AntherListen-Online/releases/latest/download/AntherListen-Signed.apk">
        <img src="https://img.shields.io/badge/Download_APK-AntherListen-101010?style=for-the-badge&logo=getpocket&logoColor=white&color=0D1117&labelColor=21262D" alt="Download AntherListen APK" />
      </a>
    </td>
  </tr>
</table>

---

## Building from Source

### Prerequisites

- Android SDK (API Level 34+)
- JDK 17+
- Gradle Wrapper (included)

### Build Instructions

1. Clone the repository:
   ```
   git clone [https://github.com/anagh9090/AntherListen.git](https://github.com/anagh9090/AntherListen.git)
   cd AntherListen
   ```

2. Build the FOSS Release APK:

```
./gradlew assembleFossRelease
```
3. Locate your compiled APK:

```
app/build/outputs/apk/foss/release/app-foss-release-unsigned.apk
```

4. Sign the APK using apksigner:

```
apksigner sign --ks release.jks app/build/outputs/apk/foss/release/app-foss-release-unsigned.apk
```

### License
This project is licensed under the GNU General Public License v3.0 (GPL-3.0). See the LICENSE file for more information.
