# OriginOS Studio (Global)

**Версия:** `1.2.1 (build 112) • ветка global • targetSdk 35 (Android 15) • RU / EN`  
**Пакет:** `rk.android.app.themedicons.vivo.global` (устанавливается параллельно с китайской версией)  
**Автор:** [H3H • Telegram: @holy3holy](https://t.me/holy3holy)  
**Платформа:** Vivo / iQOO — Global OriginOS 5 / 6 / 7 & Funtouch OS 14–15 (Android 14–17)

---

## Что нового в 1.2.1 (`global`)

- **Безотказное применение иконок на `iQOO Z10R` и всех Global OriginOS (`.itz` / `.mtz` / `.zip`, генератор Студии и Каталог):** устранён сброс сторонних приложений при распаковке в `app_process`, выровнены идентификаторы `packageId == usePackId` в `SystemStyleApply`, заменён пул резервных слотов на 8 реально существующих бесплатных тем глобального сервера Vivo и добавлен принудительный сброс бело-серых квадратов `MonochromeIcons.apk`;
- **Прямое применение `.itz`-иконпаков `@oosthemes` (`ColorOS 16`, `OneYou`, `M3 Black`) из Каталога:** исправлена ошибка `«Не удалось обработать пакет.»` — архивы `.itz` на вкладке «Иконпаки» автоматически мигрируются из кэша без повторного скачивания и применяются напрямую на рабочий стол без вызова системного установщика APK;
- **Мгновенное переподключение движка после перезагрузки и отсутствие ложного окна отладки:** оба mDNS-слушателя (`_adb-tls-connect._tcp` и `_adb-tls-pairing._tcp`) работают параллельно с поддержкой привязки `adbd` к локальному Wi-Fi интерфейсу Android 15–16, а перед запуском Тем уже сопряжённый демон тихо просыпается в фоне без показа окна «Включите отладку».

---

## Скачать

- **[Скачать OriginOS-Studio-Global-1.2.1.apk](https://github.com/Holy3holy-dev/OriginOS-Studio/releases/download/global-v1.2.1/OriginOS-Studio-Global-1.2.1.apk)**
- **[Все релизы на GitHub](https://github.com/Holy3holy-dev/OriginOS-Studio/releases)**
- **[Telegram-канал H3H](https://t.me/holy3holy)**

---

## Канал автообновления (OTA Global)

- **Манифест обновлений Global:** `https://raw.githubusercontent.com/Holy3holy-dev/OriginOS-Studio/global/update.json`
- **Облачный каталог ресурсов:** `https://raw.githubusercontent.com/Holy3holy-dev/OriginOS-Studio/global/catalog.json`
