# 888 THEKKADY Website

Static six-page website draft for 888 THEKKADY, a premium homestay in Kumily, Thekkady.

## Pages

- `index.html` - Home
- `stay.html` - Rooms and accommodation
- `spa.html` - In-house spa and massage
- `facilities.html` - Facilities, dining and activities
- `explore.html` - Explore Thekkady and location
- `contact.html` - Rates, contact and booking enquiry

## Preview

Open `index.html` directly in a browser, or serve the folder with a simple static server.

```powershell
python -m http.server 8080
```

Then visit `http://localhost:8080/`.

## Image Replacement

Drop genuine property photos into:

- `assets/images/gallery/exterior/`
- `assets/images/gallery/single-rooms/`
- `assets/images/gallery/double-rooms/`
- `assets/images/gallery/kitchen-restaurant/`
- `assets/images/gallery/balconies/`
- `assets/images/gallery/spa-massage/`
- `assets/images/gallery/activities/`

The current pages use clearly marked placeholders from `assets/images/placeholders/`.

## Editable Content

Core contact details, room reference rates, spa draft menu and translations are in `assets/js/site.js`.

The existing supplied logo was copied to `assets/images/brand/thekkady-fern-logo.png`. Replace that file later when the final brand asset is ready.

## Deployment

This site is static and can be deployed to GitHub Pages, Netlify, Vercel or any standard web host. Upload the full folder while preserving relative paths.

## Owner Approval Needed

- Final logo and favicon.
- Actual property photographs.
- Pricing basis for room rates.
- Final room rate terms, taxes, inclusions and cancellation policy if needed.
- Actual in-house spa treatment menu and tariffs.
- Any confirmed operational timings, dining details, campfire details or safari arrangement terms.
- Activity/program wording, official booking links, operator availability and final prices for Gavi, Periyar, boating, trekking, jeep safari, elephant activity, plantation visits, Vagamon and Ramakkalmedu.

## Activity Image Notes

Additional activity images were downloaded from Wikimedia Commons / Special:FilePath into `assets/images/gallery/activities/` for draft use:

- `bamboo-rafting-periyar.webp`
- `elephant-safari-thekkady.webp`
- `jeep-safari-kerala.webp`
- `plantation-visit-kerala.webp`
- `thekkady-boat-service.webp`
- `vagamon-hills.webp`
- `ramakkalmedu.webp`

Before public launch, confirm each image license/attribution requirement or replace with owner-approved photos.

## Program Reference Links

- Gavi-Kakki Eco Tourism: `https://www.gavikakkionline.com/`
- Periyar Tiger Reserve programs: `https://www.periyartigerreserve.org/ProgramView`
- KTDC boating: `https://www.ktdcboating.com/`
- Kerala Tourism Vagamon: `https://www.keralatourism.org/destination/vagamon-idukki/324/`
- Kerala Tourism Ramakkalmedu: `https://www.keralatourism.org/destination/ramakkalmedu-hill-stations-kerala/53/`
