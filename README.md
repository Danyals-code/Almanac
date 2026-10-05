# Almanac – Ancient Cycles: website

The public pages for the iPhone app **Almanac – Ancient Cycles**. GitHub Pages serves them. The App Store listing links to them.

| Page | File | Address |
|---|---|---|
| Home | `index.html` | https://danyals-code.github.io/almanac/ |
| Privacy policy | `privacy.md` | https://danyals-code.github.io/almanac/privacy/ |
| Support | `support.md` | https://danyals-code.github.io/almanac/support/ |

`_config.yml` sets the site's title, contact email and App Store link. It also keeps this README and `website-setup.md` off the published site.

The design lives in `_layouts/default.html` (the header and footer on every page) and `assets/css/site.css`. Images are in `assets/img/`: the app icon and six screenshots, resized from the app's release screenshots.

## Editing

Edit a `.md` file on github.com (the pencil icon), then commit. The site updates within a minute or two.

- **Privacy policy:** change the "Effective" date whenever the policy changes. If the app ever collects data, say what is collected and why before releasing that version. Also update the App Privacy answers in App Store Connect.
- **Support:** add to "Common questions" when people ask the same thing more than once. Each question is a `###` heading with its answer below.
- **When the app is live:** paste its App Store link after `app_store_url:` in `_config.yml`. The home page then shows a download button instead of "Coming soon".

## Used by

- App Store Connect → App Privacy → Privacy Policy URL
- App Store Connect → iOS App → Support URL, and Marketing URL (the home page)
