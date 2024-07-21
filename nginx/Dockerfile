FROM nginx

WORKDIR /etc/nginx/

#COPY wwwroot/app.css wwwroot/app.css
COPY wwwroot/appsettings.json wwwroot/appsettings.json
#COPY wwwroot/BlazorApp.styles.css wwwroot/BlazorApp.styles.css
COPY wwwroot/favicon.png wwwroot/favicon.png
COPY wwwroot/habit-tracker-wasm.styles.css wwwroot/habit-tracker-wasm.styles.css
COPY wwwroot/icon-192.png wwwroot/icon-192.png
COPY wwwroot/index.html wwwroot/index.html

COPY wwwroot/_framework wwwroot/_framework
#COPY wwwroot/bootstrap wwwroot/bootstrap

COPY wwwroot/css/app.css wwwroot/css/app.css 
COPY wwwroot/css/bootstrap wwwroot/css/bootstrap

COPY origin.pem certificates/
COPY private.key certificates/

COPY nginx.conf nginx.conf