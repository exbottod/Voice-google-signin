# My Google Login (Android)

Demo login & daftar dengan akun Google.

## Setup
1. Buat OAuth Client ID di https://console.cloud.google.com
2. Tipe Android (package `com.example.mygooglelogin` + SHA-1)
3. Tipe Web application → copy Client ID
4. Ganti `YOUR_WEB_CLIENT_ID` di `app/src/main/java/com/example/mygooglelogin/LoginActivity.java`

## Build APK otomatis
Setiap push ke `main`, GitHub Actions akan build APK.
Download di tab **Actions** → pilih run → **Artifacts** → `app-debug`.

## Lisensi
MIT
