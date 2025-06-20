# Project4-ChatAppSignalR

🗨️ **Project4-ChatAppSignalR** е реалновременнo чат приложение, изградено с помощта на [SignalR](https://learn.microsoft.com/aspnet/core/signalr/introduction), което позволява бърза и ефективна комуникация между потребителите.

## ⚙️ Технологии

- ASP.NET Core (back-end)
- SignalR (реално време)
- Entity Framework Core (база данни)
- JavaScript/TypeScript (front-end)
- HTML/CSS или Blazor (в зависимост от реализацията)
- SQL Server или друга СУБД

## 📦 Функционалности

- Регистрация и вход на потребител
- Общи и частни чат стаи
- Съобщения в реално време с използване на WebSockets (чрез SignalR)
- Известия за нови съобщения
- История на съобщенията
- Онлайн статус на потребители
- Отзивчив потребителски интерфейс (responsive UI)

## 🏁 Стартиране на проекта

### 1. Клонирай хранилището

```bash
git clone https://github.com/your-username/Project4-ChatAppSignalR.git
cd Project4-ChatAppSignalR
```

### 2. Конфигуриране на базата данни

- Актуализирай `appsettings.json` с твоята връзка към базата данни:

```json
"ConnectionStrings": {
  "DefaultConnection": "Server=.;Database=ChatAppDb;Trusted_Connection=True;"
}
```

- Извърши миграции:

```bash
dotnet ef database update
```

### 3. Стартиране на приложението

```bash
dotnet run
```

- Отвори браузъра на: `https://localhost:5001` (или `http://localhost:5000`)

## 📸 Скрийншоти

_Добави тук изображения на потребителския интерфейс_

## 🛠️ Възможности за подобрение

- Добавяне на емоджита и прикачени файлове
- Поддръжка на теми (светла/тъмна)
- Мобилна версия на приложението
- Интеграция с OAuth (напр. Google/FB вход)

## 🤝 Принос

Всички са добре дошли да допринасят чрез pull заявки, доклади за бъгове или предложения!

## 📄 Лиценз

Този проект е с отворен код и се лицензира под [MIT лиценз](LICENSE).
