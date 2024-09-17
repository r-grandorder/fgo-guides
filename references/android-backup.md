---
layout: default
title: Android Manual Backup
parent: References
nav_order: 4
---

# Manual FGO backup for Android
- This is a guide for transferring your game files in case of emergencies where you cannot create a new binding code. Follow this guide at your own risk.
- Originally posted in [Discord](https://discord.com/channels/274980577545945090/274981376543948812/1024678458351169669).

## How to do a manual backup
1. Go to `Storage/Android/data/com.aniplex.fategrandorder/files/data` (changes per Android version, read note below)
2. Copy the 4 files into a different folder (Documents or Downloads for example) that start with the following:
  - 54cc
  - 969b
  - 644b
  - e1a9

### Regarding the Path
- The path is only `Storage/Android/data/com.aniplex.fategrandorder/files/data` for all android versions less than or equal to 10 OR if it is attached by USB to a computer
- For android 11 or 12 on a phone, the path is `root/data/media/0/Android/data/com.aniplex.fategrandorder/files/data`
- For android 13+ on a phone, it's not achievable (have to use the USB method)

## Restoring
1. Install the game and let it download the initial files.
2. When you see chaldea in a snowstorm, close the app. (See this video: <https://youtu.be/NSeTUJyAC3Y?t=647> at timestamp 10:47)
3. Paste the 4 files from the backup into the same location. It should overwrite.
4. Re-open the game and check your userid, if it prompts you to continue just select cancel/don't continue (`再開しない` - Don't resume / `冒頭から再開する` - Restart from the beginning / `再開する` - Resume). It will prompt you with the start dash rewards but not actually get anything, that's fine since the game thinks you're on a new account.

## Important Notes
- These 4 files are the "login" files for your account, if someone gets access to them they can play your account. __So keep it safe and out of others' reach.__ Re-binding will change the files so you need to re-copy the files after binding if you want the backup to still work in the future.
- Android 11 and up has a stricter policy on which applications can read/write on the system storage. You might not be able to do this on some devices or you need a different set of apps.
- Options that usually work:
    - The built in files app
    - AOSP Files App or a 3rd party files app like FV File Manager
    - Accessing the files from a PC by connecting your phone via usb
- Some methods are able to just read the files and cannot write. You will need a different device, preferably with a lower Android version, to restore into if writing doesn't work.
- Backing up and Restoring to the same device is usually safe but still toes the line with the game's TOS since you're messing with the game's files. Restoring to a different device is more suspicious from Lasengle's pov because you're changing Devices without using a bind code. __We won't know if Lasengle will suddenly ban accounts for doing this method.__
- The methods differ per OS version and Manufacturer, you're better off looking for guides that are tailored for your specific device. Usual search term is "copy pasting to android data folder <manufacturer>".
- This resource has been regularly updated and is worth a read. <https://www.reddit.com/r/Android/comments/j3zgmm/managing_files_in_the_androiddata_folder_on/>

{: .info}
As of testing on 16-Sept-2024 with Android 14, the only on device app that works is FV File Manager. The other apps triggers Android's native "select folder to access" functionality and Android won't allow access to the game's data.  


## Other resources:
- Chaldea Center's guide, includes notes on iOS: <https://docs.chaldea.center/guide/import_https/transfer_data>
- Older guide on r/grandorder: <https://www.reddit.com/r/grandorder/comments/hfbz0h/fgo_save_files_for_na_and_jp_play_on_multiple/>
- Manually triggering Google's automated backup: <https://www.reddit.com/r/grandorder/comments/hej2ct/google_account_backup_stepbystep_android_set_up/>
- Another guide for writing into the data folder for Android 13: <https://droidwin.com/how-to-access-android-13-data-and-obb-folder-transfer-files-in-them/>
