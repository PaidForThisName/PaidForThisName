# Nurrel

**Measure once. Shop everywhere. Try it on before you buy.**

[nurrel.shop](https://nurrel.shop) · Frisco, TX · founded 2026

I am building Nurrel: a mobile shopping app that turns one photo into a fit profile, maps that profile onto every retailer's own grading, and lets you see a piece on your body before you pay for it.

---

## The problem

People order three sizes of the same shirt and send two back. That is treated as normal.

Fashion returns run roughly 20–40%. About half of those, and in some cuts closer to 70%, are sizing. The customer already decided they wanted the piece. They just could not tell which size would fit, because "M" is not a measurement. It is a label that changes by brand, cut, factory, and season.

The usual answers are a size chart nobody trusts, or a model photo of someone who is not you. Both still leave you guessing.

---

## What we shipped

Nurrel is one catalogue and one body.

1. **Fit from a photo.** One picture produces a measurement set. That becomes your size profile.
2. **Mapped to the brand, not the other way around.** We compare those measurements to each retailer's own grading, so the size we show you is the size that fits *that* label.
3. **The catalogue is already filtered.** You are not browsing 1,000+ products and then hoping. You are shown pieces that should fit.
4. **Virtual try-on.** See the piece rendered on your body. Put two looks side by side, the way you would in a fitting room.
5. **A closet that includes what you already own.** Style a new piece against your wardrobe before you buy it.

On the product site we currently publish **120+ retailers and brands**, **1,000+ products**, **25+ categories**, and **500+ app downloads**. Treat those as live product figures, not a research paper.

---

## How the system is supposed to work

The hard part is not "AI that looks at clothes." It is making one identity work across every surface a shopper and a seller actually use.

```
photo → measurements → fit profile
                         │
                         ├─► retailer grading maps → size per SKU
                         ├─► catalogue filter (only what should fit)
                         ├─► virtual try-on on your body
                         └─► closet / outfit (owned + considering)
```

Three constraints I care about:

**Measurement has to be cheap.** If onboarding is a tape measure and ten form fields, people bounce and you never get a fit profile to work with. A photo is the only input that has a chance of happening on a phone.

**Size is per retailer, not per person.** A single "you are a medium" model fails the moment you shop two brands. The profile has to be a body. The size is a projection onto that brand's chart.

**Try-on is a confidence layer, not the size engine.** Rendering a garment on you helps you decide if you *want* it. It should not be the only thing deciding whether an M or an L ships. Those are different problems and they fail in different ways.

That is why Nurrel is a shopping app with fit inside it, not a try-on widget bolted onto someone else's checkout.

---

## The other surfaces

The same fit profile has to work outside the phone.

**Nearby retail.** Boutiques and independent sellers sit in the same catalogue as larger brands. Buy in the app, pick it up down the street, or get it the same day when the piece is already on a rail near you. A local return should not need a shipping label.

**Nurrel Kiosk.** The fit profile and try-on on a screen the store already has. A walk-in sizes themselves, browses what is not on the floor, and sees the piece on their body before anyone unlocks a fitting room.

**Sellers.** One catalogue feed, a dashboard for inventory / orders / analytics, and a view of how their grading maps onto real bodies. New sellers start with no commission so listing is not a leap of faith.

If the fit identity only lives in one app screen, it is a feature. If it follows the shopper from phone to sidewalk to counter, it is the product.

---

## What I work on

I am the person building Nurrel — the company is [NURREL LLC](https://nurrel.shop), based in Frisco. I work across the product and the computer-vision / app side: what the fit profile is, how it gets used in the catalogue, and how that holds together as a mobile app.

This is a small team, not a solo science project. Design, sellers, and the store-facing work are shared.

Stack I actually use here: **TypeScript, React Native, Python, computer vision.**

---

## Why this is the piece I want in front of employers

I am a CS student who decided the interesting problem was not another class project. It was a real marketplace with a measurement problem, a try-on problem, and a catalogue problem, all attached to the same identity.

If you want to see the product: [nurrel.shop](https://nurrel.shop).

If you want to talk about how it is built: [dinesh.janapati2@gmail.com](mailto:dinesh.janapati2@gmail.com).
