FROM alpine:latest

LABEL maintainer="Shivam Singh <shivam.sachin.singh@gmail.com>"


# Install chrony
RUN apk add --no-cache chrony

# Copy custom config if needed
COPY chrony.conf /etc/chrony/chrony.conf

# Expose NTP port
EXPOSE 123/udp

# Run chronyd in foreground
CMD ["chronyd", "-d", "-x"]
