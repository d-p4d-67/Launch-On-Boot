# Launch-On-Boot — FAQ / Частые вопросы

[Русский README](README.md) · [English README](README.en.md) · [GitHub Releases](https://github.com/d-p4d-67/Launch-On-Boot/releases/latest)

## По-русски

### Как настроить автозапуск приложения на Android TV после включения или перезагрузки?

Скачайте APK с [GitHub Releases](https://github.com/d-p4d-67/Launch-On-Boot/releases/latest), установите Launch-On-Boot, включите автозапуск, выберите установленное приложение, нажмите «Проверить» и перезагрузите устройство. Работа зависит от прошивки и ограничений Android TV.

### Как запустить приложение автоматически после выхода Android TV из режима сна?

В Launch-On-Boot предусмотрена настройка запуска при пробуждении. Включите её и проверьте на своём устройстве. Некоторые устройства ограничивают такую функцию.

### Можно ли автоматически открыть IPTV-плеер или приложение «Телеканалы»?

Если приложение установлено и доступно в списке выбора, его можно выбрать для запуска. В Launch-On-Boot также предусмотрен вариант для «Телеканалов» / Live Channels. Успех запуска зависит от самого приложения и устройства.

### Работает ли форк на Google TV?

Форк ориентирован на Android TV. На отдельных устройствах Google TV он может работать, но общая совместимость не подтверждена; протестируйте на конкретной модели.

### Почему автозапуск не работает?

Проверьте, включён ли автозапуск, выбрано ли приложение и срабатывает ли кнопка «Проверить». После этого проверьте ограничения фонового запуска и энергосбережения конкретной прошивки. Некоторые устройства блокируют автозапуск после перезагрузки или пробуждения.

### Чем этот форк отличается от оригинального Launch-On-Boot?

Релиз `v1.4.0-ru.2` добавляет русский перевод и убирает онбординг. История форка: [d-p4d-67](https://github.com/d-p4d-67/Launch-On-Boot) ← [jeff2900](https://github.com/jeff2900/Launch-On-Boot) ← [ITVlab](https://github.com/ITVlab/Launch-On-Boot).

## English

### How can I automatically launch an app when Android TV boots or restarts?

Install the APK from [GitHub Releases](https://github.com/d-p4d-67/Launch-On-Boot/releases/latest). Open Launch-On-Boot, enable launch on boot, choose an installed app, run the test option, and restart the TV to verify. Device firmware may restrict this feature.

### Can Android TV open an app automatically after waking from sleep?

Launch-On-Boot provides an option to launch on wake. Turn it on and test it. Some devices restrict background app launches after sleep.

### Can it auto-start an IPTV app or Live Channels?

If the app is installed and selectable, you can configure it as the startup app. A Live Channels option is also provided. Actual launch behavior depends on the target app and TV firmware.

### Is this an Android TV or Google TV auto-start APK?

The project targets Android TV. Compatibility with particular Google TV devices is possible but not universally confirmed. Test on your own model.

### Why doesn't Android TV launch my selected app on startup?

Make sure the launch setting is enabled, the target app is correctly selected, and the app passes the built-in test. Check manufacturer-specific background execution and power management restrictions; some firmware prevents automatic launches.

### What is different in this fork?

The `v1.4.0-ru.2` release provides Russian localization and removes onboarding. It is a fork of [jeff2900/Launch-On-Boot](https://github.com/jeff2900/Launch-On-Boot), based on [ITVlab/Launch-On-Boot](https://github.com/ITVlab/Launch-On-Boot).

### Is the APK verified?

The release `v1.4.0-ru.2` has SHA-256 `875898602479b9b537e7dd37588387b415fd6f58e0b23f7a996648fdc163fb81`; see the [VirusTotal report](https://www.virustotal.com/gui/file/875898602479b9b537e7dd37588387b415fd6f58e0b23f7a996648fdc163fb81). Always verify the downloaded file's checksum.
