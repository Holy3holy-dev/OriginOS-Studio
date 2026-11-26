# OriginOS Studio (Global Beta)

**Версия:** `1.4.0-beta8 (build 208) • ветка global-beta • targetSdk 35 (Android 15) • RU / EN`  
**Пакет:** `rk.android.app.themedicons.vivo.global.beta` (устанавливается параллельно со стабильной Global и CN версиями)  
**Автор:** [H3H • Telegram: @holy3holy](https://t.me/holy3holy)  
**Платформа:** Vivo / iQOO — Global OriginOS 5 / 6 / 7 & Funtouch OS 14–15 (Android 14–17)

---

## Что тестируем в 1.4.0-beta8 (`global-beta`)

• [BETA 8] Окончательно устранён сбой повторного применения значков на OriginOS 6 Global (iQOO Z10 5G, vivo V60, iQOO Z10R и др.): проблемная карточка «Wonderful universe» (100001241) удалена, внедрена единая постоянная папка стейджинга .stage_theme (исключающая копирование пустых значков при чтении старого пути из SQLite БД com.bbk.theme), авто-бан повреждённых слотов и аппаратное определение региона без влияния языка меню;
• [BETA 8] Полностью убрано зависание на «Упаковка архива .itz…» до сворачивания окна: опрос замороженного системного провайдера Shizuku вынесен из UI-потока в пул с таймаутом 650 мс, закрытие диалога отделено от пост-обработки, а запись PNG в .itz переведена в прямой режим STORED без повторного сжатия;
• [BETA 8] Единый размер и цвет системных, Google и сторонних иконок на масштабе 135–140% (компенсация 236px под BBKLauncher2), плавный суперэллипс Ламе n=3.80 по умолчанию, изоляция внешних иконпаков и «Жидкого стекла» от гибридного движка, защита VPN-значков с пустым <foreground> и ползунок рисунка внутри стекла (75–145%);
• [BETA 8] Виджеты иконок 1×1: ровный квадратный холст 288×288, автоподстройка под масштаб значков рабочего стола и реальное увеличение до 145% (под размер иконок в док-баре);
• [BETA 8] Глубокое восстановление Always On Display (проверка живого провайдера com.vivo.nightpearl, очистка битых часов/AOD из импортированных тем и перезапуск службы AOD в 1 касание) + непрерывная фоновая загрузка паков и обновлений с докачкой HTTP Range.

---

## Скачать Beta

- **[Универсальная ссылка (всегда последняя Global Beta APK)](https://github.com/Holy3holy-dev/OriginOS-Studio/releases/download/global-beta-latest/OriginOS-Studio-Global-Beta.apk)**
- **[Страница релиза Global Beta (`global-beta-latest`)](https://github.com/Holy3holy-dev/OriginOS-Studio/releases/tag/global-beta-latest)**
- **[Скачать OriginOS-Studio-Global-Beta-1.4.0-beta8.apk](https://github.com/Holy3holy-dev/OriginOS-Studio/releases/download/global-beta-v1.4.0-b8/OriginOS-Studio-Global-Beta-1.4.0-beta8.apk)**
- **[Стабильная ветка Global](https://github.com/Holy3holy-dev/OriginOS-Studio/tree/global)**

---

## Канал автообновления (OTA Global Beta)

- **Манифест обновлений Global Beta:** `https://raw.githubusercontent.com/Holy3holy-dev/OriginOS-Studio/global-beta/update.json`
- **Облачный каталог ресурсов:** `https://raw.githubusercontent.com/Holy3holy-dev/OriginOS-Studio/global-beta/catalog.json`
