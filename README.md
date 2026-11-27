# Universal Visual Production Engine — V1.1

An engineering-led, model-agnostic AI skill for professional image and video production.

## Core principle

The AI must work like a visual-production engineer and art director before generation, then inspect, correct, verify, and report after generation.

**Brief → Engineering analysis → Art direction → Format/model selection → Prompt/shot design → Generation → Inspection → Iteration → Verification → Mandatory report.**

## Supported creative directions

- Photorealistic humans, portraits, documentary, cinematic, product, architecture, food, fashion, wildlife, and landscapes.
- Advertising, brand campaigns, posters, social media, packaging, banners, and commercial design.
- Anime, manga, comic, cel-shaded, chibi, storybook, and stylized animation.
- Pixel art, sprites, tilesets, retro game art, and isometric scenes.
- 3D, CGI, product visualization, architecture, low-poly, and stylized 3D.
- Illustration, watercolor, ink, vector, collage, printmaking, infographic, and experimental art.

The skill aims for realism appropriate to the selected style. It does not force photorealism onto anime, pixel art, or other stylized work.

## Mandatory workflow

Every image/video task follows the full production lifecycle, with a concise mandatory report after completed generation. See `SKILL.md` for the complete rules and report templates.

## Install / use

1. Copy `SKILL.md` into the skill directory supported by your AI assistant.
2. Import or enable the skill using that platform's supported skill mechanism.
3. Connect image/video generation tools separately.
4. Ask the AI to create media. It should follow the full workflow.

This is a portable instruction package. It does not itself provide model access, API keys, tool permissions, or universal format support. Each AI must check the tools and formats available in its own environment.

## Repository structure

```text
universal-visual-production-skill/
├── SKILL.md
├── README.md
├── LICENSE
├── templates/
│   ├── image-brief.md
│   └── video-shotlist.md
└── workflows/
    ├── image-workflow.md
    └── video-workflow.md
```

## License

MIT. See `LICENSE`.
