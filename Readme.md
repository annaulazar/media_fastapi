# Сервис для медиафалов
Сервис для загрузки медиафайлов и сохранения их по определенному пути
## Стек
- fastapi
- postgresql
## Зависимости
В файле requirements.txt
## Запуск
`uvicorn src.main:app --host 0.0.0.0 --port 8080 --reload --reload-dir .`
## Бизнес-требования
Написать сервис, который принимает изображния и видео для сохранения в медиатеку
- Данные о файле должны сохраняться в БД
- Авторизация по токену на предъявителя
- Документация
- CRUD для файла
- Для неавторизованного пользователя файл показывается с блюром, для видеофайла обложка
