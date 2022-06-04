---
layout: page
title: What's New
include_in_header: true
include_in_footer: false
locale: en
---

# Changelog

## **Version 1.1.44**

- ADDED: add delete playback history feature
- ADDED: add cloud 139 support
- ADDED: add a switch to control wheather resume playback from background
- FIXED: fix issue that connections not updated in time for iPad
- FIXED: fix issue that EPG may not updated in time
- FIXED: fix issue that some IPTV source parse failed
- FIXED: fix issue that local IPTV connection can changed file url
- FIXED: fix issue that can not connect emby for some case
- FIXED: fix issue that error message of networking error for Emby
- FIXED: fix issue that external subtitle not remembered for default video player

## **Version 1.1.43**

date: 2022-05-25 (build 149)

- ADDED: add txt format support to IPTV
- ADDED: add progress seek support to IPTV
- ADDED: add aspect ratio support to IPTV
- ADDED: add playback history to IPTV
- ADDED: add new file theme
- ADDED: add playback history support to local videos
- IMPROVED: show selected file number when editing files
- FIXED: fix issue that play audio from BaiduPan sometimes stucked
- FIXED: change to play origin file for BaiduPan
- FIXED: fix issue that reorder connections not working 
- FIXED: fix issue that some tvg logo can not displayed
- FIXED: fix issue that items number not updated after moved files

## **Version 1.1.42**

date: 2022-05-18 (build 148)

- ADDED: add image thumbnail support to WebDAV
- ADDED: add EPG support to IPTV
- ADDED: add channel list support to IPTV
- ADDED: add search feature to IPTV
- ADDED: add more subtitle online service to video player
- ADDED: add switch to control double tap to refresh library for Emby
- IMPROVED: improve user experience adding IPTV connection
- IMPROVED: improve user experience connecting to Synology with 2-Step verification
- IMPROVED: remove blank space in batch rename format mode
- IMPROVED: improve thumbnail cache for SMB
- FIXED: fix issue that navigation bar missing for Quark/115 of iPad
- FIXED: fix issue that parse some M3U always failed
- FIXED: fix issue that 189 family can not be added
- FIXED: fix issue that local M3U connection synced with iCloud
- FIXED: fix issue that video of 115 sometime can not be played

## **Version 1.1.41**

date: 2022-05-11 (build 142)

- ADDED: add support to Cloud 189
- ADDED: add image and video preview support to PikPak
- FIXED: fix some crash when click screencast button
- FIXED: fix issue that screencast result turns blank
- FIXED: fix issue that video from 115/PikPak/Quark can not resumed in library
- FIXED: fix issue that progress bar jumps when touching slider to seek for mpv player
- FIXED: fix issue that mp4 video file can not played with AVPlayer issue for 115 cloud
- FIXED: fix issue pip not shown for 115 cloud
- FIXED: fix issue that start pip always failed for some devices

## **Version 1.1.40**

date: 2022-05-08 (build 140)

- ADDED: add screencast switch to lab
- Added: adds support for subtitle background color feature for MPV player
- ADDED: add image preview support to 115
- ADDED: add image and video thumbnail support for Quark
- IMPROVED: improve IPTV user experience
- FIXED: fix issue that black border at the bottom of IPTV player
- FIXED: fix issue that address cannot be modified when editing the connection
- FIXED: fix issue that can't view pictures with 115
- FIXED: fix issue that moving files not working with 115
- FIXED: fix issue that incorrect display of file size in the search result of 115
- FIXED: fix issue that moving files not working with PikPak
- FIXED: fix issue that cannot view large images with  OneDrive E5 account

## **Version 1.1.39**

date: 2022-05-04 (build 138)

- ADDED: add iCloud sync feature to IPTV
- ADDED: add reorder feature to IPTV
- ADDED: add channel list to IPTV
- ADDED: add settings for IPTV
- ADDED: add reorder feature to connections
- ADDED: add transparency setting to video player controls
- ADDED: add 5 seconds fast forward option to video player
- IMPROVED: improve user experience using gesture to adjust volume and brightness for video player
- FIXED: fix issue that the file list maybe out of order when batch renaming
- FIXED: fix issue that text maybe truncated when selecting video verison in Emby
- FIXED: fix issue that click link in local markdown file may cause crash
- FIXED: fix issue that SMB port can not be customized
- FIXED: fix issue that not able to connect to some SMB services
- FIXED: fix issue that external subtitle selection not saved


## **Version 1.1.38**

date: 2022-04-24 (build 134)

- ADDED: add tag group feature to connections
- ADDED: move favorited cloud folders to File tab
- ADDED: add settings entrance for emby
- ADDED: add media library management feature for emby
- ADDED: add toggle switch to control display unwatched number for emby
- FIXED: fix issue that copy to filebox
- FIXED: fix issue that lock gesture button not shown in portraint mode for video player
- FIXED: fix issue that continue watching not updated in time
- FIXED: fix issue that some library do not show view all for emby
- FIXED: fix layout issue with audio player in iPhone 7

## **Version 1.1.37**

date: 2022-04-17 (build 132)

- ADDED: add format based batch rename feature
- ADDED: add global search to Quark service
- ADDED: add context menu to favorite cloud folder
- ADDED: add battery level view to video player
- IMPROVED: improve user experience of playback rate
- FIXED: fix issue that local WAV music can not be played with audio player
- FIXED: fix playlist order issue for video player
- FIXED: fix issue that can not resume video from mounted folder
- FIXED: fix issue that no error alert when login failed with PikPak

## **Version 1.1.36**

date: 2022-04-10 (build 130)

- ADDED: add global search to BaiduPan/GoogleDrive/OneDrive
- ADDED: add video and audio track memory for emby series
- ADDED: add activity indicator to cloud service searching
- ADDED: add switch control to save screenshot with one click to video player
- IMPROVED: improve search experience of emby
- FIXED: fix video color issue with HDR playing using MPV player
- FIXED: fix issue that multiple players may play at the same time when playing through URL Scheme
- FIXED: fix issue that full screen setting for video player not working with MPV player

## **Version 1.1.35**

date: 2022-04-02 (build 128)

- ADDED: add view media info feature to MPV player
- ADDED: add help function to some remote type login
- ADDED: add iCloud sync switch to some cloud services
- FIXED: fix issue that type Genre and Studio in search result of emby not supported
- FIXED: fix issue that downloaded file not shown in files list
- FIXED: fix issue that connection type can be changed when editing

## **Version 1.1.33**

date: 2022-03-30 (build 122)

- ADDED: add option to control iCloud sync for single connection
- IMPROVED: improve icon of subtitle menu
- IMPROVED: improve logics of Quark cookie expires issue
- IMPROVED: improve user experience of quick emby search
- FIXED: fix issue that mounted local folder can not open after reboot device
- FIXED: fix issue that status bar always show when playing video using iPad
- FIXED: fix issue that tabbar touch delay with emby
- FIXED: fix issue that audio player duration is empty in now playing center
- FIXED: fix issue that video from OneDrive can not be resumed in library
- FIXED: fix issue that rename file not working with PikPak and Quark
- FIXED: fix time format issue with Quark

## **Version 1.1.32**

date: 2022-03-28 (build 120)

- ADDED: add change pasword feature to Emby
- ADDED: add Quark support
- ADDED: add context menu to edit lrc file
- ADDED: add switch to control prefer load local lyrics
- ADDED: add media source name to media codec section for emby
- FIXED: fix issue that artwork will be clipped of emby item
- FIXED: fix issue that video player will be closed after saved image
- FIXED: fix issue that mp4 video served on SMB can not played with AVPlayer
- FIXED: fix issue that duration can not parsed from local FLAC files
- FIXED: fix some connection issue with PikPak connection
- FIXED: fix issue that audio player not paused when playing video using mpv player
- FIXED: fix issue that moving files not working with Google Team Drive
- REMOVED: remove MEGA support

## **Version 1.1.31**

date: 2022-03-24 (build 118)

- ADDED: add mount local folder feature
- ADDED: add PikPak support
- ADDED: add button to refresh continue wathcing section
- ADDED: add switch to prefer use system player
- IMPROVED: improve user experience of emby search
- IMPROVED: improve user experience of emby item detail page
- FIXED: fix issue that artwork of emby item maybe interrupted
- FIXED: fix issue that some Chinese subtitles may not loaded for emby
- FIXED: fix issue that app may crash when enter emby
- FIXED: fix issue that font settings not working for default video player
- FIXED: fix issue that some video on SMB can not be played

## **Version 1.1.30**

date: 2022-03-16 (build 116)

- ADDED: add adjust subtitle position feature to MPV player
- ADDED: add subtitle border settings to MPV player
- ADDED: add adjust subtitle delay feature to video player
- ADDED: add groups to IPTV
- ADDED: add favorite channel to IPTV
- ADDED: add switch control to include subtitles in screenshot for mpv player
- ADDED: add toggle password button to remote login form
- ADDED: add mark played feature to emby detail page
- IMPROVED: improve UI of upcoming list of emby
- IMPROVED: improve UX of adjust font size in video player
- FIXED: fix issue that OneDrive file list can only display max to 200 items
- FIXED: fix issue that delete file confirmation switch not working for remote files
- FIXED: fix issue that playing music item not highlighted in playlist
- FIXED: fix artwork aspect ratio issue of of emby

## **Version 1.1.29**

date: 2022-03-06 (build 112)

- ADDED: add group items count display to IPTV
- FIXED: fix issue that UI elements not displayed correctly in settings page
- FIXED: fix issue that some video's audio and subtitle track will not be loaded correctly when playing with MPV player
- FIXED: fix issue that new refresh items will be reset in emby library page

## **Version 1.1.28**

date: 2022-03-06 (build 110)

- ADDED: add create text file feature
- ADDED: add vob video format support
- ADDED: add TNAS protocol support
- ADDED: add switch control to refresh IPTV subscriptions
- ADDED: add playlist supprt to emby
- ADDED: add force to use Chinese subtitle for emby in lab
- ADDED: add groups to IPTV
- IMPROVED: improve user experience of lock button in video player
- FIXED: fix issue that mpv player not play next item when play to end
- FIXED: fix crash issue that when mpv can not get video width and height info
- FIXED: fix crash issue that when deleting watched item of emby

## **Version 1.1.27**

date: 2022-02-27 (build 108)

- ADDED: add rotate screen to MPV player
- ADDED: add font size setting to MPV player
- ADDED: add custom font setting to MPVPlayer
- ADDED: add quick access to add server
- FIXED: fix issue that selection state of audio track is wrong with MPV player
- FIXED: fix issue that auth view not disappear when authed with OneDrive
- FIXED: fix issue that the name of subtitle loaded from cloud service is wrong for MPV player
- FIXED: fix issue that subtitle with same file name of the video not automatically loaded when played using MPV player
- FIXED: fix issue that MPV player not paused when searching subtitle
- FIXED: fix issue that video can not be played again when play to end using MPV player
- FIXED: fix issue that cover incorrect in emby item detail page when item type is Movie/Series 

## **Version 1.1.26**

date: 2022-02-20 (build 106)

- ADDED: add long press context menu to move top to saved account
- IMPROVED: optimize Emby search experience
- IMPROVED: optimize player buffer progress bar color
- FIXED: fixed issue where IPTV did not enter the IPTV player after entering the small window to resume
- FIXED: fixed issue where Emby might have two players playing at the same time
- FIXED: fixed issue that Emby My Favorite list could not be loaded
- FIXED: fixed issue that the shared shortcut folder in GoogleDrive could not be loaded
- FIXED: fixed issue that mpv player does not automatically load subtitles from the same directory
- FIXED: fix issue that cloud not load subtitle with the same filename of cloud service
- FIXED: fix issue that subtitles in the same directory are not loaded when resuming playback

## **Version 1.1.25**

date: 2022-02-08 (build 102)

- ADDED: add gesture to adjust brightness and volume to tv player
- ADDED: add play with system player to local and remote video files
- ADDED: add edit lyrics feature to audio player
- ADDED: add PiP to MPV and IPTV player
- ADDED: add import M3U playlist to IPTV
- ADDED: add long press context menu to preview playlist for IPTV
- ADDED: add refresh feature to all IPTV sources
- ADDED: add playback speed setting to long pressed gesture for video player
- ADDED: add switch to control whether display remain time for video player
- ADDED: add switch to control whether display playback history in library
- IMPROVED: trim whitespaces of login password
- IMPROVED: improve user experience of emby search
- FIXED: fix issue that remote url in library can not be resumed

## **Version 1.1.24**

date: 2022-02-02 (build 100)

- ADDED: add blur background to audio player
- ADDED: add artist display to audio player
- ADDED: add M3U file format support
- ADDED: add export m3u file to tv list
- ADDED: add screenshot feature to mpv player
- ADDED: add switch to use mpv player to video player settings
- FIXED: fix issue that screen will auto turn off when playing IPTV
- FIXED: fix issue that OneDrive can not connect other account
- FIXED: fix issue that file list file do not shown time of OneDrive


## **Version 1.1.23**

date: 2022-01-29 (build 98)

- ADDED: add new feature to lab
- IMPROVED: improve mpv performance
- FIXED: fix metadata missing for audio player
- FIXED: fix playback speed will be reset when playing next item using mpv

## **Version 1.1.22**

date: 2022-01-25 (build 96)

- ADDED: add lyrics support to audio player
- ADDED: add playlist support to audio player
- ADDED: add playback speed setting to audio player
- ADDED: add auto match metadata to audio player
- ADDED: add channel list support to emby
- ADDED: add hardware decode switch to mpv player
- IMPROVED: use filename to search subtitle
- FIXED: fix issue that can not edit metadata of local audio file
- FIXED: fix issue that app crash when playback time reach to end when using mpv player
- FIXED: fix issue that can not play next video using mpv player
- FIXED: fix issue that external subtitle not loaded when using mpv player
- FIXED: fix issue that music artist page display empty
- FIXED: fix issue that audio cloud not played in audio detail page of emby

## **Version 1.1.20**

date: 2022-01-18 (build 92)

- ADDED: add default cover to music player
- IMPROVED: improve function of mpv player for emby
- FIXED: fix issue that can not play audio from emby list
- FIXED: fix issue that selected video version not played for emby
- FIXED: fix issue that selected subtitle not loaded when playing video from emby
- FIXED: fix issue that playlist only show 12 items when playing epsidoes from emby

## **Version 1.1.19**

date: 2022-01-11 (build 90)

- ADDED: add auto load subtitle with same name of the playing video file  from cloud service
- ADDED: add playlist support to cloud service for cloud videos
- ADDED: add pinch gesture to zoom video player
- ADDED: add gesture settings for video player
- ADDED: add photo support to emby
- ADDED: add hide server address in connection tab
- IMPROVED: all fields in file information page can be copied via long pressed gesture
- FIXED: fix issue that in some sence emby connection always failed
- FIXED: fix issue that cover display in wrong aspect of emby list
- FIXED: fix issue that orientation of video player always fixed

## **Version 1.1.18**

date: 2021-12-18 (build 88)

- ADDED: add Jellyfin support
- ADDED: add switch Emby server to emby search page
- ADDED: add switch control of play controls for video player
- ADDED: add open network stream entrance at lab page
- ADDED: add URL Schemes at about page
- IMPROVED: improve connection speed of emby
- IMPROVED: add video version at emby media page
- IMPROVED: improve cover display ratio in emby search result page
- IMPROVED: improve user experience of video player control
- IMPROVED: fix issue that app may crash when enter some emby media page
- FIXED: fix issue that default subtitle not selected at emby media page
- FIXED: fix issue that can not load subtitle from Files app
- FIXED: fix issue that saved account not shown in connection tab
- FIXED: fix issue that file can not upload to root directory of OneDrive
- FIXED: fix issue that new created folder does not show when moving remote files
- FIXED: fix issue that batch rename may not working with cloud files
- FIXED: fix issue that status bar will shown in movie player in iPad


## **Version 1.1.17**

date: 2021-12-06 (build 85)

- ADDED: add more AppIcon
- ADDED: add FLV video format support
- ADDED: add favorite button to emby item profile page
- ADDED: add my favorites to emby
- ADDED: add sort to emby list
- ADDED: add double tap to back/fast forward to video player
- IMPROVED: improve user experience of emby
- IMPROVED: improve control view of movie player
- IMPROVED: improve lock button to control touch is disabled
- FIXED: fix issue that baidu vip can not play video in baidu pan
- FIXED: fix issue that download file from Google Drive always failed

## **Version 1.1.16**

date: 2021-11-28 (build 82)

- ADDED: Player new press-and-hold speed playback
- ADDED: add subtitle font picker to movie player
- ADDED: add aspect ratio picker to movie player
- ADDED: add m4v/m2ts video format support
- ADDED: add m4b audio format support
- ADDED: add heic image format support
- ADDED: add support to play shortcut videos for Google Drive
- ADDED: add a switch for whether to automatically find available services
- ADDED: add function that md5, sha1, sha256 can be copied by clicking on the file profile
- ADDED: add Emby video/audio/subtitle selection
- IMPROVED: improve experience of emby
- FIXED: fix issue that Google Drive file list is not fully displayed
- FIXED: fix issue that imported photos always store in root folder
- FIXED: fix Emby play record not sync server issue
- FIXED: fix issue that SFTP cannot connect with port other than 22

## **Version 1.1.15**

date: 2021-11-18 (build 70)

- ADDED: add Google Team Drive support
- ADDED: add search to Emby
- IMPROVED: improve Emby experience
- FIXED: fix issue that some user may can not connect with Emby
- FIXED: fix issue that can not load more with Emby list
- FIXED: try to fix issue that can not play video with some SMB connection
- FIXED: fix issue that icon of saved account not display correctly in iPad
- FIXED: fix issue that edited name of cloud service will be reset

## **Version 1.1.14**

date: 2021-11-14 (build 64)

- ADDED: add long press to sort saved cloud service
- IMPROVED: improve experience of Emby
- IMPROVED: cloud service now supports editing name
- IMPROVED: increase limit of images imported from photos
- FIXED: fix issue that some video can not be played with Emby
- FIXED: fix issue that iPad keyboard left and right arrow key can not fast forward and backward
- FIXED: fix issue that created folder is not displayed when moving files
- FIXED: fix issue that selected files not moved into newly created folder when moving files
- FIXED: fix issue that video play rate not synchronized in PiP mode
- FIXED: fix issue that local music and remote music can be played at the same time

## **Version 1.1.13**

date: 2021-11-09 (build 63)

- ADDED: add emby support
- ADDED: add video quality picker for aliyun drive in laboratory
- IMPROVED: improve view information of remote files
- IMPROVED: improve movie playback rate up to 4.0x
- FIXED: fix issue that incorrect file content after remote file update
- FIXED: fix issue that batch rename will crash on iOS 14

## **Version 1.1.12**

date: 2021-11-03 (build 62)

- ADDED: add batch rename
- ADDED: add drag and drop support to local file browser
- ADDED: add drag and drop files from other applications for upload
- ADDED: add delete confirmation switch
- FIXED: fix issue that folder size always calculating
- FIXED: fix issue that upload small file to OneDrive always fails

## **Version 1.1.11**

date: 2021-10-27 (build 61)

- ADDED: add picture in picture support for local video files
- IMPROVED: improve user experience of moving remote files
- FIXED: fix issue that some video files can not be played
- FIXED: fix issue that progress of remote video not updated when play video from remote list
- FIXED: fix issue that background audio glitch issue

## **Version 1.1.10**

date: 2021-10-23 (build 60)

- ADDED: add icon size picker to files
- FIXED: fix issue that share action always shown in photo browser
- FIXED: fix issue that can not turn off app lock when FaceID is enabled
- FIXED: fix issue that when app lock enabled, presented view will be dismissed when come back from background
- FIXED: fix issue that progress of recent movie not updated

## **Version 1.1.9**

date: 2021-10-20 (build 59)

- ADDED: add lyrics editor
- FIXED: fix issue that ID3 information not updated immediately
- FIXED: fix occasional crash when closing movie player
- FIXED: fix crash that playing a movie with AutoRotate switch turned off

## **Version 1.1.8**

date: 2021-10-17 (build 58)

- IMPROVED: improve access to select audio track in video player
- IMPROVED: improve access to select subtitle in video player
- FIXED: fix issue that access token of OneDrive expires not correctly handled
- FIXED: fix issue that artwork cloud not automatically updated when metadata is missing
- FIXED: fix issue that video streamed from AliyunDrive cloud not resumed from playback history
- FIXED: fix issue that recent history not removed when the source file deleted from remote server

## **Version 1.1.7**

date: 2021-10-13 (build 57)

- ADDED: add server type indicator to recent history
- IMPROVED: improve performance of playing large amounts music
- FIXED: fix issue that shuffle folder not working
- FIXED: fix thumbnail load issue with Dropbpx
- FIXED: fix title display issue with remote grid mode

## **Version 1.1.6**

date: 2021-10-10 (build 56)

- ADDED: add grid mode to remote browser
- ADDED: add thumbnail for cloud service
- ADDED: add thumbnail support for Text and PDF files
- ADDED: add Laboratory to explore experimental features
- FIXED: fix issue that delete video from video player does not clear playback history

## **Version 1.1.5**

date: 2021-10-06 (build 54)

- ADDED: add app lock
- ADDED: add a switch for whether to pop up the player in the music player
- ADDED: add thumbnail switch to video, audio and image files
- FIXED: fix issue incorrect display of play button status after switching videos
- FIXED: fix issue that the video player did not load the progress after switching videos


## **Version 1.1.4**

date: 2021-09-28 (build 53)

- FIXED: fix crash issue with iOS 14

## **Version 1.1.3**

date: 2021-09-27 (build 52)

- ADDED: add upload queue 
- ADDED: add large file upload support
- FIXED: fix issue that load non-image files when browsing local images
- FIXED: fix issue that audio and video files of WebDAV(HTTPS) can not be played under LAN
- FIXED: fix issue that remove file/folder not working with NFS

## **Version 1.1.2**

date: 2021-09-19 (build 50)

- FIXED: fix issue that copy to Filebox not working
- FIXED: Fix issue that video cannot be played with SMB connected through discovery
- FIXED: fix issue that the error "Socket is not connected" may appear for SMB connection
- FIXED: fix crash issue with non-exist nfs server

## **Version 1.1.1**

date: 2021-09-17 (build 48)

- ADDED: add preview remote text files
- ADDED: add upload file support to BaiduPan
- FIXED: fix issue that favorites folder may not be canceled
- FIXED: fix download issue with BaiduPan and Dropbox 

## **Version 1.1.0**

date: 2021-09-14 (build 47)

- ADDED: add auto discover network share services
- ADDED: add search files to remote server
- ADDED: add keybobard control for iPad when playing video
- ADDED: remember last side bar selection for iPad
- FIXED: fix issue that pull down to refresh arrow shown behind navigation bar
- FIXED: fix issue that subtitle shown in search scopes
- FIXED: fix issue that can not upload file with WebDAC connection
- FIXED: fix issue that duration always been zero when playing video from pCloud
- FIXED: fix list some folder issue with FTP connection

## **Version 1.0.24**

date: 2021-09-03 (build 45)

- ADDED: add MEGA support
- IMPROVED: optimze filename order
- FIXED: fix brightness view does not show while adjust screen brightness

## **Version 1.0.23**

date: 2021-09-01 (build 43)

- ADDED: add pull to refresh to cloud service
- IMPROVED: remember collapsed setting of connection entry
- FIXED: fix issue that OneDrive can not list folder

## **Version 1.0.22**

date: 2021-08-26 (build 42)

- ADDED: add import videos and photos from Photos app
- ADDED: add WMV video format support
- IMPROVED: improve favorite folders from cloud service 

## **Version 1.0.21**

date: 2021-08-23 (build 41)

- ADDED: add Baidu Pan support
- ADDED: add pCloud support
- ADDED: add long press folder to shuffle
- ADDED: add batch upload files and folders
- IMPROVED: improve video player adjust volume experience
- FIXED: fix issue that load subtitle from remote server can only load subtitle within root folder
- FIXED: fix issue that remember video play history switch does not work

## **Version 1.0.20**

date: 2021-08-17 (build 40)

- ADDED: add upload context menu to local files
- IMPROVED: improve search subtitle experience
- FIXED: fix issue that remote connect account maybe saved twice
- FIXED: fix issue that connect to server that does not have a nfs server will be crashed

## **Version 1.0.19**

date: 2021-08-14 (build 39)

- ADDED: add ability to preview local HTML files
- IMPROVED: connect with SMB that address contains share name now automatically connects the specified share
- FIXED: fix issue that move remote files only moves the first file
- FIXED: fix issue that playing ts format video get duration wrong
- FIXED: fix issue that can not play video with some SMB connection

## **Version 1.0.18**

date: 2021-08-08 (build 38)

- ADDED: add Box support
- ADDED: add Google Drive support
- ADDED: add photo browser to OneDrive and Dropbox
- IMPROVED: Hide video controls when swipe to forward and backward
- FIXED: fix some folder could not list files with OneDrive connection

## **Version 1.0.17**

date: 2021-08-06 (build 37)

- ADDED: add Dropbox support
- FIXED: fix issue that recent movie title wrong with OneDrive

## **Version 1.0.16**

date: 2021-08-02 (build 36)

- ADDED: add OneDrive support
- ADDED: add local photo browser

## **Version 1.0.15**

date: 2021-07-30 (build 35)

- ADDED: add option to select audio track in video player
- ADDED: add option to turn off auto save video playback history
- FIXED: fix issue that remote audio file
- FIXED: fix issue that remember video play history not working at iPad

## **Version 1.0.14**

date: 2021-07-22 (build 34)

- ADDED: add NFS remote protocol support
- ADDED: add subtitle abilities to video player
- ADDED: add file sort menu to remote files
- ADDED: add flac and caf audio file format support
- ADDED: add webm and ogg video file format support
- FIXED: fix connection issue with Synology which enables 2-Step verification

## **Version 1.0.13**

date: 2021-07-16 (build 33)

- ADDED: add delete file action to movie player
- ADDED: add remote music file playback support
- IMPROVED: remember last expand or collapse behavior of saved accounts and favorited folders
- IMPROVED: improve reveval search result
- FIXED: fix issue that can not search song when music player is not playing
- FIXED: fix crash when using guest mode to connect to SMB server
- FIXED: fix crash when taking snapshot of a video but current player does not has a video output
- FIXED: fix issue that connect without username and password using WebDAV may cause crash
- FIXED: fix connecting issue with FTP

## **Version 1.0.12**

date: 2021-07-03 (build 32)

- ADDED: add now playing music bar to iPad
- ADDED: add auto update music metadata switch toggle
- IMPROVED: Reduce the size of app
- FIXED: fix issue that compressed file can not be decompressed for the second time
- FIXED: fix issue that folder cannot be compressed

## **Version 1.0.11**

date: 2021-06-30 (build 30)

- ADDED: add movie playlist in movie player
- ADDED: add more swipe actions to file
- FIXED: fix issue that music player maybe presented twice
- FIXED: fix issue that 7z and tar files do not decompress when tap the file

## **Version 1.0.10**

date: 2021-06-18 (build 28)

- add movie playlist in library when they are tv series
- improve library movie artwork load performance
- fix issue that auto fetch metadata not working as expected
- fix issue that movies with uppercased extension can not be played
- fix change play mode not working when playing music

## **Version 1.0.9**

date: 2021-06-13 (build 27)

- redesign the UI of file information viewer
- add image browser to remote images (WebDAV/Synology/SMB/FTP)
- add now playing item animation in playlist
- add information viewer to remote files
- fix issue that invalid address may cause crash when connect with SMB connection
- fix issue that compress file always fails

## **Version 1.0.8**

date: 2021-06-09 (build 26)

- add rating information to movie metadata
- add multiple selection support to add file from Files
- fix issue that in certain scenario WebDAV can not be connected
- fix rename file and move file issue with WebDAV connection
- fix issue that advanced information not loaded when editing saved network share account
- improve performance

## **Version 1.0.7**

date: 2021-06-05 (build 25)

- add a way to edit metadata of library recent played movies
- add a new network share protocol: WebDAV(HTTPS)
- fix connection issue with WebDAV server
- fix download file issue with WebDAV and FTP connections
- fix now playing bar music artwork not clipped issue
- improve recent played movie title to two lines to display more information


## **Version 1.0.6**

date: 2021-06-03 (build 24)

- Add playback list to recent played videos
- fix issue that toolbar will overlaped by now playing bar when editing remote server files
- fix issue that download nested folder will always failed
- fix issue that when files removed but recent played videos not updated


## **Version 1.0.5**

date: 2021-05-31 (build 22)

- Redesign Library tab
- Redesign now playing bar of music player
- add context menu to file search result
- add goto folder to file search result
- improve music player last playlist

## **Version 1.0.4**

date: 2021-05-26 (build 20)

- add movie playback history progress to remote video
- add multiple selection operations to remote files
- fix issue with deleting folder with SFTP connection

## **Version 1.0.3**

date: 2021-05-14 (build 16)

- add download HTTP resources directly
- now you can play previous/next video in video player when playing folders contains multiple videos
- fix smb path issue cause can note create folder and delete files
- optimize remote login error message
- add website in about page
- fix page control color issue in onboarding page
- fix the problem that remote folders are not updated when moving files in some cases
- fix address and protocol not saved when edit remote account

## **Version 1.0.2**

date: 2021-05-12 (build 15)

- add onboarding screen
- add home screen quick action to shuffle music
- add transfer files via AirDrop
- add sleep timer to music player
- add get started documents
- fix markdown export pdf page size issue
- fix orientation issue with video player when returned from background


## **Version 1.0.1**

date: 2021-05-09 (build 11) 

- add more icon in remote browser to trigger contextual menu
- improve video play history managment
- fix mail feedback cancel button tapped has no effect issue
- fix video can not played in downloading page
- fix font setting value not updated when new font selected
- fix airdrop cold launch files not copied issue

## **Version 1.0.0**

date: 2021-05-04 (build 10) 

* initial release