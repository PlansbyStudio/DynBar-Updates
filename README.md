<p align="center">
  <img src="assets/dynbar-logo.png" alt="DynBar" width="130">
</p>

<h1 align="center">DynBar for macOS</h1>

<p align="center">
  <strong>The MacBook notch, turned into a command surface.</strong><br>
  Media, AI agent usage, system insight, and one-click workflows — right where you already look.
</p>

<p align="center">
  <a href="https://github.com/PlansbyStudio/DynBar-Updates/releases/latest">
    <img src="https://img.shields.io/github/v/release/PlansbyStudio/DynBar-Updates?label=latest&color=0A84FF" alt="Latest version">
  </a>
  <img src="https://img.shields.io/badge/macOS-14%2B-black?logo=apple" alt="macOS 14+">
  <img src="https://img.shields.io/badge/Apple%20silicon-required-555" alt="Apple silicon">
  <img src="https://img.shields.io/badge/license-GPL%20v3-blue" alt="GPL v3">
</p>

<p align="center">
  <a href="https://github.com/PlansbyStudio/DynBar-Updates/releases/latest">
    <img src="https://img.shields.io/badge/⬇︎_Download_DynBar-0A84FF?style=for-the-badge&logoColor=white" alt="Download the latest version" height="45">
  </a>
  <br>
  <sub>Gets the signed <code>.zip</code> from the <a href="https://github.com/PlansbyStudio/DynBar-Updates/releases/latest">latest GitHub Release</a></sub>
</p>

---

Most notch apps stop at "now playing." DynBar started there too — then kept growing, because the
people building it spend all day either waiting on an AI coding agent or waiting on a render. So the
notch became the one place both live: your agent's token burn next to your export's progress bar, a
click away from whatever you were actually doing.

<p align="center">
  <img src="assets/panel-expand.gif" alt="DynBar notch expanding from a closed pill into a full panel" width="700">
  <br>
  <sub>Hover or click the notch — it expands into whatever you reached for.</sub>
</p>

## You'll like DynBar if you...

- run **Claude Code, Codex, or Cursor** and want to see token burn, cost, and which sessions are
  waiting on you — without alt-tabbing to a terminal.
- export from **Premiere Pro, Media Encoder, Lightroom, or Photoshop** and are tired of babysitting
  a progress bar in a hidden window.
- have a "standup" or "deep work" window layout you rebuild by hand every single morning.
- just want the notch to stop being 200px of dead black space.

## Highlights

### AI & agent dashboard

Live token usage, cost, and quota for **Claude**, **Codex**, and **Cursor**, plus which sessions
are running or waiting for you. Tap a session to jump straight into it.

<p align="center">
  <img src="assets/ai-dashboard.png" alt="DynBar AI & agent usage dashboard in the notch" width="760">
</p>

### Creative export detection

A live activity when **Premiere Pro**, **Media Encoder**, **Lightroom**, or **Photoshop** starts an
export, so you can glance at progress from anywhere.

<p align="center">
  <img src="assets/adobe-export.gif" alt="DynBar tracking a Premiere Pro export in a notch live activity" width="600">
</p>

### Menu-bar workflows

Launch a set of apps, folders, and files with one click, each window placed on the display and at
the size you choose (halves, quarters, maximised, centred).

<p align="center">
  <img src="assets/workflow-creation.gif" alt="Building a DynBar menu-bar workflow with per-app window placement" width="600">
</p>

### Media & live activities

Playback controls with previews, plus Focus, screen recording, downloads, battery/charging — and a
calendar preview right alongside whatever's playing.

<p align="center">
  <img src="assets/music-panel.gif" alt="DynBar media player expanding into a panel with a calendar preview" width="700">
</p>

### System insight

CPU, GPU, memory, network, and disk, sampled live.

<p align="center">
  <img src="assets/stats.png" alt="DynBar system stats panel" width="700">
</p>

### Everyday utilities

Clipboard history, a ruler-style timer, colour picker, and a built-in terminal tab — plus a webcam
mirror, mounted-volume shortcuts, and lock-screen widgets for media, timers, and weather when the
Mac is asleep.

<table>
<tr>
<td width="50%" align="center" valign="top">
  <img src="assets/clipboard.png" alt="DynBar clipboard manager with recent text, colours, and files" width="380"><br>
  <sub><strong>Clipboard history</strong> — text, colours, images, and files.</sub>
</td>
<td width="50%" align="center" valign="top">
  <img src="assets/colorpicker.png" alt="DynBar colour picker with HEX, RGB, HSL, SwiftUI, and UIColor" width="380"><br>
  <sub><strong>Colour picker</strong> — HEX, RGB, HSL, SwiftUI, and UIColor at once.</sub>
</td>
</tr>
<tr>
<td width="50%" align="center" valign="top">
  <img src="assets/timer.png" alt="DynBar ruler-style timer" width="380"><br>
  <sub><strong>Ruler-style timer</strong> — drag to set, glance at the countdown.</sub>
</td>
<td width="50%" align="center" valign="top">
  <img src="assets/terminal.png" alt="DynBar built-in terminal tab" width="380"><br>
  <sub><strong>Built-in terminal</strong> — a full shell tab, without leaving the notch.</sub>
</td>
</tr>
</table>

## Download & install

1. **[Download the latest release](https://github.com/PlansbyStudio/DynBar-Updates/releases/latest)**
   and unzip it.
2. Move **DynBar.app** into your **Applications** folder.
3. DynBar is signed but not notarised, so macOS blocks the very first launch. **Right-click the app
   → Open** once (or open *System Settings → Privacy & Security* and choose **Open Anyway**). After
   that, it launches normally.
4. Grant the permissions DynBar asks for as you use each feature.

> **Why the extra click?** DynBar isn't distributed through the App Store. The one-time
> right-click → Open is macOS Gatekeeper asking you to confirm an app from outside the store. It's
> only needed the first time.

## Staying up to date

DynBar updates itself automatically. It checks this feed and offers new versions inside the app —
just click **Install** when prompted. You don't need to come back here to update.

Every release is delivered as a signed package, and DynBar verifies that signature before installing,
so updates are tamper-proof even without notarisation.

## Requirements

- **macOS 14 (Sonoma) or later**
- **Apple silicon** Mac
- A notch (14"/16" MacBook Pro) is ideal — DynBar also runs as a floating bar on Macs and external
  displays without one.

## Support

DynBar is made by **[PlansbyStudio](https://plansbystudio.de)**.
Found a bug or have an idea? Open an issue on this repository.

---

<details>
<summary><strong>About this repository</strong> (for the curious)</summary>

<br>

This is the **public update feed** for DynBar (the app's source repository is private).

- **`appcast.xml`** is the [Sparkle](https://sparkle-project.org) feed the app polls for updates.
- Each version is published here as a **GitHub Release** with a signed `DynBar-<version>.zip` asset,
  so every user's updater can reach both the feed and the download.
- Releases are produced automatically from the app repo — `appcast.xml` is generated, not
  hand-edited.

</details>

<p align="center">
  <sub>© PlansbyStudio · Released under the GPL v3 license</sub>
</p>
