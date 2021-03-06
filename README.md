Subtle Pelican Theme
====================

[pelican-subtle](https://github.com/pR0Ps/pelican-svbhack) is a responsive theme for [Pelican](http://getpelican.com), modified from the theme by Carey Metcalfe [pelivan-svbhack](https://github.com/https://github.com/pR0Ps/pelican-svbhack) and Giulio Fidente's [pelican-svbhack](https://github.com/giulivo/pelican-svbhack) original theme.

## Demo

You can see the theme in action on [my site](http://virantha.com/).

## Features

- Clean, responsive design
- Profile image and tagline
- Syntax highlighting for pre blocks
- Google Analytics (new Unified Analytics)
- Google Authorship
- Supports displaying a custom list of links with icons in the sidebar
- Global keyword support
- Seach bar
- Hierarchical menu
- Amazon links
- JQuery Datatables integration for prettier tables


## Installing

You're welcome to look at my source changes, but some of the stuff is hard-coded to my liking and not easily
configurable for someone else's site.

Clone the [repository](https://github.com/virantha/pelican-svbhack), edit your `pelicanconf.py` and modify the `THEME` variable to point to the downloaded theme location.

## pelicanconf.py

When developing locally, you may want to set `SITEURL` to somrething like `http://localhost:8000`

This theme supports a number of custom variables:

- `GOOGLE_ANALYTICS_ID`: Your Google Analytics UA-XXXXXXXX-X code (`None` to disable analytics).
- `GOOGLE_ANALYTICS_PROP`: Your Google Analytics property name (`None` to disable analytics).
- `GOOGLE_PLUS_URL`: A link to your Google+ profile. Used for the [Google Authorship](http://www.google.com/insidesearch/features/authorship/index.html) feature.
- `USER_LOGO_URL`: The image to display as the profile image. Can be local or a remote URL.
- `DISQUS_SITENAME`: Set this to enable Disqus comments on articles.
- `COLLAPSE_COMMENTS`: Set to `True` to have article comments hidden by default. Clicking on the 'comments' link will toggle visibility.
- `TAGLINE`: The site's tagline. Rendered right below the image.
- `SCROLL_TO_CONTENT`: If this is set to `True`, when content is below the sidebar (for example, on mobile), the page will be scrolled down to the content when it loads. An exception is made for the home page.
- `FORCE_PIXELS`: Some screens (mostly mobiles) don't use pixels directly and scale based on the concept of a 'display pixel'. Setting this to `True` tells the device to use actual pixels. Enable with care.
- `MANGLE_EMAILS`: If enabled, any emails in the `SOCIAL` links will be obfuscated in HTML and have their links generated by Javascript when the page loads.
- `GLOBAL_KEYWORDS`: A list of strings that will be set as keywords for each page.
- `SERVER_LESS`: If `True`, `static/css/style.css` will be used as the style (compile it server-side). Otherwise `static/css/style.less` will be compiled client-side with `less.js`.

## Authors
pelican-svbhack is authored by [Virantha Ekanayake](https://github.com/virantha).

pelican-subtle is authored by [pR0Ps](https://github.com/pR0Ps).

pelican-svbhack is authored by [Giulio Fidente](https://github.com/giulivo).

## Licence

Released under MIT License, full details in `LICENSE` file.
