# Youtube-dl + Aria2 😉

This is a **Shell Script** I've created to easily use youtube-dl and aria2 simple use.

- **Make Sure you have youtube-dl and aria2**
- **Make Sure you add this file in your path**

Dependencies
============
 * [youtube-dl] (http://rg3.github.io/youtube-dl/)
 * [aria2] (http://aria2.sourceforge.net/)

## Commands

"yt link" will show you the video and audio id, or If this is a m3u3 file (hls) then it will start downloading immediately and faster!
 
 **Ex: yt https://www.youtube.com/watch?v=xxxxxxx** or,
	**yt https://something.something.m3u3**

"yt video-id audio-id link number-of-splites" will use aria2 and youtube-dl to download and merge the file.

 **Ex: yt best best https://www.youtube.com/watch?v=xxxxxxx 8**

"yt video-id or audio-id link number-of-splites" will use aria2 and youtube-dl to download only video or audio.

 **Ex: yt 124 https://www.youtube.com/watch?v=xxxxxxxx 8**

That's it.

*_Enjoy_*
