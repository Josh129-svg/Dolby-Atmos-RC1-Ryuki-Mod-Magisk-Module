# Dolby Atmos RC1 Ryuki Mod Magisk Module

## Descriptions
- An EQ based on Dolby Atmos RC1 from @guitardedhero.
- Bloobs known modded from ZTE A2019 Pro for 64 bit and Lenovo TB-7305I for 32 bit.
- Doesn't work with dynamic partitions

## Requirements
- Android 9, 10, or 11 64 and 32 bit devices
- Magisk installed

## Installation Guide
- Remove another Dolby module
- Disable stock dax Service app
- Reboot
- Install via Magisk Manager only
- Reboot

## Optional
- If using multiple audio mods, use one of these bellow, don't use both:
  - AML 4.0 supported
  - ACDB supported (Android 10 and bellow only for now)
- You can rename dap-default extension to use more bass enhancer boost. See /data/adb/modules_update/DolbyAtmos/system/vendor/etc/dolby

## Troubleshooting
- If Dolby force close, just reinstall again.
- Make sure manifest.xml is patched correctly.
- Use Audio Compatibility Patch if you encounter processing problem.
- If se patch still fail even added to sepolicy.rule, then add `setenforce 0` to the top of service.sh. Give logcats for fix.
- If you have some issues, like ringtones, alarm tones doesn't work, or calls opposite person doesn't hear, [do this fix.](https://t.me/audioryukimods/543)

## Attention!
- Reporting anything without sending full logcats and install process logs is ignored!
https://play.google.com/store/apps/details?id=com.dp.logcatapp
- Send run also:
  - `su`
  - `dumpsys media.audio_flinger`

## Credits
- @guitardedhero

           - Enjoy the Atmos 🎧 -
