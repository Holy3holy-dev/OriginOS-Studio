# OriginOS Studio (Global Beta)

**Версия:** `1.4.0-beta7 (build 207) • ветка global-beta • targetSdk 35 (Android 15) • RU / EN`  
**Пакет:** `rk.android.app.themedicons.vivo.global.beta` (устанавливается параллельно со стабильной Global и CN версиями)  
**Автор:** [H3H • Telegram: @holy3holy](https://t.me/holy3holy)  
**Платформа:** Vivo / iQOO — Global OriginOS 5 / 6 / 7 & Funtouch OS 14–15 (Android 14–17)

---

## Что тестируем в 1.4.0-beta7 (`global-beta`)

• [BETA 7] Исправлен сбой повторного применения значков на OriginOS 6 Global (iQOO Z10 5G, vivo V60 и др.), когда после 1-го успешного раза карточка «Wonderful universe» визуально применялась, но значки оставались стоковыми: устранена перезапись карты применения в ResBasePreview.c0(), добавлена постоянная ротация донорских слотов и гарантированный сброс кеша лаунчера даже при ручном нажатии «Применить»;
• [BETA 7] Устранено зависание окна на этапе «Упаковка архива .itz…» (когда прогресс стоял до сворачивания приложения): убрано пересоздание окна от системного RRO во время сборки, добавлен живой прогресс сборки капсул 2×1 / 2×2 и коалесцирующий троттлинг UI;
• [BETA 6] Единый 1:1 размер для ВСЕХ иконок в сторонних APK-иконпаках (Material 3 White / Dark и др.), защита сложных значков без монохромного слоя от пустых квадратов и масштаб 140% (236px);
• [BETA 5] Полная защита и автовосстановление Always On Display («Всегда на экране» / com.vivo.nightpearl) в 1 касание.

---

## Скачать Beta

- **[Универсальная ссылка (всегда последняя Global Beta APK)](https://github.com/Holy3holy-dev/OriginOS-Studio/releases/download/global-beta-latest/OriginOS-Studio-Global-Beta.apk)**
- **[Страница релиза Global Beta (`global-beta-latest`)](https://github.com/Holy3holy-dev/OriginOS-Studio/releases/tag/global-beta-latest)**
- **[Скачать OriginOS-Studio-Global-Beta-1.4.0-beta7.apk](https://github.com/Holy3holy-dev/OriginOS-Studio/releases/download/global-beta-v1.4.0-b7/OriginOS-Studio-Global-Beta-1.4.0-beta7.apk)**
- **[Стабильная ветка Global](https://github.com/Holy3holy-dev/OriginOS-Studio/tree/global)**

---

## Канал автообновления (OTA Global Beta)

- **Манифест обновлений Global Beta:** `https://raw.githubusercontent.com/Holy3holy-dev/OriginOS-Studio/global-beta/update.json`
- **Облачный каталог ресурсов:** `https://raw.githubusercontent.com/Holy3holy-dev/OriginOS-Studio/global-beta/catalog.json`
