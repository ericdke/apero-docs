Apero is a macOS native client for the [pnut.io](https://pnut.io) network (compatible 10.11+, 10.12+ recommended). 

Apero is available exclusively [on the Mac App Store.](https://itunes.apple.com/WebObjects/MZStore.woa/wa/viewSoftware?id=1219902108&mt=12)

Pnut.io is a short-messaging social network [with a strong community](https://pnut.io/about) and a nice API for developers.

Pnut.io is free to use. You can also choose to support the service and get more advanced features. 

You can start using Apero for pnut.io as soon as you have created your account on the site. Note that having an existing pnut.io account is mandatory in order to use Apero - you cannot create an account from the app.

From [the site](https://pnut.io):

> Our community network is small and sustainable. We are tied closely to our users and developers through their donations and optional pay-what-you-want features. When you invite someone, they are associated with you in the user tree. The API encourages a high level of transparency and control. You will need a third-party app to do even the simplest things, but there are plenty of options; from Android and iOS to command line and Blackberry.

...and macOS with Apero!

What does "Apero" mean, by the way? Is it like "apéro" in French? Or maybe "app hero"? Ah, "happy row"? Mm, "opera" pronounced by a peanut? Go figure... and go "Apero"! 😉

## Authorization and login

Launch Apero, enter your pnut.io login and password, confirm usage of listed features, then pnut.io will safely send back an authorization token to Apero.

Apero will then safely save this token in the macOS Keychain for future usage, then will use it to log you in the pnut network.

Successive launches of Apero will automatically log you again in the same account, unless you log out before quitting the app.

## Posting

- posts are public
- messages to users (PMs) are private
- messages to chatrooms are private or public, depending on the channel you send them to
- posts are 256 characters maximum, messages are 2048 characters maximum
- you can `@mention` users, use `#hashtags` and `[Markdown links](http:/example.com)`
- username autocompletion when writing a post/message
- there's a 5 minute window to edit typos in a post after it's been posted (works only once per post, and with restrictions - this is only a convenience feature)
- you can delete any of your posts or messages at any time
- you can "crosspost" from a chatroom to Global (if the message has less than 240 characters)
- post images/videos (see next paragraph)
- shortcuts: 
	- main/posts windows: ESC to close the window, CMD+N to make a new post
	- compose window: ESC to cancel and close the compose window, CMD+RETURN to immediately post

*Note: if you don't have any subscribed channels yet, here's a few examples to subscribe to: 617 ("tests"), 18 ("developers"), 207 ("coffee lovers")... You can also send messages (PMs) to users, which automatically subscribes you to the newly created private channel.*

## Posting with images/videos

Adding files to posts works everywhere: in new posts, new messages, replies to posts, replies to messages, chatrooms...

If you are subscribed to [pnut.io storage](https://pnut.io/account/storage), you will be able to use Apero for uploading images/videos to your pnut account and inserting them in your posts and messages.

Wether you're subscribed to this feature or not, you can always embed existing URLs pointing to images on the web (the URL(s) have to directly point to the image(s) online, not to redirecting web page(s)).

*Note: it is necessary to accept the conditions about posting with files even if your account is not (yet) subscribed to the pnut.io storage option. This will be asked only once at login.*

You can also drag & drop images/videos from the Finder (or drag from a browser if the URL points directly to an image) on the IMG+ button to create embedded images for a post/message. 

Common file formats are supported (jpg, png, gif, mpg, mp4, m4v). Some web URLs may not work (specifically if they contain complex queries or redirections).

You also have a "New video" feature where you can record a video to post on pnut. You can also post as GIF instead of video if you're using the 5 seconds or 10 seconds preset.

## Sharing/exporting files

If you are subscribed to [pnut.io storage](https://pnut.io/account/storage), you will be able to use Apero to share your files with a public link. 

You can also use this window, accessible via an icon in the file manager in your Profile, to download the file locally or to create a new post or message with the link already embedded.

## Windows with posts and messages

- at launch, when possible, the main window automatically jumps to the last post you've seen
- the main window then automatically polls new posts for Global, Home, Mentions 
- Messages windows and the Interactions window also poll for new messages
- the other "posts windows" (threads, user posts, bookmarks, explore streams) do not automatically poll new posts
- most windows automatically load more older items when the user has scrolled to the bottom of the timeline/list
- if you delete or edit with another client, Apero will reflect the changes in its windows
- click on a username/avatar or @mention to get the user profile
- click on a hashtag to get a list of posts containing this hashtag
- click on a link opens it in your browser
- images and gifs are displayed inline in posts and messages
- drag an image from Apero to the Finder or any other app
- click once on a gif to pause/play
- Apero can read the special long posts made by ChimPnut, the iOS client
- Apero can also read the videos posted by ChimPnut
- in conversation windows (threads), clicking on the text of a post/message highlights the current root and target posts/messages
- in the main window only, pull from the top to force refresh (only with trackpad, and pull must be > 40 pixels)
- right-click on a post or message to get a context menu of actions: reply, copy, hide/show post or thread, translate, interactions...
- swipe left or right on a post or message to get contextual actions (set your favorite ones in Preferences)
- shortcuts:
	- main window: CMD+1 for Global, CMD+2 for Home, CMD+3 for Mentions (or use TAB)
	- channels list window: CMD+R to refresh
	- if a messages window is active: CMD+P to compose a new PM (overrides the main CMD+P profile shortcut)

## Profile

- detailed informations about the user
- follow and unfollow, mute and unmute, block and unblock users
- see the user's followers, followings, posts and bookmarks*
- if the option is on: see the user's Post Count Achievement
- update your pnut.io profile information: name, description, avatar image, cover image...
- if you're subscribed to pnut.io storage: manage your pnut.io files (list, delete, change name, change public status, share, upload, download) and see your available storage
- write a PM to this user
- write a post mentioning this user

*bookmarks are public, but notes associated with your bookmarks are only visible by you in the Bookmarks section

## Search menu

### User by username

Enter a username and Apero will open their profile.

### User by keywords

Enter keyword(s) to search for a user in their complete name or their description.

### Chat with user

Enter a username and Apero will open an existing PM channel with this user if there's one. If not, you will be prompted for action.

### Posts with tag(s)

Enter tag(s) to search for posts containing this/these tag(s).

### Posts by keyword(s)

Enter keyword(s) to search for posts containing this/these keyword(s).

## Shortcuts and keyboard actions

 - select next stream: `TAB`
 - profile: CMD + P
 - interactions: CMD + I
 - new post: CMD + N
 - new message: CMD + M
 - global stream: CMD + 1
 - home stream: CMD + 2
 - mentions stream: CMD + 3
 - all channels: ALT + CMD + 1
 - messages (PMs): ALT + CMD + 2
 - chatrooms: ALT + CMD + 3
 - other: ALT + CMD + 4
 - explore conversations: SHIFT + CMD + 1
 - explore posts with photos: SHIFT + CMD + 2
 - explore trending posts: SHIFT + CMD + 3
 - explore lonely posts: SHIFT + CMD + 4
 - explore new users posts: SHIFT + CMD + 5
 - explore posts with polls: SHIFT + CMD + 6
 - search hashtag: CMD + T
 - search username: CMD + U
 - search user by name or description: CTRL + CMD + U
 - search chat with user: CMD + O
 - search posts using keywords: CTRL + CMD + P
 - preferences: CMD + ,
 - recall main window: ALT + CMD + 0
 - cycle between opened windows: CMD + `
 - bigger font size: CMD + `+` 
 - smaller font size: CMD + -
 - switch Dark Mode: SHIFT + CMD + D
 - compact/expand channels list: SHIFT + CMD + K

You can cycle through buttons in the Profile window with TAB and activate the current selection with SPACE.

Using TAB in the Preferences window cycles through the preferences tabs.

Using TAB in the main streams window cycles through the streams.

Hitting TAB once in other posts/messages windows+ focuses on the list, allowing selection of cells with keyboard.

Clicking once in the text body of a post/message also focuses on the list and selects the cell (see Manual posts/messages selection).

## Contextual menu and gestures

Right-click or swipe on a post/message: reply, copy, translate, search, hide post or thread, interactions and more.

Right-click or swipe on a channel: open channel, mark as read (if there's unread messages).

Right-click on a channel: set default avatar (if applicable), unsubscribe.

Option-click on the bookmark icon: bookmark with a note (also accessible via the post's contextual menu).

Favorite swipe actions are set in the Preferences panel.

When a contextual menu is displayed, you can select one of its entries by clicking it or by hitting the corresponding key.

## URL Scheme

Apero has two actions available via URL Scheme: new post and new message.

*As usual in the command line with escaped levels of text, beware of what characters you type.*

New post: use "apero://post=your text" to open a new post window prefilled with text. Example in the terminal with the "open" command: 

    $ open "apero://post=Hello from Apero"

New message: use "apero://message:@target_user=your text" to open a new message window prefilled with text. Example in the terminal with the "open" command:

    $ open "apero://message:@ericd=Hello from Apero"

*Tip: you can then send the post/message with CMD+ENTER or cancel with ESC.*

## Touch Bar

Apero fully supports Macbook Pro with TouchBar. Most actions and preferences are accessible via dedicated customizable touchbars.

## The Blacklist

Add a tag, mention, link, or even word, to the Blacklist, and any post or message containing this element will be masked in the timeline.

Don't like "#nowplaying" posts? Add the "nowplaying" tag to the Blacklist and these posts will be masked. Don't want to see any posts mentioning "@someuser"? Add the mention "someuser" to the blacklist and these posts will be masked. Etc.

And you can always do a right-click on a blacklisted post/message and click the menu to show/hide its contents (shortcut "b").

Go to Preferences -> Blacklist and enable/disable the feature from there.

This is also where you can manage the contents of the Blacklist (add/delete from the database) and export/import/delete the database.

*Note: categories are isolated. For example, blacklisting a mention only works for active (not deleted) users included in the post/message's entities (it won't search in the text or elsewhere, only in the mentions list). Blacklisting a tag only works with included tags (and same, it will only search in the tags list, not in the text or anywhere else). Etc.*

*Note: blacklisting a domain instead of a complete link would block all links containing this domain.*

## Edited posts

Posts that have been edited have a special icon. 

When clicked, the original text (before revision) is displayed. Click again to restore the edited version.

## Polls

To create a new poll, go to menu "New > Poll" (or use the `CTRL+CMD+O` shortcut). 

Create the poll then click on the "Embed" button to attach the poll to a new post. 

A poll must have a prompt, between 2 and 10 options, and a duration between 2 minutes and 14 days.

If a post has a poll attached, click on the Open Poll button to open the poll in a new window. 

From there you will be able to vote and see the poll results.

## Preferences

### Themes

You can modify Apero's colors.

To achieve this, you may just change the colors, or you may load/create a theme.

Just changing colors takes effect immediately but you have to click "Just save current colors" in order to persist the changes between launches.

You can otherwise save the set of colors as a theme, giving it a title: it will be added to the list of available themes, and recalled at each launch.

If you modify a theme, you can just save the current colors, or decide to save as a new theme after the changes.

There's also a set of default themes to choose from.

#### Starting with macOS 10.14 Mojave

Themes are associated with Dark and Light mode.

Each color theme now has a light and a dark palette. When switching from a mode to the other, the theme seamlessly changes its palette at the same time. 

A few new default themes and modified existing ones demonstrate the feature. "Classic" themes also have two palettes but they're identical by default. As usual, all default themes are modifiable, and you can create your own themes.

### Dark mode

#### macOS versions older than 10.14 Mojave

When this option is on, Apero uses dark windows. 

When this option is off (default), Apero uses white windows. 

Changing mode relaunches the application.

#### Starting with macOS 10.14 Mojave

Apero always follows the system's settings and automatically fades between light and dark modes without having to relaunch. Manual selection of Dark/Light mode is disabled.

### Fonts

Available fonts are curated to be compatible with Apero and their number is very limited on purpose.

### Monitor system changes

#### macOS versions older than 10.14 Mojave

When this option is on (default), Apero will comply to system-wide changes regarding the Dark Mode setting. These changes can be caused by macOS or by applications such as "F.lux".

#### Starting with macOS 10.14 Mojave

Apero always follows the system's settings. This option is disabled.

### Enable animations

When this option is off, Apero will minimize its use of animations.

### Highlight posts mentioning you

When this option is on, posts in Global or in Home are highlighted if they contain a mention of your username.

### Compact channels list

When this option is on, the channels list do not show any details such as the list of users and the last message.

### Rounded avatars

When this option is on (default), all avatars are rounded. 

When this option is off, the original squared image is used.

### Accent colors

*Only in macOS 10.14 Mojave and up*

Option to use the system's "Accent colors" for Apero's buttons instead of the native orange/yellow palette.

### Polling indicator is visible

When this option is on, every poll for new posts or messages displays an indeterminate circular progress indicator at the top of the window. 

When this option is off, nothing in the user interface indicates that polls are occuring.

### Timeline sticks to top

When this option is on (default, recommended), the timeline always sticks to the top of the window if you're already there, and continues to download new posts automatically.

When this option is off, the timeline doesn't stick to top at all and instead shows an icon when new posts are available - then stops downloading new posts if you don't scroll to top. It starts downloading again once you are at the top.

### Localized date in timeline

When this option is on, the date and time are displayed using Apero's user's locale and timezone. 

When this option is off, the date and time are displayed using the original poster's timezone and are not localized.

### Show verified icon

When this option is on, an icon is displayed in timelines next to the avatar of "verified" users. (This icon is also always visible in the Profile window).

### Render ASCII tags in monospace

Starting with 1.9.4, any post containing the tag #pnutprinter will be displayed in monospace font.

This option allows adding more tags that will trigger displaying a post in monospace font. Suggestions: #ascii, #asciiart...

The monospace font will be, in order of availability, either Menlo, Andale Mono or Courier.

### Open patter.chat links in Apero

When this option is on, clicking on a "patter.chat" link in Apero will try to open the channel in Apero itself. 

When this option is off, clicking on a "patter.chat" link in Apero will open the link in a browser.

### Open posts.pnut.io links in Apero

When this option is on, clicking on a "posts.pnut.io" link in Apero will try to open the post in Apero itself. 

When this option is off, Apero will open the link in a browser.

### Open beta.pnut.io links in Apero

When this option is on, clicking on a "beta.pnut.io" link in Apero will try to open the post in Apero itself (works for posts, threads and profiles). 

When this option is off, Apero will open the link in a browser.

### Show PCA in the profile window

This is an option (default: on) to display the user's "Post Count Achievement" information in the profile windows.

### Include directed posts

When this option is on, the Home timeline includes all posts from the users you follow, including the posts directed to users you don't follow.

### Manual post/message selection 

When the option is on (default: off), the selected post/message is visible and these keyboard shorcuts are available:

    - for posts:

        p = profile
        r = reply
        o = open image (if any)
        SHIFT + o = repost
        s = search user's posts
        SHIFT + s = star (bookmark) post
        OPTION + SHIFT + s = star (bookmark) post with a note
        t = thread (if any)
        SHIFT + t = translate
        e = edit (if applicable)
        SHIFT + d = delete (if applicable)
        h = hide
        SHIFT + h = hide thread (if applicable)
        c = copy content
        a = view the post's actions (if any)
        b = show/hide content of blacklisted post (if applicable)

    - for messages: 

        p = profile
        r = reply
        o = open image (if any)
        s = search messages in channel
        t = thread (if any)
        SHIFT + t = translate
        SHIFT + d = delete (if applicable)
        h = hide
        c = copy content
        b = show/hide content of blacklisted message (if applicable)

### Hide NSFW posts

When this option is on, posts tagged with "#NSFW" or programmatically marked as NSFW will be masked in the timeline. 

You can right-click to remporarily show the content and right-click again to mask the content.

### Hide Spoiler Alert posts

Posts can include a "Spoiler Alert". Such posts are displayed as collapsed by default, with a label showing the topic of the spoiler. Use the contextual menu to show the post's content.

### Automatically save draft

When this option is on, canceling a new post, message, or a reply you're writing persistently saves its content. 

This content is then automatically loaded back when you make a new post/reply/message again, and deleted once the post/reply/message has been sent.

### Clear saved drafts

Clears all drafts from memory and from disk. The action is immediate.

### Memory cache limit

Maximum cost in RAM of the images/gif cache system. 

The unit is in Megapixels. Depending of the images compression ratio and bit depth, the default cost of 500MP is usually around 250MB of jpg/png/gif cache in RAM. 

When the limit is hit, the biggest images in the cache are purged to let room for the new ones. 

Minimum: 250. No maximum - but more than 2000 would probably be useless. I suggest using 500 for most cases.

### Memory cache purge

Number of days (running time) between the images/gif memory cache cleaning cycles. 

*Note that changing this option, even to set it again to the same value, automatically triggers the memory cache cleaning procedure.*

### Disk cache purge

Number of days (calendar time) between the images/gif disk cache cleaning cycle. 

*Note that changing this option, even to set it again to the same value, automatically triggers the disk cache cleaning of the expired items.*

### Cursor position when replying

When replying to a post or a message and there's several mentions, Apero can insert the text cursor just after the leading mention, or after all the mentions.

### Leading and trailing swipe actions

You can assign any of the actions from the context menus to swipe actions. Available for posts/messages and channels.

### Translation engine

Apero can use Google Translate or Yandex Translate to translate posts and messages.

Google Translate has excellent performances, but has limitations: it cannot detect non-latin languages when doing in-app translation (it only works with translation in browser, the languages have to be specified for in-app), and the total number of languages available is rather small.

Yandex Translate has a great number of languages available and does detect non-latin languages rather well, but the combinations of source-target translations is limited: the presence of language A and language B in the list does not guarantee that Yandex will be able to translate from A to B.

When a language is selected but the translate engine cannot use it, Apero will default to "Automatic" (detection) for source, and English for target.

Also keep in mind that sometimes the @mentions, #tags and links in the text can confuse the language detector. If there's an error or results make no sense, try switching automatic/manual or using the other engine.

### Translation happens in...

Translation can happen in Apero or in browser. When happening "in Apero", the current text displayed for the post or message is replaced by its translation (right-click or swipe once again to show back the original post). But if there's an error or the service is not available, Apero will instead open the translation in a browser.

### Translation languages

The "Follow preferences" setting tells Apero that you want to translate directly using the source and target settings, without having to choose each time in a dialog box. Whereas the "Always ask" setting tells Apero that you always want to choose languages manually before translating.

### Translation source

The "Automatic" setting means that the translation engine will try to autodetect the source language. You may otherwise choose one of the listed languages as the default.

### Translation target

The language the post or message will be translated to.

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

Level 4 - From a post: right-click and select "Report user", select the report reason, send, then block the user. // Or block the user then send an email to support@pnut.io asking for moderation (give user ids, posts numbers, time table, details about issues).