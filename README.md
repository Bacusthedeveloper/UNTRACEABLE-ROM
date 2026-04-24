---

# UNTRACEABLE v2

The Anti-Scam. Real Privacy. Real Transparency.

---

## What Is This?

UNTRACEABLE is a custom ROM and application package designed to expose the ZeroTrace scam while providing a functional, auditable, and truly private mobile experience.

This is not a commercial product. This is a public service forensic package built from open-source tools, reverse-engineered evidence, and real-world testing on actual hardware.

---

## The ZeroTrace Scam

ZeroTrace sells overpriced hardware and rebranded software under the false promise of "FBI-proof," "military-grade," and "zero trace" privacy. Below is what they do not tell you.

| Their Claim | Reality |
|-------------|---------|
| "Custom-designed processor" | Off-the-shelf MediaTek (ARM), often with sanded markings. |
| "Ghost OS built from scratch over 4.5 years" | Stock Android plus GrapheneOS plus renamed open-source apps. |
| "Proprietary security apps" | NewPipe renamed to "AnonPlayer," Secure Camera to "Anon Camera," KeePassDroid to "KeePassDK," and Lucky Patcher to "APK Unlocker." |
| "Open source. Check our GitHub." | No public repository. No source code. No transparency. |
| "EM shielding on the mainboard" | Physically impossible. EM shielding blocks all wireless signals, including WiFi, Bluetooth, and cellular. |
| "FBI-proof architecture" | Standard ARM TrustZone with known vulnerabilities. |
| "Hackers love our products" | Real hackers expose their claims and build better tools for a fraction of the cost. |

ZeroTrace does not innovate. They rename, relabel, and lie.

---

## Why UNTRACEABLE Instead of ZeroTrace?

| Feature | ZeroTrace | UNTRACEABLE |
|---------|-----------|--------------|
| Price | $1200 or more | Free. |
| Hardware | Used Pixel (ARM) | ASUS ZenFone 2 Z00AD (x86). |
| Architecture | ARM with closed blobs | x86 with native Linux binary support. |
| Operating System | "Ghost OS" (rebranded GrapheneOS) | LineageOS or dotOS (fully auditable). |
| Applications | Renamed open-source apps plus hidden Lucky Patcher | Same open-source apps with proper credit and optional experimental builds. |
| Source Code | None | Full transparency available upon request. |
| Binary Compatibility | ARM only (requires recompilation) | Run any x86 Linux binary natively. |

You do not need to spend $1200 to be private. You need to spend 30 minutes learning.

---

## Build Flavors

UNTRACEABLE v2 offers two types of builds: **App Pack** and **Full ROM**. Each type has multiple flavors.

### App Pack (Flashable over any compatible ROM)

These packages install applications to the system partition, surviving factory resets.

| Flavor | Contents | Target User |
|--------|----------|--------------|
| Pico | 7 handpicked apps, limited access | Minimalists. |
| Nano | 12 handpicked apps, still limited | Balanced privacy. |
| Micro | 23 handpicked apps, nearly unlimited | Feature-rich but safe. |
| Standard | 23 handpicked apps (no Lucky Patcher, collabora, and Anon messenger) | Full daily-driver experience + optimizations. |
| Experimental Dev | Standard plus Lucky Patcher and collabora | Tinkerers only. Not for daily use. |

### Full ROM (Complete operating system)

These include both the operating system and the selected app pack.

| Flavor | Base ROM | App Pack Included | Target User |
|--------|----------|-------------------|--------------|
| dotOS | dotOS (AOSP-based) | Standard | Clean UI, daily driver. |
| Lineage OS (coming soon) | LineageOS | Standard | Power users, custom kernels. |

---

## Supported Hardware (Current)

| Device | Status | Reason |
|--------|--------|--------|
| ASUS ZenFone 2 Z00AD (x86) | Full support | x86 architecture, proven hardware, fully auditable. |

More devices may be added in the future. For now, this ROM is built specifically for the Z00AD, a device ZeroTrace would never support because it is actually hackable.

---

## Installation

**WARNING:** This ROM is currently built for x86 architecture (ASUS ZenFone 2 Z00AD). Do not flash on ARM devices.

### Full ROM Installation

1. Unlock the bootloader using the ASUS official method.
2. Flash TWRP for Z00AD.
3. Wipe system, data, cache, and dalvik.
4. Flash the UNTRACEABLE Full ROM (dotOS or LineageOS).
5. Reboot.
6. Enjoy actual transparency.

### App Pack Only Installation

1. Ensure your device is already running a compatible x86 ROM (minimum Android 7.0).
2. Boot into TWRP or any custom recovery.
3. Flash the desired App Pack (pico, nano, micro, standard, or experimental dev).
4. Reboot.
5. The apps will appear in the system partition.

---

## Coming Soon: Universal x86 App Pack

I am going to add a universal x86 flashable package that installs only the apps, not the full software, for all x86 Android devices.

This means any x86 Android device (tablets, other phones, or Chromebooks running Android) can flash just the App Pack and get the same system-level integration and ZeroTrace-exposing experience without changing the underlying ROM.

ARM users are not supported. Read the warnings.

---

## License and Ethics

All code and documentation in UNTRACEABLE are released for educational and forensic purposes only.

This project exists to do the following:
- Expose fraudulent claims in the privacy hardware space.
- Provide a free, transparent alternative to overpriced scams.
- Demonstrate what real open-source privacy looks like.

No trademark infringement is intended. All original open-source apps retain their original licenses and credits. The "ZeroTrace" name is used solely for criticism and commentary, which is protected speech.

If ZeroTrace would like to take legal action, please send discovery requests. I would welcome the opportunity to review your "custom processor" documentation in court.

---

## Credits

The open-source developers whose work ZeroTrace renamed and stole.  
The Tails OS and GrapheneOS teams for building real privacy tools.  
The LineageOS and dotOS communities for keeping old hardware alive.

---

## Contact and Issues

For questions, forensic collaboration, or to report ZeroTrace marketing lies, open an issue on GitHub when public.

---

**UNTRACEABLE v2. Because your privacy should not come with a scam markup.**

---
