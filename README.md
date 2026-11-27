# OriginOS Studio (Global Beta)

**Версия:** `1.4.0-beta11 (build 211) • ветка global-beta • targetSdk 35 (Android 15) • RU / EN`  
**Пакет:** `rk.android.app.themedicons.vivo.global.beta` (устанавливается параллельно со стабильной Global и CN версиями)  
**Автор:** [H3H • Telegram: @holy3holy](https://t.me/holy3holy)  
**Платформа:** Vivo / iQOO — Global OriginOS 5 / 6 / 7 & Funtouch OS 14–15 (Android 14–17)

---

## Что тестируем в 1.4.0-beta11 (`global-beta`)

• [BETA 11 • Хотфикс применения тем] Полностью устранён баг с циклическим перебором чужих тем (5–10 открытий подряд / зацикливание на Hello Sunshine): убран запрещённый SELinux-вызов dir.list() на /data/bbkcore/theme/icons, автоматически сбрасывается ложный бан-лист слотов и расширен пул до 16 свежих бесплатных карточек Vivo;
• [BETA 10–11] Устранены белые и залитые плашки на непокрытых приложениях (Hiddify, INCY и др.) при установке тёмных паков каталога (ColorOS 16 Dark Mint): белый шаблон launcher/icon_bg_default.png автоматически заменяется карточкой цвета и размера пака;
• [BETA 10–11] Выровнен размер карточек импортированных .itz / .mtz паков 1:1 (Галерея = Настройки = 240px) + исправлен нативный перекрас всех приложений Google (Chrome, Gmail, Play, Maps, YouTube, G Pay).

---

## Скачать Beta

- **[Универсальная ссылка (всегда последняя Global Beta APK)](https://github.com/Holy3holy-dev/OriginOS-Studio/releases/download/global-beta-latest/OriginOS-Studio-Global-Beta.apk)**
- **[Страница релиза Global Beta (`global-beta-latest`)](https://github.com/Holy3holy-dev/OriginOS-Studio/releases/tag/global-beta-latest)**
- **[Скачать OriginOS-Studio-Global-Beta-1.4.0-beta11.apk](https://github.com/Holy3holy-dev/OriginOS-Studio/releases/download/global-beta-v1.4.0-b11/OriginOS-Studio-Global-Beta-1.4.0-beta11.apk)**
- **[Стабильная ветка Global](https://github.com/Holy3holy-dev/OriginOS-Studio/tree/global)**

---

## Канал автообновления (OTA Global Beta)

- **Манифест обновлений Global Beta:** `https://raw.githubusercontent.com/Holy3holy-dev/OriginOS-Studio/global-beta/update.json`
- **Облачный каталог ресурсов:** `https://raw.githubusercontent.com/Holy3holy-dev/OriginOS-Studio/global-beta/catalog.json`
