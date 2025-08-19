# Common Issues and fixes :)

This document lists common problems when sideloading apps on iOS and provides simple solutions.

### Table of Contents
1. [“Unable to verify” error](#1-“unable-to-verify”-error)
2. [App crashes immediately after opening](#2-app-crashes-immediately-after-opening)
3. [Portal signer gives an error message](#3-portal-signer-gives-an-error-message)
4. [Installation fails](#4-installation-fails)
5. [Config is shown as "not signed"](#5-the-config-is-shown-as-not-signed)
6. [Unable to Install "Resident Evil 4"](#6-unable-to-install-resident-evil-4)

---

## 1. “Unable to verify” error

* **Problem**: The **PPQ** is blocked by the **DNS** at the initial setup.
* **Fix**: Go to **Settings** → **General** → **VPN & Device Management** → **DNS**. Change that to **"INSTALL ONLY"** and then try again. It may take a few seconds to apply.

## 2. App crashes immediately after opening

* **Problem**: This is often caused by expired certificates or a broken `.ipa` file.
* **Fix**: Either switch the **certificate** to another one or try to find a different, working `.ipa` file to install.

## 3. Portal signer gives an error message

* **Problem**: This can happen because of a problem with the **API** or if your **WiFi** connection isn’t stable. The errors can include **"Error: The request timed out"** or **"Error: A TLS error caused the secure connection to fail."**
* **Fix**: You can use one of these alternative signing websites:
    1.  [https://wsfteam.xyz/#signer](https://wsfteam.xyz/#signer)
    2.  [https://sign.ipasign.cc/](https://sign.ipasign.cc/)
    3.  [https://sign.kravasign.com](https://sign.kravasign.com)

## 4. Installation fails

* **Problem**: This can be caused by an unsupported **iOS** version or a corrupted `.ipa` file.
* **Fix**: Ensure the `.ipa` is compatible with your **iOS** version and make sure the `.ipa` is a working file.

## 5. The config is shown as “not signed”

* **Problem**: This is normal since they are not signed by Apple and they likely won’t be.
* **Fix**: Do not worry; this status is expected and does not indicate an error.

## 6. Unable to Install "Resident Evil 4"

* **Problem**: Even if you have done everything correctly, **iOS** sometimes caches a failed validation from a previous attempt.
* **Fix**: Reboot your device and try installing again.

---

### Final tip
Join the **[Discord server](https://wsfteam.xyz/discord)** for more help and support. 
