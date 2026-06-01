FROM nginx:alpine

# Eliminar contenido por defectos
RUN rm -rf /usr/share/nginx/html/*

# Copiar archivos estáticos
COPY . /usr/share/nginx/html

EXPOSE 80
