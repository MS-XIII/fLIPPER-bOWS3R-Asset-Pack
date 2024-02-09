<div align="center">
    <h1>🏴‍☠️ Bows3r asset pack 🏴‍☠️</h1>
    <p><i>"Do you fear death? Do you fear that dark abyss? All your deeds laid bare, all your sins punished?"</i><p>
</div>

## ℹ️ Introduction

This is a custom asset pack that I built for my Flipper Zero. The main theme is Bows3r of the Caribbean and all the animations are based on scenes taken from the various movies. If you want to install the pack on your Flipper check the section [below](#-installation).

> [!NOTE]
> This asset pack is a working in progress. New animations and icons will be added in the future.

## 🐬 Firmwares support

*Note: the asset pack has been created primarly for Xtreme firmware.*

| Firmware | Animations | Fonts | Icons |
| :--- | :---: | :---: | :---: |
| Official | ✅ | ❌ | ❓ |
| Xtreme | ✅ | ✅ | ✅ |
| Unleashed | ✅ | ❌ | ❓ |
| RogueMaster | ✅ | ❌ | ❓ |

- ✅ = tested and working
- ❌ = not supported
- ❓ = not tested

## 🚀 Installation

> [!TIP]
> Want to take a look before installing the pack on your flipper? Check the section [below](#-showcase).

To install the asset pack, download the zipped pack on your computer using the link below, extract it and copy the directory on your Flipper's SD (follow the instructions for your firmware):
- **Official firmware**:
    1. Replace the directory `SD Card/dolphin` with the directory `dolphin` extracted from the zip file
    2. Restart your Flipper
- **Xtreme firmware**:
    1. Copy the directory `Bows3r/` extracted from the zip file inside `SD Card/asset_packs`
    2. Open `Xtreme` > `Interface` > `Graphics` and select `Bows3r` in `Asset Pack`
- **RogueMaster firmware**:
    1. Copy all the files extracted from the zip file inside the directory `SD Card/dolphin` of your Flipper
    2. Open `CFW Settings` > `Interface` > `Desktop` and select `Bows3r` in `Animations`
- **Unleashed firmware**:
    1. Replace the directory `SD Card/dolphin` with the directory `dolphin` extracted from the zip file
    2. Restart your Flipper

**Note: you can also install single animations instead of all the asset pack but you need to update the Manifest file.**

### ⚙️ Building the pack locally

1. Clone the repo locally:
```sh
git clone https://github.com/MS-XIII/Flipper-Zero.git
```
2. Inside the repo directory, download `asset_packer.py` script from Xtreme Github repo following this [guide](https://github.com/Flipper-XFW/Xtreme-Firmware/wiki/Asset-Packs#cool-i-read-all-that-but-how-do-i-make-one).
3. Compile the pack:
```sh
./asset_packer.py
```
4. Done. You can find all the assets inside `asset_packs/Bows3r` directory.

## 🥇 Credits

Without the following people I wouldn't be able to made this pack... so shout out to them!

- [Talking Sasquach - The Ultimate Guide to Flipper Zero Animations!!](https://www.youtube.com/watch?v=trpcZLlJtNw)
- [Talking Sasquach - "Flipper Zero Animation Process"](https://tinyurl.com/squach)
