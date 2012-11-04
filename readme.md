Shanty
======

The Minimalist Home Page Template
---------------------------------
`Shanty` is a responsive, minimalist, static home page template.  It includes:

* A masthead title
* A masthead subtile
* A 3x2 grid, each unit has
 * An icon
 * A link
 * Descriptive text
* Footer

That's all ya get.

Demo
----
[ianfitzpatrick.com](http://ianfitzpatrick.com)

Technology
----------
* `Bootstrap 2.2.1` [(link)](http://twitter.github.com/bootstrap)
* `Font Awesome 2.0` [(link)](http://github.com/FortAwesome/Font-Awesome)
* `Subtle Patterns` [(link)](http://subtlepatterns.com/)
* `LESS` [(link)](http://lesscss.org/)

Responsive Design
-----------------
`Shanty` should autosize to desktop, tablet, and mobile resolutions.

Compatability
-------------
`Shanty` has been tested with latest `Firefox`, `Chrome`, and `Safari` on OSX, as well as `Internet Explorer 9`.

Making Changes
--------------

#### Basic Text Changes ####
Make sure you change:

* `<title>Shanty Home</title>`
* `<footer><p>&copy; J. Random 2012</p></footer>`
* `<h1>J. Random</h1>`
* `<p>I make stuff. Details enclosed.</p>`

#### Row Layout ####
Shanty comes default with two rows.  Here a row:

	<div class="row-fluid sites"><!-- Start Row -->
	...
	</div><!-- End row -->

You can add more rows, just copy and paste away.

Each div inside a row has an icon, a title, and descriptive text.  You get three divs per row.  I wouldn't add or delete any if I were you, it totally hasn't been tested.

	<div class="span4">
		<a href="http://twitter.com/"><i class="icon-twitter-sign"></i></a>
		<h3><a href="http://twitter.com/">@username</a></h3>
		<p>I do the Twitters.</p>
	</div>

#### Customize Icons ####
To change the icon, change the following class:

	<i class="icon-twitter-sign"></i>

...to a different class you pick from the [Font Awesome](http://fortawesome.github.com/Font-Awesome/) library, eg:

	<i class="icon-bullhorn"></i>

To change an icon's color, either edit `assets/css/style.css` and add:

	/* Icon Colors (You may actaully need to edit these) */
	.icon-bullhorn {
	  color: #46a546;
	}

Or edit `assets/less/style.less` and add: 

	/* Icon Colors (You may actaully need to edit these) */
	.icon-bullhorn {
	  color: @red;
	}

To add color variables, edit `assets/less/custom-vars.less`.

#### Change Background ####
I've included several excellent background images from [Subtle Patterns](http://subtlepatterns.com/).

If you are using `CSS`, just change the `background-image` in `assets/css/stye.css` to one of the images in `assets/images/bg/`.

If you are using `LESS`, uncomment your preferred background image in `assets/less/custom-vars.less`.

#### LESS Configuration #####

* `assets/bootstrap/less/bootstrap.less` must compile to `assets/css/botstrap.css`
* `assets/less/style.less` must compile to `assets/css/style.css`

Contact
-------

* Ian Fitzpatrick
* http://ianfitzpatrick.com
* [Github](http://github.com/ianfitzpatrick)
* [@ianfizpat](http://twitter.com/ianfitzpat)


License
-------
Shanty is licensed under CC BY 3.0:
http://creativecommons.org/licenses/by/3.0/ A mention of
'Shanty - http://github.com/ianfitzpatrick/shanty' in human-readable
source code is considered acceptable attribution (most common on the web).
If human readable source code is not available to the end user, a mention in
an 'About' or 'Credits' screen is considered acceptable (most common in desktop
or mobile software).
