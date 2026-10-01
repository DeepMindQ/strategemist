# Kefi Tech — Service × Industry Decks

16 capability brief decks for Kefi Tech, organized as a 4×4 matrix of **4 service verticals × 4 industries**.

## Service Verticals

1. **AI Transformation** — GenAI, Agentic AI, RAG, AI/ML, LLMOps, Responsible AI
2. **Data Analytics & Data Engineering** — Strategy, Engineering, Platforms, BI, Advanced Analytics, AI-Powered Analytics
3. **Digital Engineering & Transformation** — Product, Cloud-Native, Modernization, APIs, UX, DevSecOps
4. **Quality & Security Engineering** — AppSec/DevSecOps, VAPT, Performance, Test Automation, AI Testing, Quality Consulting

## Industries

1. **BFSI & Insurance**
2. **Manufacturing**
3. **Healthcare & Pharma**
4. **Education**

## Deck Structure (12 slides each)

Every deck follows the same structure:

1. Cover
2. Industry Context
3. Service Capability Overview
4. Capability Deep-Dive #1
5. Capability Deep-Dive #2
6. Capability Deep-Dive #3
7. Capability Deep-Dive #4
8. Industry Applications
9. Reference Architecture
10. Engagement Pathway
11. Why Kefi Tech
12. Closing

## Design System

- **Brand palette**: `#004c97` (brand blue) + `#ff6c0e` (accent orange) on `#FFFFFF`
- **Typography**: Sora (headings) / Inter (body) / JetBrains Mono (numeric)
- **Logo discipline**: Single image logo on cover + closing only; text wordmark elsewhere
- **No selling language**: No "PROOF:", "NEW POV", "BEST FOR:" tags, pull-quotes, or CTAs
- **Visual diagrams**: Capability maps, layered architectures, flow diagrams, industry visual cards

## Directory Layout

```
kefi_decks/
├── shared/                          # Shared global.css + kefi_logo.png
├── ai_transformation__bfsi/         # 12 HTML slides + slides_brief.json
├── ai_transformation__manufacturing/
├── ai_transformation__healthcare/
├── ai_transformation__education/
├── data_analytics__bfsi/
├── data_analytics__manufacturing/
├── data_analytics__healthcare/
├── data_analytics__education/
├── digital_engineering__bfsi/
├── digital_engineering__manufacturing/
├── digital_engineering__healthcare/
├── digital_engineering__education/
├── quality_security__bfsi/
├── quality_security__manufacturing/
├── quality_security__healthcare/
├── quality_security__education/
└── pptx/                           # 16 exported PPTX files
```

## Files Per Deck

Each deck directory contains:

- `global.css` — shared stylesheet (v5 visual diagram tokens)
- `assets/kefi_logo.png` — Kefi Tech logo (5798×981 transparent PNG)
- `slides_brief.json` — manifest with verbatim content for all 12 slides
- `slide_01.html` through `slide_12.html` — rendered slides (1280×720, standalone HTML)

## Exported PPTX Files

The `pptx/` directory contains all 16 `.pptx` files, ready for distribution.

## Regenerating

To regenerate all 16 briefs:

```bash
python3 /home/z/my-project/scripts/generate_all_briefs.py
```

To re-export all 16 PPTX files:

```bash
bash /home/z/my-project/scripts/export_all_decks.sh
```

## License

Proprietary — Kefi Tech internal use only.
