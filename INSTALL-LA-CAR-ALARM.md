# Cursor / Grok Bot — LA Car Alarm plugin

Copy everything below the line. **lacaralarm.com only.** Branch **v1**. Screenshot phone before production.

---

You are editing **sites/lacaralarm/** on branch **v1** only. One pass. Do not open other network repos. Do not invent images. Do not rewrite the homepage.

Repo: github.com/audiomotorsports-sketch/audiomotorsport
Vercel root: sites/lacaralarm
Push to **v1**. Not main. Not redesign-home-five-sites.

## Job
Insert a quote plugin **immediately under the existing banner**. Offers, FAQs, SEO copy, and chat stay.

## Files
1. Save `ams-plugin-alarm.css` as `/assets/css/ams-plugin-alarm.css`
2. Save these two photos (they are in the pack under `assets/`):
   - `assets/remote-f350-dually.jpg` → `/assets/plugin/alarm/remote-f350-dually.jpg`
   - `assets/dash-cam-wireless.jpg` → `/assets/plugin/alarm/dash-cam-wireless.jpg`
3. In the homepage `<head>`, after the other stylesheets, add:
   `<link rel="stylesheet" href="/assets/css/ams-plugin-alarm.css">`
4. Paste `ams-plugin-alarm.html` as specified below.

## HTML insert
Find this close on the homepage (`sites/lacaralarm/index.html`):

```
</section>
<section class="offer-cards"
```

The `</section>` belongs to `<section class="hero-banner hero-banner--fold">`.

Paste the full contents of `ams-plugin-alarm.html` **between** those two tags.

## Do not
- Touch `<section class="hero-banner">` or its images
- Touch chat (`ams-chat.js`, `#ams-chat`)
- Delete `#offers` / tickets
- Change `:root` colors. This desk is steel `--accent: #5A7D94`. Not hub gold. Not Beats red.
- Invent photos. Use existing:
  - `/assets/img/services-tab/06-alarms-desktop.jpg`
  - `/assets/plugin/alarm/remote-f350-dually.jpg`  (black F-350 dually — do not use the stretched white truck)
  - `/assets/plugin/alarm/dash-cam-wireless.jpg`  (wireless look, no wires)
  - `/assets/img/services-tab/08-gps-desktop.jpg`
  - `/assets/img/services-tab/09-fleet-desktop.jpg`
- Invent a Compustar 9910 plate. There is no `plate-compustar-9910.png`. Use the shop photo.
- Put dash-cam links to `/services/dash-cameras/` (plural). Use `/services/dash-camera/`
- Use the word warranty / guaranteed / lifetime / financing
- Invent prices. Only two numbers exist:
  - Viper 3108V **$269** flat, installed
  - Compustar 9910 **$499** starting, most cars
- Do **not** resurrect $340. Do **not** add $199.
- Do **not** strip $269 from existing FAQ / schema on other pages
- Invent reviews
- Spell the brand "Los Angeles Car Alarm"

## Sticky bar
`.ams-plug-sticky` has `right: 88px` so `#ams-chat` keeps the bottom-right corner.
Plugin CSS hides `.mobile-cta-bar` only while `#ams-plug-alarm` is on the page. Do not delete the old bar HTML.

## Phone / email
- Call: `tel:+13105138800` — (310) 513-8800
- Text: `sms:+12134291092` — (213) 429-1092
- Email: audiomotorsports@gmail.com
- Copy: **Ask for Nick**

## Door URLs (live menu)
- Alarm → `/services/car-alarms/`
- Remote Start → `/services/remote-start/`
- Dash Camera → `/services/dash-camera/`  (singular)
- GPS Tracking → `/services/gps-tracking/`
- Asset Protection → `/services/fleet-asset-protection/`

Photos:
- `/assets/img/services-tab/06-alarms-desktop.jpg`
- `/assets/plugin/alarm/remote-f350-dually.jpg`
- `/assets/plugin/alarm/dash-cam-wireless.jpg`
- `/assets/img/services-tab/08-gps-desktop.jpg`
- `/assets/img/services-tab/09-fleet-desktop.jpg`

Do not invent a Compustar 9910 plate. Do not invent GPS or asset prices.

## Done when
- Banner is identical
- Proof + quote sit directly under the banner
- Five tabs + five cards, real photos
- $269 and $499 only; GPS and asset protection have no price
- Offer tickets still exist below
- Phone screenshot: Text | Call left, chatbot clear bottom-right
- SMS opens to +1 213-429-1092 with year/make/model if filled
- Call is (310) 513-8800

Screenshot **phone** before production merge to branch `v1`.
