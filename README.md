# OriginOS Studio (Global Beta)

**Версия:** `1.4.0-beta15 (build 215) • ветка global-beta • targetSdk 35 (Android 15) • RU / EN`  
**Пакет:** `rk.android.app.themedicons.vivo.global.beta` (устанавливается параллельно со стабильной Global и CN версиями)  
**Автор:** [H3H • Telegram: @holy3holy](https://t.me/holy3holy)  
**Платформа:** Vivo / iQOO — Global OriginOS 5 / 6 / 7 & Funtouch OS 14–15 (Android 14–17)

---

## Что тестируем в 1.4.0-beta15 (`global-beta`)

• [BETA 15 • Правильная шкала скругления Global OriginOS и разблокировка углов] Выровнена инвертированная Global-шкала радиусов (0 = Круглые, 1 = One UI, 2 = Стандартный OriginOS 0.27, 3 = Квадратные) и сброшена привязка launcher_icon_corner_follow_system = 0: папки 1×1, ячейки при перетаскивании и анимация сворачивания больше не скругляются в круг, а ползунок «Скругленные углы» снова разблокирован;
• [BETA 15 • Убрана ступенька («огрызок») и выровнен форм-фактор карточек] Контур скругления переведён на гладкую аппаратную дугу roundRect с зажимом диаметра маски ≤ 234px (без 1–2px «огрызка» на Google-иконках), добавлен автозамер реального cornerRatio импортированных .itz-паков и унифицирован isShapelessMode (сложные/непокрытые карточки полностью совпадают с паком);
• [BETA 15 • 100% перекрас Google без гонки при холодном старте] Флаг themed_icon_enabled = 1 выставляется до force-stop лаунчера и гарантируется в finally, добавлен fallback фокуса dumpsys activity activities, увеличены паузы перед импульсом 0 -> 1 в помощнике и onStudioMovedToBackground;
• [BETA 15 • Регрессионные автотесты + DynamicSystemTintEngine] Добавлены JVM-тесты Global-шкалы скругления, пиксельного контура без «огрызка» и замера cornerRatio при полном сохранении бета-движка живой палитры DynamicSystemTintEngine.

---

## Скачать Beta

- **[Универсальная ссылка (всегда последняя Global Beta APK)](https://github.com/Holy3holy-dev/OriginOS-Studio/releases/download/global-beta-latest/OriginOS-Studio-Global-Beta.apk)**
- **[Страница релиза Global Beta (`global-beta-latest`)](https://github.com/Holy3holy-dev/OriginOS-Studio/releases/tag/global-beta-latest)**
- **[Скачать OriginOS-Studio-Global-Beta-1.4.0-beta15.apk](https://github.com/Holy3holy-dev/OriginOS-Studio/releases/download/global-beta-v1.4.0-b15/OriginOS-Studio-Global-Beta-1.4.0-beta15.apk)**
- **[Стабильная ветка Global](https://github.com/Holy3holy-dev/OriginOS-Studio/tree/global)**

---

## Канал автообновления (OTA Global Beta)

- **Манифест обновлений Global Beta:** `https://raw.githubusercontent.com/Holy3holy-dev/OriginOS-Studio/global-beta/update.json`
- **Облачный каталог ресурсов:** `https://raw.githubusercontent.com/Holy3holy-dev/OriginOS-Studio/global-beta/catalog.json`
