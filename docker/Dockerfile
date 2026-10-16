# Start from an existing Nginx image
FROM nginx:stable-alpine

# Copy our website files into Nginx's web directory
COPY website/ /usr/share/nginx/html/

# Document the port used by Nginx
EXPOSE 80