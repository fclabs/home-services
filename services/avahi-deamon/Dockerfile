FROM alpine:latest

# Install avahi-daemon
RUN apk add --no-cache --update avahi

# Expose the default avahi port
EXPOSE 5353

# Start avahi-daemon
CMD ["avahi-daemon", "--no-drop-root"]
