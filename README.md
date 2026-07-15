# Flarex Raw — one-knob stereo width

![Flarex Raw](https://raw.githubusercontent.com/RemiBlaze/FlarexRaw/main/flarexraw-ui-screenshot.png)

**One knob. Turn it up to open the stereo image — always mono-safe.**

Flarex Raw is the free, one-knob version of **Flarex**, Remi Blaze's stereo width and imaging tool. Turn the single WIDTH knob to spread synths, pads, and vocals across the field while the low end stays locked to mono, so it never phase-cancels on club systems.

Fully **signed and notarized** for macOS as **AU, VST3, and Standalone**.

---

## 🚀 Download & Install
1. Go to the [latest release](https://github.com/RemiBlaze/FlarexRaw/releases/latest).
2. Download **`FlarexRaw_Installer.pkg`**.
3. Double-click it and follow the installer. Signed & notarized by Apple — installs cleanly, no security warnings.
4. Restart your DAW and rescan plug-ins.

Full guide: **[remiblaze.com/support](https://remiblaze.com/support/)**.

---

## 🎛️ What It Does
One big **WIDTH** knob is the entire control surface. Turn it up and the stereo image opens — from mono-tight at the bottom of the range to a wide, decorrelated field at the top. Under the hood it runs a mid/side imager: at low settings the field stays centered, and as you push it, all-pass decorrelation widens the sides for a bigger image that still collapses cleanly to mono.

Mono compatibility is built in and always on — a bass-mono crossover keeps low frequencies summed to the center, and a phase-correlation safety net pulls the width back automatically if the signal ever drifts toward cancellation. You get a wider mix without the phase problems.

---

## 💻 System Requirements
- macOS 15.0 or later
- Apple Silicon or Intel Mac (Universal Binary)
- Any AU or VST3 host (your DAW of choice)

---

## 🐛 Bugs & Issues
Open an issue on the **[Issues](https://github.com/RemiBlaze/FlarexRaw/issues)** tab with your macOS version, DAW + version, and steps to reproduce.

---

## 📄 License & Credits
- **Developer:** [Remi Blaze](https://remiblaze.com).
- **Framework:** [JUCE](https://juce.com).
- **License:** free under a proprietary [Freeware License](LICENSE) (see also our [terms](https://remiblaze.com/terms/)). Reverse-engineering, repackaging, binary redistribution, or reselling the compiled installer is strictly prohibited.

---

## Trademarks

All product names, company names, and logos mentioned herein are trademarks or registered trademarks of their respective owners. Any such references are used for descriptive or compatibility purposes only and do not imply affiliation with, endorsement by, or sponsorship from their owners.

VST is a trademark of Steinberg Media Technologies GmbH, registered in Europe and other countries.

Apple, macOS, Audio Units (AU), and Apple Silicon are trademarks of Apple Inc., registered in the U.S. and other countries.
