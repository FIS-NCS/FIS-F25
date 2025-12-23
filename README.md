# Fundamentals of InfoSec - Fall 2025

## Content

- Lab 1: Cryptography and Steganography
- Lab 2: Authentication
- Lab 3: Malware Analysis
- Lab 4: Penetration Testing
- Lab 5: Binary Exploitation
- Lab 6: Digital Forensics

## Instructions

1. Ensure you have docker and docker compose plugin installed

   ```bash
   docker -v
   docker compose version
   ```

1. Clone this repository

   ```bash
   git clone https://github.com/FIS-NCS/FIS-F25
   ```

1. Change into the project directory

   ```bash
   cd FIS-F25
   ```

1. [Before running any lab] Ensure you have the latest changes.

   ```bash
   git pull
   docker compose pull
   ```

1. Update `docker-compose.yaml` to serve lab files

   ```yaml
   services:
      labenv:
        volumes:
         - ./labX:/app/workshop
   ```

1. Run the environment

   ```bash
   docker compose up -d
   ```

1. Access the lab at <http://localhost:3000>
