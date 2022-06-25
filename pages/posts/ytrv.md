---
title: YouTube ReVanced
date: 2022/6/25
description: How to Build & Install "Youtube ReVanced" Yourself (DIY)
tag: DIY, YouTube, ReVanced
author: M. H. M.
---

# YouTube ReVanced

Youtube ReVanced is the continuation of popular and now abadoned project Vanced.

**For now the YT ReVanced is aimed towards developers.**

There are several ways to build and install revanced, yourself. I will be explaining some of the ways to build it, even without any programming/coding/command-line experience.

**You will need Zulu JDK 17**

[Download Zulu JDK 17 Here](https://www.azul.com/downloads/?version=java-17-lts&package=jdk)



---

[Watch the video tutorial here.](https://www.youtube.com/watch?v=iXW2yCz3z1U)
---

---



### Method 1 - Manually

1. To manually build and install every thing you will need some files, stated as below:

[YouTube APK, preferably 17.22.36](https://www.apkmirror.com/apk/google-inc/youtube/youtube-17-22-36-release/youtube-17-22-36-2-android-apk-download/)

[ReVanced CLI](https://github.com/revanced/revanced-cli/releases/latest)

[ReVanced Patches](https://github.com/revanced/revanced-patches/releases/latest)

[ReVanced Integrations](https://github.com/revanced/revanced-integrations/releases/latest)

2. After you are done, place files in a common directory, for your ease.

3. Now run command prompt/terminal **&** `cd` to the directory containing all your files.

4. Type this command

```java
java -jar revanced-cli-<version>-all.jar -a <name_of_youtube_file>.apk -c  -o revanced.apk -b revanced-patches-<version>.jar -m app-release-unsigned.apk --experimental
```

5. You will see `revanced.apk` in the directory, just sideload or install like a normal app. That's it.

### Method 2 - Run the Script & Do Nothing

1. Download the zip file, containing all the required files to build YouTube ReVanced.

[Download Zip file from this folder](https://drive.google.com/drive/folders/1_gI1NDvLwS0ubXf3lSsFxpoaV77RCAwj)

2. Extract the zip file, and simply double click or run the `Run.cmd` script.

3. Incase you download the `Standalone.cmd` then just run it, it will automatically download the required files and generate YouTube Revanced.

4. You will see `revanced.apk` in the directory, just sideload or install like a normal app. That's it.




---
Disclaimer

Youtube is the property of Google Inc.

Revanced is the property of ReVanced Team.

I am not affliated with any of above.

Above tutorial is only for educational purposes.
