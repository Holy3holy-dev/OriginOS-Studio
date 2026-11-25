# OriginOS Studio (Global)

**Версия:** `1.3.2 (build 123) • ветка global • targetSdk 35 (Android 15) • RU / EN`  
**Пакет:** `rk.android.app.themedicons.vivo.global` (устанавливается параллельно с китайской версией)  
**Автор:** [H3H • Telegram: @holy3holy](https://t.me/holy3holy)  
**Платформа:** Vivo / iQOO — Global OriginOS 5 / 6 / 7 & Funtouch OS 14–15 (Android 14–17)

---

## Что нового в 1.3.2 (`global`)

- **Исправлен перекрас всех 30 системных значков Google без самосброса и серых квадратов:** устранён сброс переключателя «Перекрас всех приложений Google (док и папки)», исправлена передача альфа-канала линзы для «Жидкого стекла» (`BlendMode.SRC_IN`) и добавлен автоматический сброс RAM-кеша модулей лаунчера `com.android.launcher3` сразу после установки `.itz`, чтобы цвета и прозрачность Студии применялись с первого раза без перезагрузки телефона;
- **Ускорение упаковки `.itz` в 6–8 раз:** генерация широких и высоких капсул (`2×1`, `1×2`, `2×2`) переведена на многопоточный пул ядер процессора;
- **Мгновенное закрытие окна применения темы (~1 с):** добавлен учёт вычисляемого `disassemble theme_id` (`(pkgId + 0x70) + "10"`) при ротации слотов и мгновенная проверка завершения копирования по `content/config.xml`.

---

## Скачать

- **[Универсальная ссылка (всегда последняя версия Global APK)](https://github.com/Holy3holy-dev/OriginOS-Studio/releases/download/global-latest/OriginOS-Studio-Global.apk)**
- **[Актуальное описание Global (`global-latest`)](https://github.com/Holy3holy-dev/OriginOS-Studio/releases/tag/global-latest)**
- **[Скачать OriginOS-Studio-Global-1.3.2.apk](https://github.com/Holy3holy-dev/OriginOS-Studio/releases/download/global-v1.3.2/OriginOS-Studio-Global-1.3.2.apk)**
- **[Все релизы на GitHub](https://github.com/Holy3holy-dev/OriginOS-Studio/releases)**
- **[Telegram-канал H3H](https://t.me/holy3holy)**

---

## Канал автообновления (OTA Global)

- **Манифест обновлений Global:** `https://raw.githubusercontent.com/Holy3holy-dev/OriginOS-Studio/global/update.json`
- **Облачный каталог ресурсов:** `https://raw.githubusercontent.com/Holy3holy-dev/OriginOS-Studio/global/catalog.json`
