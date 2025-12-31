# Changelog

## [1.2.23] - 2025-12-31

### Changed

- Various package updates for improved stability and security.

### Fixed

- Custom size display now shows correctly on poster details.
- Movie release year data now properly syncs with search functionality.

## [1.2.20] - 2025-12-14

### Changed

- **Movie Release Year Display**: The year shown next to movie titles on poster detail pages now displays the actual movie release year from TMDB, rather than the poster year. This provides more accurate context about when the film was released. The poster year (which may differ for re-releases, anniversary editions, etc.) is still shown in the Poster Specifications section.

## [1.2.19] - 2025-12-13

### Added

- **Search by Production Company**: You can now search for posters by production company (e.g., Studio Ghibli, Pixar, Marvel Studios). Find all posters from your favorite studios instantly.
- **Search by Franchise/Collection**: Search for posters by movie franchise or collection (e.g., Star Wars Collection, Marvel Cinematic Universe, James Bond Collection). Quickly locate all posters from a series.

## [1.2.18] - 2025-12-11

### Changed

- Increased reCAPTCHA score threshold for sign-up to reduce bot accounts.
- Improved safe area handling for better mobile layout consistency.

### Fixed

- Mobile in-app purchases now sync correctly with subscription status.
- Various mobile layout fixes for iOS.

## [1.2.17] - 2025-12-09

### Changed

- Upgraded to Capacitor 8 for improved mobile app performance and stability.
- Updated Stripe integration to latest API version (2025-09-30) for better payment reliability.
- Removed onboarding video from registration flow for faster account setup.

### Fixed

- Home page now displays correct page titles.
- Added bot protection to sign-up process to prevent spam accounts.

## [1.2.16] - 2025-12-07

### Fixed

- Contributing user was display user id instead of username on mobile.

## [1.2.15] - 2025-12-06

### Fixed

- Minor stability enhancements for mobile.

## [1.2.14] - 2025-12-05

### Added

- **Public Poster Library**: The Poster Library is now accessible to non-authenticated users. Anyone can browse and explore the poster collection without signing in, making it easier to discover posters before creating an account.
- **Email Preferences**: New email preferences section in your profile settings. Control which types of emails you receive:
  - Marketing & Promotions
  - New Features announcements
  - Tips & Tricks guides
  - Marketplace Alerts
- **Unsubscribe Page**: Direct unsubscribe links in emails now lead to a dedicated page where you can manage your email preferences or unsubscribe from all emails.

### Changed

- Artist submissions on poster types now require authentication. You must be signed in to submit artist information.
- Improved sitemap for better search engine discoverability.

### Fixed

- iOS analytics tracking now works correctly.

## [1.2.13] - 2025-12-02

### Added

- New Insurance Report feature for Pro users. Generate a detailed report of your collection for insurance purposes.
- Multiple image management for Press Books and Stills on the user poster edit page. You can now add, remove, and reorder additional images when editing these poster types.

### Fixed

- Issue where back button would loop between poster edit and detail pages after saving changes.
- Loading flash that would appear when saving an edited user poster.
- Subscription sync issues with Stripe that could cause subscription status to not update correctly.
- Session handling issue where expired authentication tokens could cause features to behave as if user was on free tier. The app now automatically refreshes tokens and re-authenticates when needed.

## [1.2.12] - 2025-12-01

### Added

- New help center with documentation on all aspects of the site. Please report any errors!

## [1.2.11] - 2025-12-01

### Fixed

- Date display bug on stats page.

## [1.2.10] - 2025-11-30

### Changed

- Behind the scenes tweaks to prepare for next set of updates.

## [1.2.9] - 2025-11-29

### Added

- Expanded Achievements system is now live. There are now many more achievements to be earned with various tiers within each to unlock. This is now located on the new Achievements page from the side navbar.

### Changed

- Custom image is now required when adding a poster to the poster library.

## [1.2.8] - 2025-11-29

### Changed

- More unification of UI elements to new design updates.

## [1.2.7] - 2025-11-28

### Fixed

- Issue with Play store purchases sometimes not syncing properly.

## [1.2.6] - 2025-11-28

### Added

- Option to set default sort order for your public profile page from the Profile>Appearance tab.

## [1.2.5] - 2025-11-27

### Fixed

- Issue with jumpy search text on user collection page.

## [1.2.4] - 2025-11-27

### Changed

- Default sort order for movie and tv search poster pages to Year (oldest).

## [1.2.3] - 2025-11-26

### Added

- OTA updates for mobile.

## [1.2.2] - 2025-11-26

### Added

- Photobusta size added under Italy.

### Fixed

- Scroll position on cast & crew credits page in the mobile app.

## [1.2.1] - 2025-11-25

### Changed

- **Statistics Page Redesign**: Completely refreshed the Statistics page with a cleaner, more modern design
  - Stats now display values directly without needing to hover
  - Improved readability with horizontal bar visualizations
  - Poster types now shown as a compact tag cloud
  - Consistent styling across all stat components
- **Poster Detail Pages**: Visual improvements and unification of the layout and styling between Poster Library and My Collection detail pages for a more consistent experience
- **Movie/TV Details**: Visual improvements to movie and TV show detail pages
- **Mobile Experience**: Fixed various mobile-specific issues including modal display problems and menu behavior

### Fixed

- YouTube video playback issues on iOS devices
- Mobile menu and drawer navigation issues
- Footer overlapping content on the Messages page

## [1.2.0] - 2025-11-21

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

## [1.1.22] - 2025-11-15

### Fixed

- Issue on mobile when paging the screen would get stuck at the bottom.

### Changed

- Improved paging to allow for easier page navigation.

## [1.1.21] - 2025-11-13

### Changed

- Backend optimizations galore. Posterama performance should be even faster now!
- Improved UI for search/filter/sorting on Poster Library and My Collection pages on mobile devices.
- Other various UI improvements and consolidation throughout for a more consistent user experience.
- All stats are now FREE to all users.

## [1.1.20] - 2025-11-06

### Fixed

- Issue with links for tv shows incorrectly linking to movies.

## [1.1.19] - 2025-10-29

### Added

- Ability to customize sort order of custom collections (Go to Manage Collections from the Collections drop down on the My Poster Collection Page).
- Ability to sort by Purchase Date in the My Poster Collection view.
- Links to movie titles on user posters and poster types to link to the specific movie page.

## [1.1.18] - 2025-10-28

### Added

- Ability to select multiple options for each dropdown in a filter for more powerful filtering of collections and the poster library.

## [1.1.17] - 2025-10-27

### Added

- Justified gallery view is now available on the public user profile.

## [1.1.16] - 2025-10-26

### Added

- Additional poster sizes for Egypt.

### Fixed

- Issue with link for collection items on poster types page.

## [1.1.15] - 2025-10-25

### Added

- New settings panel for choosing Dark Mode, High Contrast Mode and 6 new colored themes to customize Posterama more to your preference.

### Changed

- Updated notification panel to match style of settings panel.

## [1.1.14] - 2025-10-17

### Added

- New condition option of Fine between Very Good and Near Mint.

### Fixed

- Issue where searching by gallery name would not return results.

### Deprecated

- Old marketplace to make way for upcoming Marketplace V2 (more info coming soon!)

## [1.1.13] - 2025-09-16

### Changed

- Various UI tweaks to improve the mobile app experience.

## [1.1.12] - 2025-09-08

### Added

- Lobby cards now have their own tab on Poster Library and Collection Pages. An All tab has also been added if you wish to view all types together.

### Changed

- Behind the scenes upgrades for improved performance and stability.

## [1.1.11] - 2025-09-03

### Fixed

- Issue with scrollability in mobile apps.

## [1.1.10] - 2025-08-25

### Changed

- Various stability improvements.

### Fixed

- Miscellaneous bug fixes.

## [1.1.9] - 2025-08-03

### Fixed

- **Hotfix**: Custom Size was no longer selectable in version 1.1.8.

## [1.1.8] - 2025-08-03

### Added

- **Pressbook and Stills**: Official support for Pressbooks/Presskits and stills. Select Pressbook or Still from Poster Type dropdown for the new Poster types.
  - Multiple image support added for Pressbook and still poster types only.

### Fixed

- Alphabetical sorting not ignoring common words like a, the, etc in gallery view.
- Several instances of bad url routing for share buttons in mobile.

### Changed

- Removed linen-backed and double sided checkboxes where not needed for a specific poster type (like Press Books, Stills, Lobby Cards).

## [1.1.7] - 2025-07-29

### Changed

- Stats calculated directly from Typesense.

## [1.1.6] - 2025-07-28

### Fixed

- Issue with rankings page not loading on mobile.

### Changed

- Adjusted cache TTL for stats to reduce unnecessary database reads.

## [1.1.5] - 2025-07-24

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
- Edit button not routing correctly when clicked from the User Collection table view.
- Table view toggle not working on web platform.
- Table view date added displaying incorrect dates.

## [1.1.4] - 2025-07-22

### Changed

- Improved login experience to provide better feedback when login is unsuccessful.

### Fixed

- Forgot password not functional on mobile apps.

## [1.1.3] - 2025-07-21

### Added

- iOS mobile app is now generally available to the public.

### Fixed

- Issue with public profile gallery when viewed in landscape on a mobile device.

## [1.1.2] - 2025-07-19

### Fixed

- Bug that allowed posters from movies and tv to get mixed together when they shared the same TMDB ID.

## [1.1.1] - 2025-07-12

### Fixed

- Minor fixes for Android and future iOS app.

## [1.1.0] - 2025-07-07

### Added

- Android mobile app is now generally available to the public.

## [1.0.7.6] - 2025-07-05

### Added

- Virtual collections. You can now create virtual collections from your Collections page to group your collection into 1 or more sub-collections. Free users are limited to 5 virtual collections. Premium members can create unlimited virtual collections.

## [1.0.7.5] - 2025-07-02

### Added

- Natural language search to user collections for Premium users. Please provide feedback on results in the Discord.

### Fixed

- Bug that would cause thumbnails and medium urls to get swapped when editing a poster. Impacted posters have been corrected.

## [1.0.7.4] - 2025-07-01

### Added

- New gallery view to public profile page. A new, exciting way to show off your collection!

### Changed

- Updated from Material UI 6.4 to MUI 7.2.
- Updated stats update timing to prevent multiple stat refreshes in a short period of time.

## [1.0.7.3] - 2025-06-23

### Changed

- **Rankings Endpoint**: Added Redis caching (1-hour TTL) and efficient batch processing to eliminate N+1 queries.
- **Cache Invalidation**: Replaced pattern-based invalidation with targeted key removal, preserving unaffected caches.
- **Stats Calculation**: Implemented 4-hour caching for user stats with smart invalidation on collection changes.
- **Similar Collectors**: Added collection summaries cache to pre-calculate poster type overlaps between users.
- **TMDB API Caching**: Created 30-day cache for movie/TV details to reduce external API calls.
- **Overall Impact**: Significantly reduced database reads, especially for stats calculations and rankings endpoints.

### Fixed

- Date conversion issues.

## [1.0.7.2] - 2025-06-22

### Changed

- Updated sort options on public profile pages to align with public library and collection pages.

## [1.0.7.1] - 2025-06-21

### Added

- Additional poster sizes for Italy and Switzerland.

### Changed

- Revamped poster suggestion submission page to allow for more complete suggestion updates.

### Fixed

- Search bug on my collection page that would not return proper results when searching by Artist name.

## [1.0.7] - 2025-06-13

### Fixed

- Bug that would prevent being able to edit a user poster in some instances.

## [1.0.6.9] - 2025-06-02

### Changed

- Default storage condition to most likely option based on poster type (for example, defaulting Lobby Cards to Flat vs rolled).
- Lots of prep work for Android mobile app!

## [1.0.6.8] - 2025-05-28

### Added

- Support for Print types. When selecting the poster type print, new fields will become available including Gallery/Publisher Name, Print Run, and noting whether a print is a variant or not. When adding a Print type to your user collection an additional field will be available, Edition Number, that allows you to catalog your specific edition number for the print.

### Fixed

- Minor UI fixes.

## [1.0.6.7] - 2025-05-25

### Changed

- Updated subscription pricing to $3.99/month and $39.99/year (save 30%).
- Enabled yearly subscription option for Pro plan.
- Updated all Stripe price IDs across development and production environments.

## [1.0.6.6] - 2025-05-24

### Added

- Special search mappings for movies with special characters that would not return without the special character (i.e. WALL·E).

### Fixed

- Issue where custom size wasn't editable on poster types.

## [1.0.6.5] - 2025-05-22

### Added

- User explorer which can be accessed at /explorer-users.
- Missing caching for profile data to prevent excessive reads and improve performance.

### Fixed

- Cache warm up function throwing error.

## [1.0.6.4] - 2025-05-20

### Changed

- More UI and style unification throughout the app.
- Rendering and performance optimizations.

### Fixed

- Bug that in some instances could cause page state to become null and make certain actions unclickable without a page refresh.

## [1.0.6.3] - 2025-05-19

### Added

- Wishlist to public user profile page.
- Ability to link directly to collection, wishlist or for sale tabs with new urls /user/username/collection, /user/username/wishlist, /user/username/forsale. Share icons are available on each tab for easy access.

### Changed

- Updated User Profile Page UI to match recent changes to styling.

## [1.0.6.2] - 2025-05-17

### Changed

- Updated poster cards and UI throughout to match updates in 1.0.6.

## [1.0.6.1] - 2025-05-17

### Fixed

- Performance issue with search on user collections.

## [1.0.6] - 2025-05-14

### Changed

- Revamped UI for User Poster and Poster Type detail pages. Information is now laid out in a more logical way and the UI feels cleaner and more modern.

### Fixed

- Bug that could prevent Autographed poster details from displaying correctly on User Poster detail page.
- Miscellaneous UI fixes and tweaks throughout the rest of the app.

## [1.0.5.3] - 2025-05-11

### Fixed

- Date displaying incorrectly on marketplace detail page.

## [1.0.5.2] - 2025-05-11

### Added

- Movie details (Genre, Director, Main Cast) to poster type detail view, user poster detail view and public profile page poster view.

## [1.0.5.1] - 2025-05-10

### Fixed

- Values not displaying on cards and table view for user collection.

## [1.0.5] - 2025-05-09

### Added

- Option to toggle single or double column view when on mobile for Collections, Posters, Wishlist and Marketplace.

### Changed

- Updated Marketplace to have more consistent UI with other pages.
- The Marketplace is now publicly viewable and linked on pages non-users visit.

## [1.0.4.1] - 2025-05-08

### Added

- Image right click protection.

### Changed

- Initial upgrade to React 19.1 from React 18.3.1.

### Fixed

- Bug where incorrect title would be displayed when adding a TV poster to a user collection.

## [1.0.4] - 2025-05-06

### Added

- Ability to search TV shows and add posters for TV shows to the public library and user collections. New visual cues have been added to designate movie or TV show.
- Helper text in various places to help users better understand the actions they are taking.

### Changed

- Adjusted terminology for buttons in various places to make more clear what action is being taken.

## [1.0.3.3] - 2025-05-05

### Added

- UK Bus Stop to poster size options.

### Changed

- Expanded size choices for France and corrected naming for existing sizes.

## [1.0.3.2] - 2025-05-03

### Added

- Movie search now allows searching by Actors.

### Fixed

- Issue with poster type edits throwing error when updating.

## [1.0.3.1] - 2025-05-02

### Added

- Page for howto videos to better explain how to use Posterama. Includes new video on adding posters to the global database and user collections.

## [1.0.3] - 2025-05-02

### Added

- Genre and director as filters on Poster Library and User Collections.
- You can now search for posters in the Poster Library and User Collection by typing the Actor name (main cast only), Director or Genre.
- Click-through functionality to all statistics components on the Stats page. Now you can simply click on any statistic (decade, condition, genre, country, or poster type) to instantly filter your collection to match. Quickly explore the posters making up each segment of your collection data with just a single click.

### Changed

- Increased limit for free tier from 25 to 50 posters.

### Fixed

- Issue with condition stats not showing all stats correctly.

## [1.0.2.5] - 2025-05-01

### Added

- Quick link to view public profile to side nav.

## [1.0.2.4] - 2025-05-01

### Added

- Missing forgot password functionality.

## [1.0.2.3] - 2025-04-30

### Fixed

- Trim spaces when searching for movies to prevent results for single word titled movies from not appearing if space is inadvertently added.

## [1.0.2.2] - 2025-04-30

### Fixed

- Issue with leading articles (i.e. a, the) were not being dropped for alphabetical sorting.
- Issue where uploading an image from mobile would open camera by default.
- Minor mobile UI tweaks/fixes.

## [1.0.2.1] - 2025-04-30

### Added

- Confirmation screen after adding poster to give user choice to quickly add another poster or go to their collection.
- URL parameter support to Public Profile Page. This is useful if you want to share your profile with a specific Poster sort order.
- Egypt, Turkey, and Ukraine as Country option with various popular sizes for these countries.

## [1.0.2] - 2025-04-29

### Added

- URL parameter synchronization to the Poster Library and User Poster Collection, allowing:
  - Bookmarking specific filtered views
  - Browser back/forward navigation with state preservation
  - Persistent filters and pagination across page refreshes
  - Seamless return to previous view after viewing poster details

### Changed

- Implemented compression for Redis cache to reduce memory usage and improve performance for large cached objects.
- Removed duplicated stats from Dashboard (All stats can be found on the Statistics page) and replaced with new quick actions for reaching common areas quickly from the Dashboard.
- Removed blocking operations when adding a user poster to increase speed of submission.

### Fixed

- Display validation error message when user attempts to upload non-image file or file that is larger than the 20MB max.

## [1.0.1.1] - 2025-04-29

### Fixed

- Error when trying to update profile or add profile image.

### Changed

- Batch TMDB api calls to improve performance.

## [1.0.1] - 2025-04-28

### Added

- Thailand as Country option with various popular sizes for this country.

### Changed

- Improved image loading performance by using smaller thumbnails on smaller screens, and right sizing images for poster cards reducing bandwidth usage.

## [1.0.0] - 2025-04-28

### Added

- Initial release of Posterama.
- Movie poster collection management.
- Poster types and categorization.
- Marketplace for trading/selling posters.
- User-to-user messaging system.
- Notifications system.
- Wishlist functionality.
- Collection statistics and analytics.
