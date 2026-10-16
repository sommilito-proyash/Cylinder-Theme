Cylinder Radar Launcher — Android Studio Project (Prototype)

এই ZIP-এ Android Studio-তে খোলার মতো সোর্স প্রজেক্ট আছে; এটি এখনো তৈরি করা APK নয়। এখানে রয়েছে:
- HOME launcher intent (ডিফল্ট হোম হিসেবে বেছে নেওয়ার জন্য)
- ইনস্টল করা launcher apps-এর নাম/আইকন দেখানো
- swipe-এ cylinder-style rotation
- ছয়টি accent color picker
- অ্যাপে tap করে launch করার প্রাথমিক ব্যবস্থা

APK তৈরি:
1. কম্পিউটারে Android Studio ইনস্টল করুন এবং Android SDK Platform 35 ও JDK সেটআপ করুন।
2. ZIP extract করে Android Studio-তে `CylinderRadarLauncher-Android` ফোল্ডারটি Open করুন।
3. Gradle sync শেষ হলে Build > Build Bundle(s) / APK(s) > Build APK(s) চাপুন।
4. APK সাধারণত app/build/outputs/apk/debug/app-debug.apk-এ তৈরি হবে।
5. APK ফোনে পাঠিয়ে install করুন। প্রয়োজন হলে Settings-এ ওই ফাইল ম্যানেজারের জন্য Install unknown apps অনুমতি দিন।
6. Settings > Apps > Manage apps > Default apps > Launcher/Home app-এ Cylinder Radar Launcher নির্বাচন করুন। Xiaomi/Redmi/POCO MIUI/HyperOS-এ মেনুর নাম ভার্সন অনুযায়ী কিছুটা আলাদা হতে পারে।

সতর্কতা:
- এটি প্রাথমিক prototype; কিছু ডিভাইসে আইকন/টাচ নির্বাচন আরও tuning দরকার হতে পারে।
- আগে আপনার বর্তমান launcher-এর নাম মনে রাখুন যাতে প্রয়োজনে আবার সেটি বেছে নিতে পারেন।
- কোনো বিশেষ অনুমতি/Accessibility permission প্রয়োজন নেই।
