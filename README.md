# WebGrabPlusPlus
Configuration of WebGrab++ for IPTVSubs: Setting it up yourself

For EPG from Canada, US and UK, it's always faster to grab from zap2it or sky than using WebGrab+.

There are two subdirectories: zap2xml contains the setting to grab EPG from zap2it/sky. wgpp contains the WebGrab+ settings to process the final file for Kodi. My set up is under a Ubuntu linux, so I have BASH, Mono, and XMLTV set up first.

~/zap2xml
For Zap2it, use zap2xml
http://zap2xml.awardspace.info

For Sky, use tv_grab_uk_sky after installing xmltv. I included a copy that uses proper double quotes.

For IPTVSubs / IPTV Express purpose, register two accounts with Zap2it. One for Bell Fibe TV in Toronto, one for DirecTV in New York

I use the following bash script to do it. Replace username and password with your Zap2it account 

I also use WG2MP.exe (from WebGrab+) to reset all timestamps to UTC before passing it to WebGrab+ for 

~/wgpp
The WebGrab+ setting assumes you have the updated EPG files under ~/zap2xml

There are a few ini files I modded and they are uploaded. Examine each to make sure the directory setting fits your set up.
