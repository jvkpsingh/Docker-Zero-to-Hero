# Dockerfile

# Use the official Nginx image as a base image
FROM nginx:latest

# Copy custom nginx configuration file
COPY nginx.conf /etc/nginx/nginx.conf

# Expose port 80 to the outside world
EXPOSE 80

# Command to run nginx in the foreground
CMD ["nginx", "-g", "daemon off;"]
