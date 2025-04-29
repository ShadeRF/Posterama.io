# Changelog

All notable changes to Posterama will be documented in this file.

## [1.0.2] - 2025-04-29
- Added URL parameter synchronization to the Poster Library and User Poster Collection, allowing:
    - Bookmarking specific filtered views
    - Browser back/forward navigation with state preservation
    - Persistent filters and pagination across page refreshes
    - Seamless return to previous view after viewing poster details
- Implemented compression for Redis cache to reduce memory usage and improve performance for large cached objects
- Display validation error message when user attempts to upload non-image file or file that is larger than the 10MB max.

## [1.0.1.1] - 2025-04-29

- Fixed error when trying to update profile or add profile image.
- Batch TMDB api calls to improve performance.

## [1.0.1] - 2025-04-28

### Added
- Improved image loading performance by using smaller thumbnails on smaller screens, and right sizing images for poster cards reducing bandwidth usage.
- Added Thailand as Country option with various popular sizes for this country.


## [1.0.0] - 2025-04-28

### Added
- Initial release of Posterama
- Movie poster collection management
- Poster types and categorization
- Marketplace for trading/selling posters
- User-to-user messaging system
- Notifications system
- Wishlist functionality
- Collection statistics and analytics
