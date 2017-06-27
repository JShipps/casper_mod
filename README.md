***
## Casper Modified : A Ghost Theme
#### The default Ghost theme __Casper__ modified by _JShipps_
***
#### Table of Contents:
* [What's different?](#whatsdifferent)
* [How to use](#howtouse)
* [Why do this?](#whydothis)
* [Changelog](#changelog)
* [Planned Features](#plannedfeatures)
* [Notes](#notes)
* [Original Casper](#ogcasper)
___
![in the wild](http://i.imgur.com/4TSA3eu.png "Casper_Modified")

A modified version of the default theme for Ghost (Casper)

View it live (https://jshipps.me)
___ 
### <a name="whatsdifferent">What's different?</a>

* Added PrismJS for syntax highlighting
* Added Disqus Comments
* Added Featured Images to home page
___ 
### <a name="howtouse">How to use</a>

##### PrismJS

![example 1](http://i.imgur.com/0BcYRuC.png "Example 1")
![example 2](http://i.imgur.com/ljU6iYA.png "Example 2")

To define the highlighting simple attach, "language-whicheverlanguage"

Example:

* language-bash
* language-php
* language-css
* language-html
* language-lolcode

##### Disqus Comments

Edit ``post.hbs`. lines 76-94.
Replace these lines with the code from your Disqus admin panel.

Currently, it's set to display comments using my Discus information - change this to depict your own.

##### Featured Image

In addition to syntax highlighting - this is something I feel is sorely missing from the default Casper. The images are set to fit the content 100% so this should not be an issue.
___ 
### <a name="whydothis">Why do this?</a>

Simple, Ghost is absolutely phenomenal, although, there are a few issues I've got - the complete lack of a native comment system is one, the other syntax highlighting and thirdly no featured image on home page support. So you end up with this modified version of the Casper theme which is going to be a work-in-progress for quite some time.
___ 
### <a name="changelog">Changelog</a>

##### Version 1.0.2

* Added linking on featured image to load into post

##### Version 1.0.1

* Added featured image support on homepage
* Added title link on homepage
* Added Disqus comments.

##### Version 1.0.0

* Added support for PrismJS

___
# <a name="plannedfeatures">Planned features</a>

- [ ] Add sidebar
- [ ] Add top posts
- [ ] Rework author page

___
# <a name="notes">Notes</a>

* This is a pet project for me
* If you use this, please let me know - I'd love to see what you do with it!
* If you have any changes, please fork this respiratory and push them!

___
# <a name="ogcasper">Original Casper</a>

The default theme for [Ghost](http://github.com/tryghost/ghost/).

To download, visit the [releases](https://github.com/TryGhost/Casper/releases) page.

## Copyright & License

Copyright (c) 2013-2017 Ghost Foundation - Released under the [MIT license](LICENSE).

