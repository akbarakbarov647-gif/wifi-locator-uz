# Wi‑Fi Locator UZ

Bu loyiha foydalanuvchi joylashgan hududda 1 km radius ichida mavjud bo'lgan Wi‑Fi access point (AP) larni skanlash, geolokatsiya qilish va xaritada ko'rsatishga qaratilgan.

Loyiha ikki komponentdan iborat:
- Android ilova (Kotlin)
- Windows desktop ilova (Electron + Node.js)

## Maqsad
- Wi‑Fi tarmoqlarini skanlash
- SSID, BSSID, signal kuchi (RSSI) va masofani aniqlash
- Mozilla Location Service orqali geolokatsiya qilish
- Foydalanuvchi xaritasida 1 km radius ichida AP larni ko'rsatish
- Foydalanuvchi uchun O'zbekcha interfeys

## Repozitoriy tuzilmasi

- `android/` — Android loyihasi
- `desktop/` — Windows desktop ilova
- `README.md` — umumiy loyiha hujjatlari
- `LICENSE` — MIT litsenziya
- `.gitignore` — umumiy git ignorlash

## Texnologiyalar
- Android: Kotlin + Android Studio + Jetpack + MapLibre
- Desktop: Electron + Node.js + Leaflet + OpenStreetMap
- Geolocation: Mozilla Location Service

## Hozirgi holat
Bu repo hozir boshlang'ich scaffold sifatida yaratilgan. Quyida loyiha bosqichma-bosqich kengaytiriladi:
- Android qilinadigan bosqichlar: Wi‑Fi scan, location ruxsatlari, map, API integratsiyasi.
- Desktop bosqichlar: Windows Wi‑Fi scan wrapper, map, UI, build.
- Build/release bosqichlari: APK va EXE tayyorlash.

## Ishga tushirish va build
Batafsil ko'rsatmalar keyingi bosqichlarda qo'shiladi.

## Xavfsizlik va qonuniy foydalanish
- Bu loyiha faqat foydalanuvchi ruxsati va ma'qullovi bilan ishlaydi.
- Parollarni topish, ruxsatsiz ulanish yoki qonuniy bo'lmagan faoliyatlar uchun mo'ljallanmagan.
- Foydalanuvchi roziligisiz AP ma'lumotlaridan tashqari ishlov berish taqiqlanadi.

## Ishlab chiqish reja
1. Android skeleton: Wi‑Fi scan + location + MapLibre
2. Desktop skeleton: Wi‑Fi scan + Leaflet map + Electron UI
3. Geolocation integratsiyasi: Mozilla Location Service
4. 1 km radius filtering
5. APK/EXE release build

## Muallif
GitHub repo tayyorlangan va keyingi bosqichlarda kengaytiriladi.
