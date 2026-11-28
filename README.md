# OriginOS Studio (Global Beta)

**Версия:** `1.4.0-beta16 (build 216) • ветка global-beta • targetSdk 35 (Android 15) • RU / EN`  
**Пакет:** `rk.android.app.themedicons.vivo.global.beta` (устанавливается параллельно со стабильной Global и CN версиями)  
**Автор:** [H3H • Telegram: @holy3holy](https://t.me/holy3holy)  
**Платформа:** Vivo / iQOO — Global OriginOS 5 / 6 / 7 & Funtouch OS 14–15 (Android 14–17)

---

## Что тестируем в 1.4.0-beta16 (`global-beta`)

• [BETA 16 • Без выбросов на рабочий стол и мгновенное окно Тем] Убран принудительный переход CATEGORY_HOME из помощника (пользователя больше не выкидывает из Studio и сторонних приложений), убрана гонка 8 таймеров отложенной синхронизации (generation-токен + последовательная блокировка + проверка смены beforeThemeId), устранён двойной рестарт лаунчера при применении полной темы со шрифтом, ускорена подготовка перед запуском Тем и убран обрезанный технический хвост из тоста;
• [BETA 16 • Разрыв фоновой самопетли LiveThemeSyncService] Исключён самотриггер theme_icons_colors_changed_explore, добавлено окно подавления собственных записей и защита от принудительного открытия Тем поверх сторонних приложений из фона;
• [BETA 16 • 100% перекрас Google во всех режимах + сохранение выбора пользователя] Явный выбор «Перекрас всех приложений Google» больше не блокируется режимом «Без рамки 1:1» и не стирается при импорте .itz или смене стиля/пака; растровые icons/<google_pkg>.png автоматически исключаются при активном перекрасе Google, чтобы BBKLauncher2 гарантированно использовал ThemedIconDrawable.

---

## Скачать Beta

- **[Универсальная ссылка (всегда последняя Global Beta APK)](https://github.com/Holy3holy-dev/OriginOS-Studio/releases/download/global-beta-latest/OriginOS-Studio-Global-Beta.apk)**
- **[Страница релиза Global Beta (`global-beta-latest`)](https://github.com/Holy3holy-dev/OriginOS-Studio/releases/tag/global-beta-latest)**
- **[Скачать OriginOS-Studio-Global-Beta-1.4.0-beta16.apk](https://github.com/Holy3holy-dev/OriginOS-Studio/releases/download/global-beta-v1.4.0-b16/OriginOS-Studio-Global-Beta-1.4.0-beta16.apk)**
- **[Стабильная ветка Global](https://github.com/Holy3holy-dev/OriginOS-Studio/tree/global)**

---

## Канал автообновления (OTA Global Beta)

- **Манифест обновлений Global Beta:** `https://raw.githubusercontent.com/Holy3holy-dev/OriginOS-Studio/global-beta/update.json`
- **Облачный каталог ресурсов:** `https://raw.githubusercontent.com/Holy3holy-dev/OriginOS-Studio/global-beta/catalog.json`
