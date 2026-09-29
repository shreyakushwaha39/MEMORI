# MEMORI Database

MEMORI uses PostgreSQL for storing application metadata and relationships.

## Core Tables

- users
- photos
- videos
- memories
- memory_items
- stories
- sync_records
- cleanup_suggestions

## Storage

Actual photos and videos are stored in cloud object storage.

PostgreSQL stores:

- Media metadata
- User information
- Memory information
- Relationships
- Synchronization records
- Cleanup suggestions