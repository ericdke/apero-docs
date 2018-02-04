## 1.7.6 (27) - 2018-01-28 - 'The Prowler'

Fixes:

- Fixed and simplified the drafts system
- Fixed keyboard shortcuts for configurations such as Dvorak, Colemak, etc 

Improvements:

- If necessary, Apero adds a thread icon to an already downloaded post that just received a reply
- Complete list of users reposting a post is available as a tooltip on the "Reposted by" label

New:

- Crosspost from a chatroom to Global
- Option for rounded (default) or squared avatars
- In the main timeline, force refresh by pulling from the top (only with trackpad)

## 1.7.5 (25) - 2018-01-05 - 'Johnny Jane'

New:

- Play the videos posted by ChimPnut

Improvements:

- Buttons in profile are grey when disabled
- Fixed a possible crash when closing a window just before posting
- Close compose windows with CMD-W or window's red button

## 1.7.3 (23) - 2017-12-15 - 'Speed Racer'

Fixes possible issues related to logout and login.

## 1.7.2 (22) - 2017-12-08 - 'Captain Caveman'

New:

- Explore posts by new users (users with less than 50 posts)
- Channels show their default avatar, when available, instead of the first user's avatar
- Right-click on a channel to set a default avatar if you have full rights (non-PM only, and you need pnut storage)
- Right-click or Swipe on a channel: mark as read (see Preferences)
- Right-click on a channel to unsubscribe
- Jump to a post by its ID

Improvements:

- You can now edit Markdown links in your profile description
- The "Compact channels list" menu displays "Compact" or "Expand" depending on current state
- Fixed display glitches when resizing then closing then reopening a Send Message window
- Fixed a possible crash if posting and closing a window at the same time
- Smaller memory footprint

## 1.7.0 (19) - 2017-10-07 - 'Wolfen'

New:

- Dynamic timelines!

If you delete or edit a post with another client, Apero will reflect the changes in its windows!

Delete a post with ChimPnut, and Apero also removes it. Edit a post with Broadsword, and Apero updates the content of the post in its timeline! Dynamic deletion also applies to PMs and channel messages.

- Share/download a file from your pnut storage! 

Get a short link, embed in a post/message or save to local disk.

- Show "verified" icon. In posts/messages next to the avatar (option, default: on) and in Profile.

- You can now cycle through buttons in the Profile window with TAB and activate the current selection with SPACE.
- Using TAB in the Preferences window cycles through the preferences tabs.
- Using TAB in the main streams window cycles through the streams.
- Hitting TAB once in other posts/messages windows+ focuses on the list, allowing selection of cells with keyboard.
- Clicking once in the text body of a post/message also focuses on the list and selects the cell.

- There's an option in Preferences to highlight the post/message selection (default: off), which also enables lots of new keyboard shortcuts for the selected item (see details in the FAQ).

- The Interactions window now groups users who made the same action simultaneously (example: users @a and @b reposted the same post at the same time).

- The "Hide deleted posts/messages" option has been removed (deleted posts/messages are now always really deleted from local memory).

Other improvements and fixes:

- If you post with another client, your post will be also editable in Apero.
- The "Message to..." window now resizes vertically like the other "New post" and "New message" windows.
- The "Open image" context menu now also shows-up for non-oembed images (simple links).
- Better error handling if the pnut.io server disconnects while Apero is running. Also improved handling of network related issues in general.
- Better handling of GIFs in posts when the user has clicked on the image to enable/disable the animation.
- Fixed an issue where the autocompletion for usernames could fail because of complex Unicode characters in the text.
- Fixed a bug where the Interactions window could crash the app if closed while loading data.
- Opening Patter links in Apero now also works with short URLs.
- Better support for d.pr images in the timeline (using direct url when available).
- The pnut files manager now downloads more older files when scrolling to the bottom, if available.
- Fixed an animation error when scrolling to last post seen at launch which could cause avatars of two adjacent users to be swapped.


## 1.6.0 (16) - 2017-09-02 - 'The Dance Of The Bees'

### New feature: search! 

- Search for posts

From the "Search" menu. Example: "apple" will find all posts containing the word "apple". Or "apple mac" to find all posts containing the word "apple" *and* the word "mac".

- Search for posts by a user
 
From a user profile, search keyword(s) which will only show posts created by this user. Also accessible via right-click (context menu) on posts lists and users lists.

- Search for messages in a channel

From an opened channel, righ-click on a message and select "search" in the context menu to search for messages with keywords in this channel. 

- Search for users
 
From the "Search" menu. Example: "pnut" will find all users whose description *or* name contains the word "pnut".

### Other updates

- Added a new option: open posts.pnut.io links in Apero. If a post or message contains a link like "https://posts.pnut.io/postnumber" or "posts.pnut.io/postnumber" and the option is on, the post will be opened directly in Apero (if the option is off, the link will be opened in a browser as usual).
- Added a right-click/control-click context menu in users list to open the user profile (in addition to the existing double-click method).
- Fixed: the title bar of the users list windows was not the same as other windows.
- Fixed: subscribing to a channel could previously fail to open the channel window when the subscription was successful if subscribing right after launching.
- Fixed: unsubscribing from a channel didn't show if the operation was successful.
- Fixed: some text input windows could fail to be closed properly in some rare cases.
- Fixed: opening some patter links in-app could sometimes bring up the subscription dialog even if the user was already subscribed to the channel.
- Fixed: the value of the polling interval for messages was not always saved from Preferences.

## 1.5.1 (15) - 2017-08-22 - 'Technicolor'

- Fixed the inactive color panels in Preferences

## 1.5.0 (14) - 2017-08-21 - 'Apocalypse, baby'

- Image upload! You can now use your pnut.io storage to upload images and gifs in your posts and messages with Apero.
- Translate! a post in Apero or in browser. Automatic language detection or manual selection.
- Icons! instead of text for these buttons: Global, Home, Mentions, New post, New message, Refresh List.
- Themes! Save and recall your custom set of colors for Apero's interface. Includes a list of default themes.
- When replying, Apero can now insert the text cursor after the leading mention or after all mentions (default: after leading).
- Most right-click actions are now also available for swipe actions. Select your favorite ones in Preferences.
- The Preferences window now uses tabs to separate categories (Theme, Interface, Streams, Other).
- The Interactions window now polls for new items regularly.
- The username completion popup now uses the same theme (dark/light) as the other windows.
- No duplicate writing boxes. Apero enforces that a new writing box cannot be created if the existing one is still opened.
- The pnut.io login page has been simplified and Apero's login window has been adapted to the new layout.
- Added accessibility labels for most of the app controls.
- Added an "open image" item in the context menu when the message/post has an image. Alternative to double-click.
- Fixed: in some cases, GIFs could fail to be released from memory when closing a window.
- Fixed: a user profile could be downloaded twice instead of once when clicking on a mention.
- Fixed: control-click wasn't available as a replacement for right-click to call the context menu.
- Fixed: the avatar tooltip doesn't show the follow status anymore if the user is yourself.
- Fixed: disabling "Timeline sticks to top" still sticked the timeline to top for some users.

## 1.4.2 (12) - 2017-06-24 - 'Beluga'

- New: Macbook Pro Touch Bar support
- Added an option to ignore system-wide Dark Mode changes

## 1.4.1 (11) - 2017-06-12 - 'Vatanen'

- Fixed: lag when scrolling the timelines. It's now blazing fast!
- New: menus and shortcuts to change the font size and to switch UI mode
- Fixed: blurry text in the Interactions window
- Fixed: get Interactions for a reposted post
- Fixed: vertically resizing the followers/followings windows
- Fixed: height of description text in profile window for logged-in user

## 1.4.0 (10) - 2017-06-06 - 'Xenomorph'

- New option: dark mode
- Saving drafts now work for posts, replies and messages
- New available fonts: Hack, Letter Gothic, Luminari, Optima
- Better rendering of fonts in the timelines
- Optimized image caching and memory management
- Edit Name, Edit Description and Search Chat With User dialog boxes are no longer modal
- The "About" window respects the app's theme and behavior and has custom title art
- Fixed: login window behavior if Apero was relaunched several times in a row (issue related to cookies)
- Fixed: where older messages sometimes could not load after scrolling to the bottom of a chat
- Fixed: where clicking in the Search window's text field could trigger a color change in Preferences (issue related to the persistent color panel)
- Right-click or swipe on a channel to open it (alternatives to the usual double-click)
- General improvements (more background threads, more GPU acceleration, faster algorithms, smaller memory footprint)

## 1.3.2 (8) - 2017-05-12 - 'Generations'

- Fixed the login window for macOS 10.11

## 1.3.1 (7) - 2017-05-08 - 'Bubble Bobble'

- The pnut.io authorization page now continues to work properly even after having entered wrong credentials in previous login attempts (this fixes the issue reported in a recent review). There's also a button to go back to the authorization forms if the user has navigated elsewhere before authorizing Apero.
- New "Interactions" window: from menubar (for the logged-in user) or contextual menu (for a post). This lists who followed/unfollowed you, who replied to your posts, bookmarks activity, etc.
- New Explore menu: "Lonely posts". An always different collection of posts which didn't spark conversations, but could/should have.
- New channels list layout with mini avatars of the channels owners, improved readability, and an option to display in normal mode (with details and preview of the last message for each channel) or compact mode (without any details).
- New option to hide posts that are tagged #NSFW, or are programmatically marked as such without using the tag.
- New option: "directed posts". When the option is on (by default), the Home timeline includes all posts from the users you follow, including the posts directed to users you don't follow.
- The "More..." button has been replaced by automatic fetching of older posts/messages when the user scrolls to the bottom of the timeline.
- Loading more older items is now also available for Explore streams, Channels list, and users lists.
- Handling of the images/gif in memory and caching them on disk has been improved. You can also customize the cache expiration values.
- Fixed the bug where the same Explore window could be opened several times - these windows are now unique.
- Fixed a bug where interface elements could be clipped when the vertical scroller is visible.
- Fixed a bug where the profile window didn't update its values when following/unfollowing another user.
- Fixed some rare issues in the handling of hidden posts/messages.
- Fixed the issue of the avatars in the followers/followings lists not being rounded.

## 1.2 (5) - 2017-04-20 - 'The Rainbow Warrior'

- Fixed: color panel from preferences window

## 1.1 (4) - 2017-04-15 - 'The Fisher King'

- New: click once on a gif to pause/play
- Fixed: crash when opening channels/messages window after API update
- Fixed: bookmark/repost a reposted post
- Fixed: "Reposted by" label content and truncation
- Fixed: UI glitches when using color panel from preferences window
- Improved: memory management (images/gif caching and other optimizations)
- Improved: timeline behavior after sleep/wakeup/close
- Improved: more usernames available in the completion list

## 1.0.3 - 2017-04-02 - "The Day After"

- New: search for an existing private conversation with a user
- New: channels are divided in 4 menus: All, Messages, Rooms, and Other (ALT+CMD+4 for Other)
- Changed: shortcuts for Explore menus are now SHIFT+CMD+1, SHIFT+CMD+2, and SHIFT+CMD+3 
- Fixed: clickable entities in the user profile description
- Fixed: see a user's posts from their profile even if they are muted
- Fixed: 2 x click to open an image in browser in some cases
- Fixed: opening an image embedded in a reposted post
- Fixed: logout sequence (better memory management)
- Fixed: version number (MAS would previously suggest an update when there was not)
- Fixed: trying to display a deleted post could crash the app
- Fixed: clicking on an avatar could crash in some rare cases

## 0.6.2/1.0 - 2017-03-27 - "Reservoir Dogs"

- Fixed: URL scheme is properly deactivated when user is logged out
- Fixed: height of user profile description for the logged in user
- Fixed: using TAB/RETURN in the Send PM window

## 0.6.1 - 2017-03-25 - "Echoes"

- Small UI adjustments (a few pixels here and there)
- New: authorize/login Apero with a browser instead of the app's web window (if you want to use a password manager)
- New: reply to a post or message with right-click in timeline then click "Reply" or hit "R"
- New: option to highlight posts mentioning you (in Global or Unified)
- New: choose the color of convo root, convo target, and highlighted post with mention
- New: custom About window with credits and EULA
- New: the Help menu opens the FAQ in a browser
- Fixed: the "More..." button is now only displayed when scrolling to bottom is initiated by the user
- Fixed: the user profile should not show youFollow/followsYou for the logged in user
- Fixed: using TAB after typing the username in the Send PM window
- Fixed: using RETURN in Search Tag or Search User to immediately launch the search
- Fixed: the All Channels list was not fetching enough channels in some cases
- Fixed: logout sequence (no more sneaking back into the account)
- Fixed: starring/reposting a post would trigger an alert in some cases
- Fixed: inconsistency in the save/load API configuration process
- Fixed: uploading avatar and cover image was broken
- Fixed: no more modal alerts in case of recoverable network failures
- Fixed: localized date format

## 0.5.2 - 2017-03-20 - "Starry Eyes"

- New: app icon
- New: custom buttons instead of macOS default
- New: new layout for user profile and preferences windows
- New: embedded and linked images in Channels/PMs
- New: right-click action on posts/messages (same ones as swipe actions)
- Fixed: double click on Send button would send the post/message twice
- Fixed: a message that you just sent to a channel could appear twice sometimes (unrelated to previous issue)
- Fixed: alert when editing a post or replying to a post or message if already composing a post/message
- Fixed: images weren't included in the Mentions stream
- Fixed: some modal alert dialogs

## 0.4.5 - 2017-03-15 - "Dungeon Master"

- New: "timeline always sticks on top" mode (option, on by default)
- New: make post or message from URL scheme, using "apero://post=text" or "apero://message:@user=text"
- New: swipe actions are now available everywhere
- Fixed: clickable entities could be shifted from their position in some cases
- Fixed: reopening the main window by clicking on the dock icon
- Fixed: wake up sequence
- Fixed: recall font size at launch in some cases
- Fixed: deleting post from user's post list
- Fixed: canceling uploading avatar/cover
- Removed: repost/star action for reposted posts (in the future, Apero will find the original post for you and let you repost/star it)

## 0.4.4 - 2017-03-12 - "Infectious Grooves"

- Fixed: crash related to editable posts when the app launches
- Fixed: app cannot exceed API rate limit anymore
- Fixed: crash if opening a channel while the channels list updates
- Fixed: list of users for some channels was incorrect
- Fixed: hiding the first post would make the app stop polling for new posts
- Fixed: after having posted, the timeline could show the new post twice sometimes
- Fixed: preferences color panels display preselected color
- Improved: less calls to the API from the channels list
- Improved: check for API configuration every ten days
- Improved: alert when doing New Post / New Message if already composing a post/message
- New: open patter.chat links in Apero (see preferences/tooltip)

## 0.4.3 - 2017-03-07 - "Cascadeur"

- Fixed: viewing a user's bookmarks (broken by 0.4.1)
- Improved: static images could disappear in the timeline

## 0.4.2 - 2017-03-07 - "Djiff"

- Fixed: embedding images (broken by 0.4.1)
- Removed: support for gifv

## 0.4.1 - 2017-03-06 - "Elliot Ness"

- New: explore posts with photos, explore conversations, explore trending posts
- New: swipe to the left on a post to temporarily hide it (objectionable content, spoiler, etc)
- New: swipe to the right on a post to copy the text, links and image links to the clipboard
- New: global preference to hide/show deleted posts/messages in timelines
- New: embed .gifv, d.pr/i and monosnap.com links
- Fixed: closing Search Tag or Search User windows with ESC
- Fixed: other clients creating stream markers different than Apero's current ones
- Fixed: network reachability
- Fixed: sleep / wake up
- Fixed: using menus and shortcuts while the app is launching
- Fixed: after having posted, the timeline could show the post twice in some cases

## 0.3.7 - 2017-03-02 - "Parcae"

- New: threads for Messages
- New: the Channels window has new layout and follows font preferences
- New: the New Post window shows the embedded image link with option to deactivate (edit the image link and it becomes the image title)
- Fixed: cursor interactivity for name/username under the avatar
- Fixed: layout of images/gifs for some configurations
- Fixed: line height for user description in Profile

## 0.3.6 - 2017-02-24 - "Larsen"

- Fixed: clickable http links in user bio
- Fixed: text was clipped for some messages in macOS 10.11
- Fixed: channel layout in channels list when last message is deleted
- Fixed: avatar tooltip text content
- Fixed: row height for deleted posts containing images
- Fixed: overlay scrollbar could overflow on reply icon
- New: hitting ESC closes thread/posts/messages windows
- New: CMD+RETURN sends post/message without asking confirmation
- New: if a messages window is active, CMD+P opens the send message window
- New: shortcuts for windows/tabs. CMD-1 = Global, CMD-2 = Unified, CMD-3 = Mentions, ALT+CMD-1 = Channels, ALT+CMD+2 = Messages, ALT+CMD-3 = Rooms
- New: tooltips on buttons
- Improved: behavior when the network is flaky or down (recovery after wakeUp is still not implemented, though)

## 0.3.5 - 2017-02-21 - "Zeno"

- Fixed: the timeline reloads images more efficiently
- Fixed: stream markers should play nicer
- Fixed: reposted posts show embeded images
- Fixed: search user menu, search tag menu work again
- Fixed: clickable links in user bio (WIP)
- Fixed: windows are properly listed in the Window menu

## 0.3.3 - 2017-02-19 - "Beta Test"

- Icons instead of words for buttons
- No more posting via Imgur
- In which we discover many network-related bugs (mostly with Global)

## 0.3.2 - 2017-02-03 - "John McClane"

- So many bug fixes...
- New: channels
- New: images and gifs in timeline (from oembed + detection)
- New: username completion in new post
- New: insertion and scrolling (recall) for posts timeline
- New: find a user via username or ID
- New: colored source and target for threads
- New: load more posts/messages when at bottom of timeline
- Change: stream marker synced via pnut API 
- Experimental: post oembed image/gif

## 0.3 - 2016-11-27 - "Sparkle Motion"

- New: multiple windows for posts, threads, lists, profiles, etc
- New: immediate action in Search window when hitting Enter
- Bug fixes and improvements

## 0.2 - 2016-11-18 - "Heavy Metal"

- Authorize (persisted in Keychain), login, logout
- Streams: global, unified, mentions
    - Auto polling
    - Stream marker synced via iCloud
- Timeline: 
    - View posts:
        - Avatar, username, date, text
        - Mentions, tags and links are colored and clickable
    - Post:
        - Detection of Markdown links
        - List of known users available
        - Supports Scheme URL
    - Reply
    - Repost
    - Mark
    - Edit
    - Delete
    - View thread
    - View user profile
    - View posts containing hashtag
    - Open links
- User profile:
    - View profile
        - Avatar
        - Cover
        - Username
        - Name
        - Description
        - Followers
        - Followings
        - Muted
        - Blocked
        - User's posts
        - User's bookmarks
    - Update profile:
        - Name, description, avatar, cover
        - Follow, unfollow
        - Mute, unmute
        - Block, unblock
- Search:
    - Posts containing hashtag
- Preferences:
    - Colors
    - Fonts
    - Default stream
    - Refresh interval
    - Number of posts loaded at launch

## 0.1 - 2016-09-16 - "Inception"