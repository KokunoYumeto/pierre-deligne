# Pierre Deligne : articles

Éditions LaTeX d'articles de Pierre Deligne : le texte français tel qu'imprimé, et des traductions anglaises. À ce jour :
*Théorie de Hodge* I–III et *La conjecture de Weil* I–II.
[English version](README.md)

| Article | Français, tel qu'imprimé | Français, corrigé | Anglais | Scan de l'imprimé | Corrections |
|---|---|---|---|---|---|
| *Théorie de Hodge. I*, Actes du Congrès international des mathématiciens (Nice, 1970), tome 1, 425–430 | [PDF](https://github.com/KokunoYumeto/pierre-deligne/releases/download/fr-2026-11-07-r2/Deligne_1970_Theorie_de_Hodge_I_FR.pdf) | [PDF](https://github.com/KokunoYumeto/pierre-deligne/releases/download/fr-corrected-2026-11-07-r2/Deligne_1970_Theorie_de_Hodge_I_FR_corrected.pdf) | [PDF](https://github.com/KokunoYumeto/pierre-deligne/releases/download/en-2026-11-07/Deligne_1970_Theorie_de_Hodge_I_EN.pdf) | — | 81 |
| *Théorie de Hodge, II*, Publications mathématiques de l'IHÉS 40 (1971), 5–57 | [PDF](https://github.com/KokunoYumeto/pierre-deligne/releases/download/fr-2026-11-07-r2/Deligne_1971_Theorie_de_Hodge_II_FR.pdf) | [PDF](https://github.com/KokunoYumeto/pierre-deligne/releases/download/fr-corrected-2026-11-07-r2/Deligne_1971_Theorie_de_Hodge_II_FR_corrected.pdf) | [PDF](https://github.com/KokunoYumeto/pierre-deligne/releases/download/en-2026-11-07/Deligne_1971_Theorie_de_Hodge_II_EN.pdf) | [Numdam](https://www.numdam.org/item/PMIHES_1971__40__5_0/) | 264 |
| *Théorie de Hodge, III*, Publications mathématiques de l'IHÉS 44 (1974), 5–77 | [PDF](https://github.com/KokunoYumeto/pierre-deligne/releases/download/fr-2026-11-07-r2/Deligne_1974_Theorie_de_Hodge_III_FR.pdf) | [PDF](https://github.com/KokunoYumeto/pierre-deligne/releases/download/fr-corrected-2026-11-07-r2/Deligne_1974_Theorie_de_Hodge_III_FR_corrected.pdf) | [PDF](https://github.com/KokunoYumeto/pierre-deligne/releases/download/en-2026-11-07/Deligne_1974_Theorie_de_Hodge_III_EN.pdf) | [Numdam](https://www.numdam.org/item/PMIHES_1974__44__5_0/) | 691 |
| *La conjecture de Weil. I*, Publications mathématiques de l'IHÉS 43 (1974), 273–307 | [PDF](https://github.com/KokunoYumeto/pierre-deligne/releases/download/fr-2026-11-07-r2/Deligne_1974_La_conjecture_de_Weil_I_FR.pdf) | [PDF](https://github.com/KokunoYumeto/pierre-deligne/releases/download/fr-corrected-2026-11-07-r2/Deligne_1974_La_conjecture_de_Weil_I_FR_corrected.pdf) | [PDF](https://github.com/KokunoYumeto/pierre-deligne/releases/download/en-2026-11-07/Deligne_1974_La_conjecture_de_Weil_I_EN.pdf) | [Numdam](https://www.numdam.org/item/PMIHES_1974__43__273_0/) | 136 |
| *La conjecture de Weil. II*, Publications mathématiques de l'IHÉS 52 (1980), 137–252 | [PDF](https://github.com/KokunoYumeto/pierre-deligne/releases/download/fr-2026-11-07-r2/Deligne_1980_La_conjecture_de_Weil_II_FR.pdf) | [PDF](https://github.com/KokunoYumeto/pierre-deligne/releases/download/fr-corrected-2026-11-07-r2/Deligne_1980_La_conjecture_de_Weil_II_FR_corrected.pdf) | [PDF](https://github.com/KokunoYumeto/pierre-deligne/releases/download/en-2026-11-07/Deligne_1980_La_conjecture_de_Weil_II_EN.pdf) | [Numdam](https://www.numdam.org/item/PMIHES_1980__52__137_0/) | 655 |

Le texte français suit l'imprimé, coquilles comprises. Pour chaque article, `corrections/` relève chaque endroit où une
transcription antérieure s'écartait de l'imprimé et chaque coquille de l'imprimé (conservée telle quelle), avec la
page. Les sources LaTeX sont dans `tex/` ; elles se compilent avec LuaLaTeX.

Le français corrigé corrige les coquilles de l'imprimé ; chaque correction figure avec sa justification dans
`corrections/*_misprints_corrected.csv`. Une réparation proposée d'un argument (*Théorie de Hodge, II*, p. 48) y figure
sans être faite dans le texte. Le texte tel qu'imprimé reste l'édition principale.

Ces éditions sont produites par IA. Le français a été transcrit par IA puis vérifié page par page sur les scans de
l'imprimé par un modèle d'IA (OpenAI gpt-6-astra) ; *Théorie de Hodge, III* et *La conjecture de Weil. II* ont été
recomposés à partir des scans. Les corrections de coquilles sont produites par IA (Anthropic Claude Opus 5.5).
L'anglais est traduit par IA (OpenAI gpt-6-astra) à partir du français tel qu'imprimé : formules, numérotation et
renvois sont ceux du français, coquilles comprises. Pour *La conjecture de Weil. I*, la traduction anglaise de
E. Goncharov ([arXiv:1807.10810](https://arxiv.org/abs/1807.10810)) a servi de référence pour la terminologie ; les
termes fixés à cette occasion ont été repris pour les autres articles. Des erreurs subsistent certainement : merci de
les signaler par une issue, avec la page.

Ce sont les articles faits à ce jour ; d'autres articles de Deligne suivront.

## Droits

Les droits sur l'œuvre originale appartiennent à son auteur ou à ses représentants ou ayants droit. Pour autant que nous détenions des droits sur la transcription, la traduction, les corrections et la composition produites par IA, ils sont placés dans le domaine public sous CC0 1.0. Cette édition est publiée à des fins éducatives et non lucratives, et nous ne revendiquons aucun droit que nous ne détenons pas. Si vous détenez des droits sur cette œuvre et vous opposez à sa publication ici, ouvrez une issue GitHub et nous la retirerons.

---

[Sponsor this work](https://github.com/sponsors/KokunoYumeto)
