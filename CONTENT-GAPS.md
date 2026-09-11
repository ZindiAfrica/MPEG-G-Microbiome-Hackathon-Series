# Content gaps and open questions

## Resolved

- **Challenge 1 accuracy figures.** The debrief gives first place 99.6%
  (4 of 1,068 wrong) and both second and third 99.7% (3 of 1,068 wrong),
  which does not support the ranking. Decision: leave as is. The page says
  "between three and four of 1,068" and publishes no per-team score.
- **Participant total.** Reported as "1,200+ data scientists" in the hero,
  without deduplication. Per-challenge figures (763 and 479) appear beside
  each challenge.
- **First place naming.** Reported as Team Tiny Margins, Big Margins, with
  Julius Mwangi (Juliuss) named as the member.
- **Cytokine count.** The sources say 62 in one place and 66 in others.
  Decision: leave as is. The page gives no dataset total and uses 66 only
  where Track 4's feature count requires it. Note that the study design
  figure now on the page states 62, so a reader comparing the figure with
  the Track 4 text will see the discrepancy.
- **Spelling and links.** Stanford, Leibniz University Hannover, the
  first-place repository URL without `/fork`, and `zindi.africa` throughout.

## Still open

**Figure licensing.** Six figures from Zhou et al. (Cell Host & Microbe,
2024) are in `assets/img/`, three of them used on the page. Each carries a
credit line, but confirm the article is open access under CC-BY before
publishing, and add the DOI to the credit. If it is not CC-BY, these have to
come out or be replaced with permission.

**Nevenka Dimitrova's affiliation.** Listed in the write-up with MSKCC, which
is not among the partners. There is a yellow flag box on the page in the
"Who ran it" section; delete it once the credit is fixed.

**Challenge 2 solution files.** Five folders under `solutions/challenge-2/`
are stubs. Add each author's code, report and licence, and confirm each
author agrees to redistribution here.

**Track detail.** The Challenge 2 debrief slides have empty "Winner Overview"
pages, so the five track descriptions come entirely from the write-up
document. If the authors' own reports contain figures, those would be better
on the page than more of the source study's figures.

**Partner logos.** The page has no partner logos, only names. The two
challenge banners carry a partner logo strip, which is the only place they
currently appear. Individual logo files would let the "Who ran it" section
carry them properly.

**Winner photographs.** None supplied. Headshots would do more for this page
than any additional data figure.

**Zhou et al. citation.** Journal and year only. Volume, issue, pages and DOI
still needed for the footer.

**Repository licence.** No `LICENSE` file. Choose one, bearing in mind the
figures above are third-party content and would need excluding from it.

**The journal proposal.** The write-up says a proposal has been submitted to
a leading journal. The page says results are being prepared for publication
and names nothing. Confirm whether more can be said.

**Prize amounts and prize sponsor.** Not in any source supplied.

## Unused images in the repository

Three figures are present but not referenced on the page, kept in case they
earn a place later:

- `body-site-structure.jpg` — within- and between-site community distance,
  and the phylogenetic tree of genera by site.
- `temporal-stability.jpg` — microbiome stability over time, by health state
  and by antibiotic or immunisation event.
- `multiomic-network.jpg` — the proteome, metabolome and lipidome network
  around the microbiome.

The page uses `study-design.jpg`, `taxa-cytokine-network.jpg` and
`mediation-analysis.jpg`. Adding more would crowd it.
