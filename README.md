# OriginOS Studio (Global Beta)

**Версия:** `1.4.0-beta3 (build 203) • ветка global-beta • targetSdk 35 (Android 15) • RU / EN`  
**Пакет:** `rk.android.app.themedicons.vivo.global.beta` (устанавливается параллельно со стабильной Global и CN версиями)  
**Автор:** [H3H • Telegram: @holy3holy](https://t.me/holy3holy)  
**Платформа:** Vivo / iQOO — Global OriginOS 5 / 6 / 7 & Funtouch OS 14–15 (Android 14–17)

---

## Что тестируем в 1.4.0-beta3 (`global-beta`)

• [BETA 3] Исправлен перекрас всех 27 приложений Google (Chrome, YouTube, Gmail, Play, Фото, Карты, Диск, YT Music и др.): гарантированный двойной импульс флагов монохрома лаунчера (material_you_overlay_enable + themed_icon_enabled) и автосинхронизация сразу при входе после обновления;
• [BETA 3] Устранены нечитаемые «белые квадраты» на тёмных паках/AMOLED/Стекле при включённой светлой (дневной) теме системы: FabricatedOverlay теперь жёстко удерживает тёмную подложку и контрастный глиф как ночью, так и днём;
• [BETA 3] Исправлено зависание установки значков при включённом Тёмном режиме системы и пустой тост «Подтвердите кнопку Применить ()»: добавлено автоподтверждение системного диалога Тёмного режима в com.bbk.theme и PID-изоляция Shizuku без конфликтов со стабильной версией;
• [BETA 3] Выровнен пиксель-в-пиксель размер значков Google и растровых иконок (компенсация множителя 62/59 в BBKLauncher2) + добавлено автоскругление острых чёрных углов у импортированных паков ColorOS / MIUI;
• [BETA 3] На главный экран Мастерской и в самое начало раздела «Виджеты» возвращена кнопка быстрого создания виджетов иконок приложений 1×1 (без бейджа Студии).

---

## Скачать Beta

- **[Универсальная ссылка (всегда последняя Global Beta APK)](https://github.com/Holy3holy-dev/OriginOS-Studio/releases/download/global-beta-latest/OriginOS-Studio-Global-Beta.apk)**
- **[Страница релиза Global Beta (`global-beta-latest`)](https://github.com/Holy3holy-dev/OriginOS-Studio/releases/tag/global-beta-latest)**
- **[Скачать OriginOS-Studio-Global-Beta-1.4.0-beta3.apk](https://github.com/Holy3holy-dev/OriginOS-Studio/releases/download/global-beta-v1.4.0-b3/OriginOS-Studio-Global-Beta-1.4.0-beta3.apk)**
- **[Стабильная ветка Global](https://github.com/Holy3holy-dev/OriginOS-Studio/tree/global)**

---

## Канал автообновления (OTA Global Beta)

- **Манифест обновлений Global Beta:** `https://raw.githubusercontent.com/Holy3holy-dev/OriginOS-Studio/global-beta/update.json`
- **Облачный каталог ресурсов:** `https://raw.githubusercontent.com/Holy3holy-dev/OriginOS-Studio/global-beta/catalog.json`
