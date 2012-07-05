# tipsy

Facebook-style tooltip plugin for jQuery

(c) 2008-2010 Jason Frame (jason@onehackoranother.com)

Released under The MIT License.

## Description:

tipsy is a simple jQuery plugin for generating Facebook-style tooltips.

It's used by Twitter, Github, Slideshare and Bitbucket, amongst others.

## Homepage:

http://onehackoranother.com/projects/jquery/tipsy

## Modified Source:

Hosted at GitHub; browse at:

  http://github.com/adriengibrat/tipsy/tree/master

Or clone from:

    git://github.com/adriengibrat/tipsy.git
    
## Original Source:

Hosted at GitHub; browse at:

  http://github.com/jaz303/tipsy/tree/master

Or clone from:

    git://github.com/jaz303/tipsy.git

## Usage:

1. Copy the contents of the repository to the corresponding asset directories in your project. 

2. Insert the neccesary elements in your document's `<head>` section, e.g.:
   
        <script type='text/javascript' src='jquery.tipsy.js'></script>
        <link rel="stylesheet" href="tipsy.css" type="text/css" />

 Remember to include jquery.tipsy.js *after* including the main jQuery library.

3. Initialise Tipsy in your document.onload, e.g.:

        <script type='text/javascript'>
         $(function() {
	       $('a[rel=tipsy]').tipsy({fade: true, gravity: 'n'});
	     });
        </script>

Please refer to the docs directory for more examples and documentation.

## A note on forking:

By forking this project you hereby grant permission for any commits to your fork to be
merged back into this repository and, with attribution, be released under the terms of
the MIT License.
