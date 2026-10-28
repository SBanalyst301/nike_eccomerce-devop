FROM nginx:alpine-slim

# Copy your HTML, CSS, JS, and image assets into the default Nginx web root
COPY . /usr/share/nginx/html

EXPOSE 80

CMD ["nginx", "-g", "daemon off;"]
