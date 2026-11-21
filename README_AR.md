# Pexil TV - مشروع Android

هذا مشروع Android Studio أولي يفتح موقع Pexil TV داخل WebView بملء الشاشة.

## بناء APK
1. ثبّت Android Studio على جهاز الكمبيوتر.
2. افتح Android Studio واختر **Open** ثم مجلد `PexilTV-Android`.
3. انتظر مزامنة Gradle وتثبيت Android SDK المطلوبة.
4. من القائمة اختر **Build > Build Bundle(s) / APK(s) > Build APK(s)**.
5. ستجد الملف عادةً في:
   `app/build/outputs/apk/debug/app-debug.apk`

## ملاحظات مهمة
- عنوان الموقع الحالي HTTP، لذلك تم السماح باتصالات HTTP داخل التطبيق حتى يعمل الرابط الحالي.
- هذا مناسب للاختبار فقط. قبل النشر على Google Play يُفضّل إعداد HTTPS بشهادة TLS صالحة.
- يجب اختبار تشغيل البث والصوت والفيديو على عدة أجهزة Android.
- هذه نسخة مصدرية قابلة للبناء وليست ملف APK موقّعاً أو جاهزاً للنشر.
