# Задача
1. Внедрить minio, настроить изолированность файлов по пользователям, на примере папок в текущей реализации
2. Внедрить аккаунты (username, password), например переписать SessionBackend под хранение  сессий и пользователей в базе, либо использовать fastapi simple oauth2
   3. пароль хэшировать при сохранении, например argon2
4. написать под это тесты
   5. проверка загрузки файла, проверить что в нужной папке для нужного пользака
   6. проверить выгрузку файла, проверить что доступ до папки у автора папки
   7. проверить что список папок выгружается для каждого пользвака свой
