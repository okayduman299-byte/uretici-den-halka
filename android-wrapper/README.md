# Üreticiden Halka Android

Bu klasör, mevcut Üreticiden Halka web uygulamasını Android uygulamasına sarmalar.

## APK oluşturma

1. Node.js ve Android Studio kurulu bir bilgisayarda bu klasörde `npm install` çalıştırın.
2. `npx cap add android` çalıştırın.
3. `npx cap sync android` çalıştırın.
4. `cd android` ardından `./gradlew assembleDebug` çalıştırın.
5. APK: `android/app/build/outputs/apk/debug/app-debug.apk`

Uygulama kimliği: `com.ureticidenhalka.app`

Uygulama mevcut yayınlanan siteyi kullanır; Supabase ve mevcut web özellikleri korunur.
