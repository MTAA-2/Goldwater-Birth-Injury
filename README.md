# Injured at Birth Claim Landing Page — GitHub Pages (static) version

A static (HTML + CSS only, no PHP) birth injury landing page for **Robert Goldwater, Esq.**, built on the framework of your uploaded birth-injury page (`index-2.html` / `style-2.css`) and filled with content from **injuredatbirthclaim.com**.

**Updated 2026-10-29 at your direction:** all firm identity information is now Goldwater's (the first build kept the framework's Weltchek branding; that has been fully replaced — see "Goldwater identity" below).

## Goldwater identity (as replaced)

- Title / meta: "Birth Injury Lawsuit | Robert Goldwater" — case review with Robert Goldwater, Esq.
- Header: Goldwater's name in the framework's text-logo style (the Weltchek logo image was removed; no Goldwater logo file was supplied), and the header phone now reads "Call Me For Immediate Help: **(877) 759-2418**" (the reference site's wording and number).
- Footer contact: Robert Goldwater, Esq., 11811 N. Tatum Blvd., Suite 3031, Phoenix, AZ 85028, phone (877) 759-2418.
- Disclaimer: the reference site's paid-advertisement line — Attorney Robert Goldwater (Phoenix address above) is licensed to practice law only in Arizona but associates with multiple law firms nationwide; while joint responsibility is maintained, cases are referred to other firms for principal responsibility. The framework's call/text consent paragraph follows it, unchanged.
- Copyright: © 2026 Robert Goldwater.
- Results section: the framework's "$700,000,000" claim was Weltchek's and was **removed** so it is not attributed to Goldwater. It now leads with the reference site's own claims — a national network of birth injury attorneys built by Attorney Goldwater, record-setting verdicts and settlements in cerebral palsy, HIE, and other complex birth injury cases, 100+ years of combined experience, "Awarded Best Attorneys of America."
- Coverage section: the Weltchek team photo and "Exceptional Peer Recognition" block were removed and replaced with Goldwater's personal commitment story from the reference site (his triplets, born more than four months premature, and his mission to advocate for children injured at birth).
- The Weltchek awards image was likewise removed (replaced by the Best Attorneys of America line as text).

## What was kept from your framework, unchanged

- Page structure, classes, the MTAA CIPA block script, and the Meta Pixel.
- The form iframe keeps your framework's birth-injury embed: `forms.mtaa.ai/f/nf_61e94f8f346b48d2b03c3f14419b8485`, in the overflow form card: the container hangs past the hero over the section below it (your own margin values, desktop and mobile), and the form frame scrolls internally with `overflow: auto` if the embed runs tall.
- Footer legal links still point to your `privacy-policy.html` and `disclaimer.html` on justicehelpnow.com — those are your own hosted legal pages from the framework and were left as-is. Say the word if you want them pointed elsewhere for this page.

## Colors (the only CSS changes)

`css/style.css` is your uploaded `style-2.css` with **color values only** changed (diff-verified against your upload — every layout, spacing, and overflow rule untouched), matched to the live injuredatbirthclaim.com palette, sampled from the rendered site on 2026-10-29:

- Deep burgundy/maroon `#5b1a1a` / `#6b1d1d` for the top bar, hero start, dark section, and footer (their header/attorney-block color)
- Charcoal `#333333` at the end of the hero gradient (their darkened-photo hero)
- Bronze/gold `#b9975b` accents (kickers, headline accents, trim), gold-light `#efc25e` highlights
- CTA buttons in gold/amber `#e0a83b` with black text, like their "Get Help Now"
- Light gray `#ededed` for the results band, black/charcoal body text

Colors were sampled visually from the rendered page, so they are close approximations rather than values read from that site's stylesheet, and its hero is a darkened photograph rather than a flat color.

## Content (from injuredatbirthclaim.com)

- Hero: "Did Your Child Suffer an Injury at or Near the Time of Birth?" — that site's headline, with its diagnosis list: cerebral palsy, hypoxic-ischemic encephalopathy (HIE), brain damage, or another serious injury; a free case evaluation with a medical-records review, and compensation for a lifetime of medical care.
- Why Seek Legal Counsel — proving the physician was responsible and the extent of damage/loss; experienced and compassionate attorneys; holding responsible parties and their insurers accountable; support for ongoing care, medical expenses, and emotional suffering. "You are not alone."
- Birth Injuries — cerebral palsy explained (decreased oxygen/blood flow), plus the other conditions that site names: HIE, brain injury/brain damage, developmental delays, intellectual disability, and seizure disorders; lifetime-care list (residential care, in-home supervision, therapies, assistive devices, medications, specialists, home modifications, surgeries).
- How It Happens — nine cards from that site's list of preceding events: emergency cesarean section; prematurity/preterm labor/cervical insufficiency; NICU stay following birth; resuscitation at birth; seizures in the newborn period; fetal distress (fetal monitor concerns); uterine rupture; placental abruption; cooling therapy / therapeutic hypothermia.
- What We Look At — from that site's form: the condition (cerebral palsy / HIE / brain injury or damage / developmental delay / other injury), NICU stay length (1–3, 4–7, 8–14, or 15+ days), year of birth (recent years back to before 2016), and the state where the birth happened.

## Files

```
github-injured-at-birth-claim-landing-page/
├── index.html
├── css/style.css   (your framework CSS, colors only changed)
└── README.md
```

Publish the same way as the other GitHub pages: upload to a repo keeping the structure, Settings → Pages → deploy from branch (root).
