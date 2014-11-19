# Card

A clean design theme based on Landscape for [Hexo]. 

[Demo]

## Installation

### Install

``` bash
$ git clone https://github.com/tomcheung789/hexo-theme-card.git themes/card
```

**Card requires Hexo 2.4 and above.**

### Enable

Modify `theme` setting in `_config.yml` to `card`.

### Update

``` bash
cd themes/card
git pull
```

## Configuration

``` yml
# Header
menu:
  Home: /
  Archives: /archives
rss: /atom.xml

# Content
excerpt_link: Read More
fancybox: true

# Sidebar
sidebar: right
widgets:
- category
- tag
- tagcloud
- archives
- recent_posts

# Miscellaneous
google_analytics:
favicon: /favicon.png
twitter:
google_plus:
```

- **menu** - Navigation menu
- **rss** - RSS link
- **excerpt_link** - "Read More" link at the bottom of excerpted articles. `false` to hide the link.
- **fancybox** - Enable [Fancybox]
- **sidebar** - Sidebar style. You can choose `left`, `right`, `bottom` or `false`.
- **widgets** - Widgets displaying in sidebar
- **google_analytics** - Google Analytics ID
- **favicon** - Favicon path
- **twitter** - Twiiter ID
- **google_plus** - Google+ ID

[Hexo]: http://zespia.tw/hexo/
[Demo]: https://www.chongcheung.com
