# mtkclient-for-termux (KernelMasterX Edition)

> Mobile-optimized, root-free MediaTek flashing and research utility designed to run natively inside Termux.

---

## 🚀 About
**mtkclient-for-termux** is a specialized, mobile-optimized adaptation of the popular `mtkclient` tool, built to run directly on Android devices via Termux. It enables low-level partition management, backups, and recovery operations on MediaTek-based devices through BROM mode—completely **root-free**, leveraging `termux-usb` and `libusb` APIs.

## ✨ Features
* **Rootless Execution:** Direct USB communication via the `termux-usb` bridge without requiring superuser permissions.
* **Mobile Optimized:** Dependencies and configurations streamlined for seamless compilation and execution inside the Termux environment.
* **Low-Level Access:** Full control over critical partitions including Preloader, LK, Boot, Recovery, and VBMeta.
* **PC-Free Recovery:** Emergency intervention and rescue operations directly from a handheld device when a desktop computer is unavailable.

## 🛠️ Requirements
* **Termux** (Installed from F-Droid or modern sources; Google Play Store versions are outdated and not recommended).
* `termux-api` and core development tools.
* USB OTG cable and a target MediaTek device.

## 📥 Installation

Clone the repository directly into your Termux environment and get ready to run:

```bash
# Clone the repository
git clone [https://github.com/KernelMasterX/mtkclient-for-termux.git](https://github.com/KernelMasterX/mtkclient-for-termux.git)
cd mtkclient-for-termux

# Install required Python dependencies
pip install -r requirements.txt

⚠️ Disclaimer
​This tool interacts directly with low-level system components and memory addresses. Incorrect usage may result in a hard-brick state. Use at your own risk; all responsibility lies with the user executing the tools.
​Developed by KernelMasterX
