This is a personalized port of the [Arabica theme for Ghost](https://github.com/slunsford/arabica) to Hugo and Micro.blog. You can find a demo [here](https://web.archive.org/web/20211231020827/https://www.amitgawande.com/) from the Wayback Machine as I don't use the theme anymore.

**PS:** I haven't made it ready to be used as a custom theme. I haven't tested for any custom settings or strings in the template not parameterized yet. So, use it cautiously and with enough testing

## Quickstart

### Install

Inside the folder of your Hugo site run:

```
$ cd themes
$ git clone https://github.com/nirocfz/arabica
```

### Preview exampleSite

```
$ cd arabica/exampleSite
$ hugo server --themesDir ../..
```

### Configure Hugo

Add the folling line to `config.toml` to use the theme

```
theme = "arabica"
```

This is the `config.toml` of [exampleSite](/exampleSite)

```
baseurl = "https://example.org/"
title = "Arabica"
author = "John Doe"
paginate = 3
theme = "arabica"

[params]
    description = "A minimal Hugo theme"
    dateFormatToUse = "2006-01-02"
    replaceGoogleFonts = "fonts.loli.net"
    twitter = "example"
    facebook = "example"
```

You can add `image` front matter to a post, see [example post](https://github.com/nirocfz/arabica/blob/master/exampleSite/content/post/creating-a-new-theme.md).

Thanks

* [Hugo](https://gohugo.io/)
* [slunsford/arabica](https://github.com/slunsford/arabica)
* [xianmin/hugo-theme-jane](https://github.com/xianmin/hugo-theme-jane)

## License

See [LICENSE](https://github.com/nirocfz/arabica/blob/master/LICENSE)
