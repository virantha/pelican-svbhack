# SVBHACK

pelican-svbhack is a responsive theme for [Pelican](http://getpelican.com), it is my hack of a svbtle-like theme.

## DEMO

You can see the [theme in action](http://www.giuliofidente.com/).

## FEATURES

- responsive
- syntax highlighting for pre blocks
- supports google analytics
- custom list of links

## KNOWN ISSUES

- no IE testing
- no custom menu

## INSTALL

Clone the [repository](https://github.com/giulivo/pelican-svbhack), edit your `pelicanconf.py` and modify the `THEME` variable to make it point to the downloaded theme location.

## PELICANCONF.PY

Supports a number of common global variables but patches are welcomed if you need better support.

- `GOOGLE_ANALYTICS` your UA-XYZ code

- `GOOGLE_PLUS_URL` A link to your Google+ profile. Used for the [Google Authorship](http://www.google.com/insidesearch/features/authorship/index.html) feature.

- `USER_LOGO_URL` you don't need to replace the logo placeholder, just change this to point to another image. Can be local or remote.`

- `DISQUS_SITENAME` set this to enable disqus comments in articles

- `COLLAPSE_COMMENTS` set to `True` to have article comments hidden by default. Clicking on the `comments` link will toggle visibility.

- `TAGLINE` some text rendered right below the logo

- `SCROLL_TO_CONTENT` If this is set to `True`, when the content is below the sidebar (for example, on mobile), the page will be scrolled down to the content when it loads. An exception is made for the home page.

- `BLOG_URL` Set this if your main blog page is different from the landing page. If this is set, a new menu item called "Blog" will be added to the top menu.

When developing locally, you may want to set the following variable: `SITEURL = http://localhost:8000`

## MODIFICATIONS

- A favicon can be added by putting a file called `favicon.ico` in the `images` folder.
- Accent color can be changed by editing `@accent` in `./static/css/style.less`.
- A different Pygmentize theme can be used by editing `./Makefile` and running `make pygments`.

## AUTHOR

pelican-svbhack is authored by Giulio Fidente.

## LICENSE

Released under MIT License, full details in `LICENSE` file.
