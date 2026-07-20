---
date: 2026-07-21
title: "How a Monochrome Sensor Sees"
hero_caption: "How the GR IV Mono's APS-C monochrome sensor captures light differently from a colour sensor with a Bayer filter overlay."
deck: "Strip off the red, green, and blue filter mask. Now put nothing in its place. What you get is not a coloured thing in greyscale — it is a sensor built from scratch to chase luminance."
hero_image: "https://ricohgr.eu/cdn/shop/files/GR-4-MONO-1_cb27a0c3-0638-41c7-9ae3-980075fd0343_1920x.jpg?v=1768240934"
kicker: "The Physics"
sources:
  - label: "Ricoh press release (US)"
    url: "https://us.ricoh-imaging.com/ricoh-launches-the-ricoh-gr-iv-monochrome/"
---

> "Each pixel of the monochrome-dedicated sensor captures the subject's brightness information."

To understand what a Ricoh GR IV Monochrome does, you have to first understand what every other modern digital camera does.

A colour CMOS sensor is, beneath its marketing, a greyscale sensor with a coloured mosaic laid over it. On every four photosites — two greens, one red, one blue — a thin colour filter blocks most of the light and lets through only a slice. The camera's processor then *guesses* what colour the missing two-thirds of each pixel was, by interpolating between neighbours. The result, with twenty years of engineering behind it, is convincing. It is also, by definition, a lie.

A monochrome sensor strips the mosaic away. No filter. Every photosite receives every photon. At the silicon level, this is a sensor that *wants* to do greyscale, and has been left alone to do it. Each pixel is 1:1 mapped to the brightness it recorded. No interpolation. No demosaic rounding. No guessing.

![Diagram comparing a colour-CFA sensor's pixel array to a monochrome sensor's — the latter receives all wavelengths directly, producing a true per-pixel luminance reading.](https://v3b.fal.media/files/b/0aa30a40/PzjnYoXQfTgSx9ovh-p73_wolj15jf.png)</new_string>

Three consequences matter for a photographer holding a $2,199 Ricoh in their hands.

The first is **per-pixel sharpness**. Because there is no demosaic step, the recorded image has no row-and-column patterns of softness. The 25.7 megapixel count on the GR IV Mono is the *honest* pixel count: each pixel resolves real detail, not interpolated detail. Reviews will show the difference as a quiet, almost architectural cleanliness — no false texture, no micro-blur.

The second is **tonal gradation**. A colour sensor turning B&W asks: how bright? how red, green, blue? — losing sensor bit depth to colour accounting. A monochrome sensor can spend every bit on luminance. The result in a strong scene — a closed door, a tiled roof under winter sun — is the ability to keep both highlight and shadow detail that a converted colour image would have crushed.

The third is **high-ISO character**. Photons that would have been blocked by the colour filter are now collected. The GR IV Mono's *Standard Output ISO range* runs to 409,600 — a number that, on a colour sensor, would be marketing nonsense, but on a real luminance sensor is closer to something the camera can actually deliver. Gain becomes not noise *amplification* but signal *collection*.

It is not strictly a better sensor than a colour equivalent. It is a sensor *built for one job* and frankly refusing any others. That refusal, at $2,199, is the bet you are paying for.
