# Тест-кейсы для API JSONPlaceholder

## Тест-кейс 1: Получение списка постов
**Описание:** Проверка успешного получения списка постов через API.
- **Метод:** GET /posts
- **Ожидаемый результат:** Статус код 200, в ответе возвращается массив постов.

## Тест-кейс 2: Создание нового поста
**Описание:** Проверка успешного создания поста через API.
- **Метод:** POST /posts
- **Тело запроса:**
  ```json
{
    "title": "Новый пост",
    "body": "Содержимое нового поста",
    "userId": 1
  }
- **Ожидаемый результат:** Статус код 201, в ответе возвращается ID созданного поста и данные, соответствующие запросу.

## Тест-кейс 3: Обновление поста
**Описание:** Проверка успешного обновления существующего поста.
- **Метод:** PUT /posts/{id}
- **Тело запроса:**
  {
    "id": 1,
    "title": "Обновленный пост",
    "body": "Содержимое обновленного поста",
    "userId": 1
  }
- **Ожидаемый результат:** Статус код 200, в ответе возвращается обновленная информация поста.

## Тест-кейс 4: Удаление поста
**Описание:** Проверка успешного удаления поста.
- **Метод:** DELETE /posts/{id}
- **Ожидаемый результат:** Статус код 204, пост успешно удален.