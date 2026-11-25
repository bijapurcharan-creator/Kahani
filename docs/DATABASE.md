# KAHANI Database Schema

## Overview
PostgreSQL database with the following main tables.

## Tables

### users
- id (Primary Key, UUID)
- email (Unique, String)
- password_hash (String)
- tier (Enum: free/starter/pro/studio)
- created_at (Timestamp)
- updated_at (Timestamp)

### generation
- id (Primary Key, UUID)
- user_id (Foreign Key → users.id)
- topic (String)
- language (String)
- output_type (Enum: script/seo/thumbnail/caption)
- result (JSON)
- created_at (Timestamp)
- updated_at (Timestamp)

### usage_logs
- id (Primary Key, UUID)
- user_id (Foreign Key → users.id)
- action (String)
- timestamp (Timestamp)
- metadata (JSON)

(Full schema with relationships to be added in Phase 1A)
