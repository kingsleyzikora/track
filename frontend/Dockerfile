FROM nginx:alpine

# Copy the custom Nginx configuration file
# COPY nginx.conf /etc/nginx/nginx.conf

# Copy static HTML files to the default Nginx web root
COPY html /usr/share/nginx/html

# Expose port 80
EXPOSE 80

# Start Nginx when the container starts
CMD ["nginx", "-g", "daemon off;"]