# Re-run Macbuddy
 Utility to re-run Macbuddy, the macOS first-run setup assistant without erasing existing user data.

This has been tested on Apple Silicon and Intel devices, but NOT tested with FileVault or Intel devices with a T2 chip (~2018 and later). The installer will fail with the below error message if Find My Mac is enabled; please ensure that Find My Mac is disabled as per [HT208987](https://support.apple.com/HT208987) before running the installer.

![Find My Mac Error](https://github.com/toru173/Re-run-Macbuddy/blob/main/Screenshots/FMM%20Enabled.png)

The installer is not signed and therefore untrusted by macOS. Please follow the instructions [on Apple's website](https://support.apple.com/guide/mac-help/mh40616/mac) to install untrusted software. The document refers to control-clicking an application - the same action can be achieved with a right-click.

When completing the setup you may need to create an additional user that MUST have a different name to any existing user. This can be subsequently removed by following the instructions [on Apple's website](https://support.apple.com/guide/mac-help/mchlp1557/mac). A future version of this utility may remove the need for this step, if deemed necessary.

This is licensed with [the Unlicense](https://unlicense.org), but I would still appreciate a shout out or a thank you if this was useful!
