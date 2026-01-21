# Changelog

All notable changes to the Open Events API will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.1.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [1.2.0] - 2026-01-20

### Added
- Multi-language content support with automatic translation queueing
- New `lang` query parameter on event endpoints for retrieving translated content
- Localization API for managing translations across events, venues, and organizers
- Support for new languages: Slovenian (sl), Italian (it), Croatian (hr)

### API Endpoints
- `GET /api/v1.0/events` - Added `lang` query parameter
- `GET /api/v1.0/events/:id` - Added `lang` query parameter
- `GET /api/v1.0/localization/languages` - List supported languages
- `GET /api/v1.0/localization/translations/events/:id` - Get all translations for an event
- `PUT /api/v1.0/localization/translations/events/:id/:lang` - Create or update event translation
- `GET /api/v1.0/localization/translations/venues/:id` - Get all translations for a venue
- `PUT /api/v1.0/localization/translations/venues/:id/:lang` - Create or update venue translation
- `GET /api/v1.0/localization/translations/organizers/:id` - Get all translations for an organizer
- `PUT /api/v1.0/localization/translations/organizers/:id/:lang` - Create or update organizer translation

---

## [1.1.0] - 2026-01-07

### Added
- API Keys with limited access scopes

---

## [1.0.0] - 2025-12-25

### Added
- Initial release of Open Events API
- Event CRUD operations
- Venue management
- Organizer management
- Image management
- Category management
- OAuth 2.0 authentication (Client Credentials flow)
- PostGIS geospatial support
- Rate limiting (240 req/min standard, 120 req/min MCP)
- RFC 7807 Problem Details error responses
- Pagination support
- Filtering and search
- Relationship includes (venues, organizers, images, subevents, categories)

### API Endpoints
- `GET /api/v1.0/events` - List events
- `POST /api/v1.0/events` - Create event
- `GET /api/v1.0/events/:id` - Get event
- `PATCH /api/v1.0/events/:id` - Update event
- `DELETE /api/v1.0/events/:id` - Delete event
- Similar CRUD endpoints for venues, organizers, images, categories

---

## Version History

- **1.2.0** - Localization and multi-language support
- **1.1.0** - API keys
- **1.0.0** - Initial release
