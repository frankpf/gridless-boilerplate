Gridless
========

Gridless is an HTML5 and CSS3, [one web](http://adactio.com/journal/1716/) boilerplate to help you make progressively-enhanced, [mobile first](http://www.lukew.com/ff/entry.asp?933) [responsive](http://www.alistapart.com/articles/responsive-web-design) websites/webapps that have [beautiful typography](http://www.informationarchitects.jp/en/100e2r/) with a [vertical rhythm](http://24ways.org/2006/compose-to-a-vertical-rhythm), sensible styles and are HTML5-ready and cross-browser compatible.

Gridless is simple and isn't littered with pre-defined non-semantic silly classes or pre-made grid systems.

Main features
-------------

- [Responsive](http://www.alistapart.com/articles/responsive-web-design) (responds to the user's device screen width with the correct content and CSS)
- Progressive enhancement, [mobile first](http://www.lukew.com/ff/entry.asp?933)
- Cross-browser compatible (even IE6 and 7)
- CSS normalization instead of CSS reset
- Beautiful typography with a vertical rhythm and heading sizes based on golden ratio
- Print styles optimized for performance
- Optimal caching
- HTML5 and CSS3 ready
- [Safe CSS hacks](http://mathiasbynens.be/notes/safe-css-hacks) instead of conditional classnames/stylesheets
- [Micro clearfix hack](http://nicolasgallagher.com/micro-clearfix-hack/)
- A well-organized folder structure


Browser support
---------------

Gridless was tested in the following browsers:
Mozilla Firefox 3.6+
Opera 11+
Google Chrome 11+
Safari 5+
Internet Explorer 6+

Although some of these browsers are very recent, Gridless should work in any modern browser without problems.

Folder structure
----------------

- **index.html**: The HTML page with the initial markup
- **assets/** *(folder)*: The folder that includes all the assets
	- **css/** *(folder)*: The folder that includes all the CSS files
		- **main.css**: The main CSS file with basic styles and media queries
	- **fonts/** *(empty folder)*: The folder where your webfonts reside
	- **img/** *(empty folder)*: The folder where your images reside
	- **js/** *(folder)*: The folder that includes all the JavaScript files
		- **respond.min.js**: Respond.js, which is a polyfill for media queries on older browsers

Make it better
--------------

- Use a command line tool like [Juicer](https://github.com/cjohansen/juicer) to help you ship code for production and achieve better performance.
- Use [HTML5 polyfills](http://github.com/Modernizr/Modernizr/wiki/HTML5-Cross-browser-Polyfills) to bring future to all browsers
- Use a tool like [resizeMyBrowser](http://resizemybrowser.com/) or [ProtoFluid](http://protofluid.com/) for testing your responsive designs on common browser widths
- Consider using [CSS3 Please!](http://css3please.com/) and [CSSPrefixer](http://cssprefixer.appspot.com/) to help you write faster CSS3
- Use a script loader like [yepnope.js](http://yepnopejs.com/) or [HeadJS](http://headjs.com/) to load your scripts faster and without blocking
- [Use more `meta` tags inside your `head`](http://gist.github.com/581868)
- Write [efficient CSS](http://css-tricks.com/efficiently-rendering-css/) for better browser performance
- Use an [HTML5 lint tool](http://lint.brihten.com/) for better markup
- Use [microdata](http://www.whatwg.org/specs/web-apps/current-work/multipage/links.html#microdata) for better search results and semantic markup
- If you'd like to use font-sizes outside the default modular scale (1.625), see http://drewish.com/tools/vertical-rhythm and http://modularscale.com
- If you'd like help people move off IE6 with an warning, add this HTML to your body:  
```
<!--[if lt IE 7]>
<div style=' clear: both; height: 59px; padding:0 0 0 15px; position: relative;'>
	<a href="http://windows.microsoft.com/en-US/internet-explorer/products/ie/home?ocid=ie6_countdown_bannercode"><img src="http://www.theie6countdown.com/images/banners/warning_bar_0000_us.jpg" border="0" height="42" width="820" alt="You are using an outdated browser. For a faster, safer browsing experience, upgrade for free today." /></a>
</div>
<![endif]-->
```

FAQ
---

### Why the name **Gridless**? ###
Because Gridless is ...well, gridless. It doesn't have any grid systems. The problem with most other CSS frameworks is that they include grid systems with presentational classes and/or ids without any semantic. Classes and ids should be unique to each project and shouldn't be declared on pre-made documents.
Still, if you don't agree with that, just include your favorite grid system (only the grid part, remove the reset, typography etc.) and it'll work like a charm!

License
-------

Major components:

- HTML5 shim: [MIT](http://www.opensource.org/licenses/mit-license.php) license
- [Normalize.css](http://necolas.github.com/normalize.css/): Public domain
- [Respond.js](https://github.com/scottjehl/Respond): [MIT](http://www.opensource.org/licenses/mit-license.php)/[GPLv2](http://www.gnu.org/licenses/gpl-2.0.html)

Everything else:

- [The Unlicense](http://unlicense.org/)

Thanks
------

[Ethan Marcotte](http://ethanmarcotte.com/), [Bryan Rieger](http://yiibu.com/), [Luke Wroblewski](http://www.lukew.com/), [Jeremy Keith](http://adactio.com/), [Paul Irish](http://paulirish.com/), [Nicolas Gallagher](http://nicolasgallagher.com/), [Jonathan Neal](https://github.com/jonathantneal/), [Scott Jehl](http://www.scottjehl.com/), [Eric Meyer](http://meyerweb.com), [Oliver Reichenstein](http://www.informationarchitects.jp/), [Wilson Miner](http://www.wilsonminer.com/), [Harry Roberts](http://csswizardry.com/), [Mathias Bynens](http://mathiasbynens.be), [Kroc Camen](http://camendesign.com/), [Chris Coyier](http://css-tricks.com/), [Richard Rutter](http://clagnut.com/), [Remy Sharp](http://remysharp.com/), [Kilian Valkhof](kilianvalkhof.com) and many others.

Contributing
------------

If you'd like to contribute to Gridless, visit https://github.com/thatcoolguy/gridless-boilerplate and send a pull request or an issue. You can also fork the project or clone it. Do anything, it's open-source!