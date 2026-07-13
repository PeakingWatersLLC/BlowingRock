# Peaking Waters LLC — BlowingRock Site

Public site for the Peaking Waters LLC umbrella: High Country Mineral Water,
the Fraser Fir Farm & Christmas Stop, Events & Adventures, and the co-packer
partnership program.

Static HTML/CSS/JS — no build step. Deploys anywhere (Vercel, GitHub Pages,
Netlify) as-is.

## Pages

| Page | Purpose |
|---|---|
| `index.html` | Home — umbrella mission, three pillars, co-pack callout |
| `water.html` | High Country Mineral Water — source story, product lines, quality, serving ideas |
| `farm.html` | Fraser Fir Farm & Christmas Stop (near Appalachian Ski Mtn) |
| `events.html` | Camping/RV, sustainability workshops, music & outdoor adventures |
| `copack.html` | Co-packer partnership, A to Z — process, responsibilities, terms, communications |

## Design system

- Palette: Mist `#F4F8F7`, Spruce `#17332A`, Well blue `#2C7A96`, Glacial `#D9EBEF`, Granite `#55605E`, Bark `#7A4A21`
- Type: Young Serif (display), Figtree (body), IBM Plex Mono (data/eyebrows)
- Signature element: the **depth gauge** — 4,000 ft elevation → −400 ft aquifer — in every hero, echoed as mono "depth chip" eyebrows
- Responsive, keyboard-focus visible, `prefers-reduced-motion` respected

## Photo & video slots

Every media placeholder is a labeled `.media` block with an HTML comment
naming the expected file. Drop real assets into `assets/img/` and
`assets/video/` with these names and add the `<img>`/`<video>` tag inside
the block (examples are in the comments):

```
assets/img/hero-ridge.jpg        home hero (or video hero-ridge.mp4)
assets/img/pillar-water.jpg      home — water card
assets/img/pillar-farm.jpg       home — farm card
assets/img/pillar-events.jpg     home — events card
assets/img/source-story.jpg      home — spring/creek
assets/img/hero-pour.jpg         water hero
assets/img/line-still.jpg        water — still
assets/img/line-sparkling.jpg    water — sparkling
assets/img/line-infusions.jpg    water — infusions
assets/img/quality-testing.jpg   water — testing
assets/img/hero-firs.jpg         farm hero
assets/img/farm-trees.jpg        farm — choose & cut
assets/img/farm-wreaths.jpg      farm — wreaths
assets/img/farm-drinks.jpg       farm — water bar
assets/img/farm-route.jpg        farm — directions
assets/img/hero-events.jpg       events hero
assets/img/events-camping.jpg    events — camping/RV
assets/img/events-workshops.jpg  events — workshops
assets/img/events-music.jpg      events — music
assets/img/events-outdoors.jpg   events — outdoors
assets/img/events-host.jpg       events — host with us
assets/img/hero-copack.jpg       copack hero
```

## Before launch

- [ ] Replace `hello@peakingwaters.com` with the real inbox (or wire forms to an API later)
- [ ] Confirm how much location detail to publish (road name vs. full address)
- [ ] Add real season hours to `farm.html`
- [ ] Add analytics if desired
- [ ] Add `docs/` PDFs when ready: capability questionnaire, NDA template, agreement outline (copack page can link them)
