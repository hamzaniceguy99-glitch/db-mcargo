# DB-M CARGO — road freight & warehousing

Static marketing site (HTML / CSS / JS, no build step) hosted on GitHub Pages
at `db-mcargo.shop`.

> Generated from `C:\Users\souha\coaching-sites-factory` (content file `sites/db-mcargo.mjs`).
> To change the content, edit that file and run `node build.mjs db-mcargo` — editing the
> HTML here directly would be overwritten on the next build.

## Before you promote this site

| Priority | What | Where |
|---|---|---|
| 🔴 Blocking | Legal page: fill every `[BRACKET]` (legal name, address, state, payment provider). Have a lawyer review it if you can. | `legal.html` |
| 🟠 Important | `contact@db-mcargo.shop` doesn't exist yet: set up free email forwarding in Namecheap (*Domain List → Manage → Redirect Email*). | Namecheap |
| 🟠 Important | Contact form: replace `VOTRE_ID_FORMSPREE` with your Formspree id (until then it falls back to `mailto:`). | `contact.html` |
| 🟠 Important | Add a real introduction of the coach (name, background, photo). Never invent credentials. | `about.html` |
| 🟡 Later | Prices ($Quote / $Quote / $Declined) and plan contents should match what you actually sell. | `index.html` `#pricing` |
| 🟡 Later | Testimonials: only add real ones, with permission. Fake reviews are illegal (FTC). | — |

## Business description (Stripe, directories…)

```
We are DB-M Cargo, a road freight and warehousing operator based in Affligem, working since 2011. We move full and part loads nationally and across Europe, handle groupage, and store goods in our own warehouse with stock recorded in and out. We hold the community licence that road haulage requires and work under a qualified transport manager, and we plan journeys to the driving and rest-time rules rather than accepting a delivery slot that would mean breaking them. One thing shippers are rarely told: international carriage by road falls under the CMR Convention, which limits compensation to 8.33 SDR per kilogram of lost or damaged goods, so high-value freight needs ad valorem cover arranged before it moves. We do not carry dangerous goods. Site: db-mcargo.shop
```

## Structure

```
index.html            Home: hero, programs, method, pricing, approach, FAQ
programs.html         The four programs in detail
about.html            How we work, principles
contact.html          Contact form
legal.html            Business info, privacy policy, terms of service
404.html              Error page (absolute paths)
assets/css/style.css  Brand colors at the top, shared styles below
assets/js/main.js     Menu, theme, animations, form
```

## DNS (Namecheap → Advanced DNS)

Delete the parking records, then add:

| Type | Host | Value |
|---|---|---|
| A Record | `@` | `185.199.108.153` |
| A Record | `@` | `185.199.109.153` |
| A Record | `@` | `185.199.110.153` |
| A Record | `@` | `185.199.111.153` |
| CNAME Record | `www` | `hamzaniceguy99-glitch.github.io.` |
