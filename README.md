# DeathToNavigator
"DeathToNavigator" Is a simple app that disables the new navigator ui on boot of your meta quest 2, 3, 3S headset!

A recent Meta Quest update replaced the classic home UI with a new SHITTY interface called Navigator.

This UI Change Ultimately Killed Most Performance For Older Headsets (Quest 2).

DeathToNavigator restores the old UI by automatically clearing the storage cache of the Quest home shell.

The Auto Clear works by using Android's Accessibility Service to navigate into Settings and click Clear Storage on your behalf, no PC or root required.

The toggle controls whether the auto-clear runs on boot. Although, This Does Make Your Headset Boot And Reach Home Slower, Its Helps Overall Performance A lot! (Only On Quest 2)

## FOR QUEST 3/3s Users

Sadly Quest 3/3s Systems Dont Support Androids Accessibility settings, i added a manual mode & On-Boot Shell Settings Mode!

Step 1: Scroll To "Storage & Cache" In Meta Horizon Shell App Settings After Clicking "KILL IT."
Step 2: Click "Clear Storage"
Step 3: Let It Respring The Shell, And You *Should* See Focused UI!

## DISCLAIMER 1 Auto Cache Refresh ONLY WORKS on Quest 2 Systems, Meta fully locked down quest 3, 3s HorizonOS!!
###

## DISCLAIMER 2 I Would Recommend Disabling Auto System Updates Using ADB!! (adb shell pm disable-user --user 0 com.oculus.updater)
###

## DISCLAIMER 3 This app Partially features AI Generated Code!!
###

<img width="375" height="661" alt="image" src="https://github.com/user-attachments/assets/cec37641-5c8e-4c91-8faf-343b58f126b1" />
