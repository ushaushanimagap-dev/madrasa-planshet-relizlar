# madrasa-planshet-relizlar

Madrasa planshet ilovasi uchun **ichki yangilanish** manbai (ochiq). Ilova faqat shu repodan o'qiydi va yuklaydi.

- `latest.json` — asosiy kanal (versiya `X.Y.Z`).
- `sinov.json` — sinov kanali (versiya `X.Y.Z-sinov.N`; ilovada «Sinov versiyalarini olish» yoqilgan bo'lsa).
- Relizlar `veb-<versiya>` — faqat o'zgargan guruh zip'lari (`qobiq`, `shrift`, `muqova`, `kitob-<id>`), kerak bo'lsa to'liq APK.

Fayllarni `madrasa-ilovasi` reposidagi «Yangilanish nashri» workflow'i yozadi (qo'lda ishga tushiriladi). Bu yerga qo'lda fayl qo'yilmaydi.
Har guruh sha256 bilan tekshiriladi; buzilgan yoki ochilmagan paketdan ilova o'zi o'rnatilgan asl versiyaga qaytadi.
