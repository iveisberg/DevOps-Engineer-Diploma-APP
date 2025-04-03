# Базовый образ
FROM nginx:alpine

# Копируем статические файлы
COPY index.html /usr/share/nginx/html/index.html
COPY error.html /usr/share/nginx/html/error.html

# Копируем конфигурацию Nginx
COPY nginx.conf /etc/nginx/nginx.conf

# Открываем порт 80
EXPOSE 80

# Запускаем Nginx
CMD ["nginx", "-g", "daemon off;"]