# Changelog

All notable changes to Posterama will be documented in this file.

## [1.2.5] [11-27-2025]

- Fixed issue with jumpy search text on user collection page.

## [1.2.4] [11-27-2025]

- Changed default sort order for movie and tv search poster pages to Year (oldest)

## [1.2.3] [11-26-2025]

- OTA updates for mobile. 

## [1.2.2] [11-26-2025]

### Added
- Photobusta size added under Italy.

### Fixed
- Fixed scroll position on cast & crew credits page in the mobile app.

## [1.2.1] [11-25-2025]

### Improved
- **Statistics Page Redesign**: Completely refreshed the Statistics page with a cleaner, more modern design
  - Stats now display values directly without needing to hover
  - Improved readability with horizontal bar visualizations
  - Poster types now shown as a compact tag cloud
  - Consistent styling across all stat components
- **Poster Detail Pages**: Visual improvements and unification of the layout and styling between Poster Library and My Collection detail pages for a more consistent experience
- **Movie/TV Details**: Visual improvements to movie and TV show detail pages
- **Mobile Experience**: Fixed various mobile-specific issues including modal display problems and menu behavior

### Fixed
- Fixed YouTube video playback issues on iOS devices
- Fixed mobile menu and drawer navigation issues
- Fixed footer overlapping content on the Messages page

## [1.2.0] [11-21-2025]

### Added
- **Profile Theme Customization**: You can now customize the appearance of your public profile! Access the new Appearance tab in your profile settings to:
  - Choose from multiple theme options to match your style or collection mood
  - Toggle film strip decorations on your public profile page
  - Control whether your wishlist appears on your public profile
  - Choose between Justified and Masonry gallery layouts
  - Select Boxed or Full Width page layouts

### Fixed
- **Browser Navigation**: Fixed issues with browser back button and app back button functionality throughout the site
  - Back button now correctly preserves your page number, filters, and search terms when returning to collection or poster library pages
  - Eliminated the need to click back button multiple times to navigate
  - Smoother navigation experience when browsing between poster details and collection views

## [1.1.22] [11-15-2025]

- Fixed issue on mobile when paging the screen would get stuck at the bottom.
- Improved paging to allow for easier page navigation.

## [1.1.21] [11-13-2025]

- Backend optimizations galore. Posterama performance should be even faster now!
- Improved UI for search/filter/sorting on Poster Library and My Collection pages on mobile devices.
- Other various UI improvements and consolidation throughout for a more consistent user experience.
- All stats are now FREE to all users.

## [1.1.20] [11-06-2025]

- Fixed issue with links for tv shows incorrectly linking to movies.

## [1.1.19] [10-29-2095]

- Added ability to customize sort order of custom collections (Go to Manage Collections from the Collections drop down on the My Poster Collection Page).
- Added ability to sort by Purchase Date in the My Poster Collection view.
- Added links to movie titles on user posters and poster types to link to the the specific movie page.

## [1.1.18] [10-28-2025]

- Added the ability to select multiple options for each dropdown in a filter for more powerful filtering of collections and the poster library.

## [1.1.17] [10-27-2025]

- Justified gallery view is now available on the public user profile.

## [1.1.16] [10-26-2025]

- Add additional poster sizes for Egypt.
- Fixed issue with link for collection items on poster types page.

## [1.1.15] [10-25-2025]

- Added new settings panel for choosing Dark Mode, High Contrast Mode and 6 new colored themes to customize Posterama more to your preference.
- Updated notification panel to match style of settings panel.

## [1.1.14] [10-17-2025]

- Fixed issue where searching by gallery name would not return results.
- Added new condition option of fine between Very Good and Near Mint.
- Deprecated old marketplace to make way for upcoming Marketplace V2 (more info coming soon!)

## [1.1.13] [09-16-2025]

- Various UI tweaks to improve the mobile app experience.

## [1.1.12] [09-08-2025]

- Lobby cards now have their own tab on Poster Library and Collection Pages. An All tab has also been added if you wish to view all types together.
- Behind the scenes upgrades for improved performance and stability.

## [1.1.11] [09-03-2025]

- Fixed issue with scrollability in mobile apps

## [1.1.10] [08-25-2025]

- Various stability improvements.
- Miscellaneous bug fixes

## [1.1.9] [08-03-2025]

- **Hotfix**: Fixed Custom Size was no longer selectable in version 1.1.8

## [1.1.8] [08-03-2025]

### Added

- **Pressbook and Stills**: Official support for Pressbooks/Presskits and stills. Select Pressbook or Still from Poster Type dropdown for the new Poster types.
  - Multiple image support added for Pressbook and still poster types only. 

### Fixed
- Fixed alphabetical sorting not ignoring common words like a, the, etc in gallery view.
- Fix several instances of bad url routing for share buttons in mobile.
- Removed linen-backed and double sided checkboxes where not needed for a specific poster type (like Press Books, Stills, Lobby Cards)

## [1.1.7] [07-29-2025]

- Stats calculated directly from typesense.

## [1.1.6] [07-28-2025]

- Fixed issue with rankings page not loading on mobile.
- Adjusted cache TTL for stats to reduce unneccesary database reads.

## [1.1.5] [07-24-2025]

### Added
- **Collection Table View Redesign**: The table view on the user collection page has been completely redesigned. The new table allows for complete user customization of data displayed as well as inline editing of data while making better use of screen real estate. Note: The table view will only be available on the desktop version of Posterama.
- **Enhanced Gallery View Search**: The gallery view now supports comprehensive search functionality including:
  - Search by actor names to find posters featuring specific actors
  - Search by director names to find posters from specific directors  
  - Search by movie genres (action, sci-fi, horror, etc.)
  - All searches now use the same powerful search engine as the main collection view
- **URL Parameters for Profile Pages**: You can now share direct links to profile pages with specific searches, sorts, and pagination
  - Gallery view: `/user/username/gallery?search=tom+cruise&sort=releaseYear-desc`
  - Profile collection view: `/user/username?search=batman&sort=movieTitle-asc&page=2`
  - For sale items: `/user/username?tab=forsale&sort=price-asc`
  - Search and sort parameters are automatically saved in the URL as you browse
- **Improved Multi-Selection Interface**: Redesigned the bulk selection experience for better usability
  - Checkboxes now appear on hover (desktop) or are long pressing (mobile)
  - Simply hover over a poster card to reveal the selection checkbox in the upper left corner
  - Click anywhere on the card when hovering to toggle selection
  - Selection state is clearly indicated with a highlighted border
- **Floating Selection Bar**: A modern floating action bar appears when items are selected
  - Shows count of selected items
  - Quick access to bulk actions (Delete, Add to Collection)
- **Bulk Delete**: You can now delete multiple posters at once
  - Select the posters you want to remove
  - Click the Delete button in the floating selection bar
  - Confirm the deletion in the dialog
  - All selected posters are deleted in one operation
- **Wishlist Pagination**: The wishlist page now supports pagination for better performance with large wishlists
  - Navigate through pages of wishlist items (24 items per page by default)
  - Page number and size are preserved in the URL for easy sharing
  - Share button added to quickly share your wishlist URL with others
- **TMDB Attribution**: Added proper attribution to The Movie Database (TMDB) on all movie/TV search and details pages as required by their API terms of service

### Changed
- **Profile Badges Display**: All earned badges are now displayed on public profiles instead of limiting to 3 badges with a "+X more" indicator
- **Public Profile UI Cleanup**: Adjusted positioning of various interactive elements on public profile page to feel less cluttered.

### Fixed
- **Public Profile Tab Navigation**: Fixed issue where clicking tabs on public profile pages didn't properly update the URL
  - All tabs (Collection, Wishlist, For Sale) now use clean URLs without query parameters
  - Direct links to wishlist (e.g., `/user/username/wishlist`) now correctly display the wishlist tab
  - Navigation between tabs is now consistent and updates the browser URL properly
- Fixed edit button not routing correctly when clicked from the User Collection table view
- Fixed table view toggle not working on web platform
- Fixed table view date added displaying incorrect dates.

## [1.1.4] [07-22-2025]

- Improved login experience to provide better feedback when login is unsuccessful. 
- Fixed forgot password not functional on mobile apps.

## [1.1.3] [07-21-2025]

- Fixed issue with public profile gallery when viewed in landscape on a mobile device.
- iOS mobile app is now generally available to the public.

## [1.1.2] [07-19-2025]

- Fixed bug that allowed posters from movies and tv to get mixed together when they shared the same TMDB ID.

## [1.1.1] [07-12-2025]

- Minor fixes for Android and future iOS app.

## [1.1.0] [07-07-2025]

- Android mobile app is now generally available to the public. 

## [1.0.7.6] [07-05-2025]

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
