# OriginOS Studio (Global Beta)

**Версия:** `1.4.0-beta14 (build 214) • ветка global-beta • targetSdk 35 (Android 15) • RU / EN`  
**Пакет:** `rk.android.app.themedicons.vivo.global.beta` (устанавливается параллельно со стабильной Global и CN версиями)  
**Автор:** [H3H • Telegram: @holy3holy](https://t.me/holy3holy)  
**Платформа:** Vivo / iQOO — Global OriginOS 5 / 6 / 7 & Funtouch OS 14–15 (Android 14–17)

---

## Что тестируем в 1.4.0-beta14 (`global-beta`)

• [BETA 14 • 100% перекрас всех 26 защищённых приложений Google GMS] В модуль лаунчера добавлены все 6 системных цветовых токенов (_light и _dark варианты для светлой и тёмной тем Android 15–17), убран мёртвый код FabricatedOverlay/ThemeIconManager, добавлен синхронный подъём рабочего стола HOME и двойной фронт 0 -> 1;
• [BETA 14 • Крупные папки и плавное скругление] Встроенный режим темы (<id>20</id><edition>1</edition><innertype>1</innertype>) теперь записывается до системного копирования в обход ограничений SELinux, возвращая полноразмерные папки и скруглённое сворачивание без квадратиков;
• [BETA 14 • Единый размер Галереи и контур углов .itz] Системные иконки (com.vivo.gallery и mBehaviorIconList) выравниваются по точному медианному диаметру пака, квадратные плитки обрезаются точно по эталонному контуру launcher/icon_mask.png, а непокрытые приложения (Настройки, Sota Connect, YouTube и др.) очищаются от белых рамок через BFS flood-fill;
• [BETA 14 • Сбалансированные 1×1 виджеты + DynamicSystemTintEngine] Равносторонний адаптивный холст виджетов (padding="0dp", offsetY=0) с полным сохранением бета-движка живой системной палитры DynamicSystemTintEngine.

---

## Скачать Beta

- **[Универсальная ссылка (всегда последняя Global Beta APK)](https://github.com/Holy3holy-dev/OriginOS-Studio/releases/download/global-beta-latest/OriginOS-Studio-Global-Beta.apk)**
- **[Страница релиза Global Beta (`global-beta-latest`)](https://github.com/Holy3holy-dev/OriginOS-Studio/releases/tag/global-beta-latest)**
- **[Скачать OriginOS-Studio-Global-Beta-1.4.0-beta14.apk](https://github.com/Holy3holy-dev/OriginOS-Studio/releases/download/global-beta-v1.4.0-b14/OriginOS-Studio-Global-Beta-1.4.0-beta14.apk)**
- **[Стабильная ветка Global](https://github.com/Holy3holy-dev/OriginOS-Studio/tree/global)**

---

## Канал автообновления (OTA Global Beta)

- **Манифест обновлений Global Beta:** `https://raw.githubusercontent.com/Holy3holy-dev/OriginOS-Studio/global-beta/update.json`
- **Облачный каталог ресурсов:** `https://raw.githubusercontent.com/Holy3holy-dev/OriginOS-Studio/global-beta/catalog.json`
