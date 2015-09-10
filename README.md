# AndroidScreencast
Automatically exported from [code.google.com/p/androidscreencast](https://code.google.com/p/androidscreencast)

Desktop app to control an android device remotely using mouse and keyboard. Should work on Windows/Linux/MacOS with any android device.

[Google Groups for support](http://groups.google.com/group/androidscreencast), no direct help request please.

## Installation
- Install the android sdk ([download here](http://developer.android.com/sdk/index.html))
- Connect your device through USB cable and ensure it's detected with "adb devices"
- Make sure you have Java Runtime Environnement 5 or later installed
- Click [HERE](http://androidscreencast.googlecode.com/svn/trunk/AndroidScreencast/dist/androidscreencast.jnlp). 
 - You can launch it by typing "javaws <jnlp file>" from a command line.


If mouse/keyboard control doesn't work, open a command line and type :

    adb shell
    su
    chmod 777 /data/dalvik-cache
    cd /data/dalvik-cache
    chmod 777 ./
    
## Features
- Mouse and keyboard control FOR ROOTED DEVICES ONLY
- Landscape mode (right click)
- Video recording
- Basic file browser

## Current limitations
- Slow refresh rate (about 4-5 fps)
- Not all keycode are mapped. See KeyMapping
- When launching the Screencast tool I receive a message "Application Blocked by Java Security"
  ![Error Dialog](http://i.imgur.com/xvq10RT.png)
 - See steps to fix on [Android Enthusiasts](http://android.stackexchange.com/questions/122737/when-launching-the-screencast-tool-i-receive-a-message-application-blocked-by-j). 
 
## Todo
- Automatic screen rotation based on the device current state.
- Improve speed
- Audio redirection

## How can i help?
- Report issues
- submit pull requests

![Screenshot](http://i.imgur.com/2c3liMJ.jpg)
