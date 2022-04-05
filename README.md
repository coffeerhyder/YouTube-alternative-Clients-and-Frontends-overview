
## **A lot of these projects are untested by the maintainer(s) of this GitHub project so use at your own risc!**
# YouTube-alternative-Clients-and-Frontends-overview
Overview of alternative YouTube Clients and Frontends along with SponsorBlock and or Return YouTube Dislike integration

## Abbreviations
Abbreviation | Meaning
--- | ---
ADB | Adblock/Adblocker
ADBW | Adblock whitelisting and or SponsorBlock whitelisting
BP | Background Playback
PiP | Picture in Picture (sometimes called "Popup Player")
SB | SponsorBlock
YT | YouTube

# Useful YT additions
## [SponsorBlock](https://sponsor.ajay.app/)
A lot of YT videos contain sponsored segments that are part of the video and thus won't get blocked using ordinary adblockers.  
What started to only skip segments containing sponsored content can now even skip other categories like intros and outros or even skip right to the point of a video, the so called 'highlight'([Example video](https://www.youtube.com/watch?v=b9FEpB36wZw)).  
Users can vote for video segments will then be automatically skipped.
It is available as addon for all major browsers and is also included in a lot of 3rd party YT clients.  
**Does the usage of SponsorBlock have an influence on creators' revenue?**  
According to a [video of LinusTechTips](https://www.youtube.com/watch?v=b9FEpB36wZw) published in feb. 2020 it does not.
Some people even made projects that can free downloaded YT videos of such segments such as [SponSkrub](https://github.com/faissaloo/SponSkrub).

## [Return YouTube Dislike](https://github.com/Anarios/return-youtube-dislike)
Return YouTube Dislike is an open-source extension that returns the YouTube dislike count.

# Overview
**If you want to sort the table down below you can go with [this solution](https://stackoverflow.com/questions/42843288/is-there-any-way-to-make-markdown-tables-sortable).**  
Project | Platforms | Open Source | Free | Based on | ADB | SB | Dislikes | Login | BP | DLs | ADBW
--- | --- | --- | --- |--- |--- |--- |--- |---  |---  |---  |---
[Browser](https://github.com/coffeerhyder/YouTube-alternative-Clients-and-Frontends-overview#browser) | All | ✅ | ✅  |--- |✅ |✅ |✅  |✅  |✅  | ✅ | ✅
[Vanced](https://github.com/coffeerhyder/YouTube-alternative-Clients-and-Frontends-overview#vanced) | Android | ❌ | ✅ | --- | ✅ | ✅ | ✅ | ✅ | ✅ | ❌ | ✅
[LibreTube](https://github.com/libre-tube/LibreTube) | Android | ✅ | ✅ | Piped | ✅ | ❌ | ❌ | ✅ | ✅ | ✅ | ❌
[NewPipe](https://github.com/TeamNewPipe/NewPipe) | Android | ✅ | ✅ | --- | ✅ | ❌ | ❌ | ❌ | ✅ | ✅ | ❌
[NewPipe x SponsorBlock](https://github.com/polymorphicshade/NewPipe) | Android | ✅ | ✅ | --- | ✅ | ✅ | ❌ | ❌ | ✅ | ✅ | ❌
[SmartTubeNext](https://github.com/yuliskov/SmartTubeNext) | AndroidTV | ✅ | ✅ | --- | ✅ | ✅ | ❌ | ✅ | ✅ | ❌ | ❌
[KODI](https://github.com/coffeerhyder/YouTube-alternative-Clients-and-Frontends-overview#KODI) | All | ✅ | ✅  |--- |✅ |✅ | ❌  |✅  |✅  | ❌ | ❌
### TODO add to overview-table:
**Android:**
* Piped https://github.com/TeamPiped/Piped Open source alternative frontend for YouTube
*  ~~Pure Tuber: https://www.puretuber.com/en or https://play.google.com/store/apps/details?id=free.tube.premium.advanced.tuber~~ **DO NOT USE!** Several people have warned about this! Seems to be a commercial version of NewPipe.
* ~~YouTube Pink~~ re-theme of [Vanced](https://github.com/coffeerhyder/YouTube-alternative-Clients-and-Frontends-overview#vanced)
* GoTube: https://play.google.com/store/apps/details?id=premium.gotube.adblock.utube
* SkyTube https://github.com/SkyTubeTeam/SkyTube
* SkyTube Extra https://android.izzysoft.de/repo/apk/free.rm.skytube.extra
* MusicPiped https://github.com/deep-gaurav/MusicPiped
* VueTube https://github.com/Frontesque/VueTube
* SongTube https://github.com/SongTube/SongTube-App | iOS + Android
* DVD https://f-droid.org/de/packages/org.yausername.dvd/ an Android front-end for [yt-dlp](https://github.com/yt-dlp/yt-dlp) (an extremely powerful downloader with support for hundreds of sites)
* ASTRON https://github.com/astroncc/astron_app (**not** open source)
* DailyTube https://play.google.com/store/apps/details?id=free.daily.tube.background
* FloatTube https://play.google.com/store/apps/details?id=com.xpp.tubeAssistant
* YouTube Thunder https://www.samapkstore.com/2022/02/youtube-thunder.html
* YouTube Pro https://www.samapkstore.com/2021/04/download-youtube-pro.html

**iOS:**
* uYou: https://github.com/MiRO92/uYou-for-YouTube
* uYouPlus: https://github.com/qnblackcat/uYouPlus a modded version of the official iOS app (arguably the most feature-complete alternative to Vanced)
* Video Lite: https://apps.apple.com/de/app/video-lite-no-ads/id1598997500
* YubePip: https://apps.apple.com/de/app/yubepip-youtube-pip-player/id1591269922
* iSponsorBlock: https://apps.apple.com/de/app/vinegar-tube-cleaner/id1591303229
* Brave Browser (includes YT adblocker): https://apps.apple.com/de/app/brave-private-internet-browser/id1052879175
* Yattee: https://github.com/yattee/yattee
* YouTube++ (no legit link yet)

**Desktop:**
* KODI + KODI and TubeCast https://github.com/enen92/script.tubecast
* MyTube https://www.microsoft.com/en-us/p/mytube/9wzdncrcwf3l#activetab=pivot:overviewtab
**Browser / alternative front-ends:**
* Invidious https://invidious.io/
* Viewtube https://github.com/ViewTube/viewtube-vue | https://viewtube.io/

**🔸Work in progress:**  
*  [ReVanced](https://revanced.app/)  
*  [VueTube](https://github.com/Frontesque/VueTube)  
*  [Hyperion](https://discord.gg/dNZ2Ay4gga)  
*  [Eclipsed](https://discord.gg/SDsaQqvGJF)  
*  [WebTube](https://discord.gg/zypWQvxuGe)

# More details
Some of the projects in the list are worth adding some extra information which you will find below.
## Browser
Use a browser of your choice + open source adblocker like [U Block Origin](https://ublockorigin.com/) + [SponsorBlock](https://sponsor.ajay.app/) addon + [Return YouTube Dislike](https://github.com/Anarios/return-youtube-dislike) addon + [Return YouTube Dislike](https://github.com/coffeerhyder/YouTube-alternative-Clients-and-Frontends-overview#return-youtube-dislike) addon.  
Other addons worth mentioning: [Enhancer for YouTube](https://www.mrfdev.com/enhancer-for-youtube)
**Browser on mobile**
On mobile, you'll need to install a browser, like [IceRaven](https://github.com/fork-maintainers/iceraven-browser) or [KiwiBrowser](https://kiwibrowser.com/), then install the addons from their respective adddon store.  
Depending on the browser, you'll additionally need to install a user script for background playber. Alternatively, the [Brave browser](https://brave.com/) supports background playback OOTB (needs to be enabled first) and a build in ad-blocker, but no extension / add-on support.
## Vanced (old website [vancedapp.com](https://vancedapp.com/))
Vanced has been [officially shut down](https://telegra.ph/Vanced-Discontinuation-03-19) but to this moment the app is still working but it might be harder to find and install.  
At this moment it's unclear whether or not someone will resume this project but there is a related subreddit in which such information can most likely be found in the future: [/r/AfterVanced](https://www.reddit.com/r/AfterVanced/)
**Be especially careful not to install fakes or adware.  
There is a re-theme of Vanced called 'YouTube Pink'. Be careful with this as well!**  
As of 2022-03-26 the 'old' Vanced Manager is still working as is contains a mirror as fallback where it gets the Vanced APKs and Vanced MicroG from so all you have to do to get Vanced is to find a source for the Vanced Manager.
Below is a collection of links that may or may not lead to genuine ways to install Vanced:
* https://www.reddit.com/r/Vanced/comments/tdzmgw/other_how_to_install_and_use_vanced_postshutdown/
* https://www.reddit.com/r/AfterVanced/comments/tk1fdr/so_you_want_to_install_andor_reinstall_vanced/
* https://www.apkmirror.com/apk/team-vanced/
* https://vanced.esherloon.com/ ([on reddit](https://www.reddit.com/r/AfterVanced/comments/tj6dsv/release_youtube_vanced_mirror_and_custom_vanced/))
* https://t.me/Unofficial_YouTube_Vanced_Module
* https://github.com/pixincreate/Vanced
* https://github.com/ReVancedTeam
* https://revanced.app/
* https://www.reddit.com/r/revancedapp/comments/tjb89y/official_revanced_subreddit/
* https://www.reddit.com/r/AfterVanced/comments/tpmzcb/how_to_change_the_channel_url_in_vanced_manager/
* https://www.reddit.com/r/AfterVanced/comments/twzq2s/the_sticky_of_stickies_all_the_important_stuff/
# [KODI](https://kodi.tv/download/)
KODI + [YT Addon](https://github.com/anxdpanic/plugin.video.youtube) + [SponsorBlock Addon](https://github.com/siku2/script.service.sponsorblock)  
**Alternative**: KODI + New YT Addon [Tubed](https://github.com/anxdpanic/plugin.video.tubed) (no SponsorBlock support yet)  
KODI + YT can be a bit complex to setup and some features like access to the "Watch later" YT playlist can be harder to accomplish.
1. Install the mentioned addons and setup YT with your personal YT API keys as explained [here](https://seo-michael.co.uk/how-to-create-your-own-youtube-api-key-id-and-secret/).
2. The watch later playlist is not accessible by default because YT has changed their API.  
If you are frequently using the watch later playlist, get your watch later playlistID as explained [here](https://github.com/anxdpanic/plugin.video.youtube/issues/69#issuecomment-766843932) and put it in the corresponding field in the KODI YT addon settings.  
It is recommended to store this internal playlistID as it never changes obtaining it from Google can be a bit time consuming.
3. Extra hint regarding handling of the watch later playlist:
By default KODI will auto-remove all watched items from the watch later playlist.  
If you do not like this behavior you can disable it in the YT addon settings.
4. SponsorBlock settings  
If you're using SponsorBlock in KODI, check out the settings by Clicking on **options** when the YT addon is highlighted -> SponsorBlock
# Misc
## Similar projects
* https://github.com/mendel5/alternative-front-ends 
* https://gist.github.com/SkyyySi/1b621c7c20ae7e0865a8ac428156c1cf
* https://www.reddit.com/r/AfterVanced/comments/tigkow/youtube_vanced_alternatives/
* https://www.reddit.com/r/AfterVanced/comments/tiqzon/youtube_music_vanced_alternatives/
## TODOs for this project
* Update main table columns: Maybe remove "Adblock" and "Adblock Whitelisting" column: All YT alternatives either have no ads or block them and nearly none provides Adblock-Whitelisting (only Vanced?)
* Update main table: Test- and add remaining projects
* Link more projects for category "Browser"
