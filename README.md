# Artemis

A minimalist theme for [Hexo](http://hexo.io/) based on the [Apollo](https://github.com/pinggod/hexo-theme-apollo) theme.

The original Apollo theme didn't appear to work with the latest version of Hexo renderer libraries since [Jade](https://jade-lang.com) is now [Pug](https://pugjs.org).

[Preview](http://hexo-theme-artemis.smplcty.com/) |  [Screenshot](https://i.imgur.com/PCVquML.png)

## Installation

### Install

```
npm install --save hexo-renderer-pug hexo-generator-feed hexo-generator-sitemap
git clone https://github.com/Dreyer/hexo-theme-artemis.git themes/artemis
```

### Enable

Modify `theme` setting in `_config.yml` to `artemis`.

You can override the theme options using `theme_config` in the main `_config.yml`:

```yaml
theme: artemis
theme_config:
  logo:
  google_analytics: UA-12345678-9
  copyright:
    since: 2016
    name: John Doe
    url: https://www.example.org/john-doe
  menu:
    Home: /
    About: /about
    GitHub: https://github.com/Dreyer
    RSS: /atom.xml
```

### Update

```
cd themes/artemis
git pull
```

## Requirements

Test with the latest versions of the following:

| Library | Min. Version |
| --- | --- |
| [Hexo](https://hexo.io/) | 3.3.x |
| [Grunt](https://gruntjs.com/) | 1.0.x |
| [Sass](http://sass-lang.com/) | 3.4.x |
| [Pug](https://pugjs.org) | 2.0.x |

**Note:** The Pug dependency is used to render the `.pug` templates in the `layout` directory when you run `hexo generate`.

## Credits

This theme is largely based on the efforts of [Sean Sun](https://github.com/pinggod).

According to classical Greek mythology, [Artemis](https://en.wikipedia.org/wiki/Artemis) is the twin sister of Apollo and as this theme is virtually identical to [hexo-theme-apollo](https://github.com/pinggod/hexo-theme-apollo), it seemed apt.

Icons are from [IconNinja](http://www.iconninja.com/fairy-tales-icon-sets-16414).

## License

MIT