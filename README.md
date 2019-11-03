# Hugo Webmonetization Demo Theme

Forked from https://github.com/onweru/newsroom.

This theme allows the creator to webmonetize their content using the [Interledger Protocol](https://interledger.org/) and the [Webmonetization](https://webmonetization.org/) standard.

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
