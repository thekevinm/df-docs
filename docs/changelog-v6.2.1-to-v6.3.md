

  # Changelog v6.2.1 to v6.3

## New Features
- Added support for GraphQL API endpoints
- Implemented real-time event streaming capabilities
- Introduced a new dashboard for enhanced API analytics

## Improvements
- Enhanced performance of database connectors, particularly for MySQL and PostgreSQL
- Upgraded the built-in rate limiting system for better scalability
- Improved error handling and logging across the platform

## Bug Fixes
- Resolved an issue with API key rotation in high-availability setups
- Fixed a race condition in the caching layer that could cause intermittent data inconsistencies
- Addressed a security vulnerability in the OAuth2 implementation

## Documentation
- Updated installation guides for Windows and Linux environments
- Added new tutorials for GraphQL API creation and management
- Expanded the API reference documentation to include new endpoints and parameters

## Deprecations
- Deprecated the legacy XML-RPC interface (to be removed in v6.4)
- Marked the `old_auth_method` as deprecated, to be replaced by the new authentication system in future releases

## Security
- Implemented additional CORS protections
- Enhanced input validation across all API endpoints
- Updated third-party dependencies to address known vulnerabilities

## Other Changes
- Refactored the internal event system for better extensibility
- Optimized database migrations for faster upgrades from previous versions
- Added support for custom HTTP headers in API responses

  