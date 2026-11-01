<p align="center">
  <img src="docs/icon.png" width="96" alt="Atelier Mobile icon">
</p>

<h1 align="center">Atelier Mobile</h1>

<p align="center">
  A Swiss Army knife for Android: the small tools you reach for every day, in one app.
</p>

<p align="center">
  <a href="https://github.com/Amariless/atelier-mobile-releases/releases/latest/download/atelier.apk"><img src="https://img.shields.io/badge/Android-APK-17161c?style=for-the-badge&labelColor=d9822b&logo=android&logoColor=white" alt="Download for Android"></a>
</p>

## What it is

Instead of installing one app for each little thing, Atelier Mobile brings together the tools I use most on my phone. No accounts, no ads, no analytics, and what you save stays on your phone. On your home screen it shows up simply as *Atelier*.

## The tools

<table>
  <tr>
    <td width="50%" valign="top">
      <h3>Music downloader</h3>
      <p>Download songs from YouTube, SoundCloud and other sites as MP3, with cover and artist already filled in. Listen before you download, and send a song from any other app with the <i>Share</i> menu.</p>
    </td>
    <td width="50%" valign="top">
      <h3>Document reader</h3>
      <p>Read PDFs and EPUB books in one place. It can be your default PDF reader.</p>
    </td>
  </tr>
  <tr>
    <td width="50%" valign="top">
      <h3>Expenses</h3>
      <p>Keep track of what you spend each month, by category.</p>
    </td>
    <td width="50%" valign="top">
      <h3>Quick ideas</h3>
      <p>Jot down a thought before it slips away.</p>
    </td>
  </tr>
  <tr>
    <td width="50%" valign="top">
      <h3>Clock</h3>
      <p>Pomodoro timer, world clock and the weather.</p>
    </td>
    <td width="50%" valign="top">
      <h3>Sync</h3>
      <p>Check how Syncthing is doing on your phone, and find conflicts and duplicate files in your synced folders.</p>
    </td>
  </tr>
  <tr>
    <td width="50%" valign="top">
      <h3>Color palette</h3>
      <p>Take a picture or pick one from your gallery and get its color palette.</p>
    </td>
    <td width="50%" valign="top">
      <h3>Texture maker</h3>
      <p>Turn a photo of a surface into a set of textures for 3D, normal map included. Works best with a camera that has macro focus.</p>
    </td>
  </tr>
  <tr>
    <td width="50%" valign="top">
      <h3>Scene generator</h3>
      <p>Ideas for 3D scenes that combine a setting, a state and an atmosphere.</p>
    </td>
    <td width="50%" valign="top">
      <h3>And it keeps growing</h3>
      <p>New tools arrive with updates, which install right from the app.</p>
    </td>
  </tr>
</table>

## Download

Atelier Mobile isn't on the Play Store; you install it from the APK. It needs Android 7.0 or newer and works on any phone, whatever its processor.

1. [Download `atelier.apk`](https://github.com/Amariless/atelier-mobile-releases/releases/latest/download/atelier.apk) on your phone and open it.
2. Android will ask you to allow your browser or file manager to install apps. You can allow it just for this install.
3. If Google Play Protect says it doesn't recognize the app, that's because it doesn't come from the Play Store. Choose *Install anyway*.

New versions install from inside the app, in *Settings → Check for update*. They're all signed with the same key, so they install over the previous one without losing your data. All versions and their notes are on the [Releases](https://github.com/Amariless/atelier-mobile-releases/releases) page.

## Permissions

The app asks for few permissions, and each one is used by a specific tool. If you don't use that tool, you can deny it and everything else keeps working.

| Permission | What it's for | If you deny it |
|---|---|---|
| **Internet** | Checking for updates, downloading music, the weather ([Open-Meteo](https://open-meteo.com)), covers, and talking to Syncthing running on your own phone. | The tools that don't need the internet still work: Expenses, Quick ideas, Document reader and Texture maker. |
| **Install apps** | Installing the app's own updates. It doesn't install anything else, and Android always asks you to confirm. | You'll need to update by downloading the APK yourself. |
| **All files access** | Checking the folders Syncthing syncs and saving your MP3s in the folder you choose. Only requested when you open one of those tools. | Sync can't check folders and music is saved in the app's own folder. |
| **Camera** | The macro camera in Texture maker and photos for Color palette. | You can pick photos from your gallery instead. |

All files access is a sensitive permission, which is why you have to turn it on yourself in Android's settings. You can remove it anytime in *Settings → Apps → Atelier → Permissions*. Only download the APK from this repository.

Only use the music downloader with content you have the right to download.

## Feedback

Found a bug, have an idea or just want to say something? Each button opens a short form.

<p>
  <a href="https://github.com/Amariless/atelier-mobile-releases/issues/new?template=bug.yml"><img src="https://img.shields.io/badge/Report_a_bug-d9822b?style=for-the-badge" alt="Report a bug"></a>
  <a href="https://github.com/Amariless/atelier-mobile-releases/issues/new?template=idea.yml"><img src="https://img.shields.io/badge/Suggest_an_idea-d9822b?style=for-the-badge" alt="Suggest an idea"></a>
  <a href="https://github.com/Amariless/atelier-mobile-releases/issues/new?template=comment.yml"><img src="https://img.shields.io/badge/Leave_a_comment-d9822b?style=for-the-badge" alt="Leave a comment"></a>
</p>

---

<sub>This repository only hosts the APK; the source code is private.</sub>
