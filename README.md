# OriginOS Studio (Global)

**Версия:** `1.3.8 (build 129) • ветка global • targetSdk 35 (Android 15) • RU / EN`  
**Пакет:** `rk.android.app.themedicons.vivo.global` (устанавливается параллельно с китайской версией)  
**Автор:** [H3H • Telegram: @holy3holy](https://t.me/holy3holy)  
**Платформа:** Vivo / iQOO — Global OriginOS 5 / 6 / 7 & Funtouch OS 14–15 (Android 14–17)

---

## Что нового в 1.3.8 (`global`)

• Устранены белые и багнутые плашки на непокрытых приложениях (Hiddify, INCY и др.) при установке тёмных паков каталога (ColorOS 16 Dark Mint и др.): шаблонный белый launcher/icon_bg_default.png больше не подмешивается в тёмные наборы и автоматически заменяется карточкой цвета и диаметра самого пака, а вложенные квадратные плитки в <foreground> очищаются до чистого глифа
• Выровнен единый размер всех карточек импортированных .itz / .mtz паков (устранена разница на 25% между Галереей и Настройками): квадратные плитки скругляются суперэллипсом Ламе строго в диаметр остальных иконок пака вместо уменьшения до 180px
• Исправлен нативный перекрас всех приложений Google (Chrome, Gmail, Play, Maps, YouTube, G Pay) на OriginOS 6 Global (iQOO Z10 5G и др.): удаляются плотностные дубликаты launcher/xxxhdpi/iconsize.xml (<width>65</width>, <originostheme>1</originostheme>), а синхронизация монохромной палитры дожидается полного завершения SystemStyleApply в менеджере тем Vivo и удерживает оба системных флага активными

---

## Скачать

- **[Универсальная ссылка (всегда последняя версия Global APK)](https://github.com/Holy3holy-dev/OriginOS-Studio/releases/download/global-latest/OriginOS-Studio-Global.apk)**
- **[Актуальное описание Global (`global-latest`)](https://github.com/Holy3holy-dev/OriginOS-Studio/releases/tag/global-latest)**
- **[Скачать OriginOS-Studio-Global-1.3.8.apk](https://github.com/Holy3holy-dev/OriginOS-Studio/releases/download/global-v1.3.8/OriginOS-Studio-Global-1.3.8.apk)**
- **[Все релизы на GitHub](https://github.com/Holy3holy-dev/OriginOS-Studio/releases)**
- **[Telegram-канал H3H](https://t.me/holy3holy)**

---

## Канал автообновления (OTA Global)

- **Манифест обновлений Global:** `https://raw.githubusercontent.com/Holy3holy-dev/OriginOS-Studio/global/update.json`
- **Облачный каталог ресурсов:** `https://raw.githubusercontent.com/Holy3holy-dev/OriginOS-Studio/global/catalog.json`
