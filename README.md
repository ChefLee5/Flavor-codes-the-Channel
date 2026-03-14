# 🎵 Flavor Codes — The Channel

**Premium 24/7 YouTube Live-Streaming Channel**  
*"Building an empire in peace. Health, wealth, consistency, and sovereign ownership."*

---

## What This Is

Flavor Codes is a 24/7 ambient live-stream channel built around four core aesthetic themes across eight global regions. Every scene is photorealistic, 8K, cinematic — designed for deep focus, luxury lounge energy, and the "Organic Hustle" ethos.

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

| ID | Theme | Region | BPM |
|---|---|---|---|
| FC-001 | Playa Peace Lounge | Brooklyn, NYC | 72–80 |
| FC-002 | Vinyl Shop / Thrift Bar | Atlanta, GA | 78–84 |
| FC-003 | Black Patagonia | Seattle, WA | 72–78 |
| FC-004 | Refined Gentleman's Lounge | Detroit, MI | 70–76 |
| FC-005 | Playa Peace Lounge | Bay Area, CA | 74–80 |
| FC-006 | Vinyl Shop / Thrift Bar | Kyoto, Japan | 68–76 |
| FC-007 | Playa Peace Lounge | New Orleans, LA | 74–80 |
| FC-008 | Refined Gentleman's Lounge | GTA 6 / Vice City | 76–82 |
| FC-009 | Black Patagonia | Tokyo, Japan | 72–78 |
| FC-010 | Black Patagonia | Brooklyn, NYC | 76–82 |
| FC-011 | Vinyl Shop / Thrift Bar | Detroit, MI | 72–78 |
| FC-012 | Refined Gentleman's Lounge | New Orleans, LA | 70–76 |
| FC-013 | Playa Peace Lounge | GTA 6 / Vice City | 78–84 |
| FC-014 | Vinyl Shop / Thrift Bar | New Orleans, LA | 76–82 |
| FC-015 | Refined Gentleman's Lounge | Kyoto, Japan | 68–74 |
| FC-016 | Vinyl Shop / Thrift Bar | Bay Area, CA | 78–84 |
| FC-017 | Black Patagonia | Minneapolis/Fargo | 70–76 |

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

## Brand

**Channel:** Flavor Codes  
**Ethos:** Organic Hustle — building an empire in peace  
**Neon Signature:** Champagne-gold (standard) · Pink/Cyan dual-tone (Vice City scenes) · Electric cyan (Tokyo scene)

---

*7 scenes remaining to complete the full blueprint: FC-018 through FC-024*
