<div align="center">

# FinePdf

**Print more pages on less paper.** 🖨️

N-up PDF converter for Windows that trims wasted margins so your text stays readable.

[![Latest release](https://img.shields.io/github/v/release/theodore-labs/FinePdf)](https://github.com/theodore-labs/FinePdf/releases/latest)
![Platform](https://img.shields.io/badge/platform-Windows%2010%2F11%20x64-blue)
![License](https://img.shields.io/badge/license-14--day%20free%20trial-green)

### [**⬇️ Download the free trial**](https://github.com/theodore-labs/FinePdf/releases/latest)

*Windows 10 / 11 (64-bit) · 14 days, every feature unlocked, no signup, no card*

</div>

---

## Same sheet. Same two pages. Bigger text.

<img width="1800" height="710" alt="comparison-readme" src="https://github.com/user-attachments/assets/27b6df35-b6bd-4839-ad4a-9b2b0dfa4f09" alt="The same two pages of a paper printed 2-up on one A4 sheet. Left: Microsoft Print to PDF, small text. Right: FinePdf, margins trimmed first, text about 1.4x larger.">



Everyone tries "2 pages per sheet" once, squints at the result, and never uses it again.
The problem isn't your printer — it's that **20–30% of a typical PDF page is blank margin**,
and the printer dutifully shrinks that empty space right along with your text.

FinePdf detects the actual content area of every page, trims the wasted white space
**first**, and only then packs the pages. Same sheet count, noticeably larger text —
about **1.4× larger** in the comparison above.

Fewer sheets. Less ink. Still readable.

## "Can't I just use Microsoft Print to PDF?"

For n-up and zooming — yes, and I'm not going to charge you for something Windows already
does. The difference is **what the zoom is measured against**.

Print to PDF scales the *page box*. It has no idea where your content actually sits, so on
pages with tight margins it pushes text straight off the edge of the sheet. You find out
after you've printed.

<img width="1800" height="600" alt="crop-detail" src="https://github.com/user-attachments/assets/10f3b40c-8014-4bd9-864e-80f19d244fbc" alt="The same paragraph printed at the same zoom. Left, Microsoft Print to PDF: every line is cut off at the right. Right, FinePdf: the sentences are complete.">



FinePdf measures where the ink actually is on each page and trims only that much. Enlarge as
far as you like — nothing gets cut.

| | Microsoft Print to PDF | FinePdf |
|---|:---:|:---:|
| Multiple pages per sheet | ✅ | ✅ |
| Shrink margins to enlarge | ⚠️ page-based | ✅ content-based |
| **Never clips your content** | ❌ | ✅ |
| Uniform text size across pages | ❌ | ✅ |
| Booklet (A5) imposition | ❌ | ✅ |
| Merge several PDFs, convert once | ❌ | ✅ |
| Ink saving baked into the output | ❌ | ✅ |
| Preview + sheets-saved counter | ❌ | ✅ |
| Reuse the same settings next time | ❌ manual every time | ✅ |

---

<img width="1766" height="1142" alt="FinePdf main window — drop a PDF, preview the layout, see how many sheets you save" src="https://github.com/user-attachments/assets/7e2d1b26-df63-4159-9cdc-b632ebf224f1" />

## ✨ Features

- 📄 **N-up layout (2 / 4 / 8 / 16 pages per sheet)** — auto-detects page orientation, picks the optimal grid
- ✂️ **Smart margin trimming** — removes wasted white space before packing, text stays as large as possible
- 📐 **Four placement modes** — Stretch, Fit, Fill, HFill (fill width, keep aspect ratio)
- 📘 **Booklet imposition** — fold A4 in half → an A5 booklet, no print shop needed
- 🔀 **Merge multiple PDFs** — drop several files, get one combined output
- 🎨 **Ink Saver & grayscale** — cut toner cost with one click
- 📊 **Live preview & savings counter** — see how many sheets you'll save *before* printing
- 🖨️ **Direct printing** — send the result straight to your printer

### Ink Saver

<table>
  <tr>
    <td width="50%"><img src="https://github.com/user-attachments/assets/76431d93-7659-44df-b51b-709b8bb974c5" alt="Original color output"></td>
    <td width="50%"><img src="https://github.com/user-attachments/assets/294332bf-de55-4e09-9bb4-cca16f6c19a5" alt="Grayscale Ink Saver output at 40%"></td>
  </tr>
  <tr>
    <td colspan="2" align="center"><i>Printing in <b>grayscale Ink Saver mode (40%)</b> — same content, a fraction of the toner.</i></td>
  </tr>
</table>

## 📦 Download & Install

Grab the latest version from the [**Releases page**](https://github.com/theodore-labs/FinePdf/releases/latest):

| File | Description |
|------|-------------|
| `FinePdf-x.y.z.msi` | Installer (recommended) — Start Menu shortcut, clean uninstall |
| `finepdf.exe` | Portable single file — no installation, just run |

**Requirements:** Windows 10 / 11 (64-bit). No .NET installation needed — everything is bundled.

> **macOS or Linux?** Not yet — FinePdf is Windows-only today.
> If you'd use a Mac version, [say so in an issue](https://github.com/theodore-labs/FinePdf/issues)
> and I'll know it's worth building.

## 💰 Pricing

Try everything for **14 days**, free. No signup, no card, no feature locks.

If you keep it: **₩23,000 KRW (≈ $16 USD), one time.** Not a subscription — you own this
version forever. For comparison, the tool this replaces costs about $100.

→ [**finepdf.lemonsqueezy.com**](https://finepdf.lemonsqueezy.com)

License files are issued by hand (I'm one person, not a company), so yours arrives by email
within 48 hours of purchase. Load it via *About → Register* and you're done.

## 💬 Support

Bug reports, feature requests, or a PDF that doesn't convert well?

- Open an [issue](https://github.com/theodore-labs/FinePdf/issues)
- Or email **finepdf.team@gmail.com**

Found a PDF that comes out wrong? That's the most useful thing you can send me — attach it
to an issue and I'll fix it.

---

<div align="center">

*Built by one developer who got tired of paying for printer paper.*

**If FinePdf saved you a stack of paper, a ⭐ helps other people find it.**

</div>
