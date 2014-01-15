title: Android Tips and Tricks
date: 2014-01-14 16:34:36
tags: android developer
---

Build from commandline an android project (replace 'Hello with name of Project')

```[shell]
android update project --name Hello --path
```


Diagram 
+ Intent Life Cycle
+ Services Life Cycle 
+ Activity Life Cycle

Always Check the manifest for all related infomration

//run the app, replace the latter with the activity you want to invoke
---
adb shell am start -n com.google.zxing.client.android/.CaptureActivity