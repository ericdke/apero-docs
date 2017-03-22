## 0.5.3 - 2017-03-22 - "Echoes"

- Small UI adjustments (a few pixels here and there)
- New: authorize/login Apero with a browser instead of the app's web window (if you want to use a password manager)
- New: reply to a post or message with right-click (or ctrl-click) in timeline then click "Reply" or hit "R"
- Fixed: the user profile should not show youFollow/followsYou for the logged in user
- Fixed: using TAB after typing the username in the Send PM window
- Fixed: using RETURN in Search Tag or Search User to immediately launch the search
- Fixed: the All Channels list was not fetching enough channels in some cases
- Fixed: logout sequence (no more sneaking back into the account)
- Fixed: starring a post would trigger an alert in some cases (bug introduced in 0.4.5)
- Fixed: inconsistency in the save/load API configuration process

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