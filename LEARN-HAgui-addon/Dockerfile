FROM alpine:3.18

# Install a basic HTTP server (using Python)
RUN apk add --no-cache python3

# Copy files into the container
COPY run.sh /run.sh
COPY www /www

# Make script executable
RUN chmod +x /run.sh

# Run the script to start the server
CMD ["/run.sh"]
