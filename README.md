# Створення виконуваного файлу через Artifacts в IntelliJ IDEA для програми криптозахисту носіїв

**Цей документ пояснює процес створення виконуваного файлу для програми криптозахисту носіїв в IntelliJ IDEA.**

### Крок 1: Налаштування проекту
- Переконайтеся, що проект відкритий в IntelliJ IDEA та готовий для збірки.

### Крок 2: Налаштування Artifacts
- Увійдіть у меню "File" (Файл) та оберіть "Project Structure" (Структура проекту).
- У вікні "Project Structure" виберіть "Artifacts" (Артефакти) зліва.
- Клацніть на "+" для додавання нового артефакту та виберіть "JAR" -> "From modules with dependencies" (З модулів з залежностями).
- Оберіть модуль **MainStart.java** із програмою криптозахисту носіїв та переконайтеся, що всі необхідні залежності відзначені ( **бібліотеки JavaFX, commons-lang3-3.12.0** ).
- В розділі "Output directory" (Директорія виводу) виберіть місце, де ви хочете зберегти ваш виконуваний файл (наприклад, "out/artifacts/DataEncryption").
- Натисніть "OK" для закриття вікна "Project Structure".

### Крок 3: Збірка проекту
- Увійдіть у меню "Build" (Збірка) та оберіть "Build Artifacts" (Збірка артефактів).
- Виберіть артефакт, який ви створили у Кроці 2 та натисніть "Build".
- IntelliJ IDEA автоматично збере проект та створить виконуваний файл у вказаній директорії.

### Крок 4: Запуск виконуваного файлу
- Тепер ви можете знайти та запустити ваш виконуваний файл у вказаній директорії. Ваша програма криптозахисту носіїв готова до використання.
