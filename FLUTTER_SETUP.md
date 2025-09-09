# Flutter Project Setup

## 🚀 Проект создан успешно!

Этот репозиторий содержит дефолтный Flutter проект с полной настройкой для разработки.

## 📁 Структура проекта

```
basic_flutter/
├── lib/
│   └── main.dart          # Основной файл приложения
├── test/
│   └── widget_test.dart   # Тесты
├── android/               # Android платформа
├── ios/                   # iOS платформа
├── web/                   # Web платформа
├── windows/               # Windows платформа
├── macos/                 # macOS платформа
├── linux/                 # Linux платформа
├── .vscode/               # Настройки VS Code
│   ├── extensions.json    # Рекомендуемые расширения
│   ├── settings.json      # Настройки проекта
│   └── launch.json        # Конфигурация запуска
├── pubspec.yaml           # Зависимости проекта
└── README.md              # Документация Flutter
```

## 🛠️ Установленные расширения VS Code

- **Dart** (dart-code.dart-code) - поддержка языка Dart
- **Flutter** (dart-code.flutter) - поддержка Flutter
- **GitLens** - расширенная работа с Git
- **GitHub Copilot** - AI-ассистент для кода
- **Docker** - контейнеризация
- **Database Client** - работа с БД
- **REST Client** - тестирование API

## 🎯 Как запустить проект

### 1. Убедитесь, что Flutter установлен:
```bash
flutter doctor
```

### 2. Получите зависимости:
```bash
flutter pub get
```

### 3. Запустите приложение:

#### В VS Code:
- Нажмите `F5` или `Ctrl+F5`
- Или используйте панель "Run and Debug"

#### В терминале:
```bash
# Запуск на подключенном устройстве/эмуляторе
flutter run

# Запуск на конкретной платформе
flutter run -d chrome          # Web
flutter run -d windows         # Windows
flutter run -d macos           # macOS
flutter run -d linux           # Linux
```

### 4. Доступные устройства:
```bash
flutter devices
```

## 🔧 Полезные команды

### Разработка:
```bash
flutter pub get              # Установить зависимости
flutter pub upgrade          # Обновить зависимости
flutter clean                # Очистить кэш
flutter build apk            # Собрать APK для Android
flutter build web            # Собрать для Web
flutter build windows        # Собрать для Windows
```

### Тестирование:
```bash
flutter test                 # Запустить тесты
flutter test --coverage      # Тесты с покрытием
```

### Анализ кода:
```bash
flutter analyze              # Анализ кода
dart format .                # Форматирование кода
```

## 📱 Поддерживаемые платформы

- ✅ **Android** - мобильные приложения
- ✅ **iOS** - мобильные приложения
- ✅ **Web** - веб-приложения
- ✅ **Windows** - десктопные приложения
- ✅ **macOS** - десктопные приложения
- ✅ **Linux** - десктопные приложения

## 🎨 Основные возможности

- **Hot Reload** - мгновенное обновление изменений
- **Hot Restart** - перезапуск приложения
- **Widget Inspector** - отладка UI
- **Performance Profiling** - профилирование производительности
- **Debug Console** - консоль отладки

## 📚 Ресурсы для изучения

- [Официальная документация Flutter](https://docs.flutter.dev/)
- [Flutter Widget Catalog](https://docs.flutter.dev/development/ui/widgets)
- [Dart Language Tour](https://dart.dev/guides/language/language-tour)
- [Flutter Cookbook](https://docs.flutter.dev/cookbook)

## 🚀 Следующие шаги

1. Откройте проект в VS Code: `code .`
2. Установите рекомендуемые расширения
3. Запустите приложение: `F5`
4. Начните разработку в `lib/main.dart`

Удачной разработки! 🎉
