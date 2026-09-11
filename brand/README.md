# Brand / 品牌系统

This directory stores PROMPTprompt brand masters, derived assets and usage rules.

## Canonical masters / 核心母版

These files are the visual source of truth. Their path geometry should not be redrawn or substituted.

- `logo/PROMPTprompt_Wordmark_Master.svg` — PROMPTprompt 标准字标母版
- `p2-mark/P2_Master.svg` — P² 核心标识母版

## Production-safe derived assets / 可直接生产使用

- `p2-mark/01_P2_Compact.svg` — 1024×1024 白底小尺寸主标
- `p2-mark/02_P2_Transparent.svg` — 1024×1024 透明底主标
- `p2-mark/08_Favicon_Source.svg` — 512×512 favicon 源文件

## Draft compositions / 待审组合资产

Horizontal / vertical lockups, hero banner and OG image are derived from the canonical masters, but their spacing and composition remain design decisions and should be reviewed before being treated as canonical.

## Current principles / 当前原则

- White base / black mark
- Strong negative space
- Typographic hierarchy over decorative graphics
- Small digital environments prioritize recognition
- Avoid generic AI imagery such as glowing particles, neural networks and neon sci-fi motifs
- Derived assets may change placement and scale, but must not alter the P² or PROMPTprompt source geometry

## Source-of-truth workflow

Illustrator master → canonical SVG paths → GitHub brand assets → Website / Notion / X / documents
