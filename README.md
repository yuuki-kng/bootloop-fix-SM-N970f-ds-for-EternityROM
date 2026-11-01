# bootloop-fix-SM-N970f-ds-for-EternityROM
simple fix for note 10 devices that runs EternityROM with bootloop issue from Apex
this isn't made by me

pre req

download the drivers from Samsung at https://developer.samsung.com/android-usb-driver

a̶n̶d̶ ̶g̶e̶t̶ ̶a̶d̶b̶ ̶f̶r̶o̶m̶ ̶h̶t̶t̶p̶s̶:̶/̶/̶d̶e̶v̶e̶l̶o̶p̶e̶r̶.̶a̶n̶d̶r̶o̶i̶d̶.̶c̶o̶m̶/̶t̶o̶o̶l̶s̶/̶r̶e̶l̶e̶a̶s̶e̶s̶/̶p̶l̶a̶t̶f̶o̶r̶m̶-̶t̶o̶o̶l̶s̶ ̶p̶i̶c̶k̶ ̶ ̶D̶o̶w̶n̶l̶o̶a̶d̶ ̶S̶D̶K̶ ̶P̶l̶a̶t̶f̶o̶r̶m̶-̶T̶o̶o̶l̶s̶ ̶f̶o̶r̶ ̶W̶i̶n̶d̶o̶w̶s̶ ̶e̶x̶t̶r̶a̶c̶t̶ ̶t̶h̶a̶t̶ ̶i̶n̶t̶o̶ ̶t̶h̶i̶s̶ ̶f̶o̶l̶d̶e̶r̶̶
 Adb is now included in the files 

Step 1 |
plug the device into the device while in download mode

Step 2 |
open "Odin3_v3.14.4.exe" and make sure the device shows up

Step 3 |
turn off auto reboot in options tabadd "EternityROM_v3.0_TWRP_OdinPack_N970F_2.tar" to slot AP and click "Start"

Step 4 |
it should say PASS! with green colour if it shows "fail" or anything like that re flash it to see if it still fails

Step 5 |
press power button + vol down when the screen turns off switch to power button + vol up if you see the twrp logo then continue to step 6

Step 6 |
run cmd in the directory that this is in e.g : C:\Users\sata\Downloads\(the folder you extracted it in)

Step 7 |
if its powershell then .\adb devices to check if its connected if it is then .\adb push "APEX_Bootloop_Fix.zip" /sdcard/

Step 8 |
in twrp click install and find "APEX_Bootloop_Fix.zip" and click it and flash it and follow the steps

========
