# Timestamp QR Code

A simple static web application that generates a QR code containing the current timestamp.

## Features

- Displays a QR code with the current timestamp
- QR code refreshes every 10 seconds
- Format: "DROPPED AT YYYY-MM-DD HH:MM"

## Deployment

This application is deployed to Azure Static Web Apps. The `package.json` file contains a minimal build script to satisfy Azure's deployment requirements, but no actual build process is needed since this is a static HTML application.

## Local Development

Simply open `index.html` in a web browser to run the application locally.
