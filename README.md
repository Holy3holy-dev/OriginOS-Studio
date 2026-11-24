# OriginOS Studio (Global)

**Версия:** `1.1.4 (build 105) • ветка global • RU / EN`  
**Пакет:** `rk.android.app.themedicons.vivo.global` (устанавливается параллельно с китайской версией)  
**Автор:** [H3H • Telegram: @holy3holy](https://t.me/holy3holy)  
**Платформа:** Vivo / iQOO — Global OriginOS 5 / 6 / 7 & Funtouch OS 14–15 (Android 14–17)

---

## Что нового в 1.1.4 (`global`)

- **Исправлено беспроводное подключение на всех прошивках и при включённом VPN:** устранён сбой `Conscrypt.exportKeyingMaterial недоступен` за счёт перехода на публичный SDK API `android.net.ssl.SSLSockets`, добавлен ввод `код + порт` прямо из шторки уведомлений (если активный VPN блокирует mDNS);
- **Эталонная штатная анимация открытия и закрытия приложений:** выровнена геометрия полей значков (`176 px` на холсте `240×240`) под `FloatingIconView` лаунчера Vivo, очищен сбитый системный флаг `deform_icons_size` и возвращены ровные зазоры между иконками в папках `3×3` и `1×3`;
- **Покраска широких пилюль `2×1` / `1×2` / `2×2` («Темы», «Настройки» и др.):** генерация полноразмерных капсул `480×240`, `240×480`, `480×480` и `384×192`, индивидуальных растянутых иконок приложений и глобальных алиасов (`com.android.thememanager`), плюс быстрый доступ к замене `Google Телефона` и `Сообщений`;
- **Линзовая оптика «Жидкого стекла»:** прозрачный центр линзы для глубокого просвечивания живых обоев, эффект Френеля по краям, верхний мениск и нижняя каустическая грань.

---

## Скачать

- **[Скачать OriginOS-Studio-Global-1.1.4.apk](https://github.com/Holy3holy-dev/OriginOS-Studio/releases/download/global-v1.1.4/OriginOS-Studio-Global-1.1.4.apk)**
- **[Все релизы на GitHub](https://github.com/Holy3holy-dev/OriginOS-Studio/releases)**
- **[Telegram-канал H3H](https://t.me/holy3holy)**

---

## Канал автообновления (OTA Global)

- **Манифест обновлений Global:** `https://raw.githubusercontent.com/Holy3holy-dev/OriginOS-Studio/global/update.json`
- **Облачный каталог ресурсов:** `https://raw.githubusercontent.com/Holy3holy-dev/OriginOS-Studio/main/catalog.json`
