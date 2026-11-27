# OriginOS Studio (Global Beta)

**Версия:** `1.4.0-beta9 (build 209) • ветка global-beta • targetSdk 35 (Android 15) • RU / EN`  
**Пакет:** `rk.android.app.themedicons.vivo.global.beta` (устанавливается параллельно со стабильной Global и CN версиями)  
**Автор:** [H3H • Telegram: @holy3holy](https://t.me/holy3holy)  
**Платформа:** Vivo / iQOO — Global OriginOS 5 / 6 / 7 & Funtouch OS 14–15 (Android 14–17)

---

## Что тестируем в 1.4.0-beta9 (`global-beta`)

• [BETA 9] Полная сквозная поддержка пакетов тем, иконпаков и шрифтов Xiaomi MIUI / HyperOS (.mtz): умный импорт многослойных (layer_animating_icons, fancy_icons) и WebP-значков с выбором максимального DPI (xxxhdpi), извлечение шрифтов и обоев, очистка несовместимых оверлеев MIUI и прямое открытие .mtz / .itz из Telegram и проводников;
• [BETA 9] Точная подгонка размеров и палитры на 135%: потолок маски и масштабирование импортированных паков согласованы с сеткой BBKLauncher2 (236px), в гибридном бета-движке скомпенсирован множитель лаунчера (59/62) и выровнен цвет подложки при выключенных тумблерах «Системного стиля» Vivo;
• [BETA 9] Виджеты и папки: добавлен ползунок «Размер карточек виджетов (под иконки): 75–108%» во вкладке «Виджеты» (включая «Фото в стекле 2×2») и кнопка быстрого перехода к системному размеру папок и ячеек Vivo во вкладке «Форма»;
• [BETA 9] Мгновенное закрытие окна «Упаковка архива .itz…» без зависаний (даже если планировщик Vivo Hans/PEM заморозил Shizuku в фоне) + усиленный детектор и авто-бан повреждённых слотов в SQLite БД приложения «Темы» (iQOO Z10 5G, vivo V60, iQOO Z10R);
• [BETA 9] Автоматическое восстановление Always On Display (AOD) при запуске Студии через живую проверку провайдера com.vivo.nightpearl (срабатывает даже после «Сброса настроек системы»).

---

## Скачать Beta

- **[Универсальная ссылка (всегда последняя Global Beta APK)](https://github.com/Holy3holy-dev/OriginOS-Studio/releases/download/global-beta-latest/OriginOS-Studio-Global-Beta.apk)**
- **[Страница релиза Global Beta (`global-beta-latest`)](https://github.com/Holy3holy-dev/OriginOS-Studio/releases/tag/global-beta-latest)**
- **[Скачать OriginOS-Studio-Global-Beta-1.4.0-beta9.apk](https://github.com/Holy3holy-dev/OriginOS-Studio/releases/download/global-beta-v1.4.0-b9/OriginOS-Studio-Global-Beta-1.4.0-beta9.apk)**
- **[Стабильная ветка Global](https://github.com/Holy3holy-dev/OriginOS-Studio/tree/global)**

---

## Канал автообновления (OTA Global Beta)

- **Манифест обновлений Global Beta:** `https://raw.githubusercontent.com/Holy3holy-dev/OriginOS-Studio/global-beta/update.json`
- **Облачный каталог ресурсов:** `https://raw.githubusercontent.com/Holy3holy-dev/OriginOS-Studio/global-beta/catalog.json`
