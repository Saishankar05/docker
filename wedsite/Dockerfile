# Use the official Nginx image from Docker Hub
FROM nginx:alpine

# Copy the HTML and CSS files to the Nginx default public directory
COPY hello.html /usr/share/nginx/html/
COPY style.css /usr/share/nginx/html/

# Expose port 80 to allow outside access to the website
EXPOSE 80

# Start Nginx in the foreground (daemon off) when the container starts
CMD ["nginx", "-g", "daemon off;"]
