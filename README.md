# SafePath - Backend API

## Application Database

**Application DB Connection String:** `postgresql://db_appdb_69b2fbc6656bf01983b1b9e0_user:%21%21%247y3u%5E%5EkUv%5EwUd0DIHcQRHtaHBr14T@ep-winter-flower-ad20oyah.c-2.us-east-1.aws.neon.tech:5432/AppDB_69b2fbc6656bf01983b1b9e0?sslmode=require`

## Web API

**WebApi URL:** https://webapi69b2fbc6656bf01983b1b9e0-production.up.railway.app

**Swagger API Tester URL:** https://webapi69b2fbc6656bf01983b1b9e0-production.up.railway.app/swagger

## Google APIs (Gemini, Maps, Speech-to-Text)

The backend can use a Google API key provided via the **GOOGLE_API_KEY** environment variable (set on Railway). Use it for Gemini LLM, Maps, and Speech-to-Text. Check **GET /api/google/status** and **GET /api/google/health** to verify the key is set and reachable.

## Recommended Tools

**Recommended SQL Editor tool (Free):** [pgAdmin](https://www.pgadmin.org/download/)

## Deployment

This backend is configured for Railway deployment using nixpacks.toml.
