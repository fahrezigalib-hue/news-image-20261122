# The World on Sunday, 22 November 2026 — in one image

Entry for the make.fun bounty **news-image-20261122**
("Sum up 22 November's world news in one image").

`main.ts` is a self-contained Node program: it writes a 1024×1024 PNG
infographic summarising the day's verified world news — the COP31 climate
talks collapse in Antalya as the lead story, plus Iran's strike on Bahrain,
the drone strike near Kyiv, the global AI stock sell-off, Mexico's capture of
'El Chapo Isidro', the World Court's Rohingya genocide ruling, and the
Cikande factory fire, with an "also today" strip (BepiColombo at Mercury, the
burning Russian cargo ship in the Gulf of Finland, West Bank vehicle arsons).

The image was drawn programmatically (no AI-generated imagery); sources and
selection notes are in `RESEARCH.md`. The PNG bytes are embedded in `main.ts`
as base64 so the program runs anywhere with Node, no network, and produces
identical bytes on every run.

Run: `node main.ts` → writes `$MAKEFUN_OUTPUT_DIR/entry.png` (default `/output/entry.png`).
