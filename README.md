# android_device_samsung_a13-common

## Clone a13 & universal3830-common trees
    git clone https://github.com/SavedByLight-WIP/android_device_samsung_a13-common.git -b android-12.1 device/samsung/a13; git clone https://github.com/SavedByLight-WIP/android_device_samsung_universal3830-common.git -b android-12.1 device/samsung/universal3830-common

## Build (twrp-12.1)
    . build/envsetup.sh; lunch twrp_a13-eng; mka recoveryimage
