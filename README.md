CTAGS Improved
==============

Improved CTAGS bundle for TextMate. 

Current features: 

- ⎇. : Jump to definition of anything selected/under the cursor (defined in your project). If multiple definitions exist you will have to select the proper file from a menu.

Still missing:

- Stack of visited files so you can easily jump back to where you came from. 

Requirements
------------

You will need a version of CTAGS that doesn't ship with OS X. You can install 
it using [Homebrew](http://mxcl.github.com/homebrew/)

	brew install ctags
 
Set the shell variable to point to your CTAGS installation, if you don't do so 
TextMate will ask you politely with instructions on how to do so.

Pictures
--------

The following picture shows what happens if you try to jump to a definition if 
multiple definitions exists.

<img src="http://farm7.static.flickr.com/6196/6105721666_1463942d72.jpg" width="500" height="87" alt="CTAGS Improved.tmbundle ">