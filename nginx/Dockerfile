FROM nginx:alpine

COPY ["index.html", "script.js", "/usr/share/nginx/html/"]

EXPOSE 80

CMD ["nginx", "-g", "daemon off;"]
