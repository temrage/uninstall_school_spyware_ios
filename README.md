<p align="center">
  <img src="https://i.imgur.com/ec0RaHP.png" width="20%" alt="UNINSTALL_SCHOOL_SPYWARE_IOS-logo">
</p>
<p align="center">
    <h1 align="center">UNINSTALL_SCHOOL_SPYWARE_IOS</h1>
</p>
<p align="center">
	<img src="https://img.shields.io/github/license/temrage/uninstall_school_spyware_ios?style=flat&logo=opensourceinitiative&logoColor=white&color=0080ff" alt="license">
	<img src="https://img.shields.io/github/last-commit/temrage/uninstall_school_spyware_ios?style=flat&logo=git&logoColor=white&color=0080ff" alt="last-commit">
	<img src="https://img.shields.io/github/languages/top/temrage/uninstall_school_spyware_ios?style=flat&color=0080ff" alt="repo-top-language">
	<img src="https://img.shields.io/github/languages/count/temrage/uninstall_school_spyware_ios?style=flat&color=0080ff" alt="repo-language-count">
# 📱 iOS/iPadOS Proxy & MDM Removal Guide

This guide will walk you through how to remove the Securly proxy and MDM profiles from your iOS/iPadOS device.

> ❗ **Important Notes**  
> - DO NOT remove the SSL certificate if your school uses SSL inspection. The certificate (ca.secururs-software) might be critical for secure access.

---

## 🔒 Removing the Securly Proxy

Follow these steps to remove the Securly proxy from your device:

1. Go to **Settings** → **General** → **VPN, DNS, & Device Management**
2. Delete all configuration profiles containing the name `".securly.com"`

For more detailed instructions, visit [Securly's official guide](https://support.securly.com/hc/en-us/articles/360040183593-How-to-uninstall-the-Securly-SSL-Certificate-from-BYOD-devices).

---

## 🛡️ Removing MDM Profiles

To remove the MDM (Mobile Device Management) profile, follow these steps:

1. Go to **Settings** → **General** → **VPN, DNS, & Device Management**
2. Delete any MDM profiles signed by `"mdm.manageengine.com"`

For further details, visit [Zoho Corp's guide](https://www.manageengine.com/products/desktop-central/agent-uninstallation-methods.html).

---

> ❗ **Troubleshooting Tips**  
> - If your internet stops working, try forgetting your Wi-Fi network and reconnecting.
> - If you encounter an HTTPS error (such as "Your connection is not private"), follow the instructions on the [SSL Inspection page](https://github.com/temrage/school_ssl_inspection) to resolve the issue.

---

Feel free to refer to these resources for more guidance, and proceed with caution when modifying your device’s configurations! 🔧
