# Changelog

All notable changes to Posterama will be documented in this file.

## [07-05-2025]

- Added virtual collections. You can now create virtual collections from your Collections page to group your collection into 1 or more sub-collections. Free users are limited to 5 virtual collections. Premium members can create unlimited virtual collections. 

## [1.0.7.5] [07-02-25]

- Added natural language search to user collections for Premium users. Please provide feedback on results in the Discord.
- Fixed bug that would cause thumbnails and medium urls to get swapped when editing a poster. Impacted posters have been corrected.


## [1.0.7.4] [07-01-25] 

- Updated from Material UI 6.4 to MUI 7.2
- Updated stats update timing to prevent multiple stat refreshes in a short period of time.
- Added new gallery view to public profile page. A new, exciting way to show off your collection!


## [1.0.7.3] [06-23-25] - Performance Optimizations

### Database Read Optimization
- **Rankings Endpoint**: Added Redis caching (1-hour TTL) and efficient batch processing to eliminate N+1 queries
- **Cache Invalidation**: Replaced pattern-based invalidation with targeted key removal, preserving unaffected caches
- **Stats Calculation**: Implemented 4-hour caching for user stats with smart invalidation on collection changes
- **Similar Collectors**: Added collection summaries cache to pre-calculate poster type overlaps between users
- **TMDB API Caching**: Created 30-day cache for movie/TV details to reduce external API calls
- **Overall Impact**: Significantly reduced database reads, especially for stats calculations and rankings endpoints
- Fixed date conversion issues

## [1.0.7.2] [06-22-25]

- Updated sort options on public profile pages to align with public library and collection pages.

## [1.0.7.1] [06-21-25]

- Revamped poster suggestion submission page to allow for more complete suggestion updates.
- Fixed search bug on my collection page that would not return proper results when searching by Artist name.
- Added additional poster sizes for Italy and Switzerland.

## [1.0.7] [06-13-25]

- Fixed bug that would prevent being able to edit a user poster in some instances.

## [1.0.6.9] [06-02-25]

- Default storage condition to most likely option based on poster type (for example, defaulting Lobby Cards to Flat vs rolled)
- Lots of prep work for Android mobile app!

## [1.0.6.8] [05-28-25]

- Added support for Print types. When selecting the poster type print, new fields will become available including Gallery/Publisher Name, Print Run, and noting whether a print is a variant or not. When adding a Print type to your user collection an additional field will be available, Edition Number, that allows you to catalog your specific edition number for the print.
- Minor UI fixes.

## [1.0.6.7] [2025-05-25]

- Updated subscription pricing to $3.99/month and $39.99/year (save 30%)
- Enabled yearly subscription option for Pro plan
- Updated all Stripe price IDs across development and production environments

## [1.0.6.6] [2025-05-24]

- Added special search mappings for movies with special characters that would not return without the special character (i.e. WALL·E)
- Fixed issue where custom size wasn't editable on poster types.

## [1.0.6.5] [2025-05-22]
- Added user explorer which can be accessed at /explorer-users
- Added missing caching for profile data to prevent excessive reads and improve performance
- Fixed cache warm up function throwing error.

## [1.0.6.4] [2025-05-20]

- More UI and style unification throughout the app.
- Fixed bug that in some instances could cause page state to become null and make certain actions unclickable without a page refresh.
- Rendering and performance optimizations.

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
