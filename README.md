# OriginOS Studio (Global)

**Версия:** `1.1.9 (build 110) • ветка global • targetSdk 35 (Android 15) • RU / EN`  
**Пакет:** `rk.android.app.themedicons.vivo.global` (устанавливается параллельно с китайской версией)  
**Автор:** [H3H • Telegram: @holy3holy](https://t.me/holy3holy)  
**Платформа:** Vivo / iQOO — Global OriginOS 5 / 6 / 7 & Funtouch OS 14–15 (Android 14–17)

---

## Что нового в 1.1.9 (`global`)

- **Гарантированный системный перекрас всех 30 приложений Google (`Chrome`, `Телефон`, `Сообщения`, `YouTube`, `Play Маркет`, `Gmail`, `Карты`, `Кошелёк` и др.):** исправлен порядок активации триггеров кэша `BBKLauncher2` (`themed_icon_enabled = 1` перед импульсом `material_you_overlay_enable: 0 -> 1`), благодаря чему `ThemedIconDrawable` создаётся на рабочем столе, в доке и папках даже при открытом окне Студии, при выборе сторонних иконпаков / `.itz` и сразу после обновления APK;
- **Поддержка гигантских архивов `.itz` / `.mtz` / `.zip` до 8 ГБ:** снято ограничение в 384 МБ и внедрена потоковая распаковка без временных гигабайтных копий с умной фильтрацией иконок под реально установленные на устройстве приложения и системные сервисы Vivo — даже многогигабайтные паки на 15 000 – 40 000 PNG мгновенно сжимаются и применяются на рабочий стол за пару секунд;
- **Защита от «залипания» на чужой скачанной теме:** изолированы `packageId = ""` в `ThemeItem`, синтетический `usePackId` в `DisassembleApplyItem` и автоподбор чистого онлайн-слота в локальной базе `ResDbUtils` (`com.bbk.theme`).

---

## Скачать

- **[Скачать OriginOS-Studio-Global-1.1.9.apk](https://github.com/Holy3holy-dev/OriginOS-Studio/releases/download/global-v1.1.9/OriginOS-Studio-Global-1.1.9.apk)**
- **[Все релизы на GitHub](https://github.com/Holy3holy-dev/OriginOS-Studio/releases)**
- **[Telegram-канал H3H](https://t.me/holy3holy)**

---

## Канал автообновления (OTA Global)

- **Манифест обновлений Global:** `https://raw.githubusercontent.com/Holy3holy-dev/OriginOS-Studio/global/update.json`
- **Облачный каталог ресурсов:** `https://raw.githubusercontent.com/Holy3holy-dev/OriginOS-Studio/global/catalog.json`
