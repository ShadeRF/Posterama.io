# Changelog

All notable changes to Posterama will be documented in this file.

## [1.0.6.3] [2025-05-19]

- Added wishlist to public user profile page. 
- Added ability to link directly to collection, wishlist or for sale tabs with new urls /user/username/collection, /user/username/wishlist, /user/username/forsale. Share icons are available on each tab for easy access
- Updated User Profile Page UI to match recent changes to styling.

## [1.0.6.2] [2025-05-17]

- Updated poster cards and UI throughout to match updates in 1.0.6

## [1.0.6.1] [2025-05-17]

- Fix performance issue with search on user collections.

## [1.0.6] [2025-05-14]

- Revamped UI for User Poster and Poster Type detail pages. Information is now laid out in a more logical way and the UI feels cleaner and more modern.
- Fixed bug that could prevent Autographed poster details from displaying correctly on User Poster detail page.
- Miscellaneous UI fixes and tweaks throughout the rest of the app.

## [1.0.5.3] [2025-05-11]

- Fixed date displaying incorrectly on marketplace detail page.

## [1.0.5.2] [2025-05-11] 

- Added movie details (Genre, Director, Main Cast) to poster type detail view, user poster detail view and public profile page poster view.

## [1.0.5.1] [2025-05-10]

- Fixed values not displaying on cards and table view for user collection.

## [1.0.5] [2025-05-09]

- Added option to toggle single or double column view when on mobile for Collections, Posters, Wishlist and Marketplace.
- Updated Marketplace to have more consistent UI with other pages.
- The Marketplace is now publicly viewable and linked on pages non-users visit.

## [1.0.4.1] [2025-05-08]

- Added image right click protection
- Fixed bug where incorrect title would be displayed when adding a TV poster to a user collection
- Initial upgrade to React 19.1 from React 18.3.1. 

## [1.0.4] [2025-05-06]

- Added ability to search TV shows and add posters for TV shows to the public library and user collections. New visual cues have been added to designate movie or TV show.
- Adjusted terminology for buttons in various places to make  more clear what action is being taken.
- Added helper text in various places to help users better understand the actions they are taking.

## [1.0.3.3] [2025-05-05]

- Expanded size choices for France and corrected naming for existing sizes.
- Added UK Bus Stop to poster size options.

## [1.0.3.2] [2025-05-03]

- Fixed issue with poster type edits throwing error when updating.
- Movie search now allows searching by Actors

## [1.0.3.1] [2025-05-02]

- Added page for howto videos to better explain how to use Posterama. Includes new video on adding posters to the global database and user collections.

## [1.0.3] [2025-05-02]

- Increased limit for free tier from 25 to 50 posters.
- Added genre and director as filters on Poster Library and User Collections.
- You can now search for posters in the Poster Library and User Collection by typing the Actor name (main cast only), Director or Genre.
- Fixed issue with condition stats not showing all stats correctly.
- Added click-through functionality to all statistics components on the Stats page. Now you can simply click on any
  statistic (decade, condition, genre, country, or poster type) to instantly filter your collection to match. Quickly
  explore the posters making up each segment of your collection data with just a single click.

## [1.0.2.5] 2025-05-01

- Added quick link to view public profile to side nav.

## [1.0.2.4] 2025-05-01

- Added missing forgot password functionality

## [1.0.2.3] 2025-04-30

- Trim spaces when searching for movies to prevent results for single word titled movies from not appearing if space is inadvertently added.

## [1.0.2.2] 2025-04-30

- Fixed issue with leading articles (i.e. a, the) were not being dropped for alphabetical sorting.
- Fixed issue where uploading an image from mobile would open camera by default.
- Minor mobile UI tweaks/fixes

## [1.0.2.1] 2025-04-30

- Added confirmation screen after adding poster to give user choice to quickly add another poster or go to their collection.
- Added URL parameter support to Public Profile Page. This is useful if you want to share your profile with a specific Poster sort order.
- Added Egypt, Turkey, and Ukraine as Country option with various popular sizes for these countries.

## [1.0.2] - 2025-04-29

- Added URL parameter synchronization to the Poster Library and User Poster Collection, allowing:
    - Bookmarking specific filtered views
    - Browser back/forward navigation with state preservation
    - Persistent filters and pagination across page refreshes
    - Seamless return to previous view after viewing poster details
- Implemented compression for Redis cache to reduce memory usage and improve performance for large cached objects
- Display validation error message when user attempts to upload non-image file or file that is larger than the 20MB max.
- Removed duplicated stats from Dashboard (All stats can be found on the Statistics page) and replaced with new quick actions for reaching common areas quickly from the Dashboard.
- Removed blocking operations when adding a user poster to increase speed of submission.

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
