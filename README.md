# OriginOS Studio (Global)

**Версия:** `1.2.0 (build 111) • ветка global • targetSdk 35 (Android 15) • RU / EN`  
**Пакет:** `rk.android.app.themedicons.vivo.global` (устанавливается параллельно с китайской версией)  
**Автор:** [H3H • Telegram: @holy3holy](https://t.me/holy3holy)  
**Платформа:** Vivo / iQOO — Global OriginOS 5 / 6 / 7 & Funtouch OS 14–15 (Android 14–17)

---

## Что нового в 1.2.0 (`global`)

- **Подлинные текстуры 1:1 при импорте любых `.itz` / `.mtz` / `.zip` и растровых стилях («Жидкое стекло», `AMOLED`, `Nothing Dot Matrix`, APK-иконпаки):** исправлен конфликт с системным флагом `themed_icon_enabled = 1` в `BBKLauncher2`, из-за которого импортированные чёрно-стеклянные и цветные паки перекрывались плоскими кружками Android Monet. При первом запуске `1.2.0` уже установленные пакеты `.itz` проявляются на рабочем столе мгновенно, а повторное нажатие «Применить иконки» пересобирает импортированный `.itz` 1:1 байт-в-байт без потери прозрачности и формы;
- **Оригинальное живое размытие папок OriginOS (`OriginFolderIconBlurView`):** в режиме папок «Родной (OriginOS)» убран блокирующий аппаратный `Blur` тег `<folder_color>` в `launcher/iconsize.xml`, благодаря чему большие папки сохраняют настоящее живое размытие обоев и заводской стеклянный контур 1:1 со стоковой OriginOS;
- **Умный перекрас всех 30 приложений Google:** автоматическая системная тонировка Google в доке и папках работает по умолчанию в чистом стиле `Material You`, а для стеклянных и кастомных стилей может включаться вручную тумблером или заменяться значками 1:1 без сброса текстур `.itz`.

---

## Скачать

- **[Скачать OriginOS-Studio-Global-1.2.0.apk](https://github.com/Holy3holy-dev/OriginOS-Studio/releases/download/global-v1.2.0/OriginOS-Studio-Global-1.2.0.apk)**
- **[Все релизы на GitHub](https://github.com/Holy3holy-dev/OriginOS-Studio/releases)**
- **[Telegram-канал H3H](https://t.me/holy3holy)**

---

## Канал автообновления (OTA Global)

- **Манифест обновлений Global:** `https://raw.githubusercontent.com/Holy3holy-dev/OriginOS-Studio/global/update.json`
- **Облачный каталог ресурсов:** `https://raw.githubusercontent.com/Holy3holy-dev/OriginOS-Studio/global/catalog.json`
