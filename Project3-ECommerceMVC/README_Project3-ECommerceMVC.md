# Project3-ECommerceMVC

**Project3-ECommerceMVC** е уеб базирано e-commerce приложение, създадено с ASP.NET MVC (C#) и MSSQL. Проектът включва пълна функционалност за онлайн магазин – от разглеждане на продукти до поръчки, плащания и администриране.

## 🧰 Използвани технологии

- ASP.NET MVC 5 / .NET Core MVC
- C#
- Entity Framework
- MSSQL Server
- Bootstrap 5 (Responsive UI)
- REST API (за мобилна съвместимост и интеграции)
- Identity (за регистрация и роля на потребители)

## 🎯 Основни функционалности

- 🔐 Регистрация и вход на потребители (с роли: Клиент, Администратор)
- 🛍️ Каталог с продукти (с категории, търсене и филтри)
- 🛒 Кошница (добавяне, редакция, премахване)
- 💳 Поръчки и интеграция с плащания (примерно с Stripe или демо плащания)
- 🧑‍💼 Административен панел (CRUD на продукти и категории, управление на поръчки)
- 🔍 Търсене и филтриране на продукти
- 📱 Мобилна съвместимост чрез responsive дизайн
- 📡 REST API за достъп до данни отвън

## 📁 Структура на проекта

```bash
Project3-ECommerceMVC/
├── Controllers/
├── Models/
│   └── ViewModels/
├── Views/
│   ├── Home/
│   ├── Product/
│   ├── Account/
│   ├── Cart/
│   ├── Order/
│   └── Admin/
├── Areas/Admin/
├── wwwroot/
├── appsettings.json
├── Program.cs
└── Startup.cs
```

## ⚙️ Настройка на проекта

1. **Клонирай репото** или разархивирай проекта:
   ```
   git clone https://github.com/your-username/Project3-ECommerceMVC.git
   ```

2. **Създай MSSQL база данни**, например с име `ECommerceDB`.

3. **Конфигурирай връзката към базата** в `appsettings.json`:
   ```json
   "ConnectionStrings": {
     "DefaultConnection": "Server=.;Database=ECommerceDB;Trusted_Connection=True;"
   }
   ```

4. **Миграции и база данни** (ако използваш EF Core):
   ```bash
   dotnet ef migrations add InitialCreate
   dotnet ef database update
   ```

5. **Стартирай проекта**:
   ```bash
   dotnet run
   ```

## 👨‍💻 Админ достъп (по подразбиране)
| Поле        | Стойност        |
|-------------|-----------------|
| Email       | admin@demo.com  |
| Парола      | Admin@123       |

> ⚠ Ако не съществува, можеш да създадеш админ роля в `Startup.cs` при инициализация.

## 📦 REST API Endpoints (примерни)

| Метод | Път                | Описание                     |
|-------|--------------------|------------------------------|
| GET   | `/api/products`    | Връща всички продукти        |
| GET   | `/api/products/{id}` | Връща конкретен продукт      |
| POST  | `/api/orders`      | Създава нова поръчка         |
| POST  | `/api/login`       | Потребителско влизане        |

## 📜 Лиценз

Този проект е предоставен под MIT лиценз. Свободен си да го използваш и модифицираш.

---

Създаден от Тодор Николов.
