# OriginOS Studio (Global)

**Версия:** `1.3.0 (build 121) • ветка global • targetSdk 35 (Android 15) • RU / EN`  
**Пакет:** `rk.android.app.themedicons.vivo.global` (устанавливается параллельно с китайской версией)  
**Автор:** [H3H • Telegram: @holy3holy](https://t.me/holy3holy)  
**Платформа:** Vivo / iQOO — Global OriginOS 5 / 6 / 7 & Funtouch OS 14–15 (Android 14–17)

---

## Что нового в 1.3.0 (`global`)

- **Нативный перекрас ВСЕХ значков прямо в лаунчере без костылей, ярлыков и угловых значков Студии:** внедрён изолированный модуль темы `com.bbk.launcher2` (`theme_values.xml`), который окрашивает все 27 защищённых GMS-приложений Google (`Chrome`, `YouTube`, `Google Play`, `Gmail`, `Телефон`, `Сообщения` и др.) строго в выбранный цвет Студии (`Material You`, «Жидкое стекло» с живой прозрачностью, `AMOLED`, иконпак или импортированный `.itz`/`.mtz`) — независимо от системной палитры Настроек телефона;
- **Полноценный перекрас растянутых иконок приложений (`2×1`, `1×2`, `2×2`) на OriginOS 6 и OriginOS 7:** снята блокировка `<originostheme>` для несистемных программ, добавлена бесшовная сборка полупрозрачных стеклянных капсул и автогенерация растянутых вариантов внутри импортированных `.itz` / `.mtz` паков;
- **100% покрытие установленных приложений при импорте `.itz` / `.mtz` / `.zip`:** приложения, которых не было у автора пака, автоматически дорендериваются в точную форму, прозрачность и цветовую пару выбранного набора;
- **Новый надёжный движок виджета «Погода 4 дня (`4×2`)»:** выделенная XML-разметка `widget_origin_weather`, прямое чтение локального провайдера погоды Vivo, векторные иконки осадков и мгновенная отрисовка при перетаскивании на рабочий стол.

---

## Скачать

- **[Универсальная ссылка (всегда последняя версия Global APK)](https://github.com/Holy3holy-dev/OriginOS-Studio/releases/download/global-latest/OriginOS-Studio-Global.apk)**
- **[Актуальное описание Global (`global-latest`)](https://github.com/Holy3holy-dev/OriginOS-Studio/releases/tag/global-latest)**
- **[Скачать OriginOS-Studio-Global-1.3.0.apk](https://github.com/Holy3holy-dev/OriginOS-Studio/releases/download/global-v1.3.0/OriginOS-Studio-Global-1.3.0.apk)**
- **[Все релизы на GitHub](https://github.com/Holy3holy-dev/OriginOS-Studio/releases)**
- **[Telegram-канал H3H](https://t.me/holy3holy)**

---

## Канал автообновления (OTA Global)

- **Манифест обновлений Global:** `https://raw.githubusercontent.com/Holy3holy-dev/OriginOS-Studio/global/update.json`
- **Облачный каталог ресурсов:** `https://raw.githubusercontent.com/Holy3holy-dev/OriginOS-Studio/global/catalog.json`
