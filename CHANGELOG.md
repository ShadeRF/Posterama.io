# Changelog

## [1.5.31] - 2026-09-18

### Added

- **Jump From Your Statistics to the Posters**: On the Statistics page, tap any genre (in **Every genre, ranked** or on the genre chart), any entry under **Formats & sizes**, or a name under **Top Directors** or **Top Cast** to open My Collection showing just those posters. It already worked for countries, decades and condition.

### Fixed

- **Genre and Director Filters in My Collection**: Choosing a genre or director in My Collection's Filters didn't narrow anything down; the choice was quietly dropped. Both filters work now, including **Exclude**. They're also saved in the page link and in Saved Views.
- **Documentation Link Went Nowhere**: The **Documentation** link in the page footer, and the same entry on the app's About screen, opened an empty page on an outside site. Both now open the Help Center inside Posterama.

## [1.5.30] - 2026-09-17

### Fixed

- **Collector Names Cut Short on the Friends Page**: On the collectors you follow, longer names and @handles were cut off, and the **Follows you** badge squeezed them down to a letter or two. Nothing is cut off now: names, handles and the badge wrap onto their own lines.
- **Accidental Unfollows on the Friends Page**: The follow button sits on a card that opens the collector's profile, so a stray tap could drop someone from your list without a word. Unfollowing now asks first; following still happens straight away.
- **Updates That Left the App Stuck**: If an update didn't unpack properly, the app could get stuck restarting itself and the only way out was to uninstall and reinstall. It now repairs itself: it reloads the update, and if that still fails it drops back to the version that came with the app, then picks the update up again.

### Added

- **App Updates in Settings**: The app's Settings screen now shows which version you're running, whether an update is waiting, and a **Check for updates** button. There's also **Reinstall the built-in version** if an update ever leaves the app misbehaving.

## [1.5.29] - 2026-09-17

### Changed

- **Two Danish One-Sheet Sizes**: Denmark now offers **One-Sheet (24x33)**, the local cinema poster used until about 2010, and **One-Sheet (27x40)**, the standard size used since. Danish one-sheets already in the library have been sorted into the right one by year; if one of yours landed in the wrong size, edit it to switch.

### Fixed

- **Wishlists Show Current Details**: When a poster in the library was corrected (its size, country, artist or picture), your wishlist kept showing the old details. Wishlists now update with the library, and a wishlisted poster that gets merged into a duplicate moves across with it instead of turning into a broken link.
- **Merged Posters Keep Your Photo**: When two duplicate library entries were merged, the posters in your collection picked up the right details, but could swap your own photo for the library's newer picture. Your photo now always stays.

## [1.5.28] - 2026-09-16

### Fixed

- **Some Movie and TV Pages Wouldn't Open**: A problem at The Movie Database, where our film details come from, stopped a batch of movie and TV pages loading — some showed an error, others just stayed blank. Those pages now load normally, asking for the details a different way when the usual request fails.
- **Statistics Stuck Loading**: If the search service had a hiccup, the Statistics page would sit on its loading placeholders forever. It now tells you it couldn't load your statistics and gives you a button to try again.
- **Searching Collection Rankings**: The search box on the rankings page only looked at the collectors on the page you were viewing, so searching for someone further down the list found nothing. It now searches everyone.
- **Adding a Poster When The Movie Database Is Down**: Adding a new poster type while The Movie Database was unreachable used to save it without its genres, cast, director or release year, so it quietly went missing from genre statistics, achievements and searches by director. It now tells you what happened and asks you to try again in a few minutes, and nothing incomplete gets saved. Saving a poster type that fails for any reason now tells you so, instead of looking like the button did nothing.

### Changed

- **Faster Statistics**: The Statistics page, the rankings page and anywhere your collection totals appear now load noticeably faster, and moving between pages of the rankings no longer reloads the whole list.
- **Faster Searches**: Searching for movies, TV shows and people, and opening their pages, now skips a request that never went anywhere.

## [1.5.27] - 2026-09-16

### Changed

- **Achievements Keep Themselves Up To Date**: Your progress is now worked out fresh each time you open the Achievements page, so what you see is always current. **Check Progress** is gone — there's a **Refresh** button if you want to nudge it, but you shouldn't need it. Before this, progress only moved when you pressed that button, you could only press it once a day, and everything sat stale in between.
- **Night Owl, Early Bird and Weekend Warrior Use Your Clock**: These three count when you added a poster, and they were reading the time in London rather than where you are. If you collect from the Americas or Asia your counts will shift — some up, some down — and they'll be right from now on. Early Bird in particular was close to impossible to earn outside Europe.
- **Tiers Read the Right Numbers Now**: A few achievements were counting wrongly — some too high, some too low — so a tier or two may move when you next look. Where one drops, you keep the badge and the date you first earned it.

### Added

- **Recent Progress**: The Achievements page now opens with the last few tiers you've earned and when you earned them, so you can see what's happened since you were last there without hunting through the whole list.
- **Earned-On Dates You Can Trust**: Each tier is now dated by the poster that actually earned it, not by the moment we noticed. Older entries have been recalculated the same way. A handful — the contributor badges — can't be traced back to a poster, so those say "recorded" instead.
- **Unlocks Tell You About Themselves**: Earn a tier while you're off doing something else and you'll be told next time you open the page, instead of finding out by noticing a number had changed.

### Fixed

- **Counts Going Backwards After Adding a Poster**: For collectors with more than a thousand posters, adding one could quietly drop some country and genre counts — sometimes by a lot — until the next time you pressed Check Progress. They now only ever reflect your whole collection.
- **Duplicate Achievements Behind the Scenes**: The library held two copies of a couple of dozen achievements, only one of which you could see, and the pair had drifted to different numbers. The hidden copies are gone.

## [1.5.26] - 2026-09-15

### Added

- **Swipe Between Pages**: On a phone or tablet, swipe left across your posters to go to the next page and right to go back. It works in My Collection, the Poster Library and your Wishlist, so you can browse a long collection with your thumb instead of reaching for the buttons at the bottom. Scrolling, pinching and holding a poster to select it all behave as before, and swipes that start at the very edge of the screen are left to your phone's own back gesture and the side menu.
- **Page Number Above Your Posters**: The page you're on is now shown at the top of My Collection, the Poster Library and your Wishlist as well as the bottom, so you can tell where you are in a long list without scrolling to the end to find out. It reads the same as the one at the bottom, noting when a search or a letter is narrowing what you see.

## [1.5.25] - 2026-09-15

### Added

- **Production Art and Heralds**: Two new poster types. **Production Art** is for one-of-a-kind artwork made for a film's campaign — prep sketches, concept art and finished paintings — and **Herald** is for the small flyers and handbills theatres handed out. Both let you enter the exact measurements yourself, since neither comes in standard sizes, and both start out stored Flat.
- **What Each Poster Type Means**: Choosing a poster type now shows a line explaining what belongs there, so the pairs that get mixed up most — advance and teaser, promo and commercial — are easier to tell apart.

### Changed

- **Storage Starts on the Right Setting**: When you log an incoming poster, changing its type or size now moves the storage condition to match — **Flat** for the pieces normally kept that way (lobby cards, window cards, press books, stills, heralds and production art) and **Rolled** for everything else. You can still set it to whatever you like.
- **Tidier Tag Suggestions**: Tags like "herald", "production art" and "original art" are now recognised as repeating the poster's type, so they get flagged alongside the others when you clean up tags.

### Fixed

- **Posters Sliding Over the Bottom Buttons**: In the iOS and Android apps with **Animations** turned on, a tall poster gliding open travelled across the row of buttons at the bottom of the screen, then dropped behind them the moment it landed. It now stays behind them the whole way.

## [1.5.24] - 2026-09-15

### Fixed

- **Smoother Page Changes From the Side Menu**: In the iOS and Android apps with **Animations** turned on, choosing a page from the side menu made the fade to the next page stutter, while the buttons along the bottom were smooth. The menu now fades away together with the page you're leaving, so both feel the same.

## [1.5.23] - 2026-09-15

### Added

- **Posters Glide Open**: Tap a poster in your collection, the Poster Library or your wishlist and the picture glides from the grid straight into its frame on the poster's page. Go back and it glides home to its spot in the grid. Moving between any other pages is a quick fade instead of a hard cut.
- **Glide Into the Viewer on Profiles**: On a collector's profile, their Featured posters and the full-page gallery, a poster grows from its tile into the viewer and shrinks back when you close it. The viewer shows the picture right away, then sharpens to the full-size image once it has loaded.
- **Animations Setting (Beta)**: The fades and glides above are in beta. They're on by default on the website, and off by default in the iOS and Android apps while we finish tuning them there. Switch **Animations** on or off in **Settings** (the gear icon on the website, or the Settings page in the app). If your device is set to reduce motion, pages change instantly either way.

### Changed

- **Going Back Is Instant**: Returning to My Collection or the Poster Library shows the posters you were just looking at straight away, instead of loading placeholders all over again, and quietly checks for changes in the background. Changing page, tab or filters keeps the current posters on screen until the next set is ready.
- **Opening My Collection**: The first visit of a session no longer flashes a page of placeholders before the collection appears.
- **Steadier Poster Pages on Phones**: On phones and in the mobile app, a poster's title and artwork now appear in place when the page finishes loading, instead of sliding up and nudging the page. The website on larger screens keeps the gentle rise.

### Fixed

- **Flicker When Going Back**: Going back to the Poster Library, your wishlist or the marketplace made the page load itself twice, which showed as a brief double flicker. It loads once now.
- **Scroll Position in the Mobile App**: In the iOS and Android apps, going back to a list jumped you to the top, so after opening a poster halfway down your collection you had to scroll to find your place again. Going back now returns you to where you were, and new pages still open at the top.
- **Back After Leaving Edit**: Opening a poster in your collection, choosing **Edit** and then leaving without saving meant the back button took you into the edit form again instead of back to your collection. It goes back to your collection now.

## [1.5.22] - 2026-09-14

### Added

- **Tag Suggestions From the Library**: As you type a tag, the tags other collectors already use that start the same way appear under the box with how many posters carry them. Tap one to add it. Tags the poster's record already covers aren't suggested.
- **Spelling and Mix-Up Nudges for Tags**: The tag box now also points out a tag written differently from the rest of the library — `IMAX style` where almost everyone writes `IMAX`, or a typo like `Video Releaee` — with a button to use the usual spelling, so the same thing is tagged the same way and turns up together in search. It notes a tag that contradicts the poster, like `KR` on a poster whose country is Denmark, and explains that tags such as `Folded` or `Linen Backed` describe one collector's copy, which has its own fields for that, rather than every copy of the poster.
- **Half Subway**: Added the 29½×45 inch Half Subway to the United States size list.

### Changed

- **Smarter "Already Recorded" Tag Nudge**: The note that a tag repeats the poster's record now recognises a studio however it's written (`Warner Bros` for Warner Bros. Pictures), a genre's other spellings (`Sci-Fi`, `Musical`), a franchise without the word "Collection" (`Star Wars`), and a tag that's already part of the title, like `Star Wars` on *Rogue One: A Star Wars Story*. Tags that say which edition a poster is, such as `3D`, `IMAX` or `Director's Cut`, are never flagged. Tags already on the poster that repeat or contradict the record are outlined in amber, with the reason when you hover, and a **Remove** button clears them all in one go — handy after pasting a long list. Instead of one long sentence naming every tag, the note now just says how many there are.
- **Tag Lists From Older App Versions**: A comma-separated list typed into a tag box on an older version of the mobile app is now split into separate tags when it's saved.
- **Tidier Library Behind the Scenes**: Moderators have better tools for merging duplicate library entries, reviewing suggested changes and cleaning up tags across the whole library, so what you search and browse stays consistent.

### Fixed

- **Hyphenated Titles in Search**: Searching `wreck it ralph` didn't find *Wreck-It Ralph*, and `x men` missed the X-Men films, because the search saw one word where you typed two. Searches in the library, your collection, your wishlist and the marketplace now find titles whether you type the hyphen or not.
- **Clearing an Artist**: Emptying the artist field on a library entry and saving put the old artist straight back. It now clears.
- **Poster Year**: A library entry's year can no longer be saved blank or as 0; it has to be a real year, and the form says so if it isn't.
- **Removing Tags Quickly**: Removing two tags in quick succession while editing a library entry could leave the first one behind. Both now go.

## [1.5.21] - 2026-09-12

### Added

- **Tag Boxes Understand a List**: Typing `NSS, Style A, 1st Printing` into a tag box and hitting Enter used to save the whole line as one tag. It now adds three. Commas and line breaks separate tags, repeats are dropped, and if you need a comma *inside* a tag, wrap it in quotes — `"I, Borg"` stays one tag.
- **A Nudge When a Tag Is Already Recorded**: If you tag a poster with something the record already holds — the film's title, country, size, year, decade, genre, a cast member, the director, the studio, the franchise or the artist — a note under the box points out that it's already searchable without a tag. It's advice, not a rule: you can still add it, because there might be a good reason.

### Fixed

- **Gallery Columns Left Half Empty**: On public profiles, the masonry gallery let some columns run long while others sat nearly empty, and posters further down wouldn't load until you had scrolled a long way through the blank space. Columns are now filled by the real height of each poster, so the grid stays even and keeps loading as you scroll.
- **Posters Briefly the Wrong Shape**: The first screenful of a gallery drew every poster as a one-sheet, so lobby cards and half-sheets looked stretched until you scrolled or reloaded. Each poster's proportions are now known before it's placed.
- **Stale Profile and Collection Pages**: A caching layer could keep showing an out-of-date public profile or collection for the rest of a session after it had changed. It's gone; pages now refresh when the underlying data does.
- **Pages Overscrolling on Phones**: Pages could scroll past their own bottom edge by roughly the height of the browser's address bar.

### Changed

- **Faster First Load**: Pages now download close to 30% less before they are usable. The world map on your statistics page, the collection table view, error reporting and several other pieces are fetched only when something actually needs them, and the posters at the top of a gallery are requested first so the first row appears sooner.
- **Icons Render Instantly, and Offline**: Icons used to be fetched one by one as pages drew, so they popped in a moment late — and two were quietly rendering as blank squares because the names were wrong. They now ship with the app, so they appear with the page and work with no connection.
- **Keyboard and Screen Reader Access**: Around a hundred cards and tiles that previously only responded to a mouse — poster cards, filter tabs, dashboard shortcuts, tracker cards and more — can now be reached with Tab and opened with Enter or Space, with a visible outline showing where you are. Icon-only buttons, dialogs and search boxes now have names a screen reader can read out.
- **Behind the Scenes**: A broad clean-up of the app's internals and a round of dependency updates.

## [1.5.20] - 2026-09-12

### Fixed

- **Search in the Mobile App**: Searching and browsing your collection in the iOS and Android apps stopped working for a short period today. This update restores it. If the app still shows an error, fully close and reopen it once so it can pick up the update.
- **Newly Added Posters Appearing in Search**: For about ninety minutes today, posters added or edited did not show up in search until we caught it. Everything from that window has been re-synced, so nothing was lost.

### Changed

- **Behind the Scenes**: A large clean-out of unused code and a security review with fixes across the site and the mobile app.

## [1.5.19] - 2026-09-11

### Added

- **Recent Sales, Reported by Collectors**: Every Poster Library entry now has a **Recent sales** section. If you've seen a copy of that exact edition sell, hit **Report a sale** and enter the price, the date and where it sold. Type any venue you like; Heritage Auctions, eMoviePoster, Propstore and eBay are suggested as you go, and common spellings are tidied so they group together. Condition and a link to the lot are optional. Everyone sees the list, five most recent first with the rest a tap away, and once two or more sales in the same currency are in, a low, median and high appear at the top. These are collector reports, not appraisals, and the page says so. You can remove anything you reported; moderators can remove anything.
- **Jumbo Lobby Card**: Added the 14×17 inch Jumbo Lobby Card to the United States size list. Jumbo cards count as lobby cards on the **Lobby Cards** tabs across your collection, the library and your wishlist.
- **Directors Are Links**: The director's name under a poster's title now opens their page, the same as the cast.
- **Posterama Desktop, an Early Companion App**: A desktop app for Windows and Mac that keeps a local copy of your collection so browsing, searching, filtering and stats are instant, and still work offline. It pulls changes from your account rather than editing them, so adding and editing posters stays in the web and mobile apps for now.

### Changed

- **Opening a Poster Feels Like One Motion**: Tapping a poster in your collection or the library no longer flashes a grey box, then a one-sheet-shaped placeholder, then the real image. The picture you tapped travels with you and is already in the frame, at its true shape, while the rest of the page fills in, and on browsers that support it the thumbnail glides into the frame. The buttons at the top no longer pop in and nudge the page either; their places are held from the first frame.
- **Sharper Type, Smaller Download**: The app now uses two typefaces throughout, and the cards generated when you share a poster or profile link match the site instead of using fonts it had dropped. Fewer font files means pages start a little faster.
- **Collection Export Is a Proper Spreadsheet**: The CSV export is now one row per poster with 33 columns, so it opens cleanly, sorts and pivots. Lists like tags and cast sit in a single cell each. Image links are no longer included; an **Own photo** column notes which posters use your own picture.
- **"Also Known As" Starts Small**: The alternate-titles list under About the film shows the two that matter most, the poster's own market title and the original-language title, with the rest behind **Show more**.
- **Clearer Counts on Library Entries**: The Library entry panel now says **Catalogued copies**, since that number counts every copy collectors have added, public and private. The **Collectors** section beneath counts only people with a public copy, so the two can legitimately differ. The Collectors header also says "other collectors" when you own a copy yourself.

### Fixed

- **Flash Along the Bottom of the Poster Viewer**: Hovering the close button on a poster opened from a public profile flashed a thin white line along the bottom edge of the viewer. Gone.
- **Library Entry Panel on Phones**: A long contributor name no longer pushes the **Follow** button onto its own line, and **Suggest changes** no longer overflows the edge of the card.
- **Poster Frame Off-Centre on Phones**: The framed artwork on poster pages sat against the right edge on narrow screens instead of centring. It centres now.
- **Everything Failing for a Minute, Then Fine**: A busy session could suddenly see every request fail for a minute or two, as if Posterama were down. The protection that stops abusive scripts was counting all visitors who reached us through the same network node as one person, so a few heavy pages from anyone nearby could trip it for everyone. It now counts each signed-in collector separately, and each visitor by their own address, and the app no longer re-sends requests that were just refused, which used to keep the block in place.

## [1.5.18] - 2026-09-09

### Changed

- **A New Look for Poster Pages**: The page for a poster in your collection, and the matching page for an entry in the **Poster Library**, have been redesigned from the ground up. The artwork now takes close to half the screen and shows the whole image at its real proportions, so a half-sheet or lobby card gets the same presence as a one-sheet. Behind the title sits a still from the film that fades into the page. The old boxed tables are gone: the poster's facts — type, size with dimensions, country, year printed, condition, storage — sit on one clean row, with details like double-sided or linen-backed tucked under the fact they belong to. On phones the poster fills the width and the rest stacks beneath it.
- **Your Record, in One Place**: Everything only you can see — what you paid, when and where you bought it, your estimated value, and your notes — now lives in a single tinted **Your record** panel with one lock icon, so it's obvious at a glance what's private. Your collections are listed at the foot of the panel, each opening straight to that collection, with an **Add to a collection** button right there.
- **Poster Library Entries Match**: The library page uses the same layout, with a **Library entry** panel showing who contributed it, when, whether a moderator has verified it, how many collectors own and want it, and the **Suggest changes** and **Report a problem** actions together in one place. If you own copies, they're listed as a compact **Your copies** ledger, one row per copy, each opening its record.
- **Actions Moved Up Top**: Edit, Sell, Library entry and Remove now sit together in the bar at the top of the page instead of being scattered down the page. On the library page, **Add to collection** is the one filled button, alongside Edit, Verify and Flag image for those who can use them.

### Added

- **Edit Notes Right on the Page**: Tap the pencil beside **Notes** to write or change your private notes in place — no trip to the full edit form. Ctrl+Enter saves, Escape cancels.
- **Release Titles**: Many posters carry a different title from the one the film is known by. Where the film was released under another name in the poster's own country, it now says so under the title — for example, *Released in United States as The Black Glove* on a US half-sheet for *Face the Music*. The film section also lists every title the film went out under, with the flags of the markets that used it, the original-language title marked, and the poster's own market first.
- **About the Film**: Below your record, a new section pulls in the film's synopsis, tagline, runtime, a scrolling cast strip with headshots that open each person's page, key credits, release date, studio, original title and franchise. TV series show seasons, network and status instead. A rating badge appears where TMDB has enough votes for it to mean something.
- **Other Posters for This Film**: A handful of the other editions the library holds for the same film appear as a row of thumbnails, sized so as many as fit in two rows are shown, with a button through to the full list.
- **Collectors Who Own This**: The library page now shows other collectors with a public copy of the same edition, as name pills that open their profiles. Collectors you follow come first and are marked, and anyone with more than one copy shows a count.
- **Film Details Setting**: If you'd rather the page focus on the poster itself, open **Settings** (the gear icon, or the Settings page in the mobile app) and turn off **Film details**. The synopsis, cast, tagline, runtime and the full list of alternate titles are hidden, and the page tightens up to suit. The backdrop image and the *Released in … as* line stay, since those belong to the poster. It's on by default.

### Fixed

- **Report a Problem Was Unreachable**: The library page had a report dialog that nothing actually opened. It's now the **Report a problem** action in the Library entry panel, and it's disabled once you've already reported an entry.

## [1.5.17] - 2026-08-24

### Fixed

- **Private Posters Were Showing on Public Profiles**: Posters you had marked private were still being listed on your public profile's Collection tab and in the gallery view, visible to anyone — including signed-out visitors. Only the Featured section was filtering correctly. Both now honour the private setting, while you and admins still see your own private posters when viewing your profile. If you have posters you meant to keep private, they are private now.
- **Making a Poster Private Didn't Work**: The Public/Private switch on a poster's own page failed every time with an error and never saved — so posters you thought you had made private were quietly left public. It saves properly now, and your profile updates immediately instead of holding on to the old setting.
- **Treated as a Free Member While Subscribed**: Occasionally a Pro member would suddenly be shown free-account limits — the "Collection Limit: 50 posters" banner and an upgrade prompt — even though everything else worked, and only signing out and back in fixed it. This happened when your sign-in quietly expired: the app couldn't confirm your plan and assumed the free tier. Now, if your session has genuinely expired, you're signed out and asked to sign back in rather than being left in a half-working state. And when your plan simply can't be confirmed, no limits or upgrade prompts are shown at all.
- **Wrong Colours and Unreadable Text**: Some collectors saw the app come up half dark and half light, with text that was unreadable — black on black in places like the search box. This happened when your saved appearance settings differed from the defaults. The app now loads your theme consistently, and it tells the browser which colour scheme it's using so Chrome no longer applies its own darkening on top.
- **Friends List Suddenly Showing Nobody**: Following a collector could make your Following, Followers, Suggested and Leaderboard lists all go empty, as though you weren't following anyone. Collector profiles now load in a single batched request rather than one per person, which was overwhelming the search service, and a list that genuinely fails to load now says so with a "Try again" button instead of pretending you have no friends.
- **Faster Collector Profiles**: The same batching makes profile-heavy pages — the Friends hub, marketplace listings — noticeably quicker to fill in.

### Changed

- **Mini Posters Sort Last**: On a movie or TV show's page, mini posters now always appear at the end of the poster list no matter which sort you've chosen, so the full-size formats you're usually looking for stay at the top. Sorting within the minis still follows your chosen order.

## [1.5.16] - 2026-08-15

### Changed

- **Table View Now Matches the Card View**: The table view of **My Collection** has caught up with the card view. It now shows the same set of tabs — **Prints** and **Incoming** were missing entirely — and every tab carries its poster count, so you can see at a glance how many lobby cards or press books you own without switching views. Flipping between cards and table also keeps you on the tab you were already on; before, it could quietly land you on a different one (**Prints** would become **Lobby Cards**, **Stills** would drop you back to **All**).

### Fixed

- **Posters You Own Marked as "Add to Collection"**: In the **Poster Library**, some posters you already own were showing **Add to Collection** with no **In Your Collection** banner — yet opening the poster showed your copy sitting right there. It hit hardest on pages where you own a lot of what's on screen (searching a favourite artist, say) and on collections with duplicate copies of the same poster, so a handful of cards per page would look unowned. Ownership is now worked out correctly no matter how many copies you own. The same fix applies to the poster lists on movie and TV pages.
- **"Set Up Your Profile" Appearing for Existing Accounts**: Opening the mobile app could occasionally greet you with the profile setup wizard — username, display name, bio — even though your account was long since set up. It happened when the app made its first request before your sign-in had finished restoring, and once the wizard appeared it stayed for the rest of the session. The app now waits for your session before asking the server anything, and a failed request no longer gets mistaken for an empty profile.
- **Faster Label Generation from the Prints Tab**: Generating labels while the **Prints** tab was open loaded your entire collection before picking out your selection. It now only loads the prints.
- **Edge-to-Edge on More Android Devices**: The Android app now uses the full screen on every Android version it supports, not just recent ones. The app download is also smaller.
- **Google Play Subscriptions**: Pro memberships bought through Google Play are now checked against Google's current subscriptions service, keeping renewal dates, expiry and cancellations accurate after Google retired the previous one.

## [1.5.15] - 2026-07-25

### Added

- **Saved Views**: Got a set of filters you come back to again and again — US one-sheets from the 80s, or the lobby cards you keep in flat storage? You can now save that combination by name and bring it back in a click. Set your filters as usual, hit **Save** in the Filters panel, and give the view a name. **My Collection** and the **Poster Library** each keep their own views, and they follow you across devices — including the mobile app. You can also mark one view per page as your **default**, and it'll be applied automatically every time you open that page. Opening a link someone shared still shows exactly what they sent, so your default never gets in the way of a shared view. Free accounts can keep 10 saved views; Pro members get 100.

### Fixed

- **Filter Chips Always Show What's Applied**: The row of filter chips above your posters only appeared after you opened Filters and pressed Apply. When filters arrived any other way — from a bookmarked or shared link, using your browser's back and forward buttons, or from your **Hide Video Game Posters** preference — your posters were filtered correctly, but the chips row sat empty and made it look like nothing was on. The chips now always match what's actually applied.

## [1.5.14] - 2026-07-17

### Added

- **Search by Alternate & Original Titles**: The Poster Library and your Collection now find a film by *any* of its names — its original-language title and its alternate/AKA titles — not just the primary title we show. So a poster catalogued as "Seven Waves Away" now also turns up when you search "Abandon Ship", and foreign films surface under their original titles too. This brings library search in line with what you'd expect from searching the movie database directly.

### Fixed

- **Alphabetical Sorting of Titles Like "Die Hard"**: Films whose title starts with a word that merely *looks* like a foreign article were being filed under the wrong letter — "Die Hard" sorted under **H** ("Hard"), "La La Land" under **L** ("La Land"), "I Am Legend" under **A**. They now sort correctly under their real first letter. Genuinely foreign-language films (like the German "Das Boot") still sort without their leading article, based on the film's actual language — so those land where you'd expect too. Applies across your Collection, the Poster Library, public profiles, and the gallery view.
- **Add-a-Poster Crash for Translated Browsers**: Fixed a crash some collectors hit while adding a poster when their browser was auto-translating the page (common for non-English visitors). The add flow now holds up under page translation.
- **Collection Page Error**: Fixed a rare error that could blank out the collection page for some collectors.
- **Editing Video Game Posters**: Editing a video game poster now shows the correct poster types and sizes, and no longer risks turning it back into a movie poster on save.
- **Video Game Poster Sizes**: Cleaned up the game size list — measurements now show inches alongside metric, the common standard sizes appear in every region (not just the US), and a duplicate entry was removed.
- **Games Search Wording**: The Games tab in search now uses game-appropriate labels instead of the movie/TV/person wording.

## [1.5.13] - 2026-07-05

### Added

- **Video Game Posters**: Posterama now collects more than movie and TV posters — you can catalogue **video game posters** too. Search for a game, open its page, and add (or edit) your poster just like you would for a film. Game entries use a dedicated **Game** poster type and offer sizes suited to where the poster was printed — the standard inch sizes everywhere, plus A-series formats in Europe and B-series in Japan.
- **Filter the Library by Category**: The Poster Library's Filters now include a **Category** option, so you can browse just **Movies & TV**, just **Video Games**, or everything together.
- **Filter Your Collection by Category**: The same **Movies & TV / Video Games** filter is now available in **My Collection**.
- **Hide Video Game Posters**: Prefer to keep things film-only? A new **Hide Video Game Posters** switch in your profile's Browsing Preferences keeps games out of the Poster Library by default — you can always bring them back with the Category filter whenever you like.

### Fixed

- **Cleaner Search Results**: Movie, TV and game search results that don't have artwork now show a tidy placeholder instead of a broken-image icon.
- **Poster Details Tidy-up**: Fixed a stray "0" that could appear on a poster's details popup.
- **Smoother Collection Search**: Searching a collection on a public profile no longer flickers or jumps back to the top of the page as you type.
- **Faster Collection Loading**: Your collection now loads its poster details in a single request, so large collections come up quicker.

## [1.5.12] - 2026-06-30

### Added

- **A Reimagined Statistics Page**: Your collection stats have been completely redesigned. A new cinematic **Story** view scrolls through your collection like a showcase — an interactive world map of where your posters were printed, your collection across the decades, the shape of your taste (genres, directors and cast), condition and value, and standout scores for how it all measures up. Prefer a quick glance? Flip to the new **Cards** dashboard using the toggle in the top-right — it remembers whichever view you prefer. Along the way you'll find richer breakdowns than before: a full genre ranking, every format and size you own, a paid-versus-current value comparison, and Vintage, Grade and Eclecticism scores that capture your collection's character.
- **Interactive World Map**: The new map brings your collection's origins to life — hover any country to see its poster count and rank, watch posters stream in to the places you collect, and click through to browse that country. Even former countries like Yugoslavia get their own markers, so every part of your collection is on the map.

### Changed

- **Refined Public Profile Viewer**: Opening a poster on someone's public profile now shows a cleaner, catalogue-style layout.
- **Home Page Refresh**: The home page has new showcase sections that bring collections and grid trackers to life.
- **Sharper Share Previews**: Links you share now generate better-looking preview images.

### Fixed

- **Images Load on More Networks**: Posters now load reliably on VPNs and networks that previously blocked our image host — they're served from our own image domain.

## [1.5.11] - 2026-06-27

### Changed

- **Incoming Posters — Attach to an Existing Library Entry**: When an incoming poster arrives and you tap **It arrived**, posters matched to a movie now let you attach to an existing library entry for that title instead of always creating a brand-new one. You'll see the existing entries for the movie and can pick one, or still choose to create a new entry as before. Either way, the condition, price, storage, tags, and other details you captured when you logged the incoming poster carry over automatically.

### Fixed

- **More Reliable Updates**: Fixed an issue that could occasionally cause the app to reload unexpectedly.

## [1.5.10] - 2026-06-25

### Fixed

- **Private Profiles Look Right**: Visiting a collector who has set their profile to private now shows a clear "This profile is private" message instead of a generic error screen.
- **Stay Signed In Reliably**: Fixed an issue where the app could get stuck thinking you were still signed in after your session had quietly expired — flooding the app with errors and sometimes forcing you to open a fresh tab to recover. The app now notices an expired session and returns you to sign-in cleanly, and signing out fully clears your session right away.

## [1.5.9] - 2026-06-19

### Added

- **Sort Your Grid Tracker Rows**: A new sort button on a grid tracker lets you reorder the movies on the fly — by title (A–Z or Z–A), release year (oldest or newest first), or how complete each row is (most or least complete first). It's great for jumping straight to the titles you're closest to finishing. Sorting only changes how the grid is shown to you and doesn't alter your saved layout.

### Fixed

- **Large Grid Trackers Now Load Reliably**: A grid tracker covering a large number of movies could fail to load its ownership data and come up empty. Big trackers now load correctly.
- **Grid Tracker Page No Longer Crashes**: Opening certain grid trackers could show an error screen instead of the grid. They now open as expected.
- **Editing Crew-Based Grid Trackers Shows Every Title**: When editing a grid tracker built from someone's crew work (a producer, director, writer, etc.), the movie list only showed the handful of films they appeared in on screen instead of their full filmography. Editing now shows the same complete list you saw when you created the tracker.
- **Grid Trackers With No Owned Posters Yet**: A tracker whose poster-type columns are discovered from your collection used to show a completely blank page until you owned at least one matching poster. It now lists all its movies right away, with a note that columns will appear as you add posters.

## [1.5.7] - 2026-06-18

### Added

- **Incoming Posters (Pro)**: Bought a poster that's still on its way? You can now log it the moment you buy it — capture the movie, poster type, size, condition, price, where you got it, and an expected-arrival date — and it lands on a new **Incoming** tab in your collection so nothing slips through the cracks while you wait. When the package arrives, tap **It arrived**, add your photo, and it's promoted into your collection as a full entry. Incoming items are tracked separately and don't count toward your collection totals until they're in hand.

### Changed

- **New Add Menu**: The **+** button in the top bar (desktop and mobile) now opens a quick menu to either add a poster you already own or log an incoming one.
- **Updates Apply Sooner**: New versions of the app now show up when you return to it after a break, instead of only after fully closing and reopening it.

### Fixed

- **Privacy Toggles Show Your Real Setting**: The "Make my profile public" and "Make my poster collection public" switches could appear on even when your account was actually set to private — so you couldn't tell your true setting at a glance. They now always reflect your real setting, and saving no longer risks flipping you public by accident.

## [1.5.5] - 2026-06-15

### Added

- **Friends & Following**: You can now follow other collectors and keep up with what they're adding. The new Friends hub has Following, Followers, an Activity feed of recent posters from collectors you follow, and a Leaderboard — plus a "Suggested for you" strip that recommends collectors followed by people you already follow.
- **Recommended for You**: A new discovery page that surfaces poster types drawn from the genres you collect most, so it's easier to find more of what you love.
- **Collector Regions**: Your profile can now show your region, making it easier to connect with collectors from the same part of the world.
- **Age Verification**: Added an 18+ age check to comply with new app-store age-assurance requirements.

### Changed

- **Cleaner Public Profiles**: Public profile pages now have an option of a more compact, polished header that keeps the collection front and center.
- **Notification Settings Shortcut**: The settings gear in the notifications panel now takes you straight to your Email Preferences.
- **Sharper Poster Images**: Improved image processing for cleaner, better-looking poster artwork across the app.

### Fixed

- **Clearing Notifications Now Asks First**: The "clear all" button in the notifications panel used to wipe everything instantly — it now asks for confirmation so you can't lose your notifications by accident.
- **Notifications Panel on Mobile**: On phones the panel could only be closed by tapping "View All Notifications". It now has a working close button and dismisses normally.
- **Updated Poster Images Everywhere**: Fixed cases where a newly approved poster image didn't appear consistently across cards and detail pages.
- **Print Submission Details**: Edition number and print-run details entered when submitting a print update are now saved correctly.

## [1.5.3] - 2026-05-31

### Fixed

- **Mobile App Stability**: Restored reliable background subscription syncing and behind-the-scenes error reporting in the mobile app, and improved compatibility with older Android devices.

## [1.5.2] - 2026-05-31

### Fixed

- **Exclude Filters in the Poster Library**: The Include/Exclude toggle on filters now works when browsing the Poster Library — switching a filter to Exclude correctly hides those results (e.g. Type · Exclude · "Theatrical Final"). Previously it only took effect in My Collection.
- **Updated Poster Images Now Show Everywhere**: When a new poster image was approved, the detail page would show the new artwork while the Poster Library card sometimes kept showing the old one. The thumbnail and the full image now stay in sync. Posters affected by this in the past have also been corrected.
- **Android App Icon**: Refreshed the Android home-screen icon so it no longer shows a faint purple edge and sits cleanly within the icon shape.

## [1.5.1] - 2026-05-30

### Added

- **Include / Exclude Filters**: Every filter now has an Include/Exclude toggle — Country, Size, Type, Condition, Decade, Genre, Director, and Storage. Flip it to Exclude and your results show everything *except* what you picked (e.g. Size · Exclude · "Mini" shows every size but mini). Excluded picks appear as red outlined chips, and the choice is saved in the page link so it survives reloads and shareable URLs. Works across My Collection, the Poster Library, and admin poster management.
- **Size Dimensions on Poster Type Pages**: The poster type detail page now shows the actual measurements (e.g. "27×40 inches") in small text right under the size name, matching the size chips used elsewhere in the app.

### Changed

- **Truer Poster Colours**: Uploaded scans that carry an embedded colour profile (like Adobe RGB) are now converted to standard sRGB when processed, so the re-saved images render with more accurate colour in browsers.

### Fixed

- **New Accounts Stuck on Onboarding**: Some brand-new users were trapped on the "set up your profile" step even after their profile had been created. Signup now completes cleanly the first time.
- **Watchlist "Ending Soon" Alerts**: The 24-hour and 1-hour auction-ending notifications for items on your watchlist had quietly stopped sending. They're working again.
- **Poster Type Pages Occasionally Failing to Load**: An intermittent database hiccup could make a poster type page error out and drop its "collectors / wishlists" counts. The connection is now kept alive and the counts fall back gracefully instead of taking down the page.
- **Edits Now Show Up Immediately**: Editing, reassigning, or merging a poster type now refreshes everyone's collection right away, instead of leaving the old title, artwork, or size showing for up to 15 minutes.
- **Duplicate Poster Types**: Closed a gap that could let a duplicate poster type slip through right after one was created or deleted for the same movie.
- **Achievements Reflecting Changes Right Away**: Choosing a showcase achievement now updates immediately instead of occasionally showing your previous selection.
- **Removed Movies No Longer Break Pages**: When a movie has been removed or merged on the movie database, affected pages now carry on gracefully instead of erroring, and the app stops needlessly re-checking entries it already knows are gone.

## [1.5.0] - 2026-04-29

### Added

- **Type Counts on Collection Tabs**: The Posters / Prints / Lobby Cards / Press Books / Stills tabs on your Collection, the Poster Library, and public profile pages now show the number of posters in each category right next to the label (e.g., "Posters · 87").
- **Type Counts on Wishlist Tabs**: The same per-type counts now appear on Wishlist tabs so you can see at a glance how many of each format you're hunting for.
- **Filter by Type on Public Profiles**: You can now filter another collector's public collection by poster type using the same tab strip you see on your own collection. Tab choice is saved in the URL so links like `/user/someone?type=lobbyCards` take you straight to that slice — great for sharing a specific subset of a collector's collection.
- **Dynamic Share Previews**: Sharing a link to a poster, a poster type, or a collector's public profile on social media or in messaging apps now shows a proper preview image generated on the fly — including the poster artwork, title, and framing. Works for poster types, user posters.
- **Poster Size Dimensions Visible Everywhere**: Hover any size chip on a poster card to see the actual dimensions (e.g., "27×40 inches (69×102 cm)"). On the poster detail page, dimensions appear in smaller text right under the size name so you don't have to look it up.
- **Italian 6 Fogli Size**: Added "6 Fogli" (55×118 inches / 140×300 cm) to the Italian poster size options.
- **Grid Tracker Lobby Card Linking**: Clicking a lobby card cell on a grid tracker now drops you into your collection filtered to that movie's lobby cards, so you can review what you've got at a glance.
- **Auto-Load on Movie/TV Poster Picker**: When picking a poster type on a movie or TV detail page, additional results now load automatically as you scroll instead of needing to tap a "Load More" button.
- **Smarter Sort on Movie/TV Poster Picker**: Sorting by year now keeps US versions grouped together first, then alphabetical by country, then by size — so the same year reads as a clean list of variants instead of jumping around. Country and Size sorts get the same secondary-sort treatment, and Size now follows the natural order of the poster-types list (One-Sheet, Insert, Half-Sheet…) rather than alphabetical.

### Changed

- **Faster First Load for Public Pages**: Public profile pages, poster type pages, and legal pages now render on the server for noticeably faster first paint and proper share-link previews. Navigation between routes keeps the sidebar and layout in place instead of flashing.
- **Snappier Page Loads**: Font preloading, better bundle splitting, and vendor separation cut down on layout shift (things jumping around while the page loads) and get content in front of you sooner.
- **Bigger Share Preview Images**: The poster image inside shared link previews now renders larger and cleaner across Slack, iMessage, Discord, and other platforms.

### Fixed

- **Year Field When Cataloguing a New Poster Type**: Adding a new poster type through "Add to Collection" or the sell flow now auto-fills the Year field from the movie's release year. This had been silently blank since mid-April.
- **Duplicate "Lobby Card" Size Option**: The Size dropdown on the Add Poster Type form showed "Lobby Card" twice for US and some other countries; now appears once.
- **Feedback Button Wording on Order Detail**: Sellers viewing a completed order now see "Leave feedback for buyer" (previously always said "for seller" regardless of which side you were on).
- **Modal & Lightbox Direct Links**: Deep links to poster lightboxes now close cleanly, and mobile drawer swipe-to-close is restored. Modals opened via URL also dismiss correctly.
- **Sidebar Flash on Navigation**: The sidebar no longer briefly disappears when moving between pages.
- **Profile Page Layout Shift**: The logo, fonts, and profile photo no longer cause the page to jump around as they load.
- **Collection Rankings Page Was Blank in Production**: The leaderboard at `/stats/rankings` was returning no collectors. Fixed.
- **Mobile App Showed Contributor IDs Instead of Names**: On the poster type detail page in the Android/iOS app, the "Contributed by" field showed a short user ID instead of the contributor's display name and avatar. Fixed.
- **Poster Detail Page 500 Error**: An occasional Firestore hiccup while computing the "X collectors / Y wishlists" stats could fail the entire poster type detail page with a server error. Counts now degrade gracefully to 0 instead of taking down the page.
- **Add to Collection Scroll Position**: After creating a brand-new poster type and being moved to the "Add to Collection" step, the page now scrolls back to the top instead of leaving you stranded mid-form.
- **Add Success Page Sometimes Showed Blank Info**: An intermittent timing issue caused the "Poster added!" confirmation to occasionally show empty title/country/size info. Fixed across Add to Collection, Profile, and other navigation hand-offs.
- **Wishlist Tabs Crashed When Switching**: Switching between Posters / Lobby Cards / etc. on the Wishlist could throw a "Rules of Hooks" error and bounce you to an error page. Fixed.
- **Poster Library Scroll Restoration**: Returning to the Poster Library from a detail page now reliably puts you back where you were instead of jumping to the top.
- **Public Profile Tab Scroll**: Switching tabs on someone's public profile no longer scrolls the page back to the top mid-browse.
- **User Profile Setup**: Onboarding completion is now correctly tracked when a profile is created, so you won't be re-prompted to onboard after signing up.

## [1.3.26] - 2026-04-11

### Added

- **Wishlist Removal on Add**: When you add a poster to your collection that's on your wishlist, the success page now offers a quick "Remove from Wishlist" button so you can keep your wishlist up to date without extra steps.
- **Profile Photos in Public Profile Modal**: When viewing a poster on someone's public profile, the detail modal now shows profile photos for cast, director, and autograph credits.
- **Search Qualifiers**: Narrow your search to a specific field using prefixes like `movie:laura`, `actor:tom hanks`, `director:spielberg`, `artist:drew struzan`, and more. Works across My Collection, Poster Library, Wishlist, and Marketplace. A dropdown menu in the search bar shows all available options.
- **Expanded Wishlist Search**: Wishlist search now covers country, genre, director, artist, size, and type — previously only title and notes were searchable.

### Changed

- **Improved Poster Detail Layout**: Genres now appear above the director credit on poster detail pages for a more natural reading flow.

### Fixed

- **Consistent Card Styling**: Wishlist cards now match the Poster Library's visual style — same button design, icon treatment, and layout for a more polished, consistent experience across the app.
- **Data Preservation on Updates**: Fixed an issue where editing a poster or other items could unintentionally clear certain fields. Updates now preserve all existing data correctly.
- **Missing Poster Fields**: Several poster details (artist, decade, signatures, and more) now load correctly from search results, fixing cases where some information wasn't appearing on cards or detail views.
- **Public Profile Sort Order**: Sorting by release year on public profile and gallery pages now groups posters correctly — same year, then alphabetical by title, then lobby card order — matching the My Collection sort behavior.

## [1.3.23] - 2026-04-08

### Changed

- **UI Framework Upgrade**: Upgraded the core UI framework to the latest major version, bringing improved performance, accessibility, and rendering across all pages.
- **Dependency Updates**: Updated several backend and frontend libraries for improved stability and security.

## [1.3.22] - 2026-04-03

### Added

- **German A2 Poster Size**: Added A2 (16.25×23.25 inches / 42×60 cm) to the German poster size options.

## [1.3.21] - 2026-03-31

### Fixed

- **Faster Collection Page Loading**: The Collection page now loads poster details in a single batch request instead of fetching each one individually, significantly reducing load times for large collections.
- **Faster Wishlist Page Loading**: The Wishlist page now batch-loads poster type details instead of making a separate request per card, dramatically improving performance.

## [1.3.20] - 2026-03-28

### Added

- **Smart Cascading Filters**: Filter dropdowns in My Collection and Poster Library now dynamically update based on your selections. Selecting a country narrows the available sizes, decades, genres, and more to only valid combinations — with live counts showing how many posters match each option.
- **Per-Filter Clear**: Each filter section now has a "Clear" link so you can reset one filter without clearing them all.
- **Scroll Indicator on Filter Dropdowns**: Dropdowns with more options than visible now show a "more" hint at the bottom that disappears when you scroll to the end.
- **Poster Library Filter Counts**: Filter options in the Poster Library now show counts next to each option, matching the My Collection experience.

### Changed

- **Faster Search & Stats**: Significant performance improvements across the app. Dashboard stats, collection rankings, grid trackers, and achievement calculations all load noticeably faster through batched search queries.

### Fixed

- **Achievement Card Dates**: Achievement cards now show when your current tier was reached, not when the achievement was first unlocked. Hover to see the exact date.
- **Genre Filter**: Fixed an issue where filtering by genre could return incorrect results.

## [1.3.19] - 2026-03-22

### Added

- **Edition & Print Run on Poster Cards**: Print posters now display their edition number and print run inline on the card (e.g., `Print · #24 / 230`). If no edition number is set, the total print run is shown instead.
- **Linen Backed & Double Sided on Poster Cards**: User poster cards now display "Linen Backed" or "Double Sided" inline next to the poster type name when applicable.

### Removed

- Removed unused legacy `PosterCard` component (replaced by `UniversalPosterCard`).

## [1.3.18] - 2026-03-22

### Added

- **Prints Tab in Poster Type Selector**: When adding a poster to your collection, the poster type selector now includes a dedicated Prints tab for easier browsing alongside Posters, Lobby Cards, Press Books, and Stills.

### Fixed

- **Print Edition Number Not Saving**: Fixed a bug where the edition number was not saved when initially adding a print to your collection. The value would only persist after going back and editing the poster.
- Updated Large Paper Banner dimensions to 24x82 inches (61x208 cm).

## [1.3.17] - 2026-03-21

### Added

- **Paper Banner Poster Sizes**: Added Small Paper Banner (5x25 inches) and Large Paper Banner (Various Sizes) under US poster sizes.
- **Lobby Card Tag Suggestions**: When adding or editing a lobby card poster type, suggested tags (Title Card, Card #1 through Card #8) now appear as clickable chips for quick tagging.
- **Re-release Tag Suggestion**: When the poster year differs from the movie's original release year, a "Re-release" tag suggestion automatically appears.

### Fixed

- Fixed tag spacing on poster cards.

## [1.3.16] - 2026-03-20

### Added

- **Storage Condition Filter**: Added a new Storage filter to the My Collection page. Filter your posters by storage method (Rolled, Folded, Tri-folded, Flat) with facet counts showing how many posters match each option. Filter state is preserved in the URL.

## [1.3.15] - 2026-03-16

### Changed

- **Poster Library Contributions**: The "contributed by" label on poster type cards is now only visible to premium subscribers.
- Restored the "In Your Collection" banner on movie and TV detail pages.

### Fixed

- Fixed an issue with Grid Trackers where person-based trackers (e.g., Steven Spielberg) could return incorrect results.
- Minor Typesense service fix for collection queries.

## [1.3.14] - 2026-03-14

### Fixed

- **Manage Subscription**: Fixed an issue where clicking "Manage Subscription" on the billing page could fail to open the Stripe billing portal.
- **Mobile App Stability**: Fixed a crash that could occur on older Android devices when viewing pages with formatted text content.
- **Collection Page Stability**: Fixed an intermittent error that could occur when browsing your poster collection.

### Performance

- **Faster Poster Library**: Reduced the number of API calls when browsing the Poster Library, resulting in faster page loads for logged-in users.

## [1.3.13] - 2026-03-11

### Added

- **Poster Library Stats Tab**: New Stats tab in the Poster Library showing a visual breakdown of the collection by decade, country, type, and genre. Click any stat to filter the library to that category.
- **Prints Tab**: Added a dedicated Prints tab to both the Poster Library and My Collection pages for easier browsing of print-type posters.
- **Wishlist Count on Poster Type Detail**: Poster type detail pages now show how many users have the poster on their wishlist, alongside the existing collectors count.
- **Clickable Movie Titles in Gallery Lightbox**: Movie titles in the gallery lightbox now link directly to the movie or TV show detail page.

## [1.3.12] - 2026-03-08

### Changed

- Removed unused dependencies to reduce bundle size.
- Various package updates (MUI 7.3.9, Sentry 10.42, ESLint 10.0.3, Typesense 3.0.2, and others).

### Fixed

- Fixed user matching on public profile pages not returning correct results in some cases.

## [1.3.11] 2026-03-02

### Added

- Added the ability to feature upto 12 posters at the top of your public user profile page.

## [1.3.10] 2026-02-26

#### Fixed

- Fixed issue with gallery view introduced in 1.3.9

## [1.3.9] - 2026-02-21

### Added

- **Wishlist Search, Sort & Filtering**: The wishlist page now supports full-text search, sort options, and tab-based filtering by poster category (All, Posters, Lobby Cards, Press Books, Stills). Search and filter state is preserved in the URL for shareable links and back-button support.

### Fixed

- Fixed incorrect missing cards count on the incomplete lobby cards tracker. Sets with a mix of numbered and unnumbered cards were undercounting the total missing.
- Fixed page flash/layout issues.
- Mobile profile page improvements.

## [1.3.6] - 2026-02-12

### Added

- Profile image cropping support when uploading or editing profile pictures.
- Japanese B4 poster size.

### Fixed

- Image rotation issue on server for profile images.
- Cache invalidation improvements for more reliable data freshness.

## [1.3.5] - 2026-02-06

### Fixed

- Fixed image rotation issues on mobile apps.

## [1.3.1] - 2026-02-06

### Added

- **Double Bill / Multi-Movie Poster Support**: Posters that feature multiple movies (double bills, triple features, combo posters) are now fully supported. When adding or editing a poster type, you can search for and attach up to 5 additional movies. Multi-movie posters display all featured titles on poster cards, detail pages, and public profiles, and are fully searchable by any of the featured movie titles.

### Fixed

- Fixed double bill posters not appearing in search results when searching by any of the featured movie titles.
- Fixed double bill posters not displaying correctly on public profile pages and gallery lightbox.
- Fixed footer overlapping content on some pages.

## [1.3.0] - 2026-02-03

### Added

- **Incomplete Lobby Cards Tracker**: A new built-in Quick Start template that automatically finds movies in your collection with incomplete lobby card sets and displays them in a tracker grid.
- **Emoji Picker for Trackers**: The tracker create and edit forms now include an emoji picker for the icon field, matching the collection form behavior.
- **Crew Role Filter**: When creating a person-based tracker, you can now filter by Cast or Crew roles. The Crew filter includes all behind-the-scenes credits (director, producer, writer, editor, cinematographer, composer, etc.), not just directing credits.

### Changed

- **Grid Trackers Open to All Users**: Grid Trackers are no longer a beta feature — they are now available to all users without requiring access grants.
- **Tracker Cards Redesigned**: Tracker cards on the list page are now displayed in a compact grid layout (up to 3 columns) instead of full-width rows.
- **Trackers Default to Public**: New trackers are now public by default instead of private.
- Removed tracker access toggle from the admin User Management page.
- Renamed role filter labels from "Actor (Cast)" / "Director (Crew)" to "Cast" / "Crew" for clarity.

### Fixed

- Fixed horizontal scrollbar appearing in tracker create/edit dialogs when clicking into filter fields.
- Fixed emoji picker button overlapping the icon field label in tracker dialogs.

## [1.2.30] - 2026-01-31

### Added

- **Premium Subscriber Badges**: Premium subscribers now display a badge on their public profile and in the app header.
- **Grid Tracker Mobile Support**: Grid Trackers are now accessible from the mobile app navigation drawer. 

### Fixed

- Fixed RevenueCat subscription status not syncing correctly on mobile.
- Fixed lightbox on public profile and public wishlist pages missing zoom/pan functionality. The fullscreen image viewer now matches the collection and poster library behavior with pinch-to-zoom, scroll-to-zoom, and pan support.

## [1.2.29] - 2026-01-26

### Added

- **Grid Tracker TV Show Support**: Grid Trackers now support TV shows in addition to movies. Create grids based on an actor's TV appearances or a director's television work.
- **Grid Tracker Artist Filtering**: Filter your grid tracker by poster artist. See which artists have created posters for films in your grid and filter to show only posters by specific artists.
- **Grid Tracker Exclusions**: Exclude specific movies or TV shows from a grid. Useful for removing short films, documentaries, or other entries you don't want to track.
- **Japanese STB Tatekan 2-panel Size**: Added new Japanese poster size option (20×57 inches / 51×145 cm) for the tall Tatekan format.

### Changed

- **Lobby Card Sorting**: When sorting your collection or the Poster Library by title, lobby cards now sort in proper order: Title Card first, followed by Card #1, Card #2, etc. Previously, lobby cards for the same movie would appear in arbitrary order.

### Fixed

- Actor search now works correctly on TV show pages. Previously searching for an actor from a TV show page would not return their TV appearances.
- Improved sorting behavior on public profile collection pages.
- Fixed grid tracker column count display issues.
- Fixed floating selection bar sometimes appearing behind the footer when selecting multiple posters.
- Fixed grid tracker lobby card tooltip showing incorrect count when a card has both "Title Card" and "Card #1" tags.

## [1.2.28] - 2026-01-25

### Added

- **Image Rotation**: You can now rotate images when adding or editing posters. After uploading an image, rotation controls appear allowing you to rotate the image 90 degrees left or right. Rotation is applied server-side for consistent results across all platforms.

### Fixed

- Fixed duplicate key warning in SignatureSelector when the same actor appears multiple times in the cast list (playing different characters).

## [1.2.27] - 2026-01-24

### Added

- **Grid Trackers (Beta)**: A new way to visualize and track your poster collection progress. Create custom grids based on a director's filmography, actor's movies, or movie franchises. Track which posters you own across different formats (One-Sheet, Insert, Lobby Card, etc.) in a visual grid layout. *This feature is currently in beta and not available to all users.*

## [1.2.26] - 2026-01-15

### Added

- **"In Your Collection" Banner on Movie/TV Pages**: When browsing poster types on movie or TV show detail pages, posters that are already in your collection now display an "In Your Collection" banner, matching the behavior in the Poster Library.

## [1.2.24] - 2026-01-10

### Added

- **Search Your Collection by Production Company & Franchise**: The production company and franchise search features (introduced in 1.2.19) now work on your personal poster collection, not just the Poster Library. Search your own posters by studio (e.g., Studio Ghibli, Pixar) or movie franchise (e.g., Star Wars Collection, MCU).

### Changed

- Various package updates for improved stability and security.

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
