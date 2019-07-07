# Base16 Theme for Jekyll

This is a fork of the [Base16 theme for Hugo](https://github.com/htdvisser/hugo-base16-theme.git) for [Jekyll](https://github.com/jekyll/jekyll).

Primary modifications:

- Hugo → Jekyll
- Basic (pure css) responsive navigation
- Categories removed (only tags)
- Support for base16 colour schemes provided by the [Base16-styles repository](https://github.com/samme/base16-styles).

# Customisation

- To change the hero image on the homepage, edit `_includes/hero.html` (see
`_sass/_hero.scss` for styling).

- To change the default colour scheme, include a style sheet from `_sass/base16-styles/sass` in `assets/css/style.scss`, e.g.
    ```scss
    ---
    ---
    @import "breakpoints";
    @import "base16-styles/sass/base16-eighties"; // ← Your theme here
    @import "core";
    @import "hero";
    ```

- See the [Jekyll tutorials](https://jekyllrb.com/tutorials/home/) for Jekyll topics and guides.

## License

MIT Licensed, see [LICENSE](https://github.com/htdvisser/hugo-base16-theme/blob/master/LICENSE).


## Don't forget to thank...

- [Hylke Visser](https://github.com/htdvisser) for the original theme

- [Chris Kempson](http://chriskempson.com) for the Base16 Eighties Colorscheme

- [Jan T. Sott](https://github.com/idleberg) for the Pygments template

- [Samme](https://github.com/samme) for [Base16-styles](https://github.com/samme/base16-styles)
