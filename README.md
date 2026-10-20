<div align="center">

<img src="assets/victorious-framework-logo.png" alt="Victorious Framework" width="900" />

<p align="center">
  <a href="https://preview.victorious-framework.pages.dev/"><img src="https://img.shields.io/badge/Victorious_Framework-Website-FFB000?style=for-the-badge&labelColor=0A0F1F&color=FFB000" alt="Victorious Framework website" /></a>
  <a href="https://victorious-designs.pages.dev"><img src="https://img.shields.io/badge/Victorious_Designs-Website-FF2E97?style=for-the-badge&labelColor=0A0F1F&color=FF2E97" alt="Victorious Designs website" /></a>
</p>

</div>

# Victorious Framework

The Victorious fleet of Android tools, on-device AI agents, and Linux installers. The apps run separately and connect to one hub app, [droidcommand-AI](https://github.com/Victorious93/droidcommand-AI).

- **Fleet manifest:** [fleet-manifest.json](https://victorious93.github.io/fleet-manifest/fleet-manifest.json)
- **Maintainer:** [Don (@Victorious93)](https://github.com/Victorious93)

> [!NOTE]
> Most of these projects are in **early development**. Each repo's README says what has and hasn't been tested on real hardware.

<p align="center"><img src="assets/logos/victorious-framework-hoodie-brand.png" alt="Victorious Framework" width="280"></p>

## 🛰️ Victorious fleet

Grouped by how each app connects to the hub. Package IDs are shown where the project defines one. Private repos are listed by name only.

**Controller / Hub**

### <img src="assets/logos/droidcommand-logo.jpg" alt="droidcommand-AI" width="64" valign="middle"> droidcommand-AI

- **Repo:** [Victorious93/droidcommand-AI](https://github.com/Victorious93/droidcommand-AI)
- **Package id:** `ai.droidcommand.app`
- **Purpose:** The fleet controller/brain — remote command and orchestration of every app in the fleet.

### <img src="assets/logos/pyraclaw-logo.jpg" alt="Pyra Claw" width="64" valign="middle"> Pyra Claw

- **Repo:** pyra-claw *(private)*
- **Package id:** *(hub / hardware — not an Android package)*
- **Purpose:** Raspberry Pi 5 + ESP32 command hub that bridges the phone controller to physical devices.

### <img src="assets/logos/victormodem-logo.jpg" alt="VictorModem" width="64" valign="middle"> VictorModem *(in planning)*

- **Repo:** victormodem *(private)*
- **Package id:** *(in planning / hardware — no confirmed package id yet)*
- **Purpose:** ESP32-S3 + cellular modem board that gives the fleet an independent second line.

**Bound Companions**

### <img src="assets/logos/hackerai-logo.jpg" alt="HackerAI-Commander" width="64" valign="middle"> HackerAI-Commander

- **Repo:** [Victorious93/HackerAI-Commander](https://github.com/Victorious93/HackerAI-Commander)
- **Package id:** `ai.hackerai.companion`
- **Purpose:** Companion to the `hackeraiETC` fork — an AI hacking assistant.

### <img src="assets/logos/pentest-swarm-logo.png" alt="Pentest-Swarm-AI" width="64" valign="middle"> Pentest-Swarm-AI

- **Repo:** [Victorious93/Pentest-Swarm-AI](https://github.com/Victorious93/Pentest-Swarm-AI)
- **Package id:** `ai.pentestswarm.companion`
- **Purpose:** Multi-agent pentest swarm companion.

### <img src="assets/logos/edl-commander-logo.png" alt="EDL-Commander" width="64" valign="middle"> EDL-Commander

- **Repo:** [Victorious93/EDL-Commander](https://github.com/Victorious93/EDL-Commander)
- **Package id:** `ai.edlcommander.companion`
- **Purpose:** Safety-first Qualcomm EDL (Emergency Download mode) framework/tool companion.

**External Nodes**

### <img src="assets/logos/rootforge-logo.jpg" alt="rootforge-os" width="64" valign="middle"> rootforge-os

- **Repo:** [Victorious93/rootforge-os](https://github.com/Victorious93/rootforge-os)
- **Package id:** `ai.rootforge.os`
- **Purpose:** Android rooting / root-management app.

### <img src="assets/logos/file-manager-logo.png" alt="File-Manager" width="64" valign="middle"> File-Manager

- **Repo:** [Victorious93/File-Manager](https://github.com/Victorious93/File-Manager)
- **Package id:** `ai.victorious.filemanager` (debug: `ai.victorious.filemanager.debug`) *(rename in progress — repo still uses `ai.victorious.victorfiles`)*
- **Purpose:** Dual-pane power-user file manager aiming to beat MT Manager VIP.

#### Victorious-Keyboard *(logo pending)*

- **Repo:** [Victorious93/Victorious-Keyboard](https://github.com/Victorious93/Victorious-Keyboard)
- **Package id:** `com.victorious.keyboard` *(code namespace still `dev.patrickgold.florisboard` — rename queued)*
- **Purpose:** Custom Android keyboard with integrated media controls.

### <img src="assets/logos/victorious-flash-logo.png" alt="Victorious Flash (Distro Installer)" width="64" valign="middle"> Victorious Flash (Distro Installer)

- **Repo:** [Victorious93/victorious-flash](https://github.com/Victorious93/victorious-flash) *(desktop app)*
- **Package id:** `com.victorious.flash.android` *(desktop app — not an APK)*
- **Purpose:** Desktop app to pick a Linux distro, download its official ISO, and write it to USB.

### <img src="assets/logos/victorious-mesh-logo.jpg" alt="Victorious Mesh" width="64" valign="middle"> Victorious Mesh

- **Repo:** [Victorious93/victorious-mesh](https://github.com/Victorious93/victorious-mesh)
- **Package id:** `com.victorious.mesh`
- **Purpose:** Secure mesh-networking / VPN Android app.

### <img src="assets/logos/victorious-browser-logo.jpg" alt="Victorious Browser" width="64" valign="middle"> Victorious Browser

- **Repo:** [Victorious93/victorious-browser](https://github.com/Victorious93/victorious-browser)
- **Package id:** `com.victorious.browser`
- **Purpose:** Fleet security / recon browser with web interception.

### <img src="assets/logos/victorsms-logo.jpg" alt="VictorSMS" width="64" valign="middle"> VictorSMS

- **Repo:** victorsms *(private)*
- **Package id:** `com.victorious.sms`
- **Purpose:** Universal messaging app (Matrix-based) with voice cloning and persona learning.

### <img src="assets/logos/victorlaunch-logo.jpg" alt="VictorLaunch" width="64" valign="middle"> VictorLaunch

- **Repo:** victorlaunch *(private)*
- **Package id:** `com.victorious.launch`
- **Purpose:** Nova-class, Lawnchair-based fleet home-screen launcher.

### <img src="assets/logos/victorspoof-logo.jpg" alt="VictorSpoof" width="64" valign="middle"> VictorSpoof

- **Repo:** victorspoof *(private)*
- **Package id:** `com.victorious.spoof`
- **Purpose:** Legal novelty / prank caller-ID app with strict compliance guardrails.

### <img src="assets/logos/victorlink64-logo.png" alt="VictorLink64" width="64" valign="middle"> VictorLink64

- **Repo:** [Victorious93/VictorLink64](https://github.com/Victorious93/VictorLink64)
- **Package id:** `org.victoriousframework.victorlink64` *(Kotlin / Jetpack Compose; Android 9+)*
- **Purpose:** Multi-game emulator + play hub — play N64 and SNES games, built-in chess, and multiplayer with friends — in one Android app.

### <img src="assets/logos/victorcam-logo.jpg" alt="VictorCam" width="64" valign="middle"> VictorCam

- **Repo:** VictorCam *(not public)*
- **Package id:** `com.victorious.cam`
- **Purpose:** OBS-style virtual camera APK.

**Termux / Host**

### <img src="assets/logos/victorsuite-logo.png" alt="VictorSuite" width="64" valign="middle"> VictorSuite

- **Repo:** [Victorious93/VictorSuite](https://github.com/Victorious93/VictorSuite)
- **Package id:** `com.termux` (lineage; `TERMUX_IPC`)
- **Purpose:** Termux-based Android Linux suite — the fleet home for container-style workloads.

### <img src="assets/logos/kyc-auditlab-logo.png" alt="KYC-AuditLab / IdentityShield" width="64" valign="middle"> KYC-AuditLab / IdentityShield

- **Repo:** [Victorious93/KYC-AuditLab](https://github.com/Victorious93/KYC-AuditLab)
- **Package id:** `com.identityshield.companion`
- **Purpose:** Local KYC / identity audit lab.

### <img src="assets/logos/bakerpi-logo.jpg" alt="BakerPi-Installer" width="64" valign="middle"> BakerPi-Installer

- **Repo:** [Victorious93/BakerPi-Installer](https://github.com/Victorious93/BakerPi-Installer)
- **Package id:** *(cross-platform tool — n/a)*
- **Purpose:** Cross-platform tool that installs/flashes in Raspberry Pi imaging style.

### DreamOS-Victorious

- **Repo:** [Victorious93/DreamOS-Victorious](https://github.com/Victorious93/DreamOS-Victorious)
- **Purpose:** Phase 1 Android ROM source integration foundation: host-side profile validator, reproducible source bundle and SHA-256 integrity verifier (not flashable).

**Social / Marketplace Apps**

### <img src="assets/logos/matchvictorious-logo.jpg" alt="MatchVictorious" width="64" valign="middle"> MatchVictorious

- **Repo:** [Victorious93/matchvictorious](https://github.com/Victorious93/matchvictorious)
- **Package id:** `com.victorious.match`
- **Purpose:** Dating app.

### <img src="assets/logos/victorpedigree-logo.jpg" alt="VictoryPed" width="64" valign="middle"> VictoryPed

- **Repo:** VictoryPed *(private)*
- **Package id:** `com.victorious.victoryped`
- **Purpose:** Social network and marketplace for bully breeders.

**Games**

### <img src="assets/logos/victorops-zombies-logo.jpg" alt="VictorOps Zombies" width="64" valign="middle"> VictorOps Zombies

- **Repo:** victorops-zombies *(private)*
- **Purpose:** Original CODBOZ-style wave-survival zombies game for Android.
