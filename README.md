# MJML Example Tutorial

Full YouTube playlist can be found [here](https://www.youtube.com/playlist?list=PLERlwnGZmXQ0jpG9s8XE_2clpl6fmmryR)

Run `yarn` and add an mjmlconfig:

`.mjmlconfig`

```
{
  "packages": [
    "mjml-mailchimp/lib/mc-section.js",
    "mjml-mailchimp/lib/mc-image.js",
    "mjml-mailchimp/lib/mc-text.js"
  ]
}
```

Run `yarn build` to convert `index.mjml` to `index.html`
