WebVTT
======

The Web Video Text Tracks Format

1. The W3C document: http://dev.w3.org/html5/webvtt/

2. Attention: Note that the track element cannot be used from a file:// URL. To see tracks in action, put files on a web server!

3. Getting Started With the Track Element: http://www.html5rocks.com/en/tutorials/track/basics/

4. <Track> Tag must has "default" attribute. For example:

  <track src="subtitle.vtt" kind="subtitles" srclang="en" label="English subtitles" default/> 
  </track>

5. the <Track> must be closed.

6. The subtitles.vtt first line must have keywords "WEBVTT". 

7. Demo URL: http://html5videoguide.net/presentations/WebVTT/#landing-slide

8. Browers supported status: http://caniuse.com/#feat=webvtt