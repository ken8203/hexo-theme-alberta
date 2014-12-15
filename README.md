# Alberta

A new theme for [Hexo] based on [landscape](https://github.com/hexojs/hexo-theme-landscape/).

- [Preview](http://jaychung.tw/)

![](http://i.imgur.com/SlKOEkR.png)

![](http://i.imgur.com/N1j1TLg.png)

## Installation

### Install

``` bash
$ git clone https://github.com/ken8203/hexo-theme-alberta.git themes/alberta
```

### Enable

Modify `theme` setting in `_config.yml` to `alberta`.

### Update

``` bash
cd themes/alberta
git pull
```

## Configuration

``` yml
# Header
menu:
  Home: /
  Archives: /archives
  About: /about
rss: /atom.xml

# Menu Icon
menu_icon:
  Home: fa-home
  Archives: fa-archive
  About: fa-user

# Content
excerpt_link: Read More
fancybox: true

# Personal Image
your_img: your_image_url

# Miscellaneous
google_analytics:
favicon: favicon.ico
twitter:
google_plus:
```

- **your_img** - Your own photo url, suggest putting a squarelike photo. (equal to or bigger than 150x150)
- **menu** - Navigation menu, you need to `hexo new page 'about'` for the about page.
- **menu_icon** - Navigation icon
- **rss** - RSS link
- **excerpt_link** - "Read More" link at the bottom of excerpted articles. `false` to hide the link.
- **fancybox** - Enable [Fancybox]
- **google_analytics** - Google Analytics ID
- **favicon** - Favicon path
- **twitter** - Twiiter ID
