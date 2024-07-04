---
title: Тестовое задание
---

# Разработать простое приложение для управления задачами с использованием Laravel:

1. Создайте модель и миграцию для задачи.

2. Реализуйте API для создания, чтения, обновления и удаления задач.

3. Добавьте возможность фильтрации задач по статусу или дате.



### **Api / Postman**

#### *Создание задачи :*

-  **Метод**: POST

-  **URL**: `http://localhost:8000/api/tasks`

-  **Тело запроса**: JSON

```
{
    "title": "Test Task",
    "description": "This is a test task",
    "status": "pending"
}
```

![](./README.png)