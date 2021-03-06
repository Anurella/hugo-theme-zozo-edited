# Hugo Theme Zozo Edited

I have made changes to the original theme by Zeuk, this can be found [ZOZO](https://github.com/imzeuk/hugo-theme-zozo.git). 
But i still reference the original theme in my Hugo-site for updates. 

[![GitHub](https://img.shields.io/github/license/imzeuk/hugo-theme-zozo.svg?color=4664DA&style=flat-square)](https://github.com/imzeuk/hugo-theme-zozo/blob/master/LICENSE)

A simple and beautiful theme for Hugo

> It's a port of [Aragaki](https://github.com/PCDotFan/Aragaki), The style is reference from [菩提树下](https://blog.caicai.me/), Some functions are referenced from [Even](https://github.com/olOwOlo/hugo-theme-even)

**Features**

+ **Responsive**
+ **Syntax highlighting with highlightjs**
+ **Math with mathjax** 
+ **Social links(Customize)**
+ **Tags page**
+ **Archive page**
+ **Disqus and [Valine](https://valine.js.org/en/index.html) comment-system**
+ **Fancybox**
+ **GoogleAnalytics**

## Sceenshots

![zozo](./images/showcase.png)

## Installation

```bash
$ git clone https://github.com/Anurella/hugo-theme-zozo-edited themes/zozo-edited
```


## Logo

If using image logo and favicon, you need to place all the following files in the static folder at the root of your site, which will overwrite those files in the `themes/zozo/static/images/` folder. I used a text based logo

## Hide Pages

Pages can be hidden and don't appear in the post list on the homepage if you add the variable `hidden = true` to the frontmatter. This allows you to link from elsewhere, i.e. just the menu.

## Shortcodes

This theme provides `img` shortcodes.

```markdown
{{< img src="path/to/xxx.png" title="xxx" >}}
```

## MathJax

This theme supports MathJax, which are turned off by default. If you want to use them, you need to set them in `config.toml`.

Set `mathjax = true` under the `[params]` to support the MathJax.

## Valine Comment System

This theme provides valine comment system, the default is closed, if you want to use, need to set in `config. toml`.

Set the `enable = true` under `[params.valine]` to open valine, and will be `appId` and `appKey` set for yourself.

## Social Link Icons

You can add a social link panel in the header by adding entries to the social block in the `config.toml`.

[Remix icon](https://remixicon.com/) is used in this theme.

## Nearly Finished

In order to see your site in action, run Hugo's built-in local server.

```bash
$ hugo server
```

Now enter `localhost:1313` in the address bar of your browser.

## License

Released under the [MIT](https://github.com/imzeuk/hugo-theme-zozo/blob/master/LICENSE) License.

## Acknowledgements

- [Aragaki](https://github.com/PCDotFan/Aragaki)
- [菩提树下](https://blog.caicai.me/)
- [olOwOlo](https://olowolo.com/)
- [Zeuk](https://github.com/imzok)
