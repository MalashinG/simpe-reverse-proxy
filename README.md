Простое веб-приложение: Python backend + Nginx reverse proxy в Docker

Как запустить
git clone https://github.com/MalashinG/simpe-reverse-proxy.git

cd simpe-reverse-proxy

docker compose up -d

Как проверить
curl http://localhost

Ожидаемый ответ: Hello!

Остановить

docker compose down
