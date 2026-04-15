---
name: awesome-design-md
description: >
  A curated collection of 66 brand DESIGN.md files (Claude, Stripe, Apple, Vercel, etc.).
  Use this skill when the user asks to design or style a UI "like [brand name]", 
  "in the style of [brand]", or references a specific brand's visual identity.
  Each DESIGN.md contains complete design system specs: color palettes, typography, 
  component styles, layout principles, and agent prompt guides.
---

# Awesome Design MD — AI Design Skill

You have access to 66 professionally curated DESIGN.md files, each capturing the complete visual design language of a well-known brand or product website.

## When to Activate

This skill should be used when the user:
- Asks to design UI/pages "in the style of [brand]" or "like [brand]"
- Mentions wanting a specific brand's look & feel
- Asks for design inspiration from a known product/company
- Wants to apply a brand's color palette, typography, or component styling

## How to Use

### Step 1: Identify the Brand

From the user's request, identify which brand they want. Use the mapping below to find the correct directory name.

### Step 2: Read the DESIGN.md

Read the file at: `design-md/<brand-id>/DESIGN.md` (relative to this skill's root directory)

### Step 3: Apply the Design System

The DESIGN.md contains 9 sections. Use them as follows:

| Section | How to Apply |
|---------|-------------|
| 1. Visual Theme & Atmosphere | Understand the overall mood and design philosophy |
| 2. Color Palette & Roles | Use exact hex values for backgrounds, text, accents, borders |
| 3. Typography Rules | Apply font families, sizes, weights, line-heights from the hierarchy table |
| 4. Component Stylings | Follow button, card, input, navigation specs including states |
| 5. Layout Principles | Use the spacing scale, grid system, and container widths |
| 6. Depth & Elevation | Apply the shadow system and surface hierarchy |
| 7. Do's and Don'ts | Follow design guardrails to stay on-brand |
| 8. Responsive Behavior | Use breakpoints and collapsing strategies |
| 9. Agent Prompt Guide | Use quick color reference and example prompts for components |

### Step 4: Generate UI

When generating HTML/CSS/components:
- Reference specific color names and hex values from the DESIGN.md
- Use the exact typography hierarchy (font family, size, weight, line-height)
- Follow the component styling specs for buttons, cards, inputs, etc.
- Apply the correct shadow/elevation system
- Respect the Do's and Don'ts section

## Brand Directory

### AI & LLM Platforms
| Brand | Directory | Description |
|-------|-----------|-------------|
| Claude / Anthropic | `claude` | Warm terracotta accent, clean editorial layout |
| Cohere | `cohere` | Vibrant gradients, data-rich dashboard aesthetic |
| ElevenLabs | `elevenlabs` | Dark cinematic UI, audio-waveform aesthetics |
| Minimax | `minimax` | Bold dark interface with neon accents |
| Mistral AI | `mistral.ai` | French-engineered minimalism, purple-toned |
| Ollama | `ollama` | Terminal-first, monochrome simplicity |
| OpenCode AI | `opencode.ai` | Developer-centric dark theme |
| Replicate | `replicate` | Clean white canvas, code-forward |
| RunwayML | `runwayml` | Cinematic dark UI, media-rich layout |
| Together AI | `together.ai` | Open-source AI infrastructure, blueprint-style |
| VoltAgent | `voltagent` | Void-black canvas, emerald accent, terminal-native |
| xAI | `x.ai` | Stark monochrome, futuristic minimalism |

### Developer Tools & IDEs
| Brand | Directory | Description |
|-------|-----------|-------------|
| Cursor | `cursor` | AI-first code editor, sleek dark, gradient accents |
| Expo | `expo` | React Native platform, dark theme, code-centric |
| Lovable | `lovable` | AI full-stack builder, playful gradients |
| Raycast | `raycast` | Productivity launcher, vibrant gradient accents |
| Superhuman | `superhuman` | Fast email client, premium dark UI, purple glow |
| Vercel | `vercel` | Black and white precision, Geist font |
| Warp | `warp` | Modern terminal, dark IDE-like, block-based |

### Backend, Database & DevOps
| Brand | Directory | Description |
|-------|-----------|-------------|
| ClickHouse | `clickhouse` | Yellow-accented, technical documentation style |
| Composio | `composio` | Modern dark with colorful integration icons |
| HashiCorp | `hashicorp` | Enterprise-clean, black and white |
| MongoDB | `mongodb` | Green leaf branding, developer docs focus |
| PostHog | `posthog` | Playful hedgehog, developer-friendly dark UI |
| Sanity | `sanity` | Red accent, content-first editorial layout |
| Sentry | `sentry` | Dark dashboard, data-dense, pink-purple accent |
| Supabase | `supabase` | Open-source Firebase alt, dark emerald theme |

### Productivity & SaaS
| Brand | Directory | Description |
|-------|-----------|-------------|
| Cal.com | `cal` | Clean neutral UI, developer-oriented simplicity |
| Intercom | `intercom` | Friendly blue palette, conversational UI |
| Linear | `linear.app` | Ultra-minimal, precise, purple accent |
| Mintlify | `mintlify` | Clean, green-accented, reading-optimized |
| Notion | `notion` | Warm minimalism, serif headings, soft surfaces |
| Resend | `resend` | Minimal dark theme, monospace accents |
| Zapier | `zapier` | Warm orange, friendly illustration-driven |

### Design & Creative Tools
| Brand | Directory | Description |
|-------|-----------|-------------|
| Airtable | `airtable` | Colorful, friendly, structured data aesthetic |
| Clay | `clay` | Organic shapes, soft gradients, art-directed |
| Figma | `figma` | Vibrant multi-color, playful yet professional |
| Framer | `framer` | Bold black and blue, motion-first |
| Miro | `miro` | Bright yellow accent, infinite canvas |
| Webflow | `webflow` | Blue-accented, polished marketing aesthetic |

### Fintech & Crypto
| Brand | Directory | Description |
|-------|-----------|-------------|
| Binance | `binance` | Bold Binance Yellow, trading-floor urgency |
| Coinbase | `coinbase` | Clean blue identity, trust-focused |
| Kraken | `kraken` | Purple-accented dark UI, data-dense |
| Revolut | `revolut` | Sleek dark, gradient cards, fintech precision |
| Stripe | `stripe` | Purple gradients, weight-300 elegance |
| Wise | `wise` | Bright green accent, friendly and clear |

### E-commerce & Retail
| Brand | Directory | Description |
|-------|-----------|-------------|
| Airbnb | `airbnb` | Warm coral accent, photography-driven, rounded |
| Meta | `meta` | Photography-first, binary light/dark, Meta Blue |
| Nike | `nike` | Monochrome, massive Futura, full-bleed photos |
| Shopify | `shopify` | Dark cinematic, neon green accent |

### Media & Consumer Tech
| Brand | Directory | Description |
|-------|-----------|-------------|
| Apple | `apple` | Premium white space, SF Pro, cinematic imagery |
| IBM | `ibm` | Carbon design system, structured blue palette |
| NVIDIA | `nvidia` | Green-black energy, technical power aesthetic |
| Pinterest | `pinterest` | Red accent, masonry grid, image-first |
| PlayStation | `playstation` | Three-surface channel layout, cyan hover |
| SpaceX | `spacex` | Stark black and white, full-bleed, futuristic |
| Spotify | `spotify` | Vibrant green on dark, bold type, album-art |
| The Verge | `theverge` | Acid-mint, ultraviolet, Manuka display type |
| Uber | `uber` | Bold black and white, tight type, urban energy |
| WIRED | `wired` | Paper-white broadsheet, custom serif, ink-blue |

### Automotive
| Brand | Directory | Description |
|-------|-----------|-------------|
| BMW | `bmw` | Dark premium surfaces, German engineering |
| Bugatti | `bugatti` | Cinema-black, monochrome, monumental type |
| Ferrari | `ferrari` | Chiaroscuro editorial, Ferrari Red |
| Lamborghini | `lamborghini` | True black cathedral, gold accent |
| Renault | `renault` | Aurora gradients, NouvelR typeface |
| Tesla | `tesla` | Radical subtraction, cinematic photography |

## Brand Aliases

When the user mentions these names, map to the correct directory:

| User Says | Map To |
|-----------|--------|
| Anthropic | `claude` |
| Claude AI | `claude` |
| Linear | `linear.app` |
| Mistral | `mistral.ai` |
| Together | `together.ai` |
| xAI / Grok | `x.ai` |
| OpenCode | `opencode.ai` |
| Runway | `runwayml` |
| Cal / Cal.com | `cal` |
| The Verge | `theverge` |
