# bootloop-fix-SM-N970f-ds-for-EternityROM
simple fix for note 10 devices that runs EternityROM with bootloop issue from Apex
this isn't made by me
pre req
download the drivers from Samsung at https://developer.samsung.com/android-usb-driver
and get adb from https://developer.android.com/tools/releases/platform-tools pick  Download SDK Platform-Tools for Windows extract that into this folder
Step 1
plug the device into the device while in download mode
Step 2
open "Odin3_v3.14.4.exe" and make sure the device shows up
Step 3
turn off auto reboot in options tabadd "EternityROM_v3.0_TWRP_OdinPack_N970F_2.tar" to slot AP and click "Start"
Step 4
it should say PASS! with green colour if it shows "fail" or anything like that re flash it to see if it still fails
Step 5
press power button + vol down when the screen turns off switch to power button + vol up if you see the twrp logo then continue to step 6
Step 6
run cmd in the directory that this is in e.g : C:\Users\sata\Downloads\(the folder you extracted it in)
Step 7
if its powershell then .\adb devices to check if its connected if it is then .\adb push "APEX_Bootloop_Fix.zip" /sdcard/
Step 8 
in twrp click install and find "APEX_Bootloop_Fix.zip" and click it and flash it and follow the steps
========
