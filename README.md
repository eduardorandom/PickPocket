# PickPocket

PickPocket is a powerful, full featured and highly customizable Cydia tweak against thieves!

I'm open sourcing it as I'll don't have the time to update it. You can do whetever you want with the code: learn from it, update it,...

The code is ugly, I know. PickPocket was the biggest tweak I ever made and didn't thought that I would need to update it. Take it as a lesson: Don't write ugly code, it will be difficult to maintain it in the future.

# Installation

Make sure you have a working theos environment, clone this repository and just run:

`make package install`

If needed, install the dependencies you're missing.

PickPocket is compatible with iOS 9 and 10. iOS 11 is not supported yet but it will run on it (your device will crash obviously)

# Notes

Back in iOS 9, I was using InfoStats 2 (which depends on WebCycript) in order to get the device location. WebCycript wasn't updated for iOS 10 so I dropped the location feature. I believe the code is still there but is commented.

I'm using camshot to take pictures. In iOS 11, running camshot (and all command line utilities) return `Killed`. I heard that you need to add the `platform-application` entitlement to the camshot executable but I can't confirm it.

-------

Have fun!
