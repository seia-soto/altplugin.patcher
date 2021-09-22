## altplugin.patcher

`p` and `f` option will do code-sign the plug-in bundle again without adding `s` option.

```
altplugin.patcher by HoJeong Go (GitHub @seia-soto)

A shell script to patch AltPlugin (mail plug-in) Info.plist file to make plug-in compatible with macOS Monterey

Usage:
  ./altplugin.patcher [options]

  [-h]    Print help message and exit
  [-p]    Replace Mail Plug-In's Info.plist only from GitHub
  [-f]    Fully replace Mail Plug-In bundle from GitHub
  [-s]    Code sign Mail Plug-in only

Warnings:
  - The AltPlugin or AltStore is the software that made by @rileytestut and I didn't associated with them.
  - This script won't download or patch AltStore beta.
  - This script requires root permision.
  - Restart Mail application and enable AltPlugin again to take effect.

To uninstall/recover:
  - Reinstalling Mail Plugin-In from AltServer application is enough.
```
