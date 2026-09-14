# Reklamcı Toolbox Android

Mevcut `reklamci-toolbox.html` uygulamasını Android WebView içinde çalıştıran basit Android projesi.

## Android Studio ile APK
1. Android Studio ile bu klasörü aç.
2. Gradle sync tamamlanmasını bekle.
3. Build > Build Bundle(s) / APK(s) > Build APK(s).
4. APK: `app/build/outputs/apk/debug/app-debug.apk`

## GitHub Actions
`.github/workflows/build-apk.yml` dosyası Android SDK kurup debug APK üretir ve artifact olarak yayınlar.
