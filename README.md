# OriginOS Studio (Global)

**Версия:** `1.1.7 (build 108) • ветка global • targetSdk 35 (Android 15) • RU / EN`  
**Пакет:** `rk.android.app.themedicons.vivo.global` (устанавливается параллельно с китайской версией)  
**Автор:** [H3H • Telegram: @holy3holy](https://t.me/holy3holy)  
**Платформа:** Vivo / iQOO — Global OriginOS 5 / 6 / 7 & Funtouch OS 14–15 (Android 14–17)

---

## Что нового в 1.1.7 (`global`)

- **Устранена нехватка памяти (`Failed to allocate 201326608 / 134217744 bytes`):** упаковка пакета значков при 350+ установленных приложениях и импорт тяжёлых архивов переведены на потоковую запись во временные файлы на диске с включённым `largeHeap`;
- **Импорт любых сторонних `.itz`, `.zip` и Xiaomi `.mtz` наборов:** автоматическое распознавание вложенных архивов, раскладка MIUI `res/drawable-*` и корневых PNG в `icons/`, маппинг системных пакетов MIUI → Vivo и чистый разбор многоязычных `<title>`;
- **Стабильность приложений после смены шрифта:** удалён сброс системного хранилища обновляемых шрифтов (`cmd font clear`), вызывавший падения живых приложений, и добавлена бинарная валидация таблиц TrueType (`.ttf`);
- **Рабочие банковские ярлыки 1:1 (`SberPay`, `T-Pay`, оплата, чаты):** запуск перекрашенных ярлыков выполняется напрямую через системный `LauncherApps.startShortcut` без потери внутренних ссылок и параметров;
- **Стоковое тёмное стекло папок OriginOS:** в режиме «Родной (OriginOS)» и новом пресете «Тёмное стекло» папки на чёрных обоях сохраняют тёмное полупрозрачное матовое стекло вместо светло-серой заливки;
- **«Жидкое стекло» прямо в Каталоге иконпаков + чистота для Vivo iManager:** встроенный офлайн-генератор на первом месте «Иконпаков», резервные прямые ссылки на все APK и устранение ложного предупреждения «Приложение с признаками рекламы».

---

## Скачать

- **[Скачать OriginOS-Studio-Global-1.1.7.apk](https://github.com/Holy3holy-dev/OriginOS-Studio/releases/download/global-v1.1.7/OriginOS-Studio-Global-1.1.7.apk)**
- **[Все релизы на GitHub](https://github.com/Holy3holy-dev/OriginOS-Studio/releases)**
- **[Telegram-канал H3H](https://t.me/holy3holy)**

---

## Канал автообновления (OTA Global)

- **Манифест обновлений Global:** `https://raw.githubusercontent.com/Holy3holy-dev/OriginOS-Studio/global/update.json`
- **Облачный каталог ресурсов:** `https://raw.githubusercontent.com/Holy3holy-dev/OriginOS-Studio/global/catalog.json`
