# ARPT reversible JPEG watermarking

**Preliminary manuscript — not peer reviewed.** Exploratory English manuscript derived from the Chinese version 3 lineage. Prepared for arXiv; not submitted or accepted.

## Contents

- [English manuscript](paper/ARPT_English_Preliminary_v1.md)
- [PDF](paper/ARPT_English_Preliminary_v1.pdf)
- [arXiv source](arxiv-source/main.tex) and a relative-path source ZIP
- Public figure assets under `figures/`, with six PNG figures included in the submission source

The scope is exploratory reversible JPEG watermarking. Adjusted payload (`P_adj`) is not gross payload; the manuscript's definitions and limitations govern interpretation. Tests use baseline sequential 4:4:4 JPEG with unit quantization; integrity checks are not authentication or a general attack-robustness guarantee. Decoding requires the shared key, deployed model and matching program. No implementation or model is released here; no additional experimental results are claimed.

Figure-rendering tools and unreleased local inputs are not included. The original JPEGs and their metadata are not distributed. No license grant is supplied; no LICENSE file is included.

Public figures: [1](figures/fig1.png), [2](figures/fig2.png), [3](figures/fig3.png), [4](figures/fig4.png), [5](figures/fig5.png), [6](figures/fig6.png).

[Download arXiv source ZIP](ARPT_English_Preliminary_v1_arxiv_source.zip). Extract into an empty directory and compile `main.tex` with pdfLaTeX (three passes). Requires standard article, Latin Modern, amsmath, microtype, placeins, longtable, booktabs, etoolbox, graphicx and hyperref/bookmark packages. The source uses relative figure paths and a nine-entry bibliography; no local data or Chinese font dependency is required.
