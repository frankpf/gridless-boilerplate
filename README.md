Gridless
========

Gridless is an HTML5 and CSS3, [one web][one web] boilerplate to help you make progressively-enhanced, [mobile first][mobile first] [responsive][responsive] websites/webapps that have [beautiful typography][100E2R] with a vertical rhythm, sensible styles and are HTML5-ready and cross-browser compatible.

Gridless is simple and isn't littered with pre-defined non-semantic silly classes or pre-made grid systems.

Main features
-------------

- [Responsive][responsive] (responds to the user's device screen width with the correct content and CSS)
- Progressive enhancement, [mobile first][mobile first]
- Cross-browser compatible (even IE6 and 7)
- CSS normalization instead of CSS reset
- A vertical rhythm
- Print styles optimized for performance
- Optimal caching
- HTML5 and CSS3 ready
- [Safe CSS hacks][safe CSS hacks] instead of conditional classnames/stylesheets
- [Micro clearfix hack] [clearfix]
- A well-organized folder structure

License
-------

Major components:

- HTML5 shim: [MIT][MIT] license
- [Eric Meyer's CSS reset][eric css reset]: Public domain
- [Respond.js][respondjs]: [MIT][MIT]/[GPLv2][GPL]

Everything else:

- [The Unlicense][Unlicense]

Folder structure
----------------

- **index.html**: The HTML page with the initial markup
- **_/** *(folder)*: The folder that includes all the assets
	- **css/** *(folder)*: The folder that includes all the CSS files
		- **main.css**: The main CSS file with basic styles and media queries
	- **fonts/** *(empty folder)*: The folder where your webfonts reside
	- **img/** *(empty folder)*: The folder where your images reside
	- **js/** *(folder)*: The folder that includes all the JavaScript files
		- **respond.min.js**: Respond.js, which is a polyfill for media queries on older browsers

Thanks
------

[Eric Meyer](http://meyerweb.com), [Scott Jehl](http://www.scottjehl.com/), [Jeremy Keith](http://adactio.com/), [Ethan Marcotte](http://ethanmarcotte.com/), [Oliver Reichenstein](http://www.informationarchitects.jp/), [Wilson Miner](http://www.wilsonminer.com/), [Bryan Rieger](http://yiibu.com/), [Paul Irish](http://paulirish.com/), [Harry Roberts](http://csswizardry.com/), [Nicolas Gallagher](http://nicolasgallagher.com/), [Mathias Bynens](http://mathiasbynens.be), [Luke Wroblewski](http://www.lukew.com/), [Kroc Camen](http://camendesign.com/), [Chris Coyier](http://css-tricks.com/), [Richard Rutter](http://clagnut.com/), [Remy Sharp](http://remysharp.com/) and many others.

FAQ
---

### Why the name **Gridless**? ###
Because Gridless is ...well, gridless. It doesn't have any grid systems. The problem with most other CSS frameworks is that they include grid systems with presentational classes and/or ids without any semantic. Classes and ids should be unique to each project and shouldn't be declared on pre-made documents.
CSS grid systems should be used for rapid prototyping (which they're awesome at), not for production.

Browser support
---------------

Gridless was tested in the following browsers:
Mozilla Firefox 3.6+
Opera 11+
Google Chrome 11+
Safari 5+
Internet Explorer 6+

Although some of these browsers are very recent, Gridless should work in any modern browser without problems.


Contributing
------------

If you'd like to contribute to Gridless, visit https://github.com/thatcoolguy/gridless-boilerplate and send a pull request or an issue. You can also fork the project or clone it. Do anything, it's open-source!

[MIT]: http://www.opensource.org/licenses/mit-license.php
[Unlicense]: http://unlicense.org/
[GPL]: http://www.gnu.org/licenses/gpl-2.0.html
[one web]: http://adactio.com/journal/1716/
[mobile first]: http://www.lukew.com/ff/entry.asp?933
[responsive]: http://www.alistapart.com/articles/responsive-web-design
[safe CSS hacks]: http://mathiasbynens.be/notes/safe-css-hacks
[clearfix]: http://nicolasgallagher.com/micro-clearfix-hack/
[respondjs]: https://github.com/scottjehl/Respond
[eric css reset]: http://meyerweb.com/eric/tools/css/reset/
[100E2R]: http://www.informationarchitects.jp/en/100e2r/