# Pierre Deligne: papers

LaTeX editions of papers by Pierre Deligne: the French text as printed, and English translations. So far: *Théorie
de Hodge* I–III and *La conjecture de Weil* I–II.
[Version française](README.fr.md)

| Paper | French, as printed | French, corrected | English | English, corrected | Scan of the print | Corrections |
|---|---|---|---|---|---|---|
| *Théorie de Hodge. I*, Actes du Congrès international des mathématiciens (Nice, 1970), tome 1, 425–430 | [PDF](https://github.com/KokunoYumeto/pierre-deligne/releases/download/fr-2026-11-07-r2/Deligne_1970_Theorie_de_Hodge_I_FR.pdf) | [PDF](https://github.com/KokunoYumeto/pierre-deligne/releases/download/fr-corrected-2026-11-07-r2/Deligne_1970_Theorie_de_Hodge_I_FR_corrected.pdf) | [PDF](https://github.com/KokunoYumeto/pierre-deligne/releases/download/en-2026-11-07/Deligne_1970_Theorie_de_Hodge_I_EN.pdf) | [PDF](https://github.com/KokunoYumeto/pierre-deligne/releases/download/en-corrected-2026-11-09/Deligne_1970_Theorie_de_Hodge_I_EN_corrected.pdf) | — | 81 |
| *Théorie de Hodge, II*, Publications mathématiques de l'IHÉS 40 (1971), 5–57 | [PDF](https://github.com/KokunoYumeto/pierre-deligne/releases/download/fr-2026-11-07-r2/Deligne_1971_Theorie_de_Hodge_II_FR.pdf) | [PDF](https://github.com/KokunoYumeto/pierre-deligne/releases/download/fr-corrected-2026-11-07-r2/Deligne_1971_Theorie_de_Hodge_II_FR_corrected.pdf) | [PDF](https://github.com/KokunoYumeto/pierre-deligne/releases/download/en-2026-11-07/Deligne_1971_Theorie_de_Hodge_II_EN.pdf) | [PDF](https://github.com/KokunoYumeto/pierre-deligne/releases/download/en-corrected-2026-11-09/Deligne_1971_Theorie_de_Hodge_II_EN_corrected.pdf) | [Numdam](https://www.numdam.org/item/PMIHES_1971__40__5_0/) | 264 |
| *Théorie de Hodge, III*, Publications mathématiques de l'IHÉS 44 (1974), 5–77 | [PDF](https://github.com/KokunoYumeto/pierre-deligne/releases/download/fr-2026-11-07-r2/Deligne_1974_Theorie_de_Hodge_III_FR.pdf) | [PDF](https://github.com/KokunoYumeto/pierre-deligne/releases/download/fr-corrected-2026-11-07-r2/Deligne_1974_Theorie_de_Hodge_III_FR_corrected.pdf) | [PDF](https://github.com/KokunoYumeto/pierre-deligne/releases/download/en-2026-11-07/Deligne_1974_Theorie_de_Hodge_III_EN.pdf) | [PDF](https://github.com/KokunoYumeto/pierre-deligne/releases/download/en-corrected-2026-11-09/Deligne_1974_Theorie_de_Hodge_III_EN_corrected.pdf) | [Numdam](https://www.numdam.org/item/PMIHES_1974__44__5_0/) | 691 |
| *La conjecture de Weil. I*, Publications mathématiques de l'IHÉS 43 (1974), 273–307 | [PDF](https://github.com/KokunoYumeto/pierre-deligne/releases/download/fr-2026-11-07-r2/Deligne_1974_La_conjecture_de_Weil_I_FR.pdf) | [PDF](https://github.com/KokunoYumeto/pierre-deligne/releases/download/fr-corrected-2026-11-07-r2/Deligne_1974_La_conjecture_de_Weil_I_FR_corrected.pdf) | [PDF](https://github.com/KokunoYumeto/pierre-deligne/releases/download/en-2026-11-07/Deligne_1974_La_conjecture_de_Weil_I_EN.pdf) | [PDF](https://github.com/KokunoYumeto/pierre-deligne/releases/download/en-corrected-2026-11-09/Deligne_1974_La_conjecture_de_Weil_I_EN_corrected.pdf) | [Numdam](https://www.numdam.org/item/PMIHES_1974__43__273_0/) | 136 |
| *La conjecture de Weil. II*, Publications mathématiques de l'IHÉS 52 (1980), 137–252 | [PDF](https://github.com/KokunoYumeto/pierre-deligne/releases/download/fr-2026-11-07-r2/Deligne_1980_La_conjecture_de_Weil_II_FR.pdf) | [PDF](https://github.com/KokunoYumeto/pierre-deligne/releases/download/fr-corrected-2026-11-07-r2/Deligne_1980_La_conjecture_de_Weil_II_FR_corrected.pdf) | [PDF](https://github.com/KokunoYumeto/pierre-deligne/releases/download/en-2026-11-07/Deligne_1980_La_conjecture_de_Weil_II_EN.pdf) | [PDF](https://github.com/KokunoYumeto/pierre-deligne/releases/download/en-corrected-2026-11-09/Deligne_1980_La_conjecture_de_Weil_II_EN_corrected.pdf) | [Numdam](https://www.numdam.org/item/PMIHES_1980__52__137_0/) | 655 |

The French text follows the print, its misprints included. For each paper, `corrections/` lists every place where an
earlier transcription differed from the print and every misprint of the print (kept as printed), with the page. The
LaTeX sources are in `tex/`; they compile with LuaLaTeX.

The corrected French fixes the misprints of the print; each correction is listed with its reason in
`corrections/*_misprints_corrected.csv`. One proposed repair of an argument (*Théorie de Hodge, II*, p. 48) is listed
there but not made in the text. The text as printed remains the main edition.

These editions are AI-produced. The French was AI-transcribed and checked page by page against scans of the print by
an AI model (OpenAI gpt-6-astra); *Théorie de Hodge, III* and *La conjecture de Weil. II* were typeset anew from the
scans. The misprint corrections are AI-produced (Anthropic Claude Opus 5.5). The English is AI-translated (OpenAI
gpt-6-astra) from the French as printed: formulas, numbering and page references are those of the French, and so are
the misprints. For *La conjecture de Weil. I*, the English translation by E. Goncharov
([arXiv:1807.10810](https://arxiv.org/abs/1807.10810)) served as a reference for terminology; the terms settled there
were used for the other papers as well. Errors certainly remain: please report them as issues, with the page.

These are the papers done so far; more of Deligne's papers will follow.

The corrected English carries each correction of the corrected French into the English translation; `corrections/*_misprints_corrected_en.csv` lists every one with its English edit (most were carried over by script, the rest by AI: OpenAI GPT-6.1 Sol and Anthropic Claude Opus 5.5).

## Rights

The rights in the original work belong to its author or the author's representatives or heirs. Where we hold rights, in the AI-produced transcription, translation, corrections and typesetting, they are dedicated to the public domain under CC0 1.0. This edition is published for educational, non-profit purposes, and we claim no rights we do not hold. If you hold rights in this work and object to its publication here, please open a GitHub issue and we will take it down.

---

[Sponsor this work](https://github.com/sponsors/KokunoYumeto)
