# Yuxin Xie — Academic Homepage

Based on HugoBlox Academic CV, with a customized academic layout and bilingual content. English is the default; Chinese is available at `/zh/`.

## Content
- `data/portfolio_en.json` and `data/portfolio_zh.json`: localized profile, publications, research, engineering projects, demos, and awards.
- `paper_url`: set to an actual paper URL when available. Empty URLs render as disabled gray labels. `paper_state` distinguishes `review`, `forthcoming`, and `no_paper`.
- `authorship`: optional localized author role, displayed next to publication status. Only add roles confirmed by the author. English labels use `First author`, `Co-first author`, and `Third author`; Chinese distinguishes `独立一作` and `共同一作`.
- `rankings`: independent venue badges with `label`, `note`, and optional source `url`. Keep only the higher CCF/CORE grade for conferences. CORE badges use the latest ICORE2026 release.
- No separately maintained research detail pages.
- `static/images/personal_page.jpg`: original photograph, displayed with a CSS crop. The source image is unchanged.

## Local preview
Hugo Extended 0.162.0 and Go are required. `pnpm dev` starts the preview; `pnpm build` generates `dist/`. The customized layouts use plain CSS and do not need Tailwind compilation.

## GitHub Pages
Target: https://github.com/singledog957/singledog957.github.io
Expected URL: https://singledog957.github.io/

Under repository Settings → Pages, select GitHub Actions. The workflow is restricted to the exact target repository and publishes pushes to `main`. No Sites service is used by this version.

Publication status and results follow the user-provided materials. Full coauthor lists, unpublished PDFs, DOIs, and missing paper URLs have not been invented. CNKD’s descriptive title is not a verified final publication title.

RECAP is summarized from the local `projects/recap.tex` manuscript and is under review at DATE 2027, with sole first authorship confirmed by the author. Its reported 1.70×–2.21× generation speedups at 32K exclude initial cache construction; they are not end-to-end request speedups or a claim of measured output equivalence.

Venue rankings checked on 2026-10-11: [DATE CORE-A](https://portal.core.edu.au/conf-ranks/421/), [ASP-DAC CORE-B](https://portal.core.edu.au/conf-ranks/162/), [ICCD CCF-B](https://www.ccf.org.cn/Academic_Evaluation/ARCH_DCP_SS/zgjsjxhtjgjxshy/bl/2017-03-13/586393.shtml), [DAC CCF-A](https://www.ccf.org.cn/Academic_Evaluation/ARCH_DCP_SS/zgjsjxhtjgjxshy/al/2019-05-14/665208.shtml), [IEEE Sensors Journal JCR Q1](https://www.iit.comillas.edu/publicacion/info_revista/en/394/IEEE_Sensors_Journal), [IEEE Internet of Things Journal JCR Q1](https://www.iit.comillas.edu/publicacion/info_revista/en/937/IEEE_Internet_of_Things_Journal), and [Electronics JCR Q2](https://www.mdpi.com/journal/Electronics). Journal SCI Q1/Q2 badges retain the author's supplied partition labels; their edition was not supplied, so do not describe them as verified current CAS partitions. SCI partition labels and JCR quartiles are distinct. ICSICT and ISEDA have no badge pending a verified ranking.

Upstream MIT license and HugoBlox attribution are preserved.
