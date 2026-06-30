# 📖 syncery.koplugin - Keep your reading progress in sync

[![Download link](https://img.shields.io/badge/Download-Release_Page-blue)](https://github.com/Genusovismachismo683/syncery.koplugin/releases)

This software manages your reading data across multiple devices. It tracks your current page, highlights, and book settings. You enjoy the same reading experience whether you use a tablet or an e-ink reader. 

## ⚙️ Requirements

You need a device that runs KOReader. This plugin works on Android, Kobo, and Kindle devices. Ensure your device connects to the internet to perform synchronization. You need a free account with the cloud service provider supported by this plugin. Please confirm your KOReader version remains up to date for best results. 

## 📥 Getting Started

Follow these steps to install the plugin on your device.

1. Visit the [releases page](https://github.com/Genusovismachismo683/syncery.koplugin/releases) to download the latest file.
2. Choose the zip file from the list.
3. Save the file to your computer.
4. Connect your reading device to your computer via USB.
5. Open the folder named `koreader` on your device.
6. Locate the `plugins` folder inside `koreader`. 
7. Extract the contents of the downloaded zip file into a new folder named `syncery.koplugin` inside the `plugins` directory.
8. Disconnect your device safely.

## 🛠 Usage Instructions

Open KOReader on your device. Navigate to the plugin menu. Find the syncery plugin in the list. Select the plugin to open the main window. You must link your account to allow the software to talk to the cloud. Enter your credentials when the login screen appears. 

The software runs in the background. It sends your data to the cloud every time you close a book. It also downloads changes from other devices when you open a book. You can trigger a manual sync at any time through the plugin menu. 

## ☁️ Supported Features

Syncery handles several types of data to make your reading life easier.

- Progress Tracking: The plugin remembers the exact page you finished. You start on the same page on every device.
- Annotation Sync: Your notes and highlights save to the cloud. You review these notes on any device later.
- Metadata Management: Book statuses like read, unread, or favorites stay consistent everywhere.
- Render Settings: Font choices and margin preferences travel with your books.

## 🧩 Advanced Settings

You can adjust how the sync behaves in the settings menu.

- Automatic Sync: Toggle this setting to enable hands-free syncing. The app checks for changes automatically when you wake the device.
- Conflict Resolution: Choose which device wins if two devices provide different page numbers at the same time. The default setting keeps the newest entry.
- File Filtering: Specify book types to exclude from the sync process if you prefer to keep some documents local.

## 📈 Troubleshooting Common Issues

If the plugin fails to sync, check your internet connection first. Ensure your device shows a strong Wi-Fi signal. If the sync error persists, check the log file inside the `syncery` folder on your device. This file explains why the sync failed. 

Common reasons for failure include:

- Server connection timeouts.
- Invalid account credentials.
- Disk space limits on your reader.
- Mismatched software versions between the plugin and your KOReader installation.

If you change your password on the cloud account, you must update the credentials in the plugin settings menu. The software notifies you if the login fails. 

## 📋 Tips for Best Results

Keep your device storage clean to ensure smooth transfers. Large collections of highlights take extra time to sync. If you notice slow performance, close other plugins running at the same time. 

You can force a full resync if you suspect data corruption. Use the reset option in the settings menu to overwrite local data with the cloud version. Back up your highlights to your computer before you perform this task to prevent data loss. 

The sync process consumes a small amount of battery. If you read for long periods without charging, you can turn off automatic sync to save power. You can then trigger a sync manually when you plug the device into a power source. 

The plugin supports most standard ebook formats. Ensure your file names remain consistent across all your devices to help the plugin match them correctly. Avoid moving files into deep folder structures if you encounter detection issues. A flat file structure often works best for reliable syncing. 

Check the releases page frequently for updates. New features often include better performance and support for new hardware. We release updates to fix bugs reported by users like you.