# About zerobyte
Zerobyte container definition.

## Frameworks used
- zerobyte

# Docker image details
Base image: ghcr.io/nicotsx/zerobyte:latest

# Deployment
## General
Service: zerobyte
Data Path: /var/lib/zerobyte

## Capabilities
- SYS_ADMIN - required for filesystem operations

## Devices
- /dev/fuse - FUSE device for filesystem mounting

## Attached volumes
- /etc/localtime (read-only) - system time synchronization
- /var/lib/zerobyte - data storage

## Environment variables
- TZ=Europe/Paris - timezone configuration
