# **YT ReVanced Extended Troubleshooting**

(For troubleshooting help related to YT **Music** Extended click [here](https://www.reddit.com/r/revancedextended/wiki/ytm-troubleshooting/).)



# **Issues Within YT ReVanced Extended**

(See below for patching and installation troubleshooting.)



#### **1. No internet connection / The home page isn't loading**

Navigate to your device settings > Accounts > Manage accounts > Vanced MicroG > Remove account. You can sign in again if you want.

If that doesn't work you can try to uninstall Vanced MicroG and reinstall [Vanced MicroG](https://github.com/TeamVanced/VancedMicroG/releases/latest) or [inotia00's Vanced MicroG fork](https://github.com/inotia00/VancedMicroG/releases/latest).




#### **2. I'm having issues signing in to my Google account**

Navigate to your device settings > Accounts > Manage accounts > Vanced MicroG > Remove account. You can sign in again if you want.

If that doesn't work you can try to uninstall Vanced MicroG and reinstall [Vanced MicroG](https://github.com/TeamVanced/VancedMicroG/releases/latest) or [inotia00's Vanced MicroG fork](https://github.com/inotia00/VancedMicroG/releases/latest).




#### **3. "com.deniscerri.ytdl is not installed."**

Refer to step 4 of the [YT guide](https://www.reddit.com/r/revancedextended/wiki/yt-guide/#wiki_downloader_setup) to understand and set up the download function in YT ReVanced Extended.




#### **4. Videos stop and buffer infinitely**

Make sure your YT ReVanced Extended is up-to-date.

If buffering persists, open YT ReVanced Extended and tap the profile picture > Settings > ReVanced Extended > Miscellaneous > Spoof player parameter, **On**. Restart the app.




#### **5. Videos I didn't watch are being saved to my Watch history**

Disable playback in feeds to avoid this. Tap the profile picture > Settings > General > Playback in feeds, **Off**. 




#### **6. Seekbar previews are hidden**

This is a side-effect of the player parameter spoof. If you disable the player parameter spoof videos will likely buffer infinitely.




#### **7. YouTube Shorts are/aren't hidden**

**To hide/unhide Shorts in feeds:**

Go to Settings > ReVanced Extended > Shorts > Hide shorts shelf, **Off**.

**To hide/unhide the Shorts button:**

Go to Settings > ReVanced Extended > Navigation > Hide shorts button, **Off**.




#### **8. The player UI doesn't go away**

**a)** Make sure you don't have it set to never go away in the Accessibility settings. To check, navigate to Settings > Accessibility. Either disable accessibility settings or lower the timer so that it goes away sooner.

**b)** If that wasn't the issue, simply restart the app.




#### **9. SponsorBlock is not working**

This likely means that the SponsorBlock servers are down. You can check the server status [here](https://status.sponsor.ajay.app/).




#### **10. Watch history isn't being saved**

Whitelist `s.youtube.com` in your ad-blocker.








# **Issues With Patching & Installation**


#### **11. My device is not supported**

You'll need to patch on a different Android device or on PC.

If you patch with the RVX Manager on a different device make sure to export the patched APK so that you can send it to the device you plan to install it on. To export the APK, tap the three dots in the upper right corner of the screen and then press "Export APK" as shown in [this image](https://imgur.com/a/JqmfzAj). Then press "Save".

If you want to patch on PC, follow the instructions for the desired method in the [GitHub documentation](https://github.com/inotia00/revanced-documentation#revanced-extended-documentation).




#### **12. "Feature not implemented: This application is a split APK and cannot be selected."**

On non-root devices you must use a full (non-bundle) APK when patching. Refer to steps 1 and 2 in the [YT guide](https://www.reddit.com/r/revancedextended/wiki/yt-guide/#wiki_1._downloading_vanced_microg.2C_rvx_manager.2C_.26amp.3B_yt_apk) to download and select the full APK from storage.




#### **13. "Error: Patch is not supported for this app version."**

Download an APK of the recommended/suggested version and patch that from storage. Refer to steps 1 and 2 in the [YT guide](https://www.reddit.com/r/revancedextended/wiki/yt-guide/#wiki_1._downloading_vanced_microg.2C_rvx_manager.2C_.26amp.3B_yt_apk).




#### **14. Patcher is Aborting / failing to apply patches**

**a)** Make sure you are using the latest [RVX Manager](https://github.com/inotia00/revanced-manager/releases/latest).

**b)** Try fully closing the Manager and trying again. (There is a common bug that this fixes)

**c)** Make sure you selected the suggested APK from storage. Refer to steps 1 and 2 in the [YT guide](https://www.reddit.com/r/revancedextended/wiki/yt-guide/#wiki_1._downloading_vanced_microg.2C_rvx_manager.2C_.26amp.3B_yt_apk).

**d)** If your device's language was set to a language that reads right-to-left when the failure occurred then set your device's language to English or any language that reads left-to-right. Then fully close the Manager, and try again.

* If it still doesn't work you can try searching the sub for your error. Alternatively, you can patch on a different device or use a different patching method.

If you patch with the RVX Manager on a different device make sure to export the patched APK so that you can send it to the device you plan to install it on. To export the APK, tap the three dots in the upper right corner of the screen and then press "Export APK" as shown in [this image](https://imgur.com/a/JqmfzAj). Then press "Save".

If you want to patch on PC, follow the instructions for the desired method in the [GitHub documentation](https://github.com/inotia00/revanced-documentation#revanced-extended-documentation).




#### **15. "Error: Non-root install is not possible with the current patches selection."**

Patch again and include the `MicroG Support` patch.




#### **16. "App not installed."**

**a)** If there was a Google Play Protect pop-up when trying to install it then you must press **"More details"** and then tap the **"Install anyway"** button. If you press the "Got it" button it will not install. [Here](https://imgur.com/a/Ck8nfhn) is an image demonstrating this.

**b)** Ensure that you have enough free storage. Depending on the device, it may require more than 1.5 gigabytes to install without issue.

**c)** Uninstall the YT ReVanced Extended app that is already on your device before trying again. Make sure it is not installed in an alternate user profile or private folder that your device features.




#### **17. "App not installed as package conflicts with an existing package."**

**a)** Uninstall the YT ReVanced Extended app that is already on your device before trying again. Make sure it is not installed in an alternate user profile or private folder that your device features.

**b)** Your patched YT APK that you are installing was exported from the RVX Manager but does not have the `MicroG Support` patch applied to it. You can verify if this is the case by doing the following:

Open the RVX Manager > Select an application > Storage > Select the **patched** APK that you were trying to install.

Now check what it says the package name is near the top (in parenthesis). Check if the package name starts with "app.rvx" like in [this image](https://imgur.com/a/TUBgLLt). If it says something else, then you'll need to patch again, (using an unpatched APK of the suggested version,) and apply the `MicroG Support` patch this time.




#### **18. "App not installed as package appears to be invalid."**

This error most often means that you are trying to install an app that is an older version than the already installed version. Android doesn't allow app downgrading. In the context of installing YT ReVanced Extended, here are some possible scenarios and solutions:

**a)** You are installing the unpatched YouTube APK that you downloaded from APKMirror.com. It is not necessary to install it. Refer to step 2 in the [YT guide](https://www.reddit.com/r/revancedextended/wiki/yt-guide/#wiki_2._patching_the_apk) for info on selecting the YT APK from storage.

**b)** Your patched YT APK that you are installing was exported from the RVX Manager but does not have the `MicroG Support` patch applied to it. You can verify if this is the case by doing the following:

Open the RVX Manager > Select an application > Storage > Select the **patched** APK that you were trying to install.

Now check what it says the package name is near the top (in parenthesis). Check if the package name starts with "app.rvx" like in [this image](https://imgur.com/a/TUBgLLt). If it says something else, then you'll need to patch again, (using an unpatched APK of the suggested version,) and apply the `MicroG Support` patch this time.

**c)** You are installing a patched YT ReVanced Extended APK that is an older version than the YT ReVanced Extended that is currently installed. Uninstall YT ReVanced Extended before installing the older version. Refer to the Exporting The Settings section in the [YT guide](https://www.reddit.com/r/revancedextended/wiki/yt-guide/#wiki_exporting_the_settings) for info on how to backup your settings from the installed YT ReVanced Extended so that you won't lose it all when you uninstall it.

**d)** You are installing an older version of Vanced MicroG than the one you already have installed. To uninstall the one you currently have installed, open your device Settings > Apps > Vanced MicroG > Uninstall.




#### **19. App crashes on startup**

What most likely happened was there was a failure or error while it was patching and you installed the broken APK. Refer to troubleshooting issue **#15** if this happened.
