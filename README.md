# JSONPlaceholder-API-Testing

Этот проект предназначен для автоматизации тестирования API с использованием Postman и Newman.

## Как запустить тесты

Чтобы запустить тесты, используйте следующую команду:

```bash
newman run postman/api-tests.postman_collection.json
```

Предварительно необходимо установить Node.js и Newman:
 ```bash
npm install -g newman
```
## Описание
Проект для тестирования REST API JSONPlaceholder. Проект включает тест-кейсы, баг-репорты, а также автоматизированные тесты, написанные в Postman и запускаемые через Newman.

## Основные методы API
- Получение постов (GET /posts)
- Создание поста (POST /posts)
- Обновление поста (PUT /posts/{id})
- Удаление поста (DELETE /posts/{id})

## Содержание
- [Тест-кейсы для API](api-test-cases.md)
- [Баг-репорты для API](api-bug-reports.md)
- [Postman коллекция](postman-collection.json)


