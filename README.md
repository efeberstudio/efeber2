<p align="center"><img src="assets/efeber2.svg" width="100" alt="EFEBER2"></p>
<h1 align="center">EFEBER2 — GLIDE MODDING STUDIO</h1>
<p align="center"><strong>Turn GTA vehicles into Garry's Mod Glide addons. Convert Simfphys Workshop vehicles to Glide.</strong></p>
<p align="center">
<img src="https://img.shields.io/badge/Windows-64--bit-202020" alt="Windows">
<img src="https://img.shields.io/badge/Release-Beta%200.6-E53935" alt="Beta 0.6">
<img src="https://img.shields.io/badge/Focus-Glide%20Vehicles-C62828" alt="Glide Vehicles">
</p>
<p align="center"><a href="https://github.com/efeberstudio/efeber2/releases"><strong>⬇ DOWNLOAD EFEBER2</strong></a> · <a href="docs/INSTALLATION.md">Getting Started</a> · <a href="docs/FAQ.md">FAQ</a> · <a href="https://github.com/efeberstudio/efeber2/issues">Report an Issue</a></p>
<p align="center"><strong>English</strong> | <a href="docs/tr/README.md">Türkçe</a></p>

---

## Build Glide vehicles without the usual complexity

**EFEBER2 is a Windows modding studio built around Garry's Mod's Glide vehicle system.** Import supported GTA San Andreas and GTA V Legacy vehicle assets, configure your vehicle in a visual editor, and export a Glide addon. You can also attempt to convert compatible **Simfphys Steam Workshop vehicles directly into Glide addons**.

Instead of manually juggling meshes, textures, wheel positions, seats, sounds, and vehicle configurations, EFEBER2 brings the workflow together in one place.

> **Public beta notice:** EFEBER2 is still in active development. Compatibility depends on the original mod, and some vehicles require manual adjustments. Always test your exported vehicle in Garry's Mod.

## 🚗 GTA → Glide Vehicle Studio

**Create a custom Glide vehicle from supported GTA assets.**

- Import **GTA San Andreas DFF/TXD** and supported **GTA V Legacy** vehicle assets
- Inspect models in an interactive **3D viewport**
- Select, edit, and scale individual parts or the whole vehicle
- Adjust **wheel positions, driver seat, and passenger seats**
- Preview seat alignment using human-sized references and a transparent car body
- Edit materials, textures, and selectable paintable body parts
- Choose **vehicle name, engine sound, and horn**
- Select driving presets: **Normal Car, Sports Car, Light Commercial, Minibus, Heavy Vehicle**
- Generate the vehicle's model and configuration for **Glide**

### Typical workflow

**Import a GTA vehicle → Inspect and scale → Set wheels and seats → Select materials and sounds → Choose a driving preset → Export for Glide.**

## 🔄 Simfphys → Glide Converter

**Already have a Simfphys vehicle from the Steam Workshop? Give it a new life in Glide.**

1. Copy the supported vehicle's **Steam Workshop URL**.
2. Paste it into **Simfphys → Glide** in EFEBER2.
3. Start the conversion.
4. Test the generated Glide addon in Garry's Mod.

EFEBER2 attempts to extract and translate supported vehicle definitions, assets, wheel positions, seat information, and dependencies. Multi-vehicle packages may also be supported.

**Important:** Simfphys vehicles often use custom wheel models, suspension, attachments, and seating arrangements. Some conversions may require additional correction; one-click conversion is not a universal compatibility guarantee.

## 🧍 GMod Player Model Tools

A secondary toolkit for preparing supported character models as **Garry's Mod player models**, including texture/UV and skeleton preparation. **CS2 export is not part of this beta.**

---

## Download and install

**Current documented version:** `efeber2_beta_0.6` · Windows 10/11 (64-bit)

### **[⬇ Get EFEBER2 from GitHub Releases](https://github.com/efeberstudio/efeber2/releases)**

Open the release, expand **Assets**, and download `efeber2_beta_0.6.exe` if it is listed. The Windows executable is distributed through Releases, not the repository's source file list.

**Requirements:** Windows 64-bit; Garry's Mod and the Glide addon to play exported Glide vehicles. Depending on your source mod, additional extraction or compilation dependencies may apply.

**[Read the installation and Glide conversion guide →](docs/INSTALLATION.md)**

## Frequently asked questions

**Does EFEBER2 work with every GTA or Simfphys vehicle?**  
No. Source models differ in axes, materials, wheels, suspension, and seat attachments. Some need manual work.

**Does choosing Sports Car change how the car drives?**  
The preset changes supported Glide configuration and physics values. Results depend on the vehicle and require in-game testing.

**Can I convert a Simfphys Workshop item just by pasting the URL?**  
That is the intended workflow for supported mods, but Workshop access, dependencies, or custom vehicle systems may need extra steps.

**Is this an official Glide product?**  
No. EFEBER2 is an independent community project, not affiliated with Glide's developers.

**Is this repository open-source?**  
Not currently. This repository provides documentation, beta announcements, and download links; no open-source license is granted for unpublished source code.

**[Read the complete FAQ →](docs/FAQ.md)**

## Help improve EFEBER2

Encountered a problem with wheel alignment, driver positioning, a texture, or a conversion? Please [open an issue](https://github.com/efeberstudio/efeber2/issues) and include the app version, source Workshop URL (when applicable), reproduction steps, and a screenshot or error log.

[Installation](docs/INSTALLATION.md) · [FAQ](docs/FAQ.md) · [Changelog](CHANGELOG.md) · [Beta 0.6 release notes](docs/RELEASE_0.6.md) · [Türkçe](docs/tr/README.md)

---

<p align="center"><strong>EFEBER2</strong> — Built for the Garry's Mod modding community.</p>
<p align="center"><sub>Independent community project. Not affiliated with or endorsed by Facepunch, Valve, Rockstar Games, or the Glide development team. Respect third-party mod authors' permissions.</sub></p>