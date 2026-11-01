# هاتفي | Hatifi — hatifistore.ma

The Hatifi store website: phone accessories in Morocco, free delivery to every city, cash on delivery.

- Static site: `index.html` plus images in `img/`. No build step.
- Orders go to WhatsApp (+212 710 256 996) through the order form.
- Prices are set in one place: the `P` object in the script at the bottom of `index.html`.

## Publishing
Connect this repository to Netlify (Add new site → Import from Git). Leave the build command empty and set the publish directory to `/`. Every push publishes the site automatically.
