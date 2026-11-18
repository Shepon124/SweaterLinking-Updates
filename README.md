# Sweater Linking Updates

এই Public repository-তে Sweater Linking Android অ্যাপের update manifest এবং release APK-এর লিংক রাখা হবে।

## Update manifest URL
https://raw.githubusercontent.com/Shepon124/SweaterLinking-Updates/main/update.json

## নতুন APK প্রকাশের নিয়ম
1. Android অ্যাপের versionCode আগের চেয়ে বাড়াতে হবে।
2. একই applicationId: com.aistudio.sweaterlinking.workmanager রাখতে হবে।
3. আগের একই signing keystore দিয়ে APK sign করতে হবে।
4. GitHub Releases-এ নতুন release তৈরি করতে হবে।
5. APK ফাইলের নাম ঠিক SweaterLinking.apk রাখতে হবে।
6. update.json-এ versionCode, versionName ও releaseNotes পরিবর্তন করতে হবে।

## নিরাপত্তা
Keystore, keystore password, key password বা GitHub token এই Public repository-তে আপলোড করবেন না।

বর্তমান baseline: versionName 2.2.0, versionCode 4।
APK release asset এখনো যোগ করা হয়নি।
