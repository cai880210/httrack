# HTTrack Website Copier - Development Repository

HTTrack is a free and open-source Web crawler and offline browser, developed by Xavier Roche and licensed under the GNU General Public License Version 3.

HTTrack allows users to download World Wide Web sites from the Internet to a local computer.[5][6] By default, HTTrack arranges the downloaded site by the original site's relative link-structure. The downloaded (or "mirrored") website can be browsed by opening a page of the site in a browser.

HTTrack can also update an existing mirrored site and resume interrupted downloads. HTTrack is configurable by options and by filters (include/exclude), and has an integrated help system. There is a basic command line version and two GUI versions (WinHTTrack and WebHTTrack); the former can be part of scripts and cron jobs.

HTTrack uses a Web crawler to download a website. Some parts of the website may not be downloaded by default due to the robots exclusion protocol unless disabled during the program. HTTrack can follow links that are generated with basic JavaScript and inside Applets or Flash, but not complex links (generated using functions or expressions) or server-side image maps.

Developer(s)	Xavier Roche
Written in	C
Operating system	Microsoft Windows, Mac OS X, GNU, GNU/Linux, FreeBSD and Android[4]
Type	Offline browser and Web crawler

## About
_Copy websites to your computer (Offline browser)_

<img src="http://www.httrack.com/htsw/screenshot_w1.jpg" width="34%">

*HTTrack* is an _offline browser_ utility, allowing you to download a World Wide website from the Internet to a local directory, building recursively all directories, getting html, images, and other files from the server to your computer.
 
*HTTrack* arranges the original site's relative link-structure. Simply open a page of the "mirrored" website in your browser, and you can browse the site from link to link, as if you were viewing it online.

HTTrack can also update an existing mirrored site, and resume interrupted downloads. HTTrack is fully configurable, and has an integrated help system.

*WinHTTrack* is the Windows 2000/XP/Vista/Seven release of HTTrack, and *WebHTTrack* the Linux/Unix/BSD release. 

## Website

*Main Website:*
http://www.httrack.com/

## Compile trunk release
```sh
git clone https://github.com/xroche/httrack.git --recurse
cd httrack
./configure --prefix=$HOME/usr && make -j8 && make install
```
