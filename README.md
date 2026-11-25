# AgroNexus

Agricultural connection: a crop-cycle platform with a marketplace, escrow payments, IoT sensor nodes and a domain-guarded AI assistant.

Prototype 1, rebuilt from zero. Prototype 0 is frozen at the tag `prototype-v0`.

## Folders
- backend/    Java 21, Spring Boot (added in Sprint 0)
- client/     Flutter app (added in Sprint 0)
- ai-service/ AI assistant service (Sprint 9)
- firmware/   ESP32 code (Sprint 8)
- docs/       report, requirements, development log

## Setup (filled in as Sprint 0 progresses)
1. Copy `.env.example` to `.env` and fill in the values.
2. Start the database: `docker compose up -d`
3. Start the backend.
4. Start the client.
5. Run the tests.
