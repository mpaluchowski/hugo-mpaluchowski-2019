# mpaluchowski 2019 Hugo Theme

The [Hugo](https://gohugo.io/) theme for my blog at https://michal.paluchowski.com.

## Installation

Clone the repository to your `/themes` directory, ie.

```shell
$ cd /your/hugo/site
$ git clone https://github.com/mpaluchowski/hugo-mpaluchowski-2019 themes/mpaluchowski-2019
```

Build the [SASS](http://sass-lang.com/) files from `/assets/css`:

```shell
$ sass --no-source-map --style=compressed --update assets:assets
```

Then tell Hugo to render your site with the theme:

```shell
$ hugo --theme=mpaluchowski-2019
```
