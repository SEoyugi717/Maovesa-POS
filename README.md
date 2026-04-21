# Maovesa SyncPOS

**Maovesa SyncPOS** is an offline-first Progressive Web App (PWA) designed for retail continuity. It ensures supermarkets and retail shops can process sales during internet outages, using local-to-cloud synchronization to prevent data loss.

## Features
* **Offline-First:** Full sales functionality without an internet connection.
* **Data Sync:** Seamless bidirectional replication between local and remote databases.
* **Stock Management:** Real-time inventory tracking for retail environments.

## Tech Stack
* **PWA:** Service Workers for offline capabilities.
* **Database:** PouchDB (Client-side) & CouchDB (Server-side).
* **Frontend:** HTML, CSS, JavaScript.

## Setup
1. Clone the repository.
2. Serve the project via a local web server (e.g., XAMPP `htdocs`).
3. Configure your CouchDB endpoint for synchronization.
4. Open the app in a browser and "Install" as a PWA if desired.
