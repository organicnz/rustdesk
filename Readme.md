# RustDesk Server Setup

This repository contains the DOCKER COMPOSE configuration for the private RustDesk ID & Relay server hosted at `rustdesk.foodshare.club`.

## Documentation
- [Connection Guide](docs/connection.md) - Step-by-step instructions on how to connect your devices.

## Services
- **mbbs**: ID and Rendezvous server.
- **hbbr**: Relay server for handling remote desktop traffic.

## Security
This server uses **mandatory encryption keys**. All clients MUST be configured with the correct public key as shown in the Connection Guide.
