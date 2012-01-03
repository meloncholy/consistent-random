CONSISTENT-RANDOM

A little PHP file that returns random-but-consistent files from a folder each time it's called.


Originally based on AUTOMATIC IMAGE ROTATOR (Version 2.2) by Dan P. Benjamin http://benjamin.org/dan/,
though there's not much of the original code left. 
		 
Also with a little help (introducing me to crc32) from here http://www.webmasterworld.com/php/3782696.htm


ABOUT

This PHP script will randomly select a file from a folder on your webserver.  You can then link to
it as you would any standard file and you'll see a random-but-consistently-selected file.
	
When you want to add or remove files from the rotation-pool, just add or remove them from the rotation folder.


INSTRUCTIONS

1. Modify the $folder setting in the configuration section below.
2. Add file types if needed (most users can ignore that part).
3. Upload this file to your server, probably in the same folder as the files you want to serve.
4. Link to the file as you would any other file:

	<a href="http://example.com/rotate.php?file=gorilla.flv">link</a>
	<img src="http://example.com/rotate.php?file=gorilla.jpg" />
	
	The file returned will be of that same type (flv or jpg above). It will not be gorilla.flv, 
	but you will get the same one every time you ask for gorilla.flv. 

There's a post here with a little info in it

http://meloncholy.com/blog/serving-up-random-but-consistent-sample-videos/

Do get in touch if you something doesn't work / you have questions / you just want to say hi. Lovely. 

http://meloncholy.com/contact/


Copyright (c) 2011 Andrew Weeks http://meloncholy.com

Licensed under the MIT licence http://meloncholy.com/licence/

Version 0.1
