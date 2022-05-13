# ApkSignZip


Aims:
1. Sign APK manually
2. Zipalign APK manually


How to use:
1. Open ApkSignZipConfig in text editor, update key path, key alias, key password first
2. Save
3. Open ApkSignZipBegin 
    (if cannot open directly, try to open Terminal and enter $root/ApkSignZipBegin )
4. Enter unsigned apk path
5. Program will check it is already signed or not
6. (Optional) ZipAlign apk 
7. Done


Updates:
 - added bin/28.0.3 folder

 - will use zipalign and apksigner in that folder instead of ~/Library/sdk/android/platform-tool/28.0.3

 - signing will now use apksigner instead of jarsigner to support v1, v2 signing schemes

