# OriginOS Studio (Global)

**Версия:** `1.2.9 (build 120) • ветка global • targetSdk 35 (Android 15) • RU / EN`  
**Пакет:** `rk.android.app.themedicons.vivo.global` (устанавливается параллельно с китайской версией)  
**Автор:** [H3H • Telegram: @holy3holy](https://t.me/holy3holy)  
**Платформа:** Vivo / iQOO — Global OriginOS 5 / 6 / 7 & Funtouch OS 14–15 (Android 14–17)

---

## Что нового в 1.2.9 (`global`)

- **Исправлен виджет «Погода 4 дня (`4×2`)» (и стеклянные виджеты Фото `2×2` / Заметка `4×2`):** устранена привязка битмапа `RemoteViews` к несуществующему ID ресурса (теперь используется `@id/image_back` с Binder-безопасным разрешением и мгновенным предпросмотром);
- **Значки Google `1×1` без синего кружка Студии в углу:** при выносе оригинальных значков Google из иконпака по умолчанию используется режим **«✨ Чистый виджет 1×1 (0% значка Студии в углу)»** вместо системного pinned-shortcut Android 15/16 (с возможностью переключиться на ярлык для дока и папок);
- **Защита значков Google от шестиугольной обрезки:** при применении квадратных полноразмерных паков и импортированных `.itz` маска `launcher/icon_mask.png` больше не наследует старую форму шестиугольника;
- **Полное покрытие системных приложений Vivo и автоподложка для игр при импорте `.itz` / `.mtz`:** добавлен мульти-алиас реестр пакетов ColorOS 16 / OxygenOS 16 / HyperOS / китайских `.itz` -> глобальных пакетов Vivo (`com.vivo.imanager` iManager, Камера, Настройки, Темы, EasyShare) и автоматическая карточка в цвет пака для непокрытых игр.

---

## Скачать

- **[Универсальная ссылка (всегда последняя версия Global APK)](https://github.com/Holy3holy-dev/OriginOS-Studio/releases/download/global-latest/OriginOS-Studio-Global.apk)**
- **[Актуальное описание Global (`global-latest`)](https://github.com/Holy3holy-dev/OriginOS-Studio/releases/tag/global-latest)**
- **[Скачать OriginOS-Studio-Global-1.2.9.apk](https://github.com/Holy3holy-dev/OriginOS-Studio/releases/download/global-v1.2.9/OriginOS-Studio-Global-1.2.9.apk)**
- **[Все релизы на GitHub](https://github.com/Holy3holy-dev/OriginOS-Studio/releases)**
- **[Telegram-канал H3H](https://t.me/holy3holy)**

---

## Канал автообновления (OTA Global)

- **Манифест обновлений Global:** `https://raw.githubusercontent.com/Holy3holy-dev/OriginOS-Studio/global/update.json`
- **Облачный каталог ресурсов:** `https://raw.githubusercontent.com/Holy3holy-dev/OriginOS-Studio/global/catalog.json`
