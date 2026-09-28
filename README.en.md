# Today's lunar date

Solar date, lunar date, sexagenary day and solar term. It turns over daily on its own.

*[Đọc bản tiếng Việt](README.md)*

**See it running:** https://nhatnguyet.org/widget/lich-hom-nay

## Paste these two lines

```html
<div data-widget="lich-hom-nay"></div>
<script async src="https://nhatnguyet.org/embed/w.js"></script>
```

No account, no API key, nothing to pay.

## What it gives your page

A tear-off day calendar shrunk to fit your page. It shows the solar date in large type, the lunar date and the sexagenary day name below it, and the solar term currently running. Turn the proverb option on and each day also carries a piece of folk verse matched to the lunar month, exactly as printed on the back of a real tear-off sheet.

## Worth knowing before you embed

- The Vietnamese lunar calendar is computed for Vietnam's own time zone, so some days fall one day apart from the Chinese calendar. That is correct, not a fault.
- The sexagenary day name counts days in a cycle of sixty, like a weekday but longer. It tells you which day it is, not whether the day is good or bad.
- Solar terms divide the year into 24 stages along the Earth's orbit, the scheme farmers used to know when to sow and when to reap.
- The proverb is inherited weather lore, there to enjoy and remember, not a forecast for the day.

## The steps

1. Paste the snippet where you want the calendar, usually a sidebar or the foot of an article.
2. If your page has a dark background, pick the dark theme in the preview and the snippet updates itself.
3. Turn on the proverb option if you want a line of folk verse each day.
4. That is all. The calendar rolls over at midnight and never needs touching again.

## Where to paste it

**WordPress.** Add a *Custom HTML* block to the post, or a *Text* widget in
the sidebar, and paste both lines there. Do not paste into the ordinary
editor: it will show the code as text instead of running it.

**Wix, Squarespace, Shopify.** Use the *Embed HTML* / *Custom HTML* block.

**Hand-written sites.** Paste it straight where you want the widget. If you
embed several widgets, the `<script>` line only needs to appear once on the
page.

**A note on width.** The widget fits the width of wherever you put it. If that is narrower than 280px, add
`data-size="compact"`; if it is a wide horizontal strip, use
`data-size="wide"`.

## Make it match your page

| Attribute | Values | Meaning |
|---|---|---|
| `data-widget` | `lich-hom-nay` | Required |
| `data-theme` | light or dark | Defaults to light |
| `data-accent` | #b3341f | Accent colour as a 6-digit hex value, to match your own branding |
| `data-lang` | vi or en | Defaults to vi |
| `data-tho` | 1 or omitted | Show a proverb matched to the lunar month below the content |
| `data-size` | compact, standard or wide | Level of detail for the width you have: compact drops secondary detail, wide lays out horizontally. Defaults to standard |

With every attribute this widget accepts, it looks like this:

```html
<div data-widget="lich-hom-nay" data-theme="dark" data-accent="#1f6f5c" data-lang="en" data-tho="1" data-size="compact"></div>
<script async src="https://nhatnguyet.org/embed/w.js"></script>
```

Want to see it for yourself before it goes near your real page? Open
[`vi-du/index.html`](vi-du/index.html) in a browser, nothing to install.

## A few things we ask

- Free for personal and business websites, with no display limit.
- Keep the attribution line at the foot of the widget. That is what you give
  in return for free use.
- Do not embed on gambling, adult, fraudulent sites or anything unlawful
  under Vietnamese law.
- The content is folk knowledge and cultural convention, offered as
  reference, not as health, financial or legal advice.

Full text: [`TERMS.md`](TERMS.md) · [https://nhatnguyet.org/widget/dieu-khoan](https://nhatnguyet.org/widget/dieu-khoan)

## Who we are

Nhat Nguyet (https://nhatnguyet.org) is a Vietnamese reference site for calendrical and
cultural knowledge: the lunar calendar computed for Vietnam's own time zone,
the sexagenary cycle, solar terms, auspicious hours, astrology, feng shui,
and a glossary of terms.

There is one thing we try hard to keep clear, even inside a 300px frame:
which parts are computed, and which are folk convention.

Lunar dates, sexagenary names and solar terms are **computed**. Run the same
calculation and you get the same answer, and we publish the underlying
datasets under CC BY 4.0 so you can check for yourself.

Auspicious hours, Bat Trach directions and Lo Ban rule bands are **cultural
convention**. There are real lookup tables behind them, but they are not
measurements. The widget tells you what the table says; how much weight to
give it is yours to decide.

Where the schools disagree, we say so, rather than quietly picking a side and
presenting it as the only reading.

Open data: [GitHub](https://github.com/Nhat-Nguyet/du-lieu-am-lich) ·
[Hugging Face](https://huggingface.co/datasets/nhatnguyet)

## Something not right?

Open an issue in this repository. We do read them.

The whole widget library: [https://nhatnguyet.org/widget](https://nhatnguyet.org/widget)
