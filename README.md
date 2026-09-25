# Portraits of the LCLS Instruments

Ten painted portraits of the instruments at SLAC's
[Linac Coherent Light Source](https://lcls.slac.stanford.edu/instruments) (LCLS) user facility.
Nine use the LCLS X-ray laser: TMO, TXI, XPP, chemRIXS, qRIXS, XCS, MFX, CXI and MEC.
The tenth, MeV-UED, is an "electron camera" that uses short pulses of fast electrons
in place of X-ray light.

Each portrait shows what the instrument lets scientists see (top half) and where that
work shows up in everyday life (bottom half). A ribbon joins the two halves. The
paintings don't show the hutch hardware.

**Website:** https://carbonscott.github.io/lcls-hutch-portraits/

## What's here

| Path | What it is |
| --- | --- |
| `index.html`, `style.css` | The gallery page, with a caption for each portrait |
| `images/<slug>.png` | The rendered portraits (900 × 1200) |
| `sketches/<slug>.html` | The source sketch for each portrait. Open one in a browser to watch it paint. |

Each sketch is a standalone HTML file. It loads [p5.js](https://p5js.org) 2.3.3 and
[p5.brush](https://github.com/acamposuribe/p5.brush) 2.2.3 from jsDelivr and paints only
with brush strokes, hatches and watercolour fills, with no images or text.

## Notes

- The science text is based on the instrument pages at lcls.slac.stanford.edu. Some of
  the everyday-life examples are our own plain-language extensions of those pages.
- This is a personal art project, not an official SLAC or LCLS website.
