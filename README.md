# A workflow file that generates macOS Tahoe recovery image

### Full installer downloaded straight from Apple and then recover image is extracted

## 🚨Updates🚨

I renamed `Generate macOS Tahoe Recovery Image` workflow to `Tahoe Beta 1 Recovery Image`, this will always generate the recovery image for the first beta of Tahoe.

But if you are looking for the latest beta recovery image run `Tahoe Beta (latest) Recovery Image`

For public release `Tahoe Public Recovery Image`

# Why you may need this ?

Without the recovery image, you need to be on macOS to install Tahoe. Since there's no stable release yet, no official recovery images are available either.
This repo will fetch the full beta installer and zip what you need to have in order to install Tahoe from recovery.

# How to use this ?

Fork this repo and run `Generate macOS Tahoe Recovery Image` worflow for Beta or `Tahoe Public Recovery Image` for Public.

Once done you will have com.apple.recovery.boot.zip artifact

Unzip it and you will have com.apple.recovery.boot

Continue with https://dortania.github.io/OpenCore-Install-Guide/installer-guide/windows-install.html

or if you are on Linux https://dortania.github.io/OpenCore-Install-Guide/installer-guide/linux-install.html

you can skip the Downloading macOS part as this repo will do that for you

## ⚠️ Legal Notice & Disclaimer

## This project does not distribute, modify, or host any Apple software.

- I do not own or claim ownership of any Apple software referenced or downloaded.

- This project is for educational and personal use only.

- No warranty or guarantee is provided—use at your own risk.

- Apple, macOS, and related marks are trademarks of Apple Inc., registered in the U.S. and other countries.
