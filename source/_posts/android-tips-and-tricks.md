title: Android and Java Tips and Trick
date: 2014-01-14 16:34:36
tags: android developer
---

Build from commandline an android project (replace 'Hello with name of Project')

```[shell]
android update project --name Hello --path
```


Run an application from adb
```android 

#example running setting

adb shell am start -a android.intent.action.Main -n com.android.settings/.Settings
```

Diagram 
+ Intent Life Cycle
+ Services Life Cycle 
+ Activity Life Cycle

Always Check the manifest for all related infomration

run the app, replace the latter with the activity you want to invoke
---
adb shell am start -n com.google.zxing.client.android/.CaptureActivity

Jars are just zips
-----
Use a utility like JD-GUI or Jad to unzip a jar and get the source. Perfect for when you lose the source or when you want to tinker.


``` shell

jar -xf YOURJAR.jar && find . -iname "*.class" | xargs ./jad -r
#cd into the directory and 
mv *.jad *.java
```
Check out http://stackoverflow.com/questions/5107187/extract-source-code-from-jar-file/5107213#5107213