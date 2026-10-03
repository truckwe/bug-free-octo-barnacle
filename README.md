# Генератор паролей — APK через GitHub Actions

## Что делать на телефоне

1. Создай новый GitHub repository, например `PasswordGenerator`.
2. Загрузи в него **все файлы и папки из этого ZIP**.
3. Открой вкладку **Actions**.
4. Выбери `Build APK`.
5. Нажми **Run workflow**.
6. Дождись зелёной галочки.
7. Открой завершившийся workflow и найди раздел **Artifacts**.
8. Скачай `PasswordGenerator-debug`.
9. В ZIP будет `app-debug.apk` — установи его на Android.

Приложение работает офлайн: HTML находится внутри APK в `assets/index.html`.
