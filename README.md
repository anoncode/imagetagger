imagetagger
===========
This program requires <a href="www.sno.phy.queensu.ca/~phil/exiftool">exiftool</a> to read/update iptc tag keywords.<br>
It needs to be renamed from <b>exiftool(-k).exe</b> to <b>exiftool.exe</b> otherwise the application pauses/requires user input before closing.

Starting the <b>setup_picasa_button.bat</b> will prepare and initalize <a href="http://picasa.google.com/">Picasa</a> with with the imagetagger button.<br><br>
The Picasa button will send the path of the file to the <b>image tagger.</b><br>
The <b>imgtgr.exe</b> will upload the image given as a 150 x 150 to www.pomf.se anonymous hosting.<br>
Then it will query http://iqdb.org and get the the best match (70%) from various booru sites.<br>
Afterwards it will update the image with the tags found.

Picasa Tag button currently has 120 file limit.<br> 
To handle more files at once generate a txt file with imgtgr.exe then process it.
