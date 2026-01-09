# Open Events API

Open Events API is a comprehensive platform for managing events, venues, organizers, and more. [Sign up here](https://openeventsapi.com).

[![Documentation](https://img.shields.io/badge/docs-available-brightgreen)](https://openeventsapi.com/docs)
[![Updates](https://img.shields.io/badge/updates-changelog-blue)](https://openeventsapi.com/updates)
[![Version](https://img.shields.io/badge/version-1.0.0-blue)](./.github/CHANGELOG.md)

---

## Overview

### Features

The Open Events API is a RESTful API that allows you to:

- **Manage Events**: Create, read, update, and delete event information
- **Handle Venues**: Manage venue data including locations, capacity, and amenities  
- **Organize Data**: Manage organizers, categories, and related metadata
- **Upload Images**: Handle image uploads and management for events and venues
- **Hierarchical Events**: Support for parent-child relationships (festivals with sub-events)
- **Model Context Protocol**: Access MCP Server capabilities via Server-Sent Events (SSE)

## Getting Started

### Base URL

```
https://openeventsapi.com/api/v1.0
```

### Quick Start

1. **Create an Account**: Register at [openeventsapi.com](https://openeventsapi.com)
2. **Get OAuth Credentials**: Navigate to your [Profile](https://openeventsapi.com/profile) to get OAuth clients
3. **Authenticate**: Use OAuth 2.0 Client Credentials flow
4. **Make API Calls**: Use your access token in the Authorization header

### Example Request

```bash
# Get events
curl https://openeventsapi.com/api/v1.0/events \
  -H "Authorization: Bearer YOUR_ACCESS_TOKEN"
```

## Documentation

- [API Documentation](https://openeventsapi.com/docs) - Interactive API reference
- [Updates](https://openeventsapi.com/updates) - User-friendly changelog and updates
- [FAQ](https://openeventsapi.com/faq) - Frequently asked questions

## Examples & Demos

See the Open Events API in action with these example applications:

| Project | Description | Repository | Live Demo |
|---------|-------------|------------|-----------|
| Event Search App | A React-based event search application with filtering, search, and detailed event views | [GitHub](https://github.com/C9Group/event-search-app) | [Demo](https://c9group.github.io/event-search-app/) |

Want to add your project? [Open an issue](https://github.com/C9Group/open-events-api/issues/new) or submit a pull request!

## Changelog

View the complete changelog: [CHANGELOG.md](./.github/CHANGELOG.md)

## Documentation

**Full API documentation**: [openeventsapi.com/docs](https://openeventsapi.com/docs)

## Contributing & Feedback

We welcome feedback, bug reports, and feature requests from our community!

### Report a Bug

Found a bug? Help us improve by reporting it:

1. **Check Existing Issues**: Search [GitHub Issues](https://github.com/C9Group/open-events-api/issues) to see if it's already reported
2. **Create New Issue**: If not found, [create a new issue](https://github.com/C9Group/open-events-api/issues/new)
3. **Provide Details**:
   - Clear, descriptive title
   - Steps to reproduce the bug
   - Expected vs actual behavior
   - API endpoint and request details (if applicable)
   - Error messages or response codes
   - Environment info (OS, programming language, etc.)

### Request a Feature

Have an idea to make the API better?

1. **Check Existing Requests**: Browse [GitHub Issues](https://github.com/C9Group/open-events-api/issues?q=is%3Aissue+label%3Aenhancement) with "enhancement" label
2. **Submit Your Idea**: [Create a feature request](https://github.com/C9Group/open-events-api/issues/new)
3. **Describe Your Use Case**:
   - What problem does this solve?
   - How would you use this feature?
   - Any examples or mockups?

### Get Help

Need assistance or have questions?

- **GitHub Issues**: [Ask a question](https://github.com/C9Group/open-events-api/issues/new) with the "question" label
- **Email Support**: [office@openeventsapi.com](mailto:office@openeventsapi.com)
- **Documentation**: Check our [API docs](https://openeventsapi.com/docs) and [FAQ](https://openeventsapi.com/faq)

### Contributing

While this is a managed API service, we appreciate:

- Bug reports and feature suggestions
- Documentation improvements
- Example code and integration guides
- Community support in discussions

**Note**: Direct code contributions to the API are not accepted, but your feedback shapes our roadmap!

## Versioning

We follow [Semantic Versioning](https://semver.org/):

- **Major version** (X.0.0): Breaking changes, major new features
- **Minor version** (1.X.0): New features, non-breaking changes
- **Patch version** (1.0.X): Bug fixes, small improvements

**Current version**: 1.0.1

## Support

- **Documentation**: [openeventsapi.com/docs](https://openeventsapi.com/docs)
- **Updates**: [openeventsapi.com/updates](https://openeventsapi.com/updates)
- **Email**: [office@openeventsapi.com](mailto:office@openeventsapi.com)

## License

© 2025 Open Events. All rights reserved.
