# Awesome-Termux

A list of awesome things related to Termux


## Termux Apps
- [Termux Float](https://play.google.com/store/apps/details?id=com.termux.window) [Termux Float - Github](https://github.com/termux/termux-float) A Termux add-on app to show the terminal in a floating terminal window.
- [Termux Widget](https://play.google.com/store/apps/details?id=com.termux.widget) The Termux:Widget add-on provides a widget with shortcuts to run scripts placed in the $HOME/.shortcuts/ folder, allowing quick access to frequently used commands without typing
- [Termux Tasker](https://play.google.com/store/apps/details?id=com.termux.tasker) A Termux add-on app allowing Termux programs to be executed from Tasker.
- https://github.com/moverest/termux-smses A simple fish script to send sms interactively with termux.

## Remote Connection Tips
- https://github.com/tomhiggins/TermuxSSHDsetup Scripts and notes for setting up and using SSHd on your Android device using Termux so that you can SSH, SFTP, and SSHFS to your Android

## Android Hacking
- https://github.com/4544fa8d/AndroTermux Simple way to build Android apps in Termux.
- https://github.com/TheDiamondYT1/termux-buildapk A simple build script to quickly build Android apps on termux. Nothing major. Doesnt work for gradle.
- [apktool](https://github.com/Hax4us/apktool) This apktool is specially compiled for termux..
- https://github.com/Harshiv-Patel/termux-jdkTools A bunch of jdk tools to use with Termux.
- https://github.com/wisehackermonkey/termux Termux server for battery monitor on andriod
- https://github.com/Hax4us/Tmux-Bunch Tmux-Bunch is a first tool for complete apk modding in TERMUX (included :- decompiling , recompiling , signapk , zipalign)
- https://github.com/michalbednarski/TermuxAm Android Oreo-compatible am command reimplementation (am (Activity Manager) command in Android can be used to start Activity or send Broadcast from shell, however since Android Oreo that command only works from adb shell, not from apps. This is modified version of that command that is usable from app.)

## Hacking
- https://github.com/cryzed/Termux-Bridge 
Simple "bridge" that allows applications not running under Termux to execute shell commands within the Termux environment and getting their output.
 - [Hacking Tools from Termux oficial page](https://wiki.termux.com/wiki/Hacking)

## Programming

### Using Jupyter notebooks
http://www.leouieda.com/blog/scipy-on-android.html


## Bash Tips

How to check if a script is running inside Termux

```bash
if [[ $0 == *termux* ]]; then
     # Add here your Termux specific code 
fi
```

