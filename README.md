# Universal Visual Production Engine — V1.2

An engineering-led, model-agnostic AI skill for professional image and video production.

## Core principle

The AI must work like a visual-production engineer and art director before generation, then inspect, correct, verify, and report after generation.

**Brief → Engineering analysis → Art direction → Format/model selection → Prompt/shot design → Generation → Inspection → Iteration → Verification → Mandatory report.**

## What is new in V1.2

- **Every style in the world:** a global style catalog (`styles/style-catalog.md`) covering photography, art movements, world traditions, anime, cyberpunk, 3D, pixel art, simple styles (stickman, doodle, sticker), retro aesthetics, and festival and occasion styles (Diwali, Holi, Eid, Christmas, Lunar New Year, birthdays, weddings, and more). The style you ask for always wins.
- **Specific, realistic prompts:** a mandatory Specification Lock and realism protocol before every generation.
- **Clear, high-resolution output:** highest native resolution first, honest upscaling, and pixel-clarity inspection at 100% zoom.
- **Realistic humans, 3D rules, and visibility:** dedicated realism protocol, mandatory 3D production rules (sub-style, materials, lighting, honest 3D-vs-3D-style reporting), and a visibility and legibility standard, all checked and reported.
- **Strict photorealism mode:** when the user asks for realism, the skill declares a realism level, forbids the HDR and painterly look, limits scenes to one hero subject plus at most three supporting elements, and fails the realism gate if only a stylized look is achieved. See `examples/photoreal-example.md`.
- **Resolution enforcement:** images below the 2048 px baseline must be upscaled with a real tool, or the resolution gate is marked failed.
- **Zero-defect standard:** known fixable defects are corrected before delivery, and unfixable ones are disclosed.
- **Strict video rules:** realistic voices, high-quality motion and graphics, continuity, and frame-by-frame inspection.
- **Mandatory Generation Method & Provenance report:** final prompts, tools, parameters, attempts, post-processing, and verification evidence for every image and video.

## Supported creative directions

- Photorealistic humans, portraits, documentary, cinematic, product, architecture, food, fashion, wildlife, and landscapes.
- Advertising, brand campaigns, posters, social media, packaging, banners, and commercial design.
- Anime, manga, comic, cel-shaded, chibi, storybook, and stylized animation.
- Pixel art, sprites, tilesets, retro game art, and isometric scenes.
- 3D, CGI, product visualization, architecture, low-poly, and stylized 3D.
- Illustration, watercolor, ink, vector, collage, printmaking, infographic, and experimental art.
- Stickman, doodle, sticker, cyberpunk, vaporwave, and other internet-era looks.
- Festival, holiday, and occasion styles with authentic symbols and colors.
- Classical and world art traditions. If a style is not listed, the skill breaks it into concrete traits and produces it anyway.

The skill aims for realism appropriate to the selected style. Intentional style traits, such as sketchy lines or film grain, are treated as style, not defects. It does not force photorealism onto anime, pixel art, or other stylized work.

## Mandatory workflow

Every image/video task follows the full production lifecycle, with a concise mandatory report after completed generation. See `SKILL.md` for the complete rules and report templates.

## Install / use

1. Copy `SKILL.md` into the skill directory supported by your AI assistant.
2. Import or enable the skill using that platform's supported skill mechanism.
3. Connect image/video generation tools separately.
4. Ask the AI to create media. It should follow the full workflow.

This is a portable instruction package. It does not itself provide model access, API keys, tool permissions, or universal format support. Each AI must check the tools and formats available in its own environment.

"Perfect" is the target, not a claim. The skill requires inspection and honest reporting. It never states that a result is flawless, 4K, or realistic unless the actual file was checked.

## Repository structure

```text
universal-visual-production-skill/
├── SKILL.md
├── README.md
├── LICENSE
├── styles/
│   └── style-catalog.md
├── examples/
│   └── photoreal-example.md
├── templates/
│   ├── image-brief.md
│   └── video-shotlist.md
└── workflows/
    ├── image-workflow.md
    └── video-workflow.md
```

## License

MIT. See `LICENSE`.
