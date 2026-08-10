তনুশ্রী জুয়েলার্স — One-click GitHub APK build

এই project WebIntoApp-এর জন্য নয়।
এটি GitHub Actions দিয়ে native Android APK বানানোর জন্য।

ফোন থেকে:
1) GitHub-এ নতুন repository তৈরি করুন।
2) এই ZIP extract করে সব file repository-র root-এ upload করুন।
3) .github/workflows/build-apk.yml file-টি অবশ্যই থাকবে।
4) GitHub → Actions → Build Tonushree Jewellers APK → Run workflow।
5) Build শেষ হলে Artifacts থেকে Tonushree-Jewellers-CLEAN-APK download করুন।
6) ZIP খুলে app-debug.apk ফোনে install করুন।

Security design:
- Android app manifest-এ কোনো uses-permission নেই।
- কোনো Internet permission নেই।
- কোনো Camera/Microphone/Location/Contacts/SMS/Phone permission নেই।
- কোনো ads/analytics/Firebase/third-party SDK dependency নেই।
- হিসাব offline/local device-এ হয়।
