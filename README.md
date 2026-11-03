# Робинзон — офлайн-приложение

Android-приложение, внутри которого база клиентов и прайс (app/src/main/assets/index.html). Работает без интернета.

Сборка:
- Android Studio: File → Open → эта папка → Build → Build APK(s). Готовый файл: app/build/outputs/apk/debug/app-debug.apk
- GitHub: загрузить папку в репозиторий, вкладка Actions → «Собрать APK» → скачать артефакт Robinzon-apk.

Обновить данные: заменить app/src/main/assets/index.html на новый файл Robinzon-offline.html и собрать заново.
