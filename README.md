# 🧙 HexHub Uploader Data

Публичный репозиторий для хранения файлов драйверов, протоколов и диагностических утилит проекта HexHub.

## 📁 Структура

Все файлы хранятся в папке `uploads/`:

```
uploads/
├── windows/      # Драйверы и утилиты для Windows
├── linux/        # Драйверы и утилиты для Linux
├── macos/        # Драйверы и утилиты для macOS
└── all/          # Кроссплатформенные файлы
```

## 📤 Загрузка файлов

Файлы можно загрузить через веб-интерфейс: **[HexHub Uploader](https://github.com/egoffn1/HexHub-Uploader)**

Или вручную через Pull Request.

### Правила именования

Называйте файлы по формату:
```
vendor-device-type-version.zip
```

Примеры:
- `realtek-rtl8821ce-wifi-driver-v5.11.zip`
- `nvidia-rtx3060-linux-v535.zip`
- `wireshark-usbpcap-windows-v1.4.zip`

## 📥 Скачивание

Файлы можно скачать через:
1. Веб-интерфейс HexHub Uploader
2. Прямые ссылки на GitHub (не рекомендуется)
3. Командную строку:

```bash
# Пример скачивания через wget
wget https://raw.githubusercontent.com/egoffn1/HexHub-Uploader-Data/main/uploads/filename.zip
```

## 🔒 Безопасность

- Все файлы проверяются перед публикацией
- Используйте антивирус перед открытием загруженных файлов
- Сообщайте о подозрительных файлах через Issues

## 📄 Лицензия

Файлы в этом репозитории могут иметь различные лицензии. Проверяйте лицензию каждого файла отдельно.

---

**Часть проекта HexHub** | [Основной репозиторий](https://github.com/egoffn1/HexHub) | [Веб-загрузчик](https://github.com/egoffn1/HexHub-Uploader)
