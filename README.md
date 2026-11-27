# OriginOS Studio (Global)

**Версия:** `1.3.9 (build 130) • ветка global • targetSdk 35 (Android 15) • RU / EN`  
**Пакет:** `rk.android.app.themedicons.vivo.global` (устанавливается параллельно с китайской версией)  
**Автор:** [H3H • Telegram: @holy3holy](https://t.me/holy3holy)  
**Платформа:** Vivo / iQOO — Global OriginOS 5 / 6 / 7 & Funtouch OS 14–15 (Android 14–17)

---

## Что нового в 1.3.9 (`global`)

• [Хотфикс применения тем] Полностью устранён баг с циклическим перебором чужих тем (5–10 открытий подряд / зацикливание на Hello Sunshine): убран запрещённый SELinux-вызов dir.list() на /data/bbkcore/theme/icons, автоматически сбрасывается ложный бан-лист слотов и расширен пул до 16 свежих бесплатных карточек Vivo
• Устранены белые и залитые плашки на непокрытых приложениях (Hiddify, INCY и др.) при установке тёмных паков каталога (ColorOS 16 Dark Mint): белый шаблон launcher/icon_bg_default.png автоматически заменяется карточкой цвета и размера пака
• Выровнен размер карточек импортированных .itz / .mtz паков 1:1 (Галерея = Настройки = 240px) + исправлен нативный перекрас всех приложений Google (Chrome, Gmail, Play, Maps, YouTube, G Pay)

---

## Скачать

- **[Универсальная ссылка (всегда последняя версия Global APK)](https://github.com/Holy3holy-dev/OriginOS-Studio/releases/download/global-latest/OriginOS-Studio-Global.apk)**
- **[Актуальное описание Global (`global-latest`)](https://github.com/Holy3holy-dev/OriginOS-Studio/releases/tag/global-latest)**
- **[Скачать OriginOS-Studio-Global-1.3.9.apk](https://github.com/Holy3holy-dev/OriginOS-Studio/releases/download/global-v1.3.9/OriginOS-Studio-Global-1.3.9.apk)**
- **[Все релизы на GitHub](https://github.com/Holy3holy-dev/OriginOS-Studio/releases)**
- **[Telegram-канал H3H](https://t.me/holy3holy)**

---

## Канал автообновления (OTA Global)

- **Манифест обновлений Global:** `https://raw.githubusercontent.com/Holy3holy-dev/OriginOS-Studio/global/update.json`
- **Облачный каталог ресурсов:** `https://raw.githubusercontent.com/Holy3holy-dev/OriginOS-Studio/global/catalog.json`
