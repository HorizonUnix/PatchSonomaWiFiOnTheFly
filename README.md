# NativeSonomaOOBEWiFiPatch
Patch the modern Broadcom Wi-Fi card on the fly during the installation of macOS Sonoma without interruption

## Prepare

- Latest [`AutoPkgInstaller.kext`](https://github.com/dortania/OpenCore-Legacy-Patcher/blob/main/payloads/Kexts/Acidanthera/) from OCLP
- Latest [`AutoPkg-Assets.pkg`](https://github.com/dortania/OpenCore-Legacy-Patcher/releases/latest/download/AutoPkg-Assets.pkg) from OCLP
- A USB/Hard drive macOS Sonoma Installer

## 1. Prepare `config.plist`
Follow this [guide](https://github.com/perez987/Broadcom-wifi-back-on-macOS-Sonoma-by-OCLP) by [perez987](https://github.com/perez987) to prepare your `config.plist`
## 2. Prepare a USB/Hard drive macOS Installer
Follow this example [guide](https://support.apple.com/en-vn/101578) from Apple or any other sources
## 3. Prepare Kext and Pkg Files
