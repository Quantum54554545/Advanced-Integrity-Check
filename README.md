# Advanced Integrity Check

**Advanced Integrity Check** — это инструмент для защиты .NET приложений от несанкционированных изменений. Он использует проверку целостности на основе MD5-хэша и обеспечивает защиту вашего приложения путем обнаружения изменений и создания механизмов противодействия крякам.

## Пример использования

Чтобы интегрировать **Advanced Integrity Check** в ваше приложение, выполните следующие шаги:

### Шаг 1: Подключите `IntegrityCheckRuntime`

1. Скачайте файл `IntegrityCheckRuntime.cs` из этого репозитория.
2. Добавьте его в свой проект .NET.

### Шаг 2: Установите библиотеку `Microsoft.CodeAnalysis`

Убедитесь, что в проекте установлена библиотека `Microsoft.CodeAnalysis`. Вы можете добавить её через NuGet:

```bash
dotnet add package Microsoft.CodeAnalysis
```
### Шаг 3: Вписание хэша в корень приложения

1. Создайте консольное приложение с кодом из файла `MD5.cs`.
2. Скомпилируете его.
3. Перенесите основное приложение с `IntegrityCheckRuntime` на иконку консольное приложение.


