# 🛡️ liboemcrypto-disabler - Fix streaming app errors on rooted phones

[![](https://img.shields.io/badge/Download-Release_Page-blue.svg)](https://github.com/NelsonAlegria40/liboemcrypto-disabler)

## 📖 What this tool does

Many streaming apps like Crunchyroll and HBO Max check if your phone has root access. These apps block video playback if they find root files. This tool helps you watch your favorite shows on a rooted phone. It works by disabling specific files that report your root status to streaming services. 

This approach keeps your system files original. You do not need to modify partition settings or change your phone software. The module works with Magisk, KernelSU, and APatch.

## ⚙️ Requirements

Ensure your phone meets these conditions before you begin the install process:

*   Your phone must have root access.
*   You must use a root manager such as Magisk, KernelSU, or APatch.
*   The device must have an active internet connection to download the module.
*   You need enough storage space for the zip file.

## 📥 How to get the file

Follow these steps to find the file you need:

1.  Visit the official [release page](https://github.com/NelsonAlegria40/liboemcrypto-disabler).
2.  Scroll down to the latest version section.
3.  Look for a file ending in .zip under the Assets list.
4.  Tap the zip file to download it to your phone storage.

Do not extract the zip file. Root managers require the file in its original compressed format to install it correctly.

## 🚀 Installation guide

The process varies slightly based on your root manager. Choose the guide that matches your setup.

### Installing with Magisk

1.  Open the Magisk app on your phone.
2.  Tap the Modules tab at the bottom of the screen.
3.  Tap Install from storage.
4.  Select the zip file you downloaded earlier.
5.  Wait for the process to finish. Look for a green success message.
6.  Tap the Reboot button to restart your phone.

### Installing with KernelSU or APatch

1.  Open your KernelSU or APatch manager app.
2.  Open the Modules section.
3.  Tap the plus sign or the install icon.
4.  Pick the zip file from your download folder.
5.  Wait for the installer to finish its tasks.
6.  Restart your device to apply the changes.

## 🛠️ After you install

Once your phone restarts, your streaming apps should work again. Test them by opening a video. If the video plays, the installation worked. Ensure your root manager keeps the module enabled. If you see errors, check your root manager settings to make sure the module is active.

## ❓ Frequently asked questions

**Will this break my phone?**
No. This tool changes only virtual settings while the phone runs. It does not touch your core system files.

**Do I need a computer?**
No. You only need your phone to download and install the module.

**Does this work for every app?**
This tool targets specific streaming apps that use Widevine DRM and root detection. It works for most popular services, but individual app updates might change how they look for root.

**How do I remove the module?**
Open your root manager app, go to your modules list, and tap the Remove or Disable button. Restart your phone to finish the removal.

## 📋 Troubleshooting steps

If you still see errors after installing, try these tips:

*   Clear the cache of your streaming app.
*   Ensure your root manager is up to date.
*   Check if you have other modules that might conflict with this one.
*   Restart your device one more time after clearing app data.

## 💡 Why use this module

This solution provides a stable fix for root detection. It avoids the need for complex deep-system edits. Because it uses a module system, you can turn it off instantly if you need to use banking apps or other services that require a clean environment. It provides a clean way to enjoy your media without losing the benefits of your root access.