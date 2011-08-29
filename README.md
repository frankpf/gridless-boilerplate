Gridless -- A boilerplate for responsive, cross-browser websites
================================================================


DESCRIPTION
-----------

Gridless is an optionated HTML5 and CSS3 boilerplate for making [mobile first](http://www.lukew.com/ff/entry.asp?933) [responsive](http://www.alistapart.com/articles/responsive-web-design), cross-browser websites with [beautiful typography](http://www.informationarchitects.jp/en/100e2r/).

Gridless encourages and uses [progressive enhancement](http://en.wikipedia.org/wiki/Progressive_Enhancement) through [mobile first](http://www.lukew.com/ff/entry.asp?933) responsive web design.

**Gridless is meant to be a starting point, which should be edited, tweaked and overwritten to suit each project's design requirements**, rather than being blindly used as a black box of non-touchiness.


PHILOSOPHY
----------

Some of the core principles of Gridless:

### DBY (Don't Bore Yourself) approach

Gridless takes the boring parts of making websites and webapps out. It comes packed with everything you're tired of doing in every new project: [CSS normalization](http://necolas.github.com/normalize.css/), [beautiful typography](http://www.informationarchitects.jp/en/100e2r/), a well-organized folder structure, [IE bugfixes](http://mathiasbynens.be/notes/safe-css-hacks) and other nice tricks.

### Progressive responsiveness

Gridless uses [mobile first](http://www.lukew.com/ff/entry.asp?933) [responsive web design](http://www.alistapart.com/articles/responsive-web-design) to adapt itself to the device's width. This means it'll work anywhere: old feature phones, newer smartphones, tablets, notebooks and bigger desktops. IE6/7/8 don't support media queries, so we use [Respond.js](https://github.com/scottjehl/Respond/) to polyfill that.

### Agnostic starting point

Gridless is extremely simple and straightforward. It doesn't come with any predefined grid systems or non-semantic classes. Gridless is meant to be a starting point, which should be edited, tweaked and overwritten to suit each project's design requirements.

MAIN FEATURES
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


BROWSER SUPPORT
---------------

Gridless was tested in the following browsers:
Mozilla Firefox 3.5+
Opera 11+
Google Chrome 11+
Safari 5+
Internet Explorer 6+

Although some of these browsers are very recent, Gridless should work in any modern browser without problems.


FILES
-----

- **README.md**: the file you're reading right now

- **index.html**: The HTML(5) page with the initial markup and some tricks to get you started quickly

- **demo.html**: A file demonstrating Gridless' styles

- **robots.txt**: Permissions for search crawlers

- **humans.txt**: Give credit to people involved in the project

- **UNLICENSE.txt**: The Unlicense, the license which Gridless is licensed 
under

- **favicon.ico, apple-touch-icon.png, apple-touch-icon-precomposed.png, apple-touch-icon-*-precomposed.png**: The favicons (bookmark icons)

- **assets/** *(folder)*: The folder that includes all the assets

	- **css/** *(folder)*: The folder that includes all the CSS files

		- **main.css**: The main CSS file with basic styles and media queries

		- **debug.css**: The debugging CSS file to help you debug your markup

	- **fonts/** *(empty folder)*: The folder where your webfonts reside

	- **img/** *(empty folder)*: The folder where your images reside

	- **js/** *(folder)*: The folder that includes all the JavaScript files

		- **respond.min.js**: Respond.js, which is a polyfill for media queries on older browsers

### PROJECT

#### CSS

- main.css:
	- CSS normalization
	- Beautiful typography
	- Vertical rhythm (baseline grid)
	- Placeholder media queries for responsive web design
	- [Safe CSS hacks](http://mathiasbynens.be/notes/safe-css-hacks) to target IE6 and IE7


MAKE IT BETTER
--------------

Some tips to improve Gridless *and* your productivity:

- Use a command line tool like [Juicer](https://github.com/cjohansen/juicer) to help you ship code for production and achieve better performance.

- Use [HTML5 polyfills](http://github.com/Modernizr/Modernizr/wiki/HTML5-Cross-browser-Polyfills) to bring future to all browsers.

- Use a tool like [resizeMyBrowser](http://resizemybrowser.com/) or [ProtoFluid](http://protofluid.com/) for testing your responsive designs on common browser widths.

- Consider using [CSS3 Please!](http://css3please.com/) and [CSSPrefixer](http://cssprefixer.appspot.com/) to help you write faster CSS3.

- Use a script loader like [yepnope.js](http://yepnopejs.com/) or [HeadJS](http://headjs.com/) to load your scripts faster and without blocking.

- [Use more `meta` tags inside your `head`](http://gist.github.com/581868).

- Write [efficient CSS](http://css-tricks.com/efficiently-rendering-css/) for better browser performance.

- Use an [HTML5 lint tool](http://lint.brihten.com/) for better markup.

- Use [microdata](http://www.whatwg.org/specs/web-apps/current-work/multipage/links.html#microdata) for better search results and semantic markup.

- If you'd like to use font-sizes outside the default modular scale (1.625), see http://drewish.com/tools/vertical-rhythm and http://modularscale.com.

- If you'd like help people move off IE6 with an warning, add this HTML to your body:

```
<!--[if lt IE 7]>
<div style=' clear: both; height: 59px; padding:0 0 0 15px; position: relative;'>
	<a href="http://windows.microsoft.com/en-US/internet-explorer/products/ie/home?ocid=ie6_countdown_bannercode"><img src="http://www.theie6countdown.com/images/banners/warning_bar_0000_us.jpg" border="0" height="42" width="820" alt="You are using an outdated browser. For a faster, safer browsing experience, upgrade for free today." /></a>
</div>
<![endif]-->
```


CURRENT STATUS
--------------

Gridless is under active development. Its current version is 2.0.


FAQ
---

### WHY THE NAME GRIDLESS?

Because Gridless is ...well, gridless. It doesn't come with any grid systems.

In my opinion, grid systems are a great idea, but ***not*** in the way they're being used today — with **lots** of presentational classes like `span-x` or `grid_y` in the markup. These classes only describe the presentation of the content, nothing else. Markup should be semantic; it is meant to describe the **structure** of the content.

Grid systems can be used, but they should be:

- Used with CSS preprocessors like [Sass](http://sass-lang.com)/[Compass](http://compass-style.org), [LESS](http://lesscss.org), [PCSS](http://pcss.wiq.com.br/) etc.

- Edited (modify the `class`es and `id`s) to suit each project's semantics

- Made from the start of each project

Still, if you don't agree with that, just include your favorite grid system (only the grid part, remove the reset, typography etc.) and it'll work like a charm!


LICENSE
-------

* Major components:

	* HTML5 shim: [MIT](http://www.opensource.org/licenses/mit-license.php) license

	* [Normalize.css](http://necolas.github.com/normalize.css/): Public domain

	* [Respond.js](https://github.com/scottjehl/Respond): [MIT](http://www.opensource.org/licenses/mit-license.php)/[GPLv2](http://www.gnu.org/licenses/gpl-2.0.html)

* Gridless and everything else:

	* [The Unlicense](http://unlicense.org/)


THANKS
------

[Ethan Marcotte](http://ethanmarcotte.com/), [Bryan Rieger](http://yiibu.com/), [Luke Wroblewski](http://www.lukew.com/), [Jeremy Keith](http://adactio.com/), [Paul Irish](http://paulirish.com/), [Nicolas Gallagher](http://nicolasgallagher.com/), [Jonathan Neal](https://github.com/jonathantneal/), [Scott Jehl](http://www.scottjehl.com/), [Eric Meyer](http://meyerweb.com), [Oliver Reichenstein](http://www.informationarchitects.jp/), [Wilson Miner](http://www.wilsonminer.com/), [Harry Roberts](http://csswizardry.com/), [Mathias Bynens](http://mathiasbynens.be), [Kroc Camen](http://camendesign.com/), [Chris Coyier](http://css-tricks.com/), [Richard Rutter](http://clagnut.com/), [Remy Sharp](http://remysharp.com/), [Kilian Valkhof](kilianvalkhof.com) and many others.


CONTRIBUTING
------------

If you'd like to contribute to Gridless' development, start by forking the GitHub repo:

https://github.com/thatcoolguy/gridless-boilerplate

The best way to get your changes merged back on Gridless is as follows:

1. Clone your fork
2. Hack away
3. If you are adding significant new functionality, document it in the README
4. Do not change the version number, I will do that on my end
5. Push the repo up to GitHub
6. Send a pull request to [thatcoolguy/gridless-boilerplate](https://github.com/thatcoolguy/gridless-boilerplate)