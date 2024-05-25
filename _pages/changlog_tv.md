---
layout: page
title: What's New tvOS
include_in_header: true
include_in_footer: false
locale: en
---

# Changelog

## **Version 1.0.27**

- IMPROVED: improve Chinese subtitle matching logic
- IMPROVED: The cloud service automatically loads subtitles and does not distinguish between uppercase and lowercase letters
- FIXED: fix issue that some emby may not update playback time properly
- FIXED: fix issue that the Emby details page may not be displayed
- FIXED: fix issue that some external ass subtitles can not be loaded for Emby/Jellyfin
- FIXED: fix connection issue with custom port for Synology protocol
- FIXED: fix playback issue with video from Google Drive using default player
- FIXED: fix issue that some FTP may not be connected
- FIXED: fix issue that can not view all files in the folder for Google Drive
- FIXED: fix issue that subtitle not auto selected when there is only one subtitle available for emby
- FIXED: fix issue that can not resume from library after switch drive for aliyun drive

## **Version 1.0.26**

date: 2024-04-08 (build 74) 

- ADDED: add Top Shelf support for Emby
- ADDDED: add upcoming area to Emby/Jellyfin home
- ADDED: add search subtitle feature to player more panel
- ADDED: add subtitle font size adjustment feature to player more panel
- ADDED: add subtitle color adjustment feature to player more panel
- ADDED: add subtitle position adjustment feature to MPV player
- IMPROVED: change default path to /dav for WebdAV protocol

## **Version 1.0.25**

date: 2024-03-11 (build 73) 

- ADDED: add cluster search feature to emby
- IMPROVED: improve voice search input box to automatically convert traditional to simplified Chinese when the traditional to simplified switch is turned on
- FIXED: fix issue that search not working with some cloud services
- FIXED: fix issue that playback progress not stopped correctly after select episode for Emby

## **Version 1.0.24**

date: 2024-02-28 (build 72) 

- FIXED: fix crash issue when auto play next video

## **Version 1.0.23**

date: 2024-02-26 (build 71) 

- ADDED: add Siri voice search Traditional Chinese to Simplified Chinese feature
- IMPROVED: improve remote protocol login user experience
- FIXED: fix issue that playback record of aliyun drive may not be loaded
- FIXED: fix issue that Synology with two-step verification can not use Quick Connect ID to login
- FIXED: fix issue that WebDAV video may not be played

## **Version 1.0.22**

date: 2024-02-19 (build 70) 

- ADDED: add Traditional Chinese support
- ADDED: add support to display iso files for cloud service
- IMPROVED: improve MPV player performance
- FIXED: fix issue that playback record of aliyun drive may not be loaded

## **Version 1.0.21**

date: 2024-01-30 (build 69) 

- ADDED: add aliyun drive playback history sync support
- ADDED: add user agent setting for IPTV
- FIXED: fix issue that Emby playback history not saved
- FIXED: fix issue that Emby can not connect when address end with slash

## **Version 1.0.20**

date: 2023-12-3 (build 68) 

- ADDED: add tiff and bmp image format support
- ADDED: add MPV cache duration and size settings
- ADDED: add MPV cache to disk settings, clear cache after player closed
- FIXED: fix issue that IPTV may crash when switch channel
- FIXED: fix issue that remote protocol login may crash
- FIXED: fix issue that player progress not sync with iOS control center

## **Version 1.0.19**

date: 2023-11-21 (build 67) 

- ADDED: add MPV settings
- ADDED: add QR code login support to BaiduPan
- ADDED: add support to play with Infuse
- FIXED: fix issue that password with space can not login

## **Version 1.0.18**

date: 2023-08-29 (build 66) 

- ADDED: add resource drive support for aliyun drive
- FIXED: fix issue that screen saver may be shown during playback
- FIXED: fix issue that file size calculation error

## **Version 1.0.17**

date: 2023-07-25 (build 65) 

- FIXED: fix issue that favorited SMB folder can not be opened
- FIXED: fix issue that Quick Connect ID can not be used for Synology
- FIXED: fix possible crash issue caused by network library
- FIXED: fix issue that IPTV playback may crash

## **Version 1.0.16**

date: 2023-05-30 (build 64) 

- ADDED: add feature load subtitle from cloud folder
- ADDED: add audio and subtitle preferred language setting
- IMPROVED: improve user experience of dragging slider for video player
- FIXED: fix issue that some subtitle may not automatically loaded
- FIXED: fix issue that playback control may not shown when video is paused

## **Version 1.0.15**

date: 2023-04-20 (build 63) 

- ADDED: add aliyun drive support
- ADDED: add playback info to control center
- ADDED: add video preference settings for Emby
- ADDED: add iCloud sync switch for Emby
- ADDED: add close subtitle option
- IMPROVED: improve the player pause after the gesture slide fast positioning user experience
- FIXED: fix SMB playback issue with MPV player

## **Version 1.0.14**

date: 2023-03-07 (build 62) 

- ADDED: add jellyfin support
- ADDED: add SMB support for mpv player
- ADDED: add DAT video format support
- ADDED: add auto load danmaku file feature
- IMPROVED: upgrade mpv version to 0.35.1
- FIXED: fix issue that remote IPTV can not be added
- FIXED: fix issue of opening the root directory of the favorited directory
- FIXED: fix issue that favorited directory not displaying starred icon
- FIXED: fix issue that deleting favorited directory not updating home page

## **Version 1.0.12**

date: 2023-02-07 (build 60) 

- FIXED: fix issue that recent playback history can not be resumed
- FIXED: fix issue that subtitles within same directory can not be loaded

## **Version 1.0.11**

date: 2022-10-06 (build 52) 

- Redesign home view
- Add playback history to home view

## **Version 1.0.8**

date: 2022-08-01 (build 48) 

- ADDED: add lab area on settings page
- ADDED: add SFTP support
- FIXED: fix issue that the image viewer does not display full screen
- FIXED: fix issue that the picture browser cannot preview pictures occasionally
- FIXED: fix issue that the picture browser did not display the selected picture
- FIXED: fix issue thatvideo player does not remember the selected inner sub
- FIXED: fix issue that some media library contents of Emby are not fully displayed
- FIXED: fix issue that IPTV does not pause when entering the background

## **Version 1.0.7**

date: 2022-06-28 (build 47) 

- ADDED: add search feature to cloud service
- ADDED: add photo browser
- ADDED: add thumbnail support to cloud videos (if cloud serivce supported)
- ADDED: close player when playback ended
- FIXED: fix issue that playback will be paused when return from playlist control using MPV player
- FIXED: fix auto refresh issue with IPTV
- FIXED: fix issue that the playlist shows the whole list when entering the playlist under IPTV group
- FIXED: fix issue that can not delete local M3U/TXT files
- FIXED: fix playback issue with some WebDAV using mpv player

## **Version 1.0.6**

date: 2022-06-10 (build 46) 

- ADDED: SMBv3.0.2 switch added to settings
- ADDED: IPTV adds the ability to upload local M3U/TXT files
- ADDED: IPTV player adds MPV player (controlled by player options)
- IMPROVED: Optimize the user experience of searching channels on IPTV
- FIXED: fixe issue of not being able to use channel +/- to quickly switch IPTV channels
- FIXED: fix issue of Emby search result page jumping
- FIXED: fix issue that that FTP connection can only use port number 22
- FIXED: fix issue that some IPTV connections cannot be played

## **Version 1.0.4**

date: 2022-06-01 (build 44) 

- ADDED: add playback history to IPTV
- ADDED: add TXT format support to IPTV
- ADDED: add search channel feature to IPTV
- ADDED: add back to emby home button to emby profile page
- ADDED: add aspect ratio feature to player
- ADDED: add forward/backward step feature to player
- IMPROVED: change video quality to origin for BaiduPan
- IMPROVED: improve user experience for IPTV playback selection
- FIXED: fix issue that edit IPTV not working
- FIXED: fix issue that some tvg logo can not displayed
- FIXED: fix issue that last played channel not remembered for IPTV
- FIXED: fix issue that playback speed not updated after changed speed
- FIXED: fix issue that playback history not saved for Emby

## **Version 1.0.3**

date: 2022-05-12 (build 43) 

- ADDED: add mpv optimization switch control
- FIXED: fix issue that playback history not updated when close video player
- FIXED: fix issue that speed indicator always shown for default video player
- FIXED: fix issue that video title not updated when auto play next item


## **Version 1.0.2**

date: 2022-05-05 (build 42) 

- ADDED: add IPTV entrance
- ADDED: add iCloud sync feature to IPTV
- ADDED: add arrow down(up) to show(hide) info tab
- ADDED: add overview info to video info tab
- ADDED: add playback history to cloud video files
- ADDED: add reorder feature to cloud files
- FIXED: fix emby reorder related bugs
- FIXED: fix issue that focus state of info tab list
- FIXED: fix issue that can not change playlist
- FIXED: fix issue that info not updated when change playing item
- FIXED: fix issue that playing title not updated when change playing item
- FIXED: fix issue that metadata provider can not changed

## **Version 1.0.1**

date: 2022-04-24 (build 41) 

- ADDED: add audio track selection in swipe down panel for video player
- ADDED: add subtitle track selecton in swipe down panel for video player
- ADDED: add playlist selection in swipe down panel for video player
- FIXED: fix issue that play from beginning not working for emby
- FIXED: fix issue that video resolution not displayed

## **Version 1.0.1**

date: 2022-04-18 (build 40) 

- initial release