# Awesome Design MD — AI Design Agent Instructions

> This directory contains 66 curated DESIGN.md files capturing the complete visual design language of well-known brands and products. Use these as reference when designing UI.

## When to Use

When the user asks you to design or style a UI "like [brand name]", "in the style of [brand]", or references a specific brand's visual identity, you should:

1. **Find the brand** in the directory listing below
2. **Read** the file at `design-md/<brand-id>/DESIGN.md` (relative to this file)
3. **Apply** the design system specifications to your UI generation

## DESIGN.md Structure

Each DESIGN.md contains 9 standardized sections:

1. **Visual Theme & Atmosphere** — Mood, density, design philosophy
2. **Color Palette & Roles** — Semantic name + hex + functional role
3. **Typography Rules** — Font families, full hierarchy table
4. **Component Stylings** — Buttons, cards, inputs, navigation with states
5. **Layout Principles** — Spacing scale, grid, whitespace philosophy
6. **Depth & Elevation** — Shadow system, surface hierarchy
7. **Do's and Don'ts** — Design guardrails and anti-patterns
8. **Responsive Behavior** — Breakpoints, touch targets, collapsing strategy
9. **Agent Prompt Guide** — Quick color reference, ready-to-use prompts

## Available Brands (66 total)

### AI & LLM Platforms
- `claude` — Claude (Anthropic): Warm terracotta accent, clean editorial layout
- `cohere` — Cohere: Vibrant gradients, data-rich dashboard aesthetic
- `elevenlabs` — ElevenLabs: Dark cinematic UI, audio-waveform aesthetics
- `minimax` — Minimax: Bold dark interface with neon accents
- `mistral.ai` — Mistral AI: French-engineered minimalism, purple-toned
- `ollama` — Ollama: Terminal-first, monochrome simplicity
- `opencode.ai` — OpenCode AI: Developer-centric dark theme
- `replicate` — Replicate: Clean white canvas, code-forward
- `runwayml` — RunwayML: Cinematic dark UI, media-rich layout
- `together.ai` — Together AI: Open-source AI infra, blueprint-style
- `voltagent` — VoltAgent: Void-black canvas, emerald accent
- `x.ai` — xAI: Stark monochrome, futuristic minimalism

### Developer Tools & IDEs
- `cursor` — Cursor: AI-first code editor, sleek dark, gradient accents
- `expo` — Expo: React Native platform, dark theme, code-centric
- `lovable` — Lovable: AI full-stack builder, playful gradients
- `raycast` — Raycast: Productivity launcher, vibrant gradient accents
- `superhuman` — Superhuman: Premium dark UI, keyboard-first, purple glow
- `vercel` — Vercel: Black and white precision, Geist font
- `warp` — Warp: Modern terminal, dark IDE-like, block-based

### Backend, Database & DevOps
- `clickhouse` — ClickHouse: Yellow-accented, technical documentation
- `composio` — Composio: Modern dark with colorful integration icons
- `hashicorp` — HashiCorp: Enterprise-clean, black and white
- `mongodb` — MongoDB: Green leaf branding, developer docs focus
- `posthog` — PostHog: Playful hedgehog, developer-friendly dark UI
- `sanity` — Sanity: Red accent, content-first editorial layout
- `sentry` — Sentry: Dark dashboard, data-dense, pink-purple accent
- `supabase` — Supabase: Dark emerald theme, code-first

### Productivity & SaaS
- `cal` — Cal.com: Clean neutral UI, developer-oriented simplicity
- `intercom` — Intercom: Friendly blue palette, conversational UI
- `linear.app` — Linear: Ultra-minimal, precise, purple accent
- `mintlify` — Mintlify: Clean, green-accented, reading-optimized
- `notion` — Notion: Warm minimalism, serif headings, soft surfaces
- `resend` — Resend: Minimal dark theme, monospace accents
- `zapier` — Zapier: Warm orange, friendly illustration-driven

### Design & Creative Tools
- `airtable` — Airtable: Colorful, friendly, structured data aesthetic
- `clay` — Clay: Organic shapes, soft gradients, art-directed
- `figma` — Figma: Vibrant multi-color, playful yet professional
- `framer` — Framer: Bold black and blue, motion-first
- `miro` — Miro: Bright yellow accent, infinite canvas
- `webflow` — Webflow: Blue-accented, polished marketing aesthetic

### Fintech & Crypto
- `binance` — Binance: Bold Binance Yellow, trading-floor urgency
- `coinbase` — Coinbase: Clean blue identity, trust-focused
- `kraken` — Kraken: Purple-accented dark UI, data-dense dashboards
- `revolut` — Revolut: Sleek dark, gradient cards, fintech precision
- `stripe` — Stripe: Purple gradients, weight-300 elegance
- `wise` — Wise: Bright green accent, friendly and clear

### E-commerce & Retail
- `airbnb` — Airbnb: Warm coral accent, photography-driven, rounded
- `meta` — Meta: Photography-first, binary light/dark, Meta Blue
- `nike` — Nike: Monochrome, massive Futura, full-bleed photography
- `shopify` — Shopify: Dark cinematic, neon green accent

### Media & Consumer Tech
- `apple` — Apple: Premium white space, SF Pro, cinematic imagery
- `ibm` — IBM: Carbon design system, structured blue palette
- `nvidia` — NVIDIA: Green-black energy, technical power aesthetic
- `pinterest` — Pinterest: Red accent, masonry grid, image-first
- `playstation` — PlayStation: Three-surface channel, cyan hover
- `spacex` — SpaceX: Stark black and white, full-bleed, futuristic
- `spotify` — Spotify: Vibrant green on dark, bold type, album-art
- `theverge` — The Verge: Acid-mint, ultraviolet, Manuka display type
- `uber` — Uber: Bold black and white, tight type, urban energy
- `wired` — WIRED: Paper-white broadsheet, custom serif, ink-blue

### Automotive
- `bmw` — BMW: Dark premium surfaces, German engineering aesthetic
- `bugatti` — Bugatti: Cinema-black, monochrome, monumental type
- `ferrari` — Ferrari: Chiaroscuro editorial, Ferrari Red
- `lamborghini` — Lamborghini: True black cathedral, gold accent
- `renault` — Renault: Aurora gradients, NouvelR typeface
- `tesla` — Tesla: Radical subtraction, cinematic photography

## Brand Aliases

| User Says | Map To |
|-----------|--------|
| Anthropic / Claude AI | `claude` |
| Linear | `linear.app` |
| Mistral | `mistral.ai` |
| Together | `together.ai` |
| xAI / Grok | `x.ai` |
| OpenCode | `opencode.ai` |
| Runway | `runwayml` |
| Cal / Cal.com | `cal` |
| The Verge | `theverge` |

## Usage Tips

- Always read the **full DESIGN.md** before generating UI — don't guess colors or fonts
- Pay special attention to the **Do's and Don'ts** section to avoid off-brand mistakes
- Use the **Agent Prompt Guide** section for ready-to-use component descriptions
- Reference colors by their **semantic name and hex value** (e.g., "Parchment #f5f4ed")
- When combining brands, pick one as primary and note which elements come from which brand
