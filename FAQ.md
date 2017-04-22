Apero is a macOS client for the [pnut.io](https://pnut.io) network (compatible 10.11+, 10.12 recommended). You must have a pnut.io account in order to use Apero.

Apero is available [on the Mac App Store.](https://itunes.apple.com/WebObjects/MZStore.woa/wa/viewSoftware?id=1219902108&mt=12)

## What does "Apero" mean?

Is it like "apéro" in French? Or maybe "app hero"? Ah, "happy row"? Mm, "opera" pronounced by a peanut? Go figure... and go "Apero"! ;)

## Authorization and login

Authorize Apero to access your pnut.io account:

- launch Apero, enter your pnut.io login and password, confirm, then pnut.io will safely send back an authorization token
- Apero will then safely save this token in the macOS Keychain for future usage, then will use it to log you in the pnut network
- successive launches of Apero will automatically log you again in the same account, unless you log out before quitting the app

## Posting

- posts are public
- messages to users (PMs) are private
- messages to chatrooms are private or public, depending on the channel you send them to
- posts are 256 characters maximum, messages are 2048 characters maximum
- you can @mention users, use #hashtags and `[Markdown links](http:/example.com)`
- username autocompletion when writing a post/message
- there's a 5 minute window to edit typos in a post (only once, and with restrictions - this is only a convenience feature)
- you can delete any of your posts or messages at any time
- support for posting oembed images is experimental and uses free services, may fallback to just include the image link in the post if said services decline or are unavailable
- uploading images to your own pnut.io account and posting them as oembed will be available at a future date, when pnut.io opens the feature
- shortcuts: 
	- main/posts windows: ESC to close the window, CMD+N to make a new post
	- compose window: ESC to cancel and close the compose window, CMD+RETURN to immediately post

## Windows with posts and messages

- at launch, when possible, the main window automatically jumps to the last post you've seen
- the main window then automatically polls new posts for Global, Home, Mentions (same for the Messages windows)
- the other "posts windows" (threads, user posts, bookmarked posts, "explore"...) do not automatically poll new posts
- all "posts windows" have a button to load more old posts except "explore", available when scrolled to the bottom of the timeline/list
- click on a username/avatar or @mention to get the user profile
- click on a hashtag to get a list of posts containing this hashtag
- click on a link to open it in your browser
- double click on an image to open it in your browser
- images and gifs are displayed inline in posts and messages
- click on a gif to pause/play
- Apero can read the special long posts made by ChimPnut, the iOS client, but can not post them
- in conversation windows (threads), clicking on the text of a post/message highlights the current root and target posts/messages
- shortcuts:
	- main window: CMD+1 for Global, CMD+2 for Home, CMD+3 for Mentions
	- channels list window: CMD+R to refresh
	- if a messages window is active: CMD+P to compose a new PM

## Profile

- detailed informations about the user
- update your pnut.io profile information: name, description, avatar image, cover image...
- follow and unfollow, mute and unmute, block and unblock users
- see the user's followers/followings, posts and bookmarks
- write a PM to this user
- write a post mentioning this user

## Menus

Shortcuts:

 - profile: CMD+P
 - new post: CMD+N
 - new PM: CMD+M
 - all channels: ALT+CMD+1
 - messages (PMs): ALT+CMD+2
 - chatrooms: ALT+CMD+3
 - other: ALT+CMD+4
 - explore conversations: SHIFT+CMD+1
 - explore posts with photos: SHIFT+CMD+2
 - explore trending posts: SHIFT+CMD+3
 - search hashtag: CMD+T
 - search user: CMD+U
 - search chat with user: CMD+O
 - preferences: CMD+,
 - recall main window: ALT+CMD+0

## Contextual menu and gestures

- swipe towards left on a post/message: quick hide (see the Objectionable Content chapter on this page)
- swipe towards right on a post/message: copy a digest of its content to the clipboard
- right-click on a post/message for a contextual menu of the same options (and other when available, like reply)

## Preferences

Changing colors takes effect immediately but you have to click "Save current theme" in order to persist the theme between launches.

Available fonts are curated to be compatible with Apero and their number is very limited on purpose.

"Timeline always sticks to top": when this option is on, the timeline always sticks to the top of the window if you're already there.

"Hide deleted posts/messages": when this option is on, deleted posts and messages are not visible in the timeline. When this option is off, deleted posts and messages are displayed but have no content - the intent is that if the post or message is part of a thread, you can still access the thread from the deleted posts/message.

"Highlight posts mentioning you": when this option is on, posts in Global or in Home are highlighted if they contain a mention of your username.

"Localized date in timeline": when this option is on, the date and time are displayed using Apero's user's locale and timezone. When this option is off, the date and time are displayed using the original poster's timezone and are not localized.

"Polling indicator is visible": when this option is on, every poll for new posts or messages displays an indeterminate circular progress indicator at the top of the window. When this option is off, nothing in the user interface indicates that polls are occuring.

"Hijack patter.chat links in posts/messages": when this option is on, clicking on a "patter.chat" link in Apero will try to open the channel in Apero itself. When this option is off, clicking on a "patter.chat" link in Apero will open the link in a browser.

"Automatically save draft": works but is still experimental. Will be rewritten in a future udpate. Only works for posts. When this option is on, canceling a new post you're writing persistently saves its content. This content is then automatically loaded back when you click "New post" again.

## Support

- For an issue about Apero the application itself, contact apero@aya.io
- For an issue about the pnut.io network or a user, contact support@pnut.io
- The pnut.io [Terms of Service](https://pnut.io/docs/tos) and [Privacy Policy](https://pnut.io/docs/privacy) apply when using Apero. Do not post inappropriate content or behave in inappropriate ways. Your account may be suspended by pnut.io without warning if deemed a threat to others or to the service's maintenance and upkeep. 
- If you want to report a specific user, send an email to support@pnut.io. In Apero, you can yourself filter objectionable content and users with the hide, mute and block features, see the Objectionable Content chapter on this page.

## Features and availability
 
Apero does not guarantee uptime or delivery of the pnut.io services, it is only an independent client application. If pnut.io doesn't work for any reason, then Apero doesn't work, as one would expect. In this sense, buying Apero does not guarantee any period of functioning time for the application.

## Privacy

Apero does not collect user information in any way. Users list such as those used for username autocompletion are only populated while the application is running, live, and do not persist into any form of storage, neither while the application is running nor after it's been quit.

## Objectionable Content

Apero users have four possible actions against objectionable content.

Level 1 - Swipe towards left, or right-click, to quickly hide the post/message. This is temporary and lasts only until the next time the current content is reloaded, be it automatically or manually. This is a simple convenience intended to quickly hide the objectionable content before deciding upon further possible action.

Level 2 - Click the Mute button in a user profile: if you mute a user, you won't see their posts anymore. This works like a filter, managed on API side by pnut.io. The effects are immediate and stay active forever unless you click the Unmute button.

Level 3 - Click the Block button in a user profile: if you block a user, they will be automatically muted (as in level 2), they will also be unfollowed, then it limits their account: they will automatically unfollow you, and they won't be able to follow you again, to message you or to do any other action related to your account anymore. This is also managed on API side by pnut.io. The effects are immediate and the limits stay active forever unless you click the Unblock button.

Level 4 - Report: block the user, then send an email to support@pnut.io asking for moderation (give user ids, posts numbers, details about issue).
