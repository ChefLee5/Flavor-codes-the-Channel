# FLAVOR CODES — Scene 001 Manifest
## Playa Peace Lounge × Brooklyn
**Scene ID:** FC-001  
**Resolution:** 8K (7680×4320) → downsampled for streaming at 4K/1080p  
**Loop Duration:** 8 seconds (seamless)  
**Vibe Codes:** Bohemian Luxury · Organic Hustle · Brooklyn Grit · Rooftop Sovereignty  

---

## Visual Inventory

| Element | Description | Animation |
|---|---|---|
| FLAVOR CODES neon | Champagne-gold, exposed brick wall | Subtle flicker pulse, ~0.3s interval |
| Sheer linen curtains | Cream white, open French doors | Gentle billow, 4-second cycle |
| Clay fire bowl | Terra cotta, center sunken pit | Amber flame dance, continuous |
| Crystal decanter | Teak coffee table, amber spirit | Light refraction catch |
| Palo santo smoke | Silver tray, low coffee table | Thin smoke thread rising, slow curl |
| Vinyl record | Reclaimed wood shelf, right side | Continuous spin |
| Brooklyn skyline | Golden hour → deep violet dusk | Static, rain streaks on glass |
| Rain on glass | Left window panel | Slow vertical streak, 6-second loop |

---

## Regional Modifiers Applied (Brooklyn)

- **Architecture:** Brownstone penthouse, exposed brick, raw wood ceiling beams
- **Lighting:** Streetlamp amber cutting through summer rain + golden-hour dusk blend
- **Skyline:** NYC water towers, mid-rise rooftops, distant Manhattan tower silhouette
- **Audio Easter Egg:** Distant subway rumble at 5% volume, subtle traffic hum

---

## Audio Generation Brief (Lyria 3 — 30-Track Playlist)

### Vibe Parameters
- **BPM Range:** 72–80 BPM
- **Genre Blend:** Neo-soul boom-bap / lo-fi trap / jazz-inflected G-funk
- **Reference Artists:** Curren$y (automotive luxury, smooth sample flips), Larry June (crisp motivational bounce), Big Boi (heavy bass Southern soul)
- **ASMR Layer (10% vol):** Distant NYC subway rumble · light summer rain on concrete · muffled street conversation from below · occasional fire crackle

### Vocal Chop Palette (buried deep in mix, 8–12% vol)
> "Keep going" · "Flavor" · "Organic" · "Numbers up" · "Stay focused" · "Build" · "Codes"

### 30-Track Sequence

| # | Track Name | Mood Tag | BPM | Key Elements |
|---|---|---|---|---|
| 01 | Empire State of Mind (Instrumental) | Establishing · Arrival | 74 | Piano keys, dusty 808, vinyl crackle |
| 02 | Rooftop Sovereign | Grounded · Focused | 76 | Muted guitar loop, hi-hat pattern |
| 03 | Brooklyn Blend | Nostalgic · Smooth | 72 | Soul sample flip, walking bass |
| 04 | Amber Decanter | Luxury · Still | 78 | Rhodes chord stabs, brushed drums |
| 05 | Linen Breeze | Bohemian · Open | 75 | Flute sample, light trap snare |
| 06 | Coded Frequencies | Motivational · Low | 80 | Sub bass pulse, chopped vocal |
| 07 | Palo Santo Smoke | Meditative · Deep | 70 | Sitar loop, sparse percussion |
| 08 | Water Tower View | Cinematic · Steady | 76 | String pad, boom-bap kick |
| 09 | Vinyl Ritual | Analog · Warm | 74 | Crate-dig sample, dusty filter |
| 10 | Fire Bowl Sessions | Focused · Rich | 77 | Fender Rhodes, syncopated drums |
| 11 | Brownstone King | Confident · Swag | 80 | G-funk bass, crisp snare |
| 12 | Rain On Glass | Introspective · Deep | 72 | Lo-fi piano, rain texture |
| 13 | Terracotta Hours | Creative · Free | 75 | Acoustic guitar loop, light keys |
| 14 | Hustle In Peace | Duality · Drive | 78 | Boom-bap drums, horn stab |
| 15 | Neon Residue | Atmospheric · Glow | 73 | Synth pad, sub bass, vinyl hiss |
| 16 | Sovereign Stack | Wealth · Calm | 80 | Trumpet sample, walking 808 |
| 17 | Curtains Blowing | Dreamy · Still | 70 | Ambient pad, brushed snare |
| 18 | Codes & Keys | Intellectual · Sharp | 77 | Piano riff, hi-hat shuffle |
| 19 | Late Night Commerce | Nocturnal · Rich | 76 | Bass-heavy, muted guitar pick |
| 20 | The Long View | Aspirational · Wide | 74 | Orchestral swell, boom-bap drums |
| 21 | Flavor Architecture | Complex · Rich | 79 | Multi-layer sample, jazz chord |
| 22 | Groundwork | Steady · Foundation | 75 | Simple drum loop, synth bass |
| 23 | Sky Over BK | Expansive · Hopeful | 73 | Choir sample, light trap pattern |
| 24 | Crystal Clear | Precise · Focused | 78 | Melodic synth, 4-bar loop |
| 25 | Steam Rising | Ambient · Transitional | 71 | Texture wash, minimal percussion |
| 26 | Empire Builder | Motivational · Peak | 82 | Energy lift, chopped soul vocal |
| 27 | Sunday Sovereign | Ease · Reward | 74 | Lazy drums, warm chord stabs |
| 28 | Coded Luxury | Brand · Identity | 77 | Bass groove, vinyl scratch accent |
| 29 | Night Architecture | Late · Cinematic | 75 | Dark pad, syncopated hi-hat |
| 30 | Back To The Crib | Closing · Grounded | 72 | Warm outro loop, fade to vinyl crackle |

---

## OBS Scene Setup

### Scene Name: `FC-001 | Playa Peace Lounge × Brooklyn`

```
[OBS Scene Configuration]

SOURCE 1 — Background Video Loop
  Type: Media Source
  File: flavor_codes_scene001_loop.mp4
  Loop: TRUE
  Restart on Activate: TRUE
  Use Hardware Decoding: TRUE
  Position: 0, 0
  Size: 1920×1080 (scale from 4K source)

SOURCE 2 — Audio Layer: Brooklyn ASMR
  Type: Media Source (Audio Only)
  File: brooklyn_asmr_layer.mp3
  Loop: TRUE
  Volume: 10%
  Contents: Subway rumble, light rain, fire crackle, muted street audio

SOURCE 3 — Music Track (Lyria 3 Playlist)
  Type: VLC Video Source (playlist mode)
  Playlist: flavor_codes_brooklyn_30track.m3u
  Volume: 100%
  Shuffle: FALSE (sequential, gapless)

SOURCE 4 — Channel Overlay (optional)
  Type: Browser Source
  URL: localhost:8080/overlay-fc001.html
  Width: 1920, Height: 1080
  Custom CSS: background: transparent;

AUDIO MIXER
  Track 1 (Stream): Music + ASMR blend
  Track 2 (Recording): Full mix
  Monitoring: Off
```

### Transition Settings
```
Scene Transition: Fade
Duration: 2000ms
When looping between scenes: Apply cross-dissolve at loop point
```

---

## Deployment Folder Structure

```
/flavor-codes-channel/
├── scenes/
│   └── FC-001_playa_brooklyn/
│       ├── flavor_codes_scene001_playa_brooklyn.png   ← 8K base image
│       ├── flavor_codes_scene001_loop.mp4              ← 8-second animated loop
│       └── flavor_codes_scene001_manifest.md           ← this file
├── audio/
│   ├── brooklyn_asmr_layer.mp3
│   └── playlists/
│       └── fc001_brooklyn_30track.m3u
├── overlays/
│   └── overlay-fc001.html
└── obs/
    └── FC-001_scene_collection.json
```

---

## Next Scene Queue

| Priority | Theme | Region | Status |
|---|---|---|---|
| FC-002 | Vinyl Shop / Thrift Bar | Atlanta | Queued |
| FC-003 | Black Patagonia | Seattle | Queued |
| FC-004 | Refined Gentleman's Lounge | Detroit | Queued |
| FC-005 | Playa Peace Lounge | Bay Area | Queued |

---

*Generated by Flavor Codes Creative Director · Session 001 · March 14, 2026*
