# Changelog

All notable changes to the Open Events API will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.1.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

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

- **1.0.0** - Initial release
