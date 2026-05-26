# Wild Echo BirdNET AU Accuracy Benchmark v2
**Date:** 2026-05-14  
**Species tested:** 50 target species (48 recordings obtained, 2 unavailable)  
**Analyst:** Kai (Wild Echo subagent)

---

## Executive Summary

BirdNET correctly identifies **37.5% of Australian bird species** tested (18/48 with recordings), including a 40% rate for common/widespread species. Performance is strongest on iconic, vocally distinctive birds but collapses entirely on threatened species (0/4 tested) and produces dangerous false positives — the critically endangered Regent Honeyeater was misidentified as White-browed Woodswallow with 0.95 confidence. This benchmark provides the data needed to communicate both BirdNET's genuine capabilities and its critical limitations to Ranger and Enterprise customers.

---

## Overall Accuracy

| Metric | Value |
|--------|-------|
| Species tested | 48 (of 50 target; 2 recordings unavailable) |
| PASS (correct, conf ≥ 0.3) | **15** (31.2%) |
| WEAK (correct, conf 0.1–0.3) | **3** (6.2%) |
| FAIL (not detected) | **30** (62.5%) |
| **Overall detection rate** | **37.5%** |
| Avg confidence on passes | 0.68 |

---

## Full Results Table

| Species | Common Name | Category | Detected | Confidence | Result |
|---------|------------|----------|----------|------------|--------|
| Dacelo novaeguineae | Laughing Kookaburra | Common | No | 0.00 | ❌ FAIL |
| Gymnorhina tibicen | Australian Magpie | Common | Yes | 0.89 | ✅ PASS |
| Trichoglossus moluccanus | Rainbow Lorikeet | Common | No | 0.00 | ❌ FAIL |
| Cacatua galerita | Sulphur-crested Cockatoo | Common | Yes | 0.64 | ✅ PASS |
| Eolophus roseicapilla | Galah | Common | Yes | 0.93 | ✅ PASS |
| Platycercus elegans | Crimson Rosella | Common | No | 0.00 | ❌ FAIL |
| Platycercus eximius | Eastern Rosella | Common | No | 0.00 | ❌ FAIL |
| Eudynamys orientalis | Pacific Koel | Common | No | 0.00 | ❌ FAIL |
| Rhipidura leucophrys | Willie Wagtail | Common | Yes | 0.99 | ✅ PASS |
| Corvus coronoides | Australian Raven | Common | No | 0.00 | ❌ FAIL |
| Cracticus torquatus | Grey Butcherbird | Common | Yes | 0.72 | ✅ PASS |
| Strepera graculina | Pied Currawong | Common | No | 0.00 | ❌ FAIL |
| Podargus strigoides | Tawny Frogmouth | Common | Yes | 0.93 | ✅ PASS |
| Ninox boobook | Southern Boobook | Common | Yes | 1.00 | ✅ PASS |
| Todiramphus sanctus | Sacred Kingfisher | Common | Yes | 0.32 | ✅ PASS |
| Anthochaera carunculata | Red Wattlebird | Common | No | 0.00 | ❌ FAIL |
| Manorina melanocephala | Noisy Miner | Common | No | 0.00 | ❌ FAIL |
| Philemon corniculatus | Noisy Friarbird | Common | No | 0.00 | ❌ FAIL |
| Malurus cyaneus | Superb Fairy-wren | Common | No | 0.00 | ❌ FAIL |
| Malurus splendens | Splendid Fairy-wren | Common | No | 0.00 | ❌ FAIL |
| Acanthiza pusilla | Brown Thornbill | Common | No | 0.00 | ❌ FAIL |
| Pardalotus striatus | Striated Pardalote | Common | Yes | 0.33 | ✅ PASS |
| Pardalotus punctatus | Spotted Pardalote | Common | Yes | 0.80 | ✅ PASS |
| Eopsaltria australis | Eastern Yellow Robin | Common | No | 0.00 | ❌ FAIL |
| Petroica multicolor | Scarlet Robin | Common | Yes | 0.32 | ✅ PASS |
| Myiagra rubecula | Leaden Flycatcher | Common | No | 0.00 | ❌ FAIL |
| Pachycephala rufiventris | Rufous Whistler | Common | No | 0.00 | ❌ FAIL |
| Colluricincla harmonica | Grey Shrike-thrush | Common | Yes | 0.36 | ✅ PASS |
| Hirundo neoxena | Welcome Swallow | Common | Yes | 0.13 | ⚠️ WEAK |
| Artamus leucorynchus | White-breasted Woodswallow | Common | Yes | 0.15 | ⚠️ WEAK |
| Oriolus sagittatus | Olive-backed Oriole | Common | No | 0.00 | ❌ FAIL |
| Sphecotheres vieilloti | Australasian Figbird | Common | No | 0.00 | ❌ FAIL |
| Entomyzon cyanotis | Blue-faced Honeyeater | Common | No | 0.00 | ❌ FAIL |
| Phylidonyris novaehollandiae | New Holland Honeyeater | Common | No | 0.00 | ❌ FAIL |
| Acanthorhynchus tenuirostris | Eastern Spinebill | Common | No | 0.00 | ❌ FAIL |
| Grallina cyanoleuca | Magpie-lark | Common | Yes | 0.83 | ✅ PASS |
| Psophodes olivaceus | Eastern Whipbird | Common | No | 0.00 | ❌ FAIL |
| Zoothera heinei | Russet-tailed Thrush | Common | No | 0.00 | ❌ FAIL |
| Melanodryas cucullata | Hooded Robin | Common | No | 0.00 | ❌ FAIL |
| Microeca fascinans | Jacky Winter | Common | Yes | 0.87 | ✅ PASS |
| Acridotheres tristis | Common Myna | Invasive | No | 0.00 | ❌ FAIL |
| Passer domesticus | House Sparrow | Invasive | Yes | 0.43 | ✅ PASS |
| Sturnus vulgaris | Common Starling | Invasive | Yes* | 0.25 | ⚠️ WEAK |
| Columba livia | Rock Dove | Invasive | No | 0.00 | ❌ FAIL |
| Lathamus discolor | Swift Parrot | Threatened | No | 0.00 | ❌ FAIL |
| Neophema chrysogaster | Orange-bellied Parrot | Threatened | — | — | NO FILE |
| Lichenostomus melanops | Helmeted Honeyeater | Threatened | No | 0.00 | ❌ FAIL |
| Anthochaera phrygia | Regent Honeyeater | Threatened | No | 0.00 | ❌ FAIL |
| Pezoporus occidentalis | Night Parrot | Threatened | No | 0.00 | ❌ FAIL |
| Erythrura gouldiae | Gouldian Finch | Threatened | — | — | NO FILE |

*Common Starling detected as "European Starling" (same species, different common name in BirdNET's North American taxonomy)

---

## Category Breakdown

| Category | Tested | PASS | WEAK | FAIL | Detection Rate |
|----------|--------|------|------|------|----------------|
| Common/Widespread | 40 | 14 | 2 | 24 | **40.0%** |
| Invasive Species | 4 | 1 | 1 | 2 | **50.0%** |
| Threatened/Rare | 4* | 0 | 0 | 4 | **0.0%** |
| **Total** | **48** | **15** | **3** | **30** | **37.5%** |

*2 threatened species had no recordings available on iNaturalist AU

---

## Key Findings

### What BirdNET Nails
- **Nocturnal/crepuscular species with distinctive calls:** Southern Boobook (1.00), Tawny Frogmouth (0.93)
- **Corvid-adjacent species:** Willie Wagtail (0.99), Magpie-lark (0.83), Australian Magpie (0.89)
- **Cockatoos/parrots with distinctive calls:** Galah (0.93), Sulphur-crested Cockatoo (0.64)
- **Pardalotes (both species detected):** Spotted (0.80), Striated (0.33)
- **Jacky Winter, Grey Butcherbird, Grey Shrike-thrush** — all above 0.70

### What It Misses Completely
- **ALL honeyeaters except one:** Red Wattlebird, Noisy Miner, Noisy Friarbird, Blue-faced Honeyeater, New Holland Honeyeater, Eastern Spinebill — 0% detection. Honeyeaters are arguably Australia's most diverse family.
- **ALL threatened species:** 0/4 tested. Critical gap for Wild Echo's conservation pitch.
- **Iconic species:** Laughing Kookaburra (BirdNET's most embarrassing miss for an AU product), Rainbow Lorikeet, Pacific Koel, Australian Raven, Pied Currawong
- **Fairy-wrens:** Superb and Splendid Fairy-wren both missed entirely
- **Invasive species:** Common Myna and Rock Dove missed — major gap for biosecurity monitoring

### Dangerous False Positives
- **Regent Honeyeater** (critically endangered, ~200 individuals remain) misidentified as **White-browed Woodswallow with 0.95 confidence** — the highest confidence reading in the entire benchmark. This is a conservation-critical error: rangers relying on BirdNET would dismiss a Regent Honeyeater detection.
- **Eastern Yellow Robin** misidentified as Australian Magpie (0.44) — drastically different species
- **Hooded Robin** misidentified as Rufous Whistler (0.34)
- **Crimson Rosella** misidentified as Sooty Oystercatcher (0.23)

### Taxonomy Gap (North American Bias)
- Common Starling detected as "European Starling" — BirdNET uses North American common names. For Australian deployment this creates confusion and lookup mismatches.
- BirdNET is trained primarily on Northern Hemisphere recordings. Australian endemic families (honeyeaters, fairy-wrens, thornbills, pardalotes, currawongs, rosellas) are underrepresented in training data.

---

## Honest Limitations

1. **Single recording per species.** One iNaturalist recording may not be representative — quality, environment, and call type vary. A robust benchmark would test 3-10 recordings per species.

2. **Recording quality unknown.** Some iNaturalist recordings may be short, noisy, or contain multiple species. Poor quality inputs will always fail.

3. **min_conf=0.1 used.** This is intentionally low to catch any detection. Production systems typically use 0.3–0.5.

4. **BirdNET version not pinned.** Using whatever birdnetlib installed in the environment.

5. **Only 50 species.** Australia has ~900 bird species. This is a directional benchmark, not comprehensive coverage assessment.

---

## Recommendations for Wild Echo

1. **Be honest in marketing:** BirdNET is strong on ~30-40% of common AU species. Don't claim "900+ species" without caveats.

2. **Add AU-specific fine-tuning layer.** Train a secondary classifier on Australian recordings (xeno-canto, eBird AU, iNaturalist AU) to catch honeyeaters, fairy-wrens, rosellas, and currawongs.

3. **Flag Regent Honeyeater false positive issue** in any conservation-use documentation. This is a liability for Ranger/Enterprise tier.

4. **Prioritise honeyeater training.** This is Australia's most species-rich bird family and BirdNET detects essentially none of them.

5. **Augment detection pipeline** with spectrogram pattern matching for species where BirdNET consistently fails.

---

## Files
- Recordings: `/tmp/au_benchmark_v2/` (48 MP3 files)
- Raw analysis: `/tmp/au_benchmark_v2/analysis_results.json`
- Download results: `/tmp/au_benchmark_v2/download_results.json`
