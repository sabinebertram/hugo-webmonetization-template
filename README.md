# Hugo Webmonetization Demo Theme

Forked from https://github.com/onweru/newsroom.

![Hugo + Webmonetization](static/images/hugowm.png)

This theme allows the creator to webmonetize their content using the [Interledger Protocol](https://interledger.org/) and the [Webmonetization](https://webmonetization.org/) standard.

## Add the Theme

Add this theme as a Git submodule inside your Hugo site folder:
```
git submodule add https://github.com/sabinebertram/hugo-webmonetization-theme themes/hugo-webmonetization-theme
```

## Enable Webmonetization

Add your [payment pointer](https://webmonetization.org/docs/receiving#payment-pointer) to the `config.toml`:

```
[params]
  monetization = "$twitter.xrptipbot.com/sabinebertram_"
```

## Create Exclusive Content

Include the following `<div>` tag in your markdown file:
```html
<div id='exclusive'></div>
```
Everything below this tag will only be visible if the user is streaming payments.
