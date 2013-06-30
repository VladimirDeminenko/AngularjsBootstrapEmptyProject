Запуск сервера, приложения и тестов производить из папки проекта.

1. Запуск сервера:
>node .\scripts\web-server.js

2. Запуск модульного теста (unit):
> .\scripts\test.bat (для Windows или test.sh для *nix-платформ)

3. Запуск системного теста (end-to-end или e2e):
- для пользователей Node: http://localhost:8000/test/e2e/runner.html
- для пользователей других http-серверов: http://localhost:[port-number]/[context-path]/test/e2e/runner.html