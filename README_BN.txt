Tarikul Attendance - Android Studio Project

এই ফোল্ডারটি Android Studio-তে খুলে APK তৈরি করা যাবে।

APK বানানোর নিয়ম:
1. Android Studio ইনস্টল করে এই project folder Open করুন।
2. Gradle sync শেষ হওয়া পর্যন্ত অপেক্ষা করুন (ইন্টারনেট লাগবে, প্রথমবার Android SDK 35 ডাউনলোড হতে পারে)।
3. Build > Build Bundle(s) / APK(s) > Build APK(s) নির্বাচন করুন।
4. APK পাওয়া যাবে: app/build/outputs/apk/debug/app-debug.apk
5. APK ফোনে পাঠিয়ে Install করুন। প্রয়োজনে Android Settings-এ Install unknown apps অনুমতি দিন।

অ্যাপটি HTML attendance sheet-কে Android WebView-এর মধ্যে চালায়। JavaScript ও local storage চালু আছে।
সময়ের রেকর্ড ফোনের লোকাল স্টোরেজে থাকবে; অ্যাপের ডেটা Clear/Uninstall করলে রেকর্ড মুছে যেতে পারে। CSV export Android-এ Share flow ব্যবহার করতে পারে।
