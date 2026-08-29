# Creative Fabrica Studio Partnership Concepts
## Combined final finishing pass

### Objective

One last pass on the existing 6-page document. This combines every remaining defect into a single instruction set so no further passes are needed.

Do not redesign anything. Preserve the current layout, visual system, typography direction, cards and composition exactly as they are. Every instruction below is a surgical fix.

---

# FIX 1: Text-layer spaces in three headings

The document DISPLAYS these headings correctly, but the underlying PDF text stream is missing the space characters. Copying the text out of the exported PDF produces merged words. This matters for copy-paste, search and screen readers.

Affected:

- Page 1 heading: text layer contains `testfirst`; must contain `test first`
- Page 5 decision-rule item: text layer contains `Partnerincentive`; must contain `Partner incentive`
- Page 6 heading: text layer contains `machine,then`; must contain `machine, then`

Root cause is usually a heading built with manual letter positioning or a line break replacing the space. Fix by retyping each affected text run as one normal string with real space characters, then re-applying the visual styling. Do not fix this by nudging glyph positions; the space must exist as a character in the text itself.

Verification after export: open the exported PDF, select and copy each of the three phrases, paste into a plain text editor, and confirm the spaces survive. If any phrase pastes merged, the fix did not take.

# FIX 2: Two em dashes

Replace with the wording given; do not just swap punctuation.

- Page 2, section heading currently reading "WHY IT SCALES — BUILD THE ACTIVATION KIT ONCE": change to "WHY IT SCALES: BUILD THE ACTIVATION KIT ONCE".
- Page 3, sentence currently reading "The emotional value already exists in the original drawing — AI adds movement, format and utility without replacing the child's authorship." Change to: "The emotional value already exists in the original drawing. AI adds movement, format and utility without replacing the child's authorship."

After these two changes, zero em dashes and zero en dashes remain anywhere in the document. Verify with a text search of the export.

# FIX 3: Insert the workbook links

Replace all six placeholder link objects with live hyperlinks to the workbook URL supplied at insertion time. Keep the existing visible labels exactly:

1. View full concept scoring (page 1)
2. Model partner pipeline + contact routes (page 2)
3. Family + creativity target list (page 3)
4. Brand activation pipeline + timing (page 4)
5. Open workbook (page 5, the most prominent one)
6. Open research + target workbook (page 6)

No raw URLs printed in the document. Confirm every hyperlink survives PDF export and is clickable in the exported file.

If the URL is not yet available when this pass runs, leave the placeholders as editable link objects and say so in the handback note; do not invent a URL.

# FIX 4: Insert the page 3 images

Fill the two image frames on page 3:

- DROP IN: ORIGINAL DRAWING receives the supplied drawing image
- DROP IN: STUDIO RESULT receives the supplied Studio output image

Fit each image inside its existing frame without changing the frame's size or position. If the images are not supplied when this pass runs, leave the frames as they are and say so in the handback note; do not fill them with stock or generated placeholder art.

# PRESERVE (unchanged from before)

- The 6-page structure and all existing copy not named above
- The top-right label WORKING DOCUMENT · NOT OFFICIAL CF MATERIAL on page 1
- No Creative Fabrica logo, no Studio screenshots, no official Creative Fabrica assets anywhere
- Page 3 line "Programme details as last publicly documented." stays exactly as is
- Page 2 has no evidence note under the first-targets row; keep it that way

# EXPORT QA

1. Visually inspect all six pages at 100% zoom.
2. Run the copy-paste test on the three FIX 1 phrases from the exported PDF.
3. Text-search the export for em and en dashes; expect zero.
4. Click every workbook link in the exported PDF.
5. Confirm no text is cropped, nothing overlaps, arrows and separators render correctly.
6. Confirm text remains selectable and the export is print-ready high resolution.
7. Proofread the exported PDF itself, not only the editable source.

This is a finishing pass. If a fix cannot be applied exactly as written, stop and say so in the handback note rather than improvising.
