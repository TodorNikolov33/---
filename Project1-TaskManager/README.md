# ✅ TaskManager (.NET 8 MVC + SQLite)

**TaskManager** е уеб приложение, разработено с ASP.NET Core MVC, което позволява създаване, редактиране и управление на задачи. Подходящо е както за индивидуално, така и за екипно проследяване на ежедневни ангажименти и цели.

---

## 🎯 Основни цели

- Управление на списък със задачи (ToDo списък)
- CRUD функционалност (създаване, редакция, изтриване)
- Лесен за използване и адаптация потребителски интерфейс
- Демонстрация на MVC архитектура с Entity Framework Core и SQLite

---

## 🛠️ Използвани технологии

| Технология        | Версия         |
|-------------------|----------------|
| ASP.NET Core MVC  | .NET 8         |
| Entity Framework  | EF Core 8      |
| База данни        | SQLite         |
| UI библиотека     | Bootstrap 5    |
| Front-End          | Razor Pages, HTML5, CSS3 |

---

## 📦 Инсталация и стартиране

1. Клонирайте репото или копирайте директорията:

```bash
git clone https://github.com/NikolovTodor/Portfolio.git
cd Project1-TaskManager

2. Възстановете зависимостите:
```bash
dotnet restore

3. Създайте базата данни и приложете миграциите:
```bash
dotnet ef migrations add InitialCreate
dotnet ef database update

4. Стартирайте приложението:
```bash
dotnet run

# 🧱 Архитектура

Controllers – отговарят за логиката и маршрутизацията (TasksController.cs)

Models – дефинират структурата на задачите (TaskItem.cs)

Views – представят потребителския интерфейс (Razor + Bootstrap)

Data – съдържа контекста на базата данни (ApplicationDbContext.cs)

# 🔁 Основни екрани и действия
/Tasks – преглед на всички задачи

/Tasks/Create – форма за добавяне

/Tasks/Edit/{id} – редакция на съществуваща задача

/Tasks/Delete/{id} – изтриване

📜 Лиценз
Проектът е с отворен код и публикуван под MIT лиценз.

📫 Автор и контакти
Твоето име
📧 t.nikolov33@abv.bg
🔗 github.com/NikolovTodor
