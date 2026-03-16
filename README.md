# 🎵  The Flavor Codes — The Channel

**Premium 24/7 YouTube Live-Streaming Channel**  
*"Building an empire in peace. Health, wealth, consistency, and sovereign ownership."*

---

## What This Is

The Flavor Codes is a 24/7 ambient live-stream channel built around four core aesthetic themes across eight global regions. Every scene is photorealistic, 8K, cinematic — designed for deep focus, luxury lounge energy, and the "Organic Hustle" ethos.

**Audio Signature:** Jugg music meets luxury lounge. Mid-tempo 70–85 BPM. Curren$y · Larry June · Big Boi DNA.  
**Visual Standard:** 8K photorealistic · Rembrandt or neon-noir lighting · locked-off angles · subtle looping animation.

---

## The Four Themes

| Theme | Vibe |
|---|---|
| **Playa Peace Lounge** | Bohemian open-air · sunken seating · fire bowls · desert luxury |
| **Vinyl Shop / Thrift Bar** | Warm analog · crate digging · espresso · golden hour |
| **Black Patagonia** | Gorpcore / techwear · A-frame interiors · pour-over · nature-adjacent |
| **Refined Gentleman's Lounge** | Dark mahogany · crystal decanter · midnight skylines · cigar smoke |

---

## Scene Library (17 of 24 Complete)

| ID | Theme | Region | BPM | Signature Detail |
|---|---|---|---|---|
| FC-001 | Playa Peace Lounge | Brooklyn, NYC | 72–80 | Fire bowl · rain on glass · dusk skyline · palo santo smoke |
| FC-002 | Vinyl Shop / Thrift Bar | Atlanta, GA | 78–84 | Gold rims as art · Spanish moss · ATL Braves case · soul/jazz/funk/trap crates |
| FC-003 | Black Patagonia | Seattle, WA | 72–78 | Mt. Rainier through fog · Chemex steam · A-frame glass · WA topo map |
| FC-004 | Refined Gentleman's Lounge | Detroit, MI | 70–76 | Motown vinyl art · Temptations/Marvin Gaye framed · snowy Renaissance Center |
| FC-005 | Playa Peace Lounge | Bay Area, CA | 74–80 | Golden Gate through fog bank · lowrider books · green smoothie |
| FC-006 | Vinyl Shop / Thrift Bar | Kyoto, Japan | 68–76 | Cherry blossoms · zen garden courtyard · City Pop crates · tetsubin steam |
| FC-007 | Playa Peace Lounge | New Orleans, LA | 74–80 | Ceiling fan · heat lightning · wrought iron balcony · beignets |
| FC-008 | Refined Gentleman's Lounge | GTA 6 / Vice City | 76–82 | Retrowave sunset · Ocean Drive · pink/cyan neon · marble floors |
| FC-009 | Black Patagonia | Tokyo, Japan | 72–78 | Shibuya crossing below · Tokyo Tower · cyan neon · rain wall |
| FC-010 | Black Patagonia | Brooklyn, NYC | 76–82 | Fire escape silhouette · rain on industrial glass · pour-over steam |
| FC-011 | Vinyl Shop / Thrift Bar | Detroit, MI | 72–78 | J Dilla easter egg · muscle car in snow · Motown heritage wall · factory skylights |
| FC-012 | Refined Gentleman's Lounge | New Orleans, LA | 70–76 | Gilt crown molding · upright piano · cigar smoke · heat lightning through wrought iron |
| FC-013 | Playa Peace Lounge | GTA 6 / Vice City | 78–84 | Infinity pool edge · palm sway · Art Deco neon skyline · cabana curtains |
| FC-014 | Vinyl Shop / Thrift Bar | New Orleans, LA | 76–82 | Sovereign Groove Records · Louis Armstrong plinth · brass tuba/trumpet · Bourbon St shutters |
| FC-015 | Refined Gentleman's Lounge | Kyoto, Japan | 68–74 | Yamazaki whisky · Hiroshige prints · cherry blossoms drifting in · incense smoke · shoji lamp |
| FC-016 | Vinyl Shop / Thrift Bar | Bay Area, CA | 78–84 | Golden Gate through warehouse roll-up door · E-40/Mac Dre posters · avocado toast · Impala mag |
| FC-017 | Black Patagonia | Minneapolis/Fargo | 70–76 | Prairie blizzard · cast iron stove ember · bare birch trees · Pendleton blanket · Prince DNA audio |

*7 scenes remaining to complete the full blueprint: FC-018 through FC-024.*

---

## Asset Structure (Per Scene)

```
scenes/FC-XXX_theme_region/
├── flavor_codes_sceneXXX_[name].png     ← 8K base image
├── flavor_codes_sceneXXX_loop.mp4       ← 8-second seamless animated loop
└── flavor_codes_sceneXXX_manifest.md    ← Full production doc
```

Each manifest includes:
- Visual inventory with animation specs
- Regional modifiers and easter eggs
- 30-track Lyria 3 audio brief (BPM, mood tags, key elements per track)
- ASMR layer specification (10% volume, matched to region)
- OBS scene configuration (source stack, audio routing, transition settings)
- Deployment folder structure

---

## OBS Deployment

1. Add each `.mp4` as a **Media Source** — enable **Loop**, enable **Use Hardware Decoding**
2. Layer ASMR audio from each manifest at **10% volume** on a dedicated audio track
3. Load the 30-track Lyria 3 playlist on the main music track
4. Use **Advanced Scene Switcher** plugin to auto-rotate scenes (recommended: 20–40 min per scene)
5. Optional: Add a transparent browser source overlay for channel branding / lower thirds

---

## Audio DNA

> Generate continuous 3-minute instrumentals blending boom-bap, neo-soul, and lo-fi trap.  
> Layer environmental ASMR at 10% volume matched to the current Regional Modifier.  
> Add subtle vocal chops buried deep in the mix: *"Keep going" · "Numbers" · "Organic" · "Stay focused"*

---

## Project Status

| Milestone | Status |
|---|---|
| Scene design (17 of 24) | ✅ In progress |
| Audio briefs (510 tracks briefed) | ✅ Complete per scene |
| Asset manifests | ✅ Generated per scene |
| OBS deployment config | ✅ Documented |
| FC-018 through FC-024 | 🔲 Remaining |
| Live channel launch | 🔲 Pending scene completion |

---

## Brand

**Channel:** Flavor Codes  
**Ethos:** Organic Hustle — building an empire in peace  
**Neon Signature:** Champagne-gold (standard) · Pink/Cyan dual-tone (Vice City scenes) · Electric cyan (Tokyo scene)

---

*Last updated: March 2026 · 17 of 24 scenes complete · 510 audio tracks briefed · 136 seconds of looped content*
