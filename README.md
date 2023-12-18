Создайте новый сервис, используя готовый шаблон.

### Шаги:

1. **Скачайте шаблон сервиса**

    ```
    dotnet new install Dex.Template.Service
    ```

2. **Откройте терминал в IDE (Rider, Visual Studio) и выполните команду**

    ```
    dotnet new service -n ИмяСервиса -F Версия
    ```

    Где:
    - `-n` - имя сервиса, например: Admin, Notification, Profile (обязательно)
    - `-F` - версия dotnet для .csproj, например: net6.0, net7.0, net8.0 (не обязательно, по умолчанию net6.0)
