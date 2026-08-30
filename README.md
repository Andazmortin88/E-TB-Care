# E-TB Care

Aplikasi digital health coaching untuk pendampingan perawatan tuberkulosis.

- Web: <https://andazmortin88.github.io/E-TB-Care/>
- Android: wrapper WebView pada direktori `app/`

## Build APK

GitHub Actions akan membangun APK debug secara otomatis ketika proyek Android berubah. Artifact `E-TB-Care-APK` berisi:

- `E-TB-Care.apk`
- `SHA256SUMS.txt`

Build manual memerlukan JDK 17, Android SDK 35, dan Gradle 8.9:

```bash
gradle :app:assembleDebug
```
