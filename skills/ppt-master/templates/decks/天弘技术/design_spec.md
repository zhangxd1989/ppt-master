---
deck_id: 天弘技术
kind: deck
display_name: 技术研发部PPT模板
category: general
summary: 天弘基金技术研发部内部汇报模板，深红 #B7002E 为唯一品牌色，白底克制网格风格，适用于财富管理 / 基金业务 / 资产管理季度汇报、技术研发部门工作汇报、年度总结。
canvas_format: ppt169
page_count: 5
page_types: [cover, toc, chapter, content, ending]
primary_color: "#B7002E"
keywords: [财富管理, 基金, 资产管理, 企业汇报, 技术研发, 年度总结, 中式金融, 天弘]
fonts:
  latin: Helvetica Neue
  cjk_fallback: [Microsoft YaHei, PingFang SC, sans-serif]
placeholders:
  - PRESENTATION_TITLE
  - AUTHOR_AND_DATE
  - TOC_ITEM_1_TITLE
  - TOC_ITEM_1_DESC
  - TOC_ITEM_2_TITLE
  - TOC_ITEM_2_DESC
  - TOC_ITEM_3_TITLE
  - TOC_ITEM_3_DESC
  - CHAPTER_NUMBER
  - CHAPTER_TITLE
  - CHAPTER_SUBTITLE
  - PAGE_NUMBER
  - PAGE_TITLE
  - CONTENT_AREA
---

# 技术研发部PPT模板（天弘技术）

> Five faithful template pages reconstructed from source slides 1 / 2 / 3 / 4 / 88 of the original deck (`projects/template.pptx`, 99 pages). Each SVG preserves the source's exact geometry, decoration, image references, and path artwork — only editable text content has been replaced with `{{}}` placeholders. Coordinates are wrapped in a single outer `transform="scale(0.5)"` so the source's native 2560 × 1440 numbers render correctly inside the canonical 1280 × 720 ppt169 viewBox.

## I. Template Overview

A restrained, finance-corporate deck identity centered on a single deep-crimson brand color `#B7002E` over a white canvas. Distinctive recurring elements: red side panels with shallow white-curve overlays, top-left red-square + light-gray title bar chrome, ribbon + 45°-rotated rounded-square page-number badges, and a brand-logotype lockup composed of vector-path Chinese characters (天弘 / 技术管理) plus a Latin "TIANHONG TECHNOLOGY" wordmark.

Designed for internal corporate reporting at 天弘基金's technology R&D department. The aesthetic intentionally avoids decoration: lots of whitespace, sober typography, geometry built from rectangles + circles + ribbons.

## II. Color Scheme

| Role | Hex | Use |
|---|---|---|
| Primary brand | `#B7002E` | Cover & ending red panels, section markers, chapter ribbons & bottom bar, accent squares |
| Chrome gray | `#F2F2F2` | Content-page title bar, footer strip |
| Body text | `#3E4451` | Titles, paragraph text on white surfaces |
| Hairline gray | `#CCCED1` / `#E8E8EA` / `#F7F7F8` | Center-ring outline, dot strokes |
| White | `#FFFFFF` | Canvas background, text-on-red, panel curves at low opacity |

The Keynote stock theme accents (`#00A2FF`, `#16E7CF`, etc.) recorded in the source theme XML are **not** part of this deck's identity — they were never used on any sampled slide and are explicitly excluded.

## III. Signature Design Elements

- **Red side panel with overlay curves** — cover and ending pages use a large rectangular red field with two stacked white-curve overlays at ~3% opacity, giving a subtle silk-fold effect on top of the flat color.
- **Vector-path brand logotype** — the cover's brand wordmark (天弘 / 技术管理 / TIANHONG TECHNOLOGY) is rendered as SVG paths, not editable text. This is intentional brand artwork and stays untouched across all variants.
- **Top-left section-number block** — every content page opens with a red square in the upper-left corner containing the section number (e.g. `1.1`) in white, flush against a light-gray title bar.
- **Ribbon + rotated rounded-square badge** — chapter and TOC pages use a horizontal ribbon (red-to-transparent gradient) terminating in a 45°-rotated white rounded square that holds a two-digit number in `#B7002E`.
- **Six-card information ring** — the canonical content page (slide 4 style) arranges six rounded-rectangle info ribbons radially around a center circular photo placeholder, connected by hairline-stroked dots. This is the deck's signature data-visualization pattern.
- **45°-rotated red wave bottom bar** — chapter pages anchor the bottom with a downward chevron emerging from a notched bottom red bar.

## IV. Page Roster

Five reconstructed templates, each derived from a specific source slide via faithful copy-with-placeholder reconstruction; outer viewBox is `0 0 1280 720` and source content sits inside a `transform="scale(0.5)"` group so the original 2560 × 1440 coordinates render verbatim.

| File | Page type | Derived from | What was preserved |
|---|---|---|---|
| `01_cover.svg` | cover | source slide 1 | Red panel + white-curve overlays, two drop-shadow accent squares, top-right white logo chip with `image3.png`, bottom-left tagline mark, bottom-right vector-path brand logotype (天弘 + 技术管理 + TIANHONG TECHNOLOGY rendered as three path groups) |
| `02_toc.svg` | toc | source slide 2 | Left ~32% red panel with vertical 目录 ideographs, "Contents" subtitle, three white accent squares at top, "CONTENTS" wordmark at bottom-left. Right side stacks three ribbon entries with rotated rounded-square 01/02/03 number badges |
| `03_chapter.svg` | chapter | source slide 3 | Right hero image (`image4.png`) inside a sub-SVG with viewBox crop; bottom-left quantum-dots background (`image5.png`); red notched bottom bar with white chevron at canvas center; centered chapter number ribbon + rounded-square badge with `{{CHAPTER_NUMBER}}`; three top-right red accent squares |
| `04_content.svg` | content | source slide 4 | Top-left red section block + `{{SECTION_NUMBER}}`, light-gray title bar with `{{PAGE_TITLE}}` + step number, top-right header logo (`image2.png`), bottom footer strip (`image1.jpeg`). Body is blank — the entire area between the title bar (y ≈ 90 px display) and the footer (y ≈ 680 px display) is the editable content region |
| `05_ending.svg` | ending | source slide 88 | Full-bleed red panel + white-curve overlays + centered closing graphic (`image42.png`) at the canvas's lower-middle |

### Page-by-page description (load-bearing for downstream Strategist)

- **`01_cover.svg`** — Title cover. The red panel occupies ~94% of canvas. Edit `{{PRESENTATION_TITLE}}` (cover title, white, 80 px native) and `{{AUTHOR_AND_DATE}}` (white-with-90%-opacity subtitle, 44 px native) at left. Fixed elements (not editable): the brand tagline `稳健理财 值得信赖` in the bottom-left margin next to a red square accent, the 天弘 / 技术管理 / TIANHONG TECHNOLOGY vector logotype at bottom-right, and the `assets/image3.png` cover logo inside the top-right white rounded chip.
- **`02_toc.svg`** — Three-section TOC. The 目录/Contents lockup on the left red panel is fixed. Edit the three ribbon entries' titles (`{{TOC_ITEM_N_TITLE}}`, 46 px) and short descriptions (`{{TOC_ITEM_N_DESC}}`, 28 px). To extend beyond 3 sections, copy a ribbon group and translate by +303 px (native) on Y; for >5 sections, fork to a 2-page TOC.
- **`03_chapter.svg`** — Section divider. The right hero image (`assets/image4.png`) and bottom-left quantum-dots backdrop (`assets/image5.png`) are part of the chapter mood — replace the hero file (keeping the same crop viewBox) to change scene per chapter. Edit `{{CHAPTER_NUMBER}}` (the badge digit), `{{CHAPTER_TITLE}}` (large title, 80 px native, centered) and `{{CHAPTER_SUBTITLE}}` (single-line subtitle below the title, 44 px native, centered).
- **`04_content.svg`** — Generic body-page chassis. Chrome only (z-order: backgrounds → images → text):
  1. Red 107×107 corner block top-left
  2. Light-gray title bar 1852×107 spanning the top row
  3. Bottom 76 px gray + footer-strip image (`assets/image1.jpeg`)
  4. Small red square mark inset into the footer
  5. Top-right header logo `assets/image2.png` (227×33 px display) on the gray bar
  6. `{{PAGE_NUMBER}}` text — single white digit/identifier centered in the red corner block (e.g. `1` or `1.1`)
  7. `{{PAGE_TITLE}}` text — dark slate, in the gray title bar
  8. `content-area` — dashed slate-gray outlined rectangle marking the editable content region, with a centered `{{CONTENT_AREA}}` label. Bounds: x=40-1240, y=110-670 (display); x=80-2480, y=220-1340 (source). Downstream Strategist replaces this group with whatever body pattern the page needs (two-column / card grid / chart / bullet list / hexagram / etc.) while keeping the chrome groups untouched. **Content must be generated in 2560 × 1440 source coordinates** — do NOT wrap content in a nested `<svg>` (the PPTX converter drops non-image shapes inside nested SVGs). If the Executor's content is authored in 1280 × 720 and needs remapping into the source space, use `<g transform="matrix(1.875 0 0 1.607 80 220)">` (derived from `min(2400/1280, 1120/720)`) instead. Create per-page variants (suffix-letter convention, e.g. `04a_content_two_col`, `04b_content_card_grid`) as the deck requires.
- **`05_ending.svg`** — Closing slide. The red panel, white-curve overlays, and centered `assets/image42.png` (the source deck's closing graphic) are preserved as-is. No editable placeholders — fork the file if a different closing message is needed.

## V. Asset Inventory

All 10 source assets are bundled under `assets/` with original filenames so the path rewrites are mechanical (`../assets/imageN.xxx` → `assets/imageN.xxx`).

| File | Used by | Role |
|---|---|---|
| `assets/image1.jpeg` | `04_content.svg` | Bottom footer strip pattern |
| `assets/image2.png` | `04_content.svg` | Header logo (top-right of content pages) |
| `assets/image3.png` | `01_cover.svg` | Cover logo inside white rounded chip |
| `assets/image4.png` | `03_chapter.svg` | Chapter hero image (right side) |
| `assets/image5.png` | `03_chapter.svg` | Quantum-dots backdrop (bottom-left fade) |
| `assets/image42.png` | `05_ending.svg` | Closing graphic (centered logotype / message) |

## VI. Usage Notes

1. **Canvas wrap discipline** — every page wraps its content in `<g transform="scale(0.5)">` with the outer SVG declared at viewBox `0 0 1280 720`. When extending these templates, write new content in the source's native 2560 × 1440 coordinate space and let the wrap scale it. Mixing wrapped + un-wrapped geometry on the same page will produce 2× scale mismatches. **Never use nested `<svg>` elements for content areas** — the PPTX converter only handles `<svg>` as sprite-crop image wrappers; use `<g transform="matrix(...)">` instead (see shared-standards.md §"Scaled Canvas Templates").
2. **Chapter count beyond 3** — the TOC supports 3 ribbon entries natively. For 4–5, copy the third ribbon block and translate +303 px on Y inside the scaled coordinate space. For >5, fork to a 2-page TOC.
3. **Content-page variants** — `04_content.svg` is the deck's signature pattern (six-card ring). Real decks need other body patterns (two-column / table / bullet list / chart). Create variants `04a_content_two_col.svg`, `04b_content_card_grid.svg`, etc., keeping the four chrome groups (`content-section-block`, `content-title-bar`, `content-header-logo`, `content-footer-strip` + `content-footer-mark`) intact and replacing only the body groups.
4. **Brand identity is load-bearing** — the deep red `#B7002E`, the vector-path 天弘 logotype on the cover, the `image2.png` header logo, the `image42.png` closing graphic and tagline `稳健理财 值得信赖` together define this deck. Don't recolor or replace any one of them in isolation. If a different brand is needed, fork the directory and swap all four in one pass.
5. **No background images on non-content pages** — `01_cover.svg`, `02_toc.svg`, `03_chapter.svg`, `05_ending.svg` keep only the background imagery they already ship with (cover logo chip, chapter hero + dots, ending closing graphic). Do NOT add further background photos, illustrations, or decorative imagery to those pages. The only page where background imagery may be freely added is `04_content.svg` body region (per-page variants).
6. **Source-asset replacement** — when reusing this template, swap `image4.png` (chapter hero) for a context-appropriate photo by replacing the file in place. Keep filenames identical to avoid editing every `<image href>` reference.
