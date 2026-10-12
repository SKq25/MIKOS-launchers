# MIKOS Launcher 5G (Kotlin + Jetpack Compose)

## Chalane ka tarika
1. Android Studio (Koala ya naya) me `MIKOS` folder open karo, Gradle sync hone do.
2. Phone/emulator par Run dabao. Home dabao aur MIKOS ko "Always" chuno.

## Features
- Lock screen: swipe up unlock, torch + camera buttons, notification cards
- Dynamic Island: tap karke expand (battery, weather, time)
- Home: 2 pages (swipe), live clock, real weather, greeting (time ke hisaab se), asli installed apps
- Control Center (neeche swipe): brightness aur volume sliders, torch, Wi-Fi/Bluetooth/Focus/Timer/Camera
- App Library (upar swipe): search + sab installed apps + MIKOS apps
- Built-in apps: AI chat, 5G Speed Test (real), Weather (real), Notes (save), Calculator
- Wallpaper: Canvas me bana floating-island scene

## Settings
- Sheher badalne ke liye `Util.kt` me CITY, LAT, LON badlo.
- Weather: Open-Meteo, Speed test: Cloudflare (internet chahiye).
