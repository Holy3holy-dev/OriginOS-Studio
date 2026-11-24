# OriginOS Studio (Global)

**Версия:** `1.2.2 (build 113) • ветка global • targetSdk 35 (Android 15) • RU / EN`  
**Пакет:** `rk.android.app.themedicons.vivo.global` (устанавливается параллельно с китайской версией)  
**Автор:** [H3H • Telegram: @holy3holy](https://t.me/holy3holy)  
**Платформа:** Vivo / iQOO — Global OriginOS 5 / 6 / 7 & Funtouch OS 14–15 (Android 14–17)

---

## Что нового в 1.2.2 (`global`)

- **Полноценная смена стиля шрифта во всех странах мира (`RU` / `KZ` / `BY` / `UA` / `EU` / `ASIA`):** устранено попадание на платные региональные карточки шрифтов (из-за чего менялась только насыщенность текста, а сама гарнитура не применялась) — внедрён единый кросс-региональный пул бесплатных слотов `400000001..400000012`, чтение фактического пути из `ResDbUtils`, непустой HEX `packageId` и фильтр платных кнопок;
- **Работа в плавающем смарт-окне боковой панели OriginOS (`freeform`) и быстрый выбор файлов в 1 касание:** добавлены `configChanges` и `resizeableActivity` против сброса окна при возврате из системного проводника, а также встроенный диалог мгновенного выбора `.itz / .mtz / .zip` и `.ttf / .otf` прямо из папок `Download` и `Telegram`;
- **Защита от экрана «Нет ресурсов» в приложении Тем Vivo:** все 10 слотов тем заменены на универсальные мировые бесплатные ID (`100001241..100001259`) с автоматическим переключением на следующий слот при обнаружении `ListBlankView`.

---

## Скачать

- **[Скачать OriginOS-Studio-Global-1.2.2.apk](https://github.com/Holy3holy-dev/OriginOS-Studio/releases/download/global-v1.2.2/OriginOS-Studio-Global-1.2.2.apk)**
- **[Все релизы на GitHub](https://github.com/Holy3holy-dev/OriginOS-Studio/releases)**
- **[Telegram-канал H3H](https://t.me/holy3holy)**

---

## Канал автообновления (OTA Global)

- **Манифест обновлений Global:** `https://raw.githubusercontent.com/Holy3holy-dev/OriginOS-Studio/global/update.json`
- **Облачный каталог ресурсов:** `https://raw.githubusercontent.com/Holy3holy-dev/OriginOS-Studio/global/catalog.json`
