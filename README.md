# ESGST - Enhanced SteamGifts & SteamTrades

A script that adds some cool features to SteamGifts and SteamTrades.

---

## [Patrons](https://www.patreon.com/revilheart) - Thank you!

* [Pilda](https://www.steamgifts.com/user/Pilda)

---

## Installation

To install the extension:

* Firefox -> Download [this file](https://github.com/revilheart/ESGST/raw/master/Extension/esgst.xpi) and drag it into "about:addons".
* Chrome -> Clone the repository to your computer, go to "chrome://extensions/", enable developer mode, click "Load unpacked extension" and select the "Extensions" folder in the repository. Using the extension on Chrome might be a nuisance, since every time you open the browser you will get a message saying that using extensions in developer mode can be unsafe.

Other browsers might work with the extension, but only Firefox and Chrome have been tested and confirmed as working.

To install the script, you must install [Greasemonkey](http://www.greasespot.net/) (not 100% compatible with the latest versions of Firefox), [Tampermonkey](https://tampermonkey.net/), or some other userscript manager first. Then [click here](https://github.com/revilheart/ESGST/raw/master/ESGST.user.js) and you should be prompted to install it.

You can also install the script in your Android through Firefox with Violentmonkey or USI. Though some features might not work.

To upgrade from the script to the extension, all you have to do is export all your data from the script, install the extension and import all the data you had exported into the extension.

---

## Compatibility

Fully tested and working in the latest version of:

* Firefox
* Google Chrome

Should be working in the latest version of:

* Opera

May or may not be working (try at your own risk) in the latest version of:

* Edge

---

# Features

---

## General

* [Fixed Elements](#fixed-elements)
* [Endless Scrolling](#endless-scrolling)
* [Grid View](#grid-view)
* [Header Icons Refresher](#header-icons-refresher)
* [Accurate Timestamp](#accurate-timestamp)
* [Points Refresher](#points-refresher)
* [Visible Attached Images](#visible-attached-images)

---

## Giveaways

* [Giveaway Templates](#giveaway-templates)
* [Stickied Giveaway Groups](#stickied-giveaway-groups)
* [Advanced Giveaway Search](#advanced-giveaway-search)
* [Pinned Giveaways Button](#pinned-giveaways-button)
* [Giveaway Filters](#giveaway-filters)
* [Entered Giveaways Filter](#entered-giveaways-filter)
* [Enter / Leave Giveaway Button](#enter--leave-giveaway-button)
* [Giveaway Description / Comment Box Popup](#giveaway-description--comment-box-popup)
* [Giveaway Winning Chance](#giveaway-winning-chance)
* [Giveaway Groups Popup](#giveaway-groups-popup)
* [Giveaway Winners Link](#giveaway-winners-link)
* [Giveaway Error Search Links](#giveaway-error-search-links)
* [Delivered Gifts Notifier](#delivered-gifts-notifier)
* [Unsent Gifts Sender](#unsent-gifts-sender)
* [Entries Remover](#entries-remover)

---

## Discussions

* [Active Discussions On Top](#active-discussions-on-top)
* [Discussions Highlighter](#discussions-highlighter)
* [Main Post Popup](#main-post-popup)
* [Discussion Edit Detector](#discussion-edit-detector)

---

## Commenting

* [Comment History](#comment-history)
* [Comment Tracker](#comment-tracker)
* [Comment Formatting Helper](#comment-formatting-helper)
* [Main Comment Box Popup](#main-comment-box-popup)
* [Multi-Reply](#multi-reply)
* [Reply From Inbox](#reply-from-inbox)
* [Reply Mention Link](#reply-mention-link)

---

## Users, Groups & Games

* [Username History](#username-history)
* [Permanent User Notes](#permanent-user-notes)
* [Real Won / Sent CV Links](#real-won--sent-cv-links)
* [Sent / Won Ratio](#sent--won-ratio)
* [SteamGifts Profile Button](#steamgifts-profile-button)
* [SteamTrades Profile Button](#steamtrades-profile-button)
* [Shared Groups Checker](#shared-groups-checker)
* [Permanent User Tags](#permanent-user-tags)
* [Whitelist / Blacklist Highlighter](#whitelist--blacklist-highlighter)
* [Whitelist / Blacklist Checker](#whitelist--blacklist-checker)
* [Not Activated / Multiple Wins Checker](#not-activated--multiple-wins-checker)
* [Not Received Finder](#not-received-finder)
* [User Giveaways Data](#user-giveaways-data)
* [Inbox Winners Highlighter](#inbox-winners-highlighter)
* [Avatar Popout](#avatar-popout)
* [Game Categories](#game-categories)

---

## Games

* [Entered Games Highlighter](#entered-games-highlighter)
* [Game Tags](#game-tags)

---

## Other

* [Featured Container Hider](#featured-container-hider)
* [Blacklist Stats Hider](#blacklist-stats-hider)
* [Multi-Tag](#multi-tag)
* [Groups Highlighter](#groups-highlighter)
* [Groups Stats](#groups-stats)
* [Archive Searcher](#archive-searcher)

---

* [Other Info](#other-info)

---

### Unfaded Entered Giveaways

`steamgifts.com/*`

* Removes SG's default fade for entered giveaways.

### Created/Entered/Won Giveaway Details

`steamgifts.com/giveaways/(created|entered|won)/*`

* Adds more details to the created/entered/won pages, such as the number of points, the link to the Steam store page of the game, the name of the creator, the type of the giveaway and the level. It also loads the giveaway groups below the giveaway if Giveaway Groups Loader is enabled.

### Is There Any Deal? Info

`steamgifts.com/giveaway/*`

* Adds Is There Any Deal? info to giveaway pages, including the best current deal, the historical lowest price (optional) and the list of bundles that the game has been in, with a cache that can be updated after 24 hours since the last check.

![](http://i.imgur.com/epF2am3.png)

### Last Page Link

`steamgifts.com/*`

* Adds a "Last Page" link to some places that are missing it, for example: discussion pages with 100+ pages, user pages, group pages with 100+ pages.

### Giveaway Maker

`steamgifts.com/giveaways/new/*`

* Allows you to create multiple giveaways or a train of giveaways (multiple giveaways that are linked to one another).
* You can view detailed information about a giveaway by hovering over it.
* You can re-order/remove the giveaways by dragging and dropping them in the correspondent areas.
* All giveaways will be created without reviewing or validating, so make sure all fields are filled correctly, or the giveaway creation will fail (if a train is being created, the failed giveaway will be disconnected and the previous giveaway will be connected to the next instead).

![](http://i.imgur.com/Pf9j7gN.png)

### Discussions Sorter

`steamgifts.com/discussions/*`

* Allows you to sort discussions by creation date (from newest to oldest).

![](http://i.imgur.com/pMAoVq9.png)

### Whitelist/Blacklist Sorter

`steamgifts.com/account/manage/whitelist|blacklist/*`

* Allows you to view your whitelist/blacklist sorted by added date, both from oldest to newest and from newest to oldest.

![](http://i.imgur.com/Vyr1LWi.png)

### Steam Activation Link

`steamgifts.com/giveaways/won*`

* Allows you to easily activate a won game.

![](http://i.imgur.com/0hnY0yD.png)

### User Filters

`steamgifts.com/*`

* Allows you to filter out posts, discussions and giveaways from users.
* Filtered posts are completely removed, along with all replies to it.
* Each user has their own settings, which can be configured through their profile (or their avatar if you're using Avatar Popout).
* You can enable an option in the settings menu to automatically filter out all users that you have blacklisted. If you set a custom setting to a blacklisted user on their profile, that setting will overwrite the automatic setting.
* You can see a list of filtered users in the settings menu.

### Giveaway Bookmarks

`steamgifts.com/*`

* Allows you to bookmark giveaways to enter later.
* You can enable an option to highlight the button if a giveaway is about to end, given a certain amount of hours specified in the settings menu.
* Giveaways that have not started yet will not appear in the list of bookmarked giveaways. Instead, they will stay in a sort of hidden state until they start. When they start, the header bookmark button will turn green, indicating that you must open the list of bookmarked giveaways so that the started giveaways can be updated with their end times. When giveaways are about to end, the button will red. If there are both started and ending giveaways, the button will be colored with a brown-ish color. Hovering over the button also gives you more details about how many giveaways have started and/or are ending.

![](http://i.imgur.com/6e8UyL3.png)
![](http://i.imgur.com/kNxEDZV.png)
![](http://i.imgur.com/7OAYXa9.png)

### Quick Giveaway Browsing

`steamgifts.com/*`

* Allows you to quickly go to recommended/wishlist/group/new giveaways without having to first go to the main page and then select it at the sidebar.

![](http://imgur.com/NDgqzFj.png)

### Game Categories

`steamgifts.com/*`

* Displays categories for games. Categories so far: bundled, trading cards, achievements, multiplayer, Steam cloud, Linux, Mac, DLC and genres.
* The bundle list must be synced through the settings menu for the bundled category to work.

![](http://i.imgur.com/DmYIM2V.png)
![](http://i.imgur.com/70Gyhxu.png)
![](http://i.imgur.com/jsL0aVB.png)
![](http://i.imgur.com/zGeKiag.png)

### Giveaway Filters

`steamgifts.com/giveaways/*`

* Allows you to filter out certain giveaways in a page.
* Works well with Game Categories.

![](http://i.imgur.com/Ez4NyMm.png)

### Real CV Calculator

`steamgifts.com/giveaway/new`

* Calculates how much real CV you should get for a giveaway.
* It's only accurate if you have synced the bundle list from the settings menu and also scanned your sent giveaways using User Giveaways Data. But even then, it's only 100% accurate if the user has 0 not received giveaways, since User Giveaways Data doesn't currently know if the giveaways have been received or not.
* In the example below, as I had previously given away 3 copies of Max Payne 3, the sixth copy is worth 10% less (18P). So the 3 new copies would equal 58P:

![](http://i.imgur.com/oCGStUq.png)

### Giveaway Encrypter/Decrypted

`steamgifts.com/*`

* Allows users of the script to encrypt giveaways and hide them in their posts, so that they can be easily seen by other users of the script.
* To add encrypt a giveaway and hide it in a post, you must have the option enabled for Comment Formatting Helper.
* If there are any encrypted giveaways hidden in a page, a button will be added to the header menu where you can access them.

### Settings Menu

`steamgifts.com/account/*`

* Allows you to enable / disable features.
* Allows you import / export your data.
* Allows you to manage `Whitelist / Blacklist Highlighter` and `Not Activated / Multiple Wins Checker` caches.
* Allows you to sync your data and enable / disable the automatic sync.

### Level Progress Visualizer

`steamgifts.com/*`

* Shows your level progress in the main button.

![](http://imgur.com/RJmCnpR.png)

### Hidden Featured Container

`steamgifts.com/giveaways/*`

![](http://i.imgur.com/QjTxvo2.png)

* Hides the featured container in the giveaways pages.

### Hidden Blacklist Stats

`steamgifts.com/stats/personal/community`

![](http://i.imgur.com/yB3pQSI.png)

* Hides blacklist stats in the stats page.

### Fixed Header
### Fixed Sidebar
### Fixed Main Page Heading
### Fixed Footer

`(steamgifts|steamtrades).com/*`

* Allows you to fix the header, heading, sidebar and footer, so that they scroll together with the page.
* You can disable any of the elements through the settings menu.
* In case it isn't clear, this is the heading:

![](http://i.imgur.com/6Hk0nus.png)

### Endless Scrolling

`(steamgifts|steamtrades).com/*`

![](http://i.imgur.com/sCJ97Dk.png)

* Allows you to endlessly scroll through pages.
* You can choose in which pages you want to enable the endless scrolling from the settings menu.
* If you click on the link to a page and that page is currently loaded, it will jump to the page instead of loading it. This only works on SteamGifts though, and if you jump between pages that aren't next to each other, the pagination gets messed up, but you can fix it by then going to the immediate previous / next page and returning.
* You can refresh pages without leaving the page.
* You can pause / resume the endless scrolling.
* You can enable reverse scrolling for discussions.

### Active Discussions On Top/Sidebar

`steamgifts.com/*`

* Moves the active discussions to the top/sidebar of the page.
* More info about the sidebar choice: if you have Advanced Giveaway Search enabled, it will be hidden and triggered when hovering hover the search field; the username and avatar of the user who last posted will be removed (the button to go to the last comment will remain intact); Accurate Timestamps will not run for any timestamps inside the active discussions; and any user tags you might have saved for users will be hidden inside the active discussions (they will still be visible if you click the tag button to edit them).

![](http://i.imgur.com/XEeroVn.png)

### Grid View

`steamgifts.com/giveaways*`

![](http://i.imgur.com/jhd1m4A.png)

### SteamGifts Profile Button

`steamtrades.com/user/*`

![](http://i.imgur.com/k4P3OMy.png)

* Adds a button that links to an user's SteamGifts profile.

### SteamTrades Profile Button

`steamgifts.com/user/*`

![](http://i.imgur.com/iJxVz6D.png)

* Adds a button that links to an user's SteamTrades profile.

### Shared Groups Checker

`steamgifts.com\/*`

![](http://i.imgur.com/5NkCrum.png)

* Allows you to check which groups you and another user have in common.

### Comment History

`steamgifts.com/*`

![](http://i.imgur.com/lDSXYcS.png)

* Keeps track of the comments you make (they can be seen from the settings menu).
* This feature **only** works with Main Comment Box Popup, Discussion Edit Detector and Multi-Reply / Reply From Inbox. If you submit a comment though SG's native comment box, the comment will not be tracked.

### Username History

`steamgifts.com/user/*`

![](http://i.imgur.com/cTnt7sk.png)

* Keeps track of usernames from the [database](https://docs.google.com/spreadsheets/d/1rZQuo6T02zutwSo1edbDzW8q9GmpDIbaVvKN79TyFqA/edit?usp=sharing) and detects username changes every month.
* There are currently 7200+ users being tracked.
* An user is added to the database when you click on the arrow next to their username.
* You can view recent username changes from the settings menu.

### User Notes

`(steamgifts|steamtrades).com/user/*`

![](http://i.imgur.com/lF9YKjm.png)
![](http://i.imgur.com/1AvN0Co.png)

* Allows you to add notes to users.
* The notes are permanent because they are tied to an user's SteamID64 instead of their username.
* The icon changes if the notes are not empty:

![](http://i.imgur.com/PYm3Ds7.png)

### User Tags

`(steamgifts|steamtrades).com/*`

![](http://i.imgur.com/AIPs4d1.png)
![](http://i.imgur.com/4660IaT.png)

* Allows you to add tags to users.
* Unlike the permanent user notes, the tags are not tied to an user's SteamID64, because that information is only available in the profile page, but they are still permament because upon adding a tag to an user, it automatically detects username changes and returns any old tags you might have saved for that user before they changed their username.
* While the tags are not tied to an user's SteamID64, it still has to retrieve the user's profile page in order to save to the storage, so if you're adding tags to an user for the first time, it might take a while to do so.
* Separation of tags is purely cosmetic.

### Multi-Tag

`(steamgifts|steamtrades).com/*`

![](http://i.imgur.com/aZRQkxr.png)
![](http://i.imgur.com/mhjTmn1.png)

* Allows you to tag multiple users / games at the same time.
* It goes without saying that this feature only works if either Permanent User Notes or Game Tags are enabled.

### Whitelist/Blacklist Highlighter

`(steamgifts|steamtrades).com/*`

![](http://i.imgur.com/rxqGu9i.png)
![](http://i.imgur.com/mRIrwb7.png)

* Adds a heart or ban icon next to the username of all users from your whitelist / blacklist.
* The users must be scanned through the settings menu for the feature to work. You can scan them manually or enable the automatic scan to run every once in a while.

### Whitelist/Blacklist Checker

`steamgifts.com/*`

![](http://i.imgur.com/KDAHDme.png)
![](http://i.imgur.com/x6AWyp7.png)

* Allows you to check if an user or a list of users have whitelisted / blacklisted you.
* Results are cached for 24 hours.
* The caches can be seen and updated from the settings menu.
* The checker has a simplified version that only checks / shows whitelists. It can be activated from the settings menu by enabling `Show blacklist information.`. If this version is activated and the checker finds an user that has blacklisted you, it will return `There is not enough information to know if you are whitelisted or blacklisted.` instead of `You are blacklisted.`.
* You can highlight users who have whitelisted / blacklisted you by enabling this option through the settings menu. This functionality is supported on SteamTrades (`steamtrades.com/*`). The following icons will be added next to their username:

![](http://i.imgur.com/yPoDrnm.png)
![](http://i.imgur.com/BRLSAXD.png)

### Real Won/Sent CV Links

`steamgifts.com/user/*`

![](http://i.imgur.com/NvGf47L.png)
![](http://i.imgur.com/Shwsgdh.png)

* Adds links to an user's SGTools real won / sent CV pages.
* Has an option to automatically load the real CV and show it on the profile.

### Sent/Won Ratio

`steamgifts.com/user/*`

![](http://i.imgur.com/eqBybQQ.png)

* Shows the sent / won ratio of an user.

### Not Activated/Multiple Wins Checker

`steamgifts.com/(user|giveaway/.../winners)/*`

![](http://i.imgur.com/QsNfLPJ.png)
![](http://i.imgur.com/vaSRuPJ.png)
![](http://i.imgur.com/nBeDvPw.png)

* Allows you to check if an user or a page of winners from a giveaway have any not activated / multiple wins.
* Results are cached for 7 days.
* The caches can be seen from the settings menu (updating all of them at once is not possible).
* You can highlight users who have not received / multiple wins by enabling this option through the settings menu. This functionality is supported on SteamTrades (`steamtrades.com/*`). Their username will change to the following colors:

![](http://i.imgur.com/6Oo1Bkg.png)
![](http://i.imgur.com/IH9khSq.png)

### Not Received Finder

`steamgifts.com/user/*`

![](http://i.imgur.com/lgjr9mo.png)
![](http://i.imgur.com/8AXpAd2.png)

* Allows you to find an user's not received giveaways.
* If the user doesn't have any not received giveaways, the button will not appear.
* Results are cached for 7 days.

### User Giveaways Data

![](http://i.imgur.com/1ZeyWtw.png)
![](http://i.imgur.com/Vq0Toc1.png)
![](http://i.imgur.com/q3xqDym.png)

* Gathers data about an user's giveaways, listing them by type and level.
* Lists the most given away games for sent checks and the users most won from for won checks.
* The data is not 100% accurate if the user has not received giveaways.

### Level Up Calculator

`steamgifts.com/user/*`

![](http://i.imgur.com/eTBR402.png)

* Approximately calculates how much real CV an user needs to level up.

### Inbox Winners Highlighter

`steamgifts.com/messages`

![](http://i.imgur.com/l5IeKoHg.png)

* Highlights the winners of your giveaways in your inbox.
* A winner is added to the storage when you send the gift to them through the winners page of the giveaway or through Unsent Gifts Sender.

### Avatar Popout

`steamgifts.com/*`

![](http://i.imgur.com/aEEKnim.png)
![](http://i.imgur.com/o8os3un.png)

* Pops out a box with info about an user / group if you click on their avatar.
* Has all the features that run on `steamgifts.com/user/*` built-in.

### Unsent Gifts Sender

`steamgifts.com/created/*`

![](http://i.imgur.com/IXgP9G0.png)
![](http://i.imgur.com/69wbkUP.png)

* Allows you to send all your unsent gifts directly from your created giveaways page.
* You can choose to only send the gifts to winners with 0 not activated / multiple wins or who are whitelisted.

### Entries Remover

`steamgifts.com/giveaways/entered/*`

![](http://i.imgur.com/kXTZeWo.png)

* Allows you to remove entries for owned games.
* In order for the feature to work, you must enter your Steam API Key in section 9 of the settings menu (get a Steam API Key [here](https://steamcommunity.com/dev/apikey)):

![](http://i.imgur.com/MK5cVax.png)

### Giveaway Templates

`steamgifts.com/giveaways/new`

![](http://i.imgur.com/yl9ogWx.png)
![](http://i.imgur.com/PFML0cc.png)

* Allows you to save giveaway templates for later use.
* To edit a template, simply apply it normally, perform your changes and save it with the same name.

### Stickied Giveaway Groups

`steamgifts.com/giveaways/new`

![](http://i.imgur.com/5QeKO7e.png)

* Allows you to sticky groups while creating a giveaway.

### Header Icons Refresher

`steamgifts.com/*`

* Updates the header icons every 60 seconds (only if the tab is active).
* You can enable an option that runs the refresher in the background and changes the icon of the tab when not active.

### Delivered Gifts Notifier

`steamgifts.com/*`

![](http://i.imgur.com/z4EZZm6.png)

* Notifies you if one of your won gifts has been delivered.

### Advanced Giveaway Search

`steamgifts.com/giveaways/*(!(wishlist|created|entered|won)`

![](http://i.imgur.com/RHYmAGs.png)

* Allows you to easily search giveaways using SG's [search parameters](https://www.steamgifts.com/discussion/8SzdT/).

### Pinned Giveaways Button

`steamgifts.com/giveaways/*`

![](http://i.imgur.com/oiXdLx3.png)

* Allows you to collapse the pinned giveaways container after expanding it.

### Points Refresher

`steamgifts.com/?`

* Updates your points every 60 seconds (only if the tab is active).
* You can enable an option that runs the refresher in the background and changes the title of the tab when not active.

### Visible Attached Images

`(steamgifts|steamtrades).com/*`

![](http://i.imgur.com/IoZ7JhK.png)

* Shows all attached images by default.

### Games Highlighter

`steamgifts.com/*`

![](http://i.imgur.com/gblD658.png)

* Highlights games you have already entered giveaways for.

### Giveaway Panel
### Entered Giveaways Filter

`steamgifts.com/*`

* Hides entered giveaways.

### Enter/Leave Giveaway Button

`steamgifts.com/(giveaways|user|group)/*`

![](http://i.imgur.com/dR5gyHW.png)

* Allows you to enter / leave giveaways directly from the giveaways pages.

### Giveaway Description/Reply Box Popup

`steamgifts.com/(giveaways|user|group)/*`

![](http://i.imgur.com/6HJTICj.png)

* Allows you to view giveaway descriptions and add comments to giveaways directly from the giveaways pages.
* You can enable an option to show it automatically upon entering a giveaway if Enter / Leave Giveaway Button is enabled.

### Giveaway Winning Chance

`steamgifts.com/(giveaways|giveaways/entered|giveaway|user|group)/*`

![](http://i.imgur.com/Pib5Tom.png)

* Displays your winning chance for a giveaway.

### Groups Highlighter

`steamgifts.com/giveaway/groups/*`

![](http://i.imgur.com/eaGeLUj.png)

* Highlights which groups you are a member of in the giveaway groups page.

### Groups Stats

`steamgifts.com/account/steam/groups/*`

![](http://i.imgur.com/b7jV7Gu.png?1)

* Shows your status in groups from your groups page.

### One-Click Hide Giveaway Button

`steamgifts.com/*`

* Allows you to hide giveaways with one click.

### Giveaway Groups Loader

`steamgifts.com/*`

![](http://i.imgur.com/PN73phv.png)

* Loads the groups of a giveaway and shows them below it.
* Groups that you are a member of are highlighted in bold.

### Giveaway Error Search Links

`steamgifts.com/giveaway/*`

![](http://i.imgur.com/GM6bX3s.png)

* Provides search links for the game when you cannot access a giveaway.

### Discussions Highlighter

`steamgifts.com/discussions/*`

![](http://i.imgur.com/A2o14yw.png)

* Allows you to highlight discussions.

### Comment Tracker

`(steamgifts|steamtrades).com/*(!messages)`

![](http://i.imgur.com/6nALh8y.png)

* Fades out giveaways / discussions / support tickets / trades you have already visited. Note that this does not mean every comment inside the page has been read, it simply means you have visited it.
* Keeps track of comments / editions and fades out those you have already read.
* To mark a comment as read, click on the eye icon below it:

![](http://i.imgur.com/UCb55vi.png)

* Adds a panel that allows you to go to the first unread comment of the page or mark all comments of the page as read:

![](http://i.imgur.com/8fPMwjG.png)

* Keeps track of discussion comments and shows how many comments are unread on the discussions page.
* Allows you to go to the first unread comment of a discussion or mark all its comments as read directly from the discussions page.

### Accurate Timestamps

`(steamgifts|steamtrades).com/*`

* Increases the accuracy of timestamps by changing them from `2 hours ago` to `1/1/2017, 0:00:00 AM - 2 hours ago`.
* You can disable it in the main giveaways pages through the settings menu.

### Comment Formatting Helper

`(steamgifts|steamtrades).com/*`

![](http://i.imgur.com/g9C3e0g.png)

* Adds a panel that helps you with comment formatting.
* Allows you to turn automatic links / images paste formatting on / off.
* You can disable any items of the panel through the settings menu, except for the automatic links / images paste formatting item.

### Reply Box Popup

`(steamgifts|steamtrades).com/*`

![](http://i.imgur.com/hmaZQYn.png)
![](http://i.imgur.com/ClGzBNS.png)

* Hides the main comment box and adds a button that pops up a box which allows you to add comments to the page.
* Has `Discussion Edit Detector` built-in.

### Multi-Reply

`(steamgifts|steamtrades).com/*`

* Allows you to reply to multiple comments at the same time, since each comment has their own comment box and the page isn't reloaded after submitting it.
* Has `Discussion Edit Detector` built-in.

### Reply From Inbox

`(steamgifts|steamtrades).com/messages/*`

* Allows you to reply to your messages directly from your inbox.
* Has `Multi-Reply` built-in.

### Game Tags

`steamgifts.com/*`

![](http://i.imgur.com/qCLDa2g.png)
![](http://i.imgur.com/g4pTzCe.png)

* Allows you to add tags to games.
* Separation of tags is purely cosmetic.

### Giveaway Winners Link

`steamgifts.com/*`

![](http://i.imgur.com/g2kaFD9.png)

* Adds a link to the winners page of a giveaway.

### Main Post Popup

`steamgifts.com/discussion/*`

![](http://i.imgur.com/lA9QNLM.png)

* Hides the main post and adds a button that pops it up.
* If `Comment Tracker` is enabled, the main post is only hidden if it has been marked as read.

### Discussion Edit Detector

`steamgifts.com/discussion/*`

* Detects if the discussion you're posting a comment to has been edited since the time you opened it and saves your comment correctly.
* This fixes a bug on SteamGifts that does not save your comment to a discussion if you submit it after the discussion has been edited.

### Reply Mention Link

`(steamgifts|steamtrades).com/*`

![](http://i.imgur.com/SgEzjXC.png)

* Adds a mention link to the comment replied to.

### Archive Searcher

`steamgifts.com/archive/*`

![](http://i.imgur.com/DtvFj5J.png)
![](http://i.imgur.com/bkUPFuV.png)

* Allows you to search the archive by exact title / AppID.

### Embedded Videos

`steamgifts|steamtrades.com*`

* Embeds YouTube and Vimeo videos into the page.
* Videos are only embedded if the links are in the format [URL](URL) and the only content in a line.

For example:

[https://www.youtube.com/watch?v=cD1e0BNNifk](https://www.youtube.com/watch?v=cD1e0BNNifk)

The video above gets embedded.

[Orange Sphincter To The Rescue](https://www.youtube.com/watch?v=cD1e0BNNifk)

The video above does not get embedded.

I watched [https://www.youtube.com/watch?v=cD1e0BNNifk](https://www.youtube.com/watch?v=cD1e0BNNifk) and it was hilarious.

The video above does not get embedded.

### Pagination Navigation On Top

`steamgifts|steamtrades.com*`

* Moves the pagination navigation to the top of the page.

### Reply Box On Top

`steamgifts|steamtrades.com*`

* Moves the reply box to the top of the page.

### Other Info

* All requests from `Whitelist / Blacklist Checker`, `Not Activated / Multiple Wins Checker`, `Not Received Finder` and `Archive Searcher` are limited to 2 per second, to prevent a stress on the SG servers.
* If you try to leave the page while `Whitelist / Blacklist Checker`, `Not Activated / Multiple Wins Checker`, `Not Received Finder` and `Archive Searcher` are running, you will get a confirmation dialog asking you if you want to leave the page. Additionally, while these features are running, their buttons are faded out.
* `Whitelist / Blacklist Checker`, `Not Activated / Multiple Wins Checker`, `Not Received Finder` and `Archive Searcher` allow for real-time options. For example, if you start `Whitelist / Blacklist Checker` with `Also check for whitelist.` enabled, but in the middle of the process you decide to disable that option, from that point onwards it will no longer check for whitelist.

---

## Changelog

**7.0.2 (October 8, 2017):**

<ul>
    <li>The extension should now update automatically on Firefox.</li>
</ul>

**7.0.1 (October 8, 2017):**

<ul>
    <li>Fixed a bug in requests for the same domain on the extension.</li>
</ul>

**7.0.0 (October 8, 2017):**

<ul>
    <li>Replaced the Dropbox SDK with the HTTP endpoints, which should fix some bugs.</li>
    <li>Fixed a bug in Header Refresher that was not updating the enter buttons in the page.</li>
    <li>When inside a giveaway that you have no points to enter, the "Not Enough Points" button will now be replaced by Enter/Leave Giveaway Button and update accordingly when you get more points without the need to refresh the page.</li>
</ul>
<p>
    <b>ESGST has been ported to an extension (currently only tested with Firefox and Chrome). Head over to the ESGST discussion or GitHub page to learn how to upgrade. The script version of ESGST will continue to be updated normally for now, whenever the extension is updated (I will decide whether or not to discontinue it based on the extension reception). The "Beta" drop in the version name does not mean the script has become stable.</b>
</p>

**6.Beta.39.0 (October 8, 2017):**

<ul>
    <li>Fixed a bug in Fixed Sidebar that was happening if the window height was too small.</li>
    <li>Added options to show the number of unread messages, unviewed keys and unentered wishlist giveaways from Header Refresher as browser notifications (closes <a href="https://github.com/revilheart/ESGST/issues/40">#40</a>).</li>
    <li>Added "Previously Entered" (must have Entered Games Highlighter enabled) and "Previously Won" filters to Giveaway Filters (closes <a href="https://github.com/revilheart/ESGST/issues/17">#17</a> and <a href="https://github.com/revilheart/ESGST/issues/44">#44</a>).</li>
    <li>Enter/Leave Giveaway Button no longer shows the enter button for previously won giveaways (closes <a href="https://github.com/revilheart/ESGST/issues/17">#17</a>).</li>
    <li>You can now filter emojis by name when selecting them in Comment Formatting Helper.</li>
</ul>
<p>Renamed the following features>:</p>
<ul>
    <li>Train Giveaways Extractor -> Giveaways Extractor - Fixed all bugs, as far as I'm aware (closes <a href="https://github.com/revilheart/ESGST/issues/1">#1</a>).</li>
</ul>

**6.Beta.38.6 (October 5, 2017):**

<ul>
    <li>Fixed a bug that was preventing Enter/Leave Giveaway Button from working correctly.</li>
</ul>

**6.Beta.38.5 (October 4, 2017):**

<ul>
    <li>Fixed a bug that was happening if Giveaway Popup was enabled, but Giveaway Winning Chance/Ratio, Enter/Leave Giveaway Button and Created/Entered/Won Giveaway Details were disabled.</li>
    <li>Extended the option to hide individual giveaways to group pages.</li>
    <li>Added an option to Enter/Leave Giveaway Button that allows repeated descriptions from the same creator to be cached for 1 hour and only shown once.</li>
    <li>You can now add your own description filters to Enter/Leave Giveaway Button.</li>
</ul>

**6.Beta.38.4 (October 2, 2017):**

<ul>
    <li>Fixed a few bugs in Giveaway/Discussion Filters.</li>
    <li>Introducing "Overrides" to Giveaway/Discussion Filters, which allows you to configure some filters to always filter no matter what exceptions are set.</li>
</ul>

**6.Beta.38.3 (October 2, 2017):**

<ul>
    <li>Fixed a bug in Old Active Discussions Design that was preventing the script from loading correctly.</li>
</ul>

**6.Beta.38.2 (October 2, 2017):**

<ul>
    <li>Fixed a bug in Comment Formatting Helper that broke the heading buttons.</li>
    <li>Fixed a style issue that had changed the font in the Comment Formatting Helper popouts (closes <a href="https://github.com/revilheart/ESGST/issues/2">#2</a>).</li>
    <li>Added an option (Games.3.1) to Game Categories that shows the category colors as a bottom border to the giveaways in Grid View (closes <a href="https://github.com/revilheart/ESGST/issues/5">#5</a>).</li>
</ul>

**6.Beta.38.1 (October 2, 2017):**

<ul>
    <li>Added an option that automatically syncs your groups/games when syncing through SG (closes <a href="https://github.com/revilheart/ESGST/issues/10">#10</a>).</li>
    <li>Fixed a bug that was not handling some option dependencies correctly (closes <a href="https://github.com/revilheart/ESGST/issues/32">#32</a>).</li>
    <li>Giveaway Filters exceptions are now applied to all filters instead of just to basic filters.</li>
    <li>Fixed a bug that was preventing Discussion Filters exceptions from working correctly (closes <a href="https://github.com/revilheart/ESGST/issues/31">#31</a>).</li>
    <li>Enter/Leave Giveaway Button now recognizes identical descriptions from the same creator and shows the description only once so you don't have to keep reading the same description over and over again (the cache is stored for 1 hour).</li>
    <li>Added an option (2.17.1) to Enter/Leave Giveaway Button that filters out useless descriptions.</li>
    <li>Fixed a bug in Giveaway Popup that was popping the description once again after entering the giveaway.</li>
    <li>Added a 2 minutes delay between the creation of identical giveaways to Multiple Giveaways Creator, as SG now blocks the creation of identical giveaways in less than 2 minutes apart from each other.</li>
</ul>

**6.Beta.38.0 (October 2, 2017):**

<ul>
    <li>Made some style changes to the code.</li>
    <li>Removed obsolete classes and renamed a few classes.</li>
    <li>Opening the giveaway description is now mandatory in Enter/Leave Giveaway Button.</li>
</ul>
<p>Added the following features:</p>
<ul>
    <li>2.16 Giveaway Popup</li>
</ul>

**6.Beta.37.3 (September 29, 2017):**

<ul>
    <li>Fixed a bug that was not remembering some data.</li>
    <li>Fixed a bug that was preventing Multiple Giveaways Creator from creating giveaways.</li>
</ul>

**6.Beta.37.2 (September 29, 2017):**

<ul>
    <li>Fixed a bug that was not allowing the user to delete/undelete comments.</li>    
    <li>Fixed a bug in Multiple Giveaways Creator that was not showing the correct name/exporting games with quotes in their title.</li>
</ul>

**6.Beta.37.1 (September 29, 2017):**

<ul>
    <li>Fixed a bug in Comment Formatting Helper that was not remembering the choice for uploading images.</li>
</ul>

**6.Beta.37.0 (September 29, 2017):**

<ul>
    <li>localStorage data has been moved back to GM storage, due to size limitations and other factors (closes <a href="https://github.com/revilheart/ESGST/issues/27">#27</a>).</li>
    <li>Fixed a bug in Endless Scrolling that was not showing the correct link for page divisors  (closes <a href="https://github.com/revilheart/ESGST/issues/28">#28</a>).</li>
    <li>You can now upload images to Comment Formatting Helper through Imgur (closes <a href="https://github.com/revilheart/ESGST/issues/26">#26</a>).</li>
</ul>

**6.Beta.36.5 (September 28, 2017):**

<ul>
    <li>When importing/exporting/deleting data you can now see how much size each type of data is takin g in the storage and how much is being used by computer/browser storage (closes <a href="https://github.com/revilheart/ESGST/issues/21">#21</a>).</li>
    <li>You can now specify how often you want Header Refresher to refresh.</li>
    <li>Hitting the Enter key in the input fields on Advanced Giveaway Search now triggers the search (closes <a href="https://github.com/revilheart/ESGST/issues/23">#23</a>).</li>
</ul>

**6.Beta.36.4 (September 26, 2017):**

<ul>
    <li>Revamped all tables that used the class ".UGDData", which does not exist anymore.</li>
    <li>Added a couple options to User Giveaways Data that allow you to gather stats about the user's playtime/achievements from won giveaways (currently it cannot check playtime/achievements for DLCs/packages).</li>
</ul>

**6.Beta.36.3 (September 24, 2017):**

<ul>
    <li>Fixed image borders for giveaways with missing image.</li>
    <li>Added the new search parameters to Advanced Giveaway Search.</li>
</ul>

**6.Beta.36.2 (September 21, 2017):**

<ul>
    <li>Fixed a bug that was happening when commenting in giveaways.</li>
    <li>Fixed a bug that was preventing Search Magnifying Glass Button from working.</li>
</ul>

**6.Beta.36.1 (September 16, 2017):**

<ul>
    <li>Added the option to import/export using Dropbox.</li>
</ul>

**6.Beta.36.0 (September 16, 2017):**

<ul>
    <li>Fixed a couple bugs.</li>
</ul>
<p>Added the following features:</p>
<ul>
    <li>3.3 Close/Open Discussion Button</li>
</ul>

**6.Beta.35.4 (September 16, 2017):**

<ul>
    <li>Fixed a bug that was preventing features from loading in the main page (closes <a href="https://github.com/revilheart/ESGST/issues/13">#13</a>).</li>
    <li>Fixed a bug in Header Refresher (closes <a href="https://github.com/revilheart/ESGST/issues/12">#12</a>).</li>
    <li>Fixed a bug in Comment Formatting Helper that was not adding the selected text as title to links/images (closes <a href="https://github.com/revilheart/ESGST/issues/11">#11</a>).</li>
</ul>

**6.Beta.35.3 (September 15, 2017):**

<ul>
    <li>Removed obsolete functions and made minor style changes to the code.</li>
    <li>Shortcut Keys has been separated into options so that you can decide which shortcuts to enable.</li>
    <li>Header Refresher should now refresh individually for different accounts (closes <a href="https://github.com/revilheart/ESGST/issues/4">#4</a>).</li>
</ul>

**6.Beta.35.2 (September 13, 2017):**

<ul>
    <li>Added options to Giveaway Winning Chance/Ratio that allow you to customize how the chances/ratios are shown better (by not adding 1 to the calculation and/or showing the advanced chance/ratio along with the basic one).</li>
    <li>Fixed a bug in Train Giveaways Extractor that kept extracting when clicking on "Cancel".</li>
</ul>
<p>Removed the following features:</p>
<ul>
    <li>Entries Remover - <a href="https://www.steamgifts.com/discussion/L5URh/">Implemented on SG.</a></li>
</ul>

**6.Beta.35.1 (September 8, 2017):**

<ul>
    <li>Fixed a bug in Endless Scrolling that was not loading One-Click Hide Giveaway Button for pages 2+.</li>
    <li>Fixed a bug in Train Giveaways Extractor that was getting the extraction stuck in an endless loop (closes <a href="https://github.com/revilheart/ESGST/issues/407">#407</a>).</li>
</ul>

**6.Beta.35.0 (September 8, 2017):**

<ul>
    <li>Fixed the script for the recent <a href="https://www.steamgifts.com/discussion/0X36E/">SG changes</a> (closes <a href="https://github.com/revilheart/ESGST/issues/408">#408</a>).</li>
</ul>
<p>Added the following features:</p>
<ul>
    <li>2.22 Stickied Giveaway Countries</li>
</ul>

---

Older changelog is only available in the source code of the script.
