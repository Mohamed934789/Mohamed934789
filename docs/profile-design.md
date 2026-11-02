# Profile design and maintenance

This redesign is proposed on `design/ai-portfolio-2026-11-02`, based on `95cb255439927dc0e8c4dd494e0b23d78be3629b`. The original README remains in [the base revision](https://github.com/Mohamed934789/Mohamed934789/blob/95cb255439927dc0e8c4dd494e0b23d78be3629b/README.md). The existing banner and snake workflow are retained without edits.

## Visual system

- Navy `#070D19` / `#0B1220`, cyan `#50E4F2`, violet `#A78BFA`.
- Repository-owned, script-free SVG hero, typing line, and dividers.
- One column; no fixed-width project tables. Images scale within GitHub's renderer.
- GitHub owns the surrounding page theme. README HTML cannot set a page-wide background.
- Hero animation is decorative; the typing line runs once. Both custom animations honor reduced-motion preferences and have fully visible static base states.
- Identity, interests, skills, project summaries, and contact links also exist as ordinary text.
- Shields.io provides five technology badges and two live GitHub count badges. All have meaningful alt text and equivalent text or destination links.
- The contribution snake uses the existing `output` branch. The three latest scheduled runs were successful on 2026-10-31, 2026-11-01, and 2026-11-02. No workflow changes or manual dispatch are needed.
- The existing snake asset does not provide a reduced-motion variant. The native contribution-calendar link remains available if the image is unavailable.
- No rankings, activity targets, model performance metrics, or experience levels are claimed.

## Content provenance

Verified against public repository information on 2026-11-02. These are portfolio summaries of the repository documentation, not an independent code or model audit.

| Content | Source |
| --- | --- |
| Name, final-year AI study, Kafrelsheikh University, Samsung AI Track, prior Microsoft Student Club mentoring, interests, opportunity preferences, LinkedIn and public email | [Existing profile README](https://github.com/Mohamed934789/Mohamed934789/blob/95cb255439927dc0e8c4dd494e0b23d78be3629b/README.md) |
| TenderProof description, stack, team context | [TenderProof README](https://github.com/Mohamed934789/TenderProof-Core/blob/main/README.md) |
| Personal TenderProof contribution focus | Existing profile README above |
| RAG pipeline and stack | [rag-doc-qa README](https://github.com/Mohamed934789/rag-doc-qa/blob/main/README.md) |
| Custom agent loop, streaming, frontend and backend stack | [signal-ai-agent README](https://github.com/Mohamed934789/signal-ai-agent/blob/main/README.md) |
| TF-IDF, stacking, batch scoring, SIC context and stack | [fake-job-detector README](https://github.com/Mohamed934789/fake-job-detector/blob/main/README.md) |
| Contribution animation generation | [Successful scheduled run](https://github.com/Mohamed934789/Mohamed934789/actions/runs/41381557199) |

The LinkedIn and email addresses are already intentionally published in the existing profile. Email delivery and LinkedIn account ownership cannot be independently tested by a link check.

## Updating the portfolio

Edit project summaries and technology lists in `README.md`. Keep claims tied to public project evidence. Edit visual assets in `assets/portfolio/`; no build step, fonts, JavaScript, tokens, or additional dependencies are needed. Preserve the SVG viewBox and accessible title/description.

The original `assets/ai-engineering-banner.svg` is intentionally retained. The existing workflow remains responsible for the snake; if it stops generating, the last image and native GitHub activity links remain usable.
