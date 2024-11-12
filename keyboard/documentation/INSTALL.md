# Installation
Ready to start typing in Meriteji effortlessly? Add a Unicode keyboard to your device and use [this chart](/unicode/Meriteji%20Syllables%20Specification.pdf) to add each syllable, provided you have the right font to support it.\
Okay, okay. That *works*, but there's a much better solution. Currently supported for Mac, with Windows support coming soon, you can type directly into complete syllable blocks.
> [!NOTE]
> Ligatures (OpenType feature `rlig`) must be turned on so that adjacent Meriteji *jin* display correctly. This should be on by default for most software, but if not, manual Unicode entry must be used to produce correct syllable blocks.
## macOS
### 1. Download
Download the [latest release](https://github.com/meritite-union/meriteji/releases/latest) right here on GitHub:
`Meriteji Keyboard Installer.dmg`
### 2. Gatekeeper bypass
Open `Meriteji Keyboard Installer`. You will see a very scary security warning, essentially telling you that my keyboard wasn't officially notarized by Apple. At this point, you'll have to just trust me. It is your choice, but to proceed you will have to work against Apple's warnings several times. Your Mac will tell you that the app is damaged and can't be opened. Open System Settings > Security & Privacy > **Open anyway**. From there, it will still say it's broken. Go back to the app icon and open it again. From there, click **Open** and **Use Password...** and enter an administrator password to force your Mac to open the app.
<details>
<summary>Screenshots</summary>
<picture>
  <source media="(prefers-color-scheme: dark)" srcset="/keyboard/documentation/images/diskimage-dark.png">
  <source media="(prefers-color-scheme: light)" srcset="/keyboard/documentation/images/diskimage-light.png">
  <img alt="Disk image example with app and keyboard" src="/keyboard/documentation/images/diskimage-light.png" width="75%">
</picture>
<picture>
  <source media="(prefers-color-scheme: dark)" srcset="/keyboard/documentation/images/settings-dark.png">
  <source media="(prefers-color-scheme: light)" srcset="/keyboard/documentation/images/settings-light.png">
  <img alt="Disk image example with app and keyboard" src="/keyboard/documentation/images/settings-light.png" width="75%">
</picture>
<picture>
  <img alt="First warning from macOS." src="/keyboard/documentation/images/first-warning.png" width="25%">
</picture>
<picture>
  <img alt="Second warning from macOS." src="/keyboard/documentation/images/second-warning.png" width="25%">
</picture>
<picture>
  <img alt="Third warning from macOS." src="/keyboard/documentation/images/third-warning.png" width="25%">
</picture>
</details>

### 3. Installation
Well, that was scary! Sorry about that, but I promise you'll be okay! To complete the installation, you'll need to drag `Meriteji.keylayout` to the area at the bottom of the app, and then click **Install for current user**. The app will close, and that is it! Feel free to delete any other files, they are now installed on your system.
### 4. Restart and you're done!

### 5. Uninstallation
To remove Meriteji as an input method, go to System Settings > Keyboard > Input Sources (Under "Text Input") > **Edit...** > Meriteji > **-**.
To fully remove Meriteji from your system, 
