# OriginOS Studio (Global)

**Версия:** `1.3.6 (build 127) • ветка global • targetSdk 35 (Android 15) • RU / EN`  
**Пакет:** `rk.android.app.themedicons.vivo.global` (устанавливается параллельно с китайской версией)  
**Автор:** [H3H • Telegram: @holy3holy](https://t.me/holy3holy)  
**Платформа:** Vivo / iQOO — Global OriginOS 5 / 6 / 7 & Funtouch OS 14–15 (Android 14–17)

---

## Что нового в 1.3.6 (`global`)

• Окончательно устранён сбой повторного применения значков на OriginOS 6 Global (iQOO Z10 5G, vivo V60, iQOO Z10R и др.): проблемный слот «Wonderful universe» (100001241) исключён, внедрена единая постоянная папка стейджинга .stage_theme (устраняющая сброс значков в сток при чтении старого пути из БД com.bbk.theme), авто-бан повреждённых слотов и аппаратное определение региона без влияния языка системы
• Полностью убрано зависание на «Упаковка архива .itz…» до сворачивания окна: опрос замороженного системного провайдера Shizuku вынесен из UI-потока с таймаутом 650 мс, закрытие диалога отделено от пост-обработки, а запись PNG в .itz переведена в быстрый режим STORED без повторного сжатия
• Единый 1:1 размер и цвет системных, Google и сторонних иконок на масштабе 135–140% (компенсация 236px под BBKLauncher2), плавный суперэллипс Ламе n=3.80 по умолчанию, точный рендер однотонных APK-паков (Material 3 White/Dark), защита VPN-значков с пустым <foreground> и ползунок рисунка внутри «Жидкого стекла» (75–145%)
• Виджеты иконок 1×1: ровный квадратный холст 288×288, автоподстройка под размер значков рабочего стола и реальное увеличение до 145% (под размер док-бара) + настройка системного размера папок
• Глубокое восстановление Always On Display (проверка живого провайдера com.vivo.nightpearl, фильтрация битых часов/AOD из импортированных тем и перезапуск службы AOD в 1 касание) + непрерывная фоновая загрузка из каталога с докачкой HTTP Range

---

## Скачать

- **[Универсальная ссылка (всегда последняя версия Global APK)](https://github.com/Holy3holy-dev/OriginOS-Studio/releases/download/global-latest/OriginOS-Studio-Global.apk)**
- **[Актуальное описание Global (`global-latest`)](https://github.com/Holy3holy-dev/OriginOS-Studio/releases/tag/global-latest)**
- **[Скачать OriginOS-Studio-Global-1.3.6.apk](https://github.com/Holy3holy-dev/OriginOS-Studio/releases/download/global-v1.3.6/OriginOS-Studio-Global-1.3.6.apk)**
- **[Все релизы на GitHub](https://github.com/Holy3holy-dev/OriginOS-Studio/releases)**
- **[Telegram-канал H3H](https://t.me/holy3holy)**

---

## Канал автообновления (OTA Global)

- **Манифест обновлений Global:** `https://raw.githubusercontent.com/Holy3holy-dev/OriginOS-Studio/global/update.json`
- **Облачный каталог ресурсов:** `https://raw.githubusercontent.com/Holy3holy-dev/OriginOS-Studio/global/catalog.json`
