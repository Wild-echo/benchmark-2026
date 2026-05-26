# Wild Echo BirdNET AU Accuracy Benchmark — BATCH 2
**Date:** 2026-05-14  
**Species tested:** 60 (56 with audio available)  
**Scoring:** ✅ PASS ≥0.3 | ⚠️ WEAK 0.1–0.3 | ❌ FAIL <0.1 | 🚫 NO AUDIO

---

## Overall Results

| Metric | Count | % of tested |
|--------|-------|-------------|
| ✅ PASS (conf ≥ 0.3) | 19 | 33.9% |
| ⚠️ WEAK (conf 0.1–0.3) | 5 | 8.9% |
| ❌ FAIL (not detected) | 32 | 57.1% |
| 🚫 NO AUDIO (iNat miss) | 4 | — |
| **Total species** | **60** | |
| **Total tested** | **56** | |
| **Pass rate** | **33.9%** | |
| **Detect rate (PASS+WEAK)** | **24 / 56** | **42.9%** |

---

## Category Breakdown

| Category | Tested | PASS | WEAK | FAIL | Pass Rate |
|----------|--------|------|------|------|-----------|
| Waterbirds | 7 | 1 | 0 | 6 | 14.3% |
| Raptors | 7 | 5 | 0 | 2 | 71.4% |
| Seabirds/Coastal | 4 | 0 | 2 | 2 | 0% (detect: 50%) |
| Parrots | 7 | 1 | 1 | 5 | 14.3% |
| Honeyeaters | 5 | 2 | 0 | 3 | 40.0% |
| Finches | 3 | 1 | 0 | 2 | 33.3% |
| Cuckoos | 3 | 2 | 0 | 1 | 66.7% |
| Pigeons/Doves | 4 | 2 | 0 | 2 | 50.0% |
| Rails/Swamphen | 2 | 1 | 0 | 1 | 50.0% |
| Shorebirds | 2 | 0 | 0 | 2 | 0.0% |
| Nightjars | 1 | 1 | 0 | 0 | 100% |
| Passerines | 10 | 3 | 2 | 5 | 30.0% |

---

## Full Results Table

### Waterbirds

| # | Common Name | Scientific Name | Score | Conf | Notes |
|---|-------------|-----------------|-------|------|-------|
| 1 | White-faced Heron | Egretta novaehollandiae | ❌ FAIL | 0.000 | Top: Musk Duck 0.346 |
| 2 | Pacific Heron | Ardea pacifica | ❌ FAIL | 0.000 | No detections |
| 3 | Australian White Ibis | Threskiornis molucca | ❌ FAIL | 0.000 | No detections |
| 4 | Straw-necked Ibis | Threskiornis spinicollis | 🚫 NO AUDIO | — | iNat: no research-grade sounds |
| 5 | Royal Spoonbill | Platalea regia | ❌ FAIL | 0.000 | Top: Barn Owl 0.666 |
| 6 | Little Black Cormorant | Phalacrocorax sulcirostris | ❌ FAIL | 0.000 | No detections |
| 7 | Little Pied Cormorant | Microcarbo melanoleucos | ✅ PASS | 0.335 | ⚠️ Top detection was Little Corella — genus/word false match |
| 8 | Australian Pelican | Pelecanus conspicillatus | ❌ FAIL | 0.000 | Top: Black Swan 0.545 |

### Raptors

| # | Common Name | Scientific Name | Score | Conf | Notes |
|---|-------------|-----------------|-------|------|-------|
| 9 | Wedge-tailed Eagle | Aquila audax | ❌ FAIL | 0.000 | No detections |
| 10 | Brown Goshawk | Accipiter fasciatus | ✅ PASS | 0.864 | ✅ Correct species confirmed in detections (0.848) |
| 11 | Swamp Harrier | Circus approximans | ❌ FAIL | 0.000 | No detections |
| 12 | Australian Kestrel | Falco cenchroides | ✅ PASS | 0.309 | ⚠️ Detected via genus match (Falco) — BirdNET returned Peregrine Falcon |
| 13 | Australian Hobby | Falco longipennis | ✅ PASS | 0.993 | ⚠️ Top: Australian Magpie — scored via "australian" word match (false positive) |
| 14 | Black-shouldered Kite | Elanus axillaris | ❌ FAIL | 0.000 | No detections |
| 15 | White-bellied Sea Eagle | Haliaeetus leucogaster | ✅ PASS | 0.999 | ✅ Perfect match, consistent across all 22 chunks |

### Seabirds & Coastal

| # | Common Name | Scientific Name | Score | Conf | Notes |
|---|-------------|-----------------|-------|------|-------|
| 16 | Little Tern | Sternula albifrons | ❌ FAIL | 0.000 | Top: Zebra Finch 0.118 |
| 17 | Lesser Crested Tern | Thalasseus bengalensis | 🚫 NO AUDIO | — | iNat: no research-grade sounds |
| 18 | Silver Gull | Larus novaehollandiae | ⚠️ WEAK | 0.189 | ✅ Correct: Chroicocephalus novaehollandiae (renamed genus) |
| 19 | Pied Oystercatcher | Haematopus longirostris | ⚠️ WEAK | 0.134 | ✅ Correct species detected |
| 20 | Masked Lapwing | Vanellus miles | ❌ FAIL | 0.000 | No detections |

### Parrots

| # | Common Name | Scientific Name | Score | Conf | Notes |
|---|-------------|-----------------|-------|------|-------|
| 21 | Australian King-Parrot | Alisterus scapularis | ❌ FAIL | 0.000 | No detections |
| 22 | Superb Parrot | Polytelis swainsonii | ❌ FAIL | 0.000 | No detections |
| 23 | Musk Lorikeet | Glossopsitta concinna | ❌ FAIL | 0.000 | No detections |
| 24 | Pink Cockatoo (Major Mitchell's) | Cacatua leadbeateri | ❌ FAIL | 0.000 | No detections |
| 25 | Red-tailed Black Cockatoo | Calyptorhynchus banksii | ✅ PASS | 0.999 | ✅ Perfect — all 7 chunks matched |
| 26 | Yellow-tailed Black Cockatoo | Calyptorhynchus funereus | ❌ FAIL | 0.000 | No detections |
| 27 | Little Lorikeet | Glossopsitta pusilla | ❌ FAIL | 0.000 | Top: Australian Magpie 0.116 |
| 28 | Australian Ringneck | Barnardius zonarius | ⚠️ WEAK | 0.113 | ✅ Ringneck detected at 0.113; also Raven 0.167, Sparrowhawk 0.158 |

### Honeyeaters

| # | Common Name | Scientific Name | Score | Conf | Notes |
|---|-------------|-----------------|-------|------|-------|
| 29 | Brown Honeyeater | Lichmera indistincta | ✅ PASS | 0.986 | ✅ Perfect — 10 detections, all consistent |
| 30 | White-naped Honeyeater | Melithreptus lunatus | ❌ FAIL | 0.000 | Top: Common Bronzewing 0.194 |
| 31 | White-eared Honeyeater | Nesoptilotis leucotis | ❌ FAIL | 0.000 | No detections |
| 32 | White-plumed Honeyeater | Ptilotula penicillata | ✅ PASS | 0.390 | ✅ Correct species |
| 33 | Macleay's Honeyeater | Xanthotis macleayanus | ❌ FAIL | 0.000 | No detections |

### Finches & Munias

| # | Common Name | Scientific Name | Score | Conf | Notes |
|---|-------------|-----------------|-------|------|-------|
| 34 | Chestnut-breasted Munia | Lonchura castaneothorax | ❌ FAIL | 0.000 | Top: Golden-headed Cisticola 0.996 (wrong) |
| 35 | Zebra Finch | Taeniopygia guttata | ✅ PASS | 0.894 | ✅ Perfect match |
| 36 | Red-browed Finch | Neochmia temporalis | ❌ FAIL | 0.000 | No detections |
| 37 | Black-throated Finch | Poephila cincta | 🚫 NO AUDIO | — | iNat: no research-grade sounds |

### Cuckoos

| # | Common Name | Scientific Name | Score | Conf | Notes |
|---|-------------|-----------------|-------|------|-------|
| 38 | Shining Bronze-Cuckoo | Chrysococcyx lucidus | ❌ FAIL | 0.000 | No detections |
| 39 | Horsfield's Bronze-Cuckoo | Chrysococcyx basalis | ✅ PASS | 0.994 | ✅ Perfect — 4 consistent chunks |
| 40 | Fan-tailed Cuckoo | Cacomantis flabelliformis | ✅ PASS | 0.979 | ✅ Correct species |

### Pigeons & Doves

| # | Common Name | Scientific Name | Score | Conf | Notes |
|---|-------------|-----------------|-------|------|-------|
| 41 | Common Bronzewing | Phaps chalcoptera | ✅ PASS | 0.965 | ✅ Perfect — 7 chunks, highly consistent |
| 42 | Diamond Dove | Geopelia cuneata | ❌ FAIL | 0.000 | No detections |
| 43 | Peaceful Dove | Geopelia striata | ❌ FAIL | 0.000 | No detections |
| 44 | Crested Pigeon | Ocyphaps lophotes | ✅ PASS | 0.965 | ✅ Perfect — 6 chunks confirmed |

### Rails & Swamphen

| # | Common Name | Scientific Name | Score | Conf | Notes |
|---|-------------|-----------------|-------|------|-------|
| 45 | Buff-banded Rail | Gallirallus philippensis | ✅ PASS | 0.550 | ✅ Correct species, multiple chunks |
| 46 | Australasian Swamphen | Porphyrio melanotus | ❌ FAIL | 0.000 | Top: White-browed Woodswallow 0.381 |
| 47 | Black-tailed Nativehen | Tribonyx ventralis | 🚫 NO AUDIO | — | iNat: no research-grade sounds |

### Shorebirds

| # | Common Name | Scientific Name | Score | Conf | Notes |
|---|-------------|-----------------|-------|------|-------|
| 48 | Black-fronted Dotterel | Charadrius melanops | ❌ FAIL | 0.000 | No detections |
| 49 | Bar-tailed Godwit | Limosa lapponica | ❌ FAIL | 0.000 | No detections |

### Nightjars

| # | Common Name | Scientific Name | Score | Conf | Notes |
|---|-------------|-----------------|-------|------|-------|
| 50 | Spotted Nightjar | Eurostopodus argus | ✅ PASS | 0.610 | ✅ Correct species |

### Passerines

| # | Common Name | Scientific Name | Score | Conf | Notes |
|---|-------------|-----------------|-------|------|-------|
| 51 | Grey-crowned Babbler | Pomatostomus temporalis | ⚠️ WEAK | 0.103 | ✅ Correct (BirdNET uses "Gray" spelling) |
| 52 | Brown Treecreeper | Climacteris picumnus | ✅ PASS | 0.758 | ✅ Correct species |
| 53 | Varied Sittella | Daphoenositta chrysoptera | ❌ FAIL | 0.000 | No detections |
| 54 | Black-faced Monarch | Monarcha melanopsis | ❌ FAIL | 0.000 | No detections |
| 55 | Restless Flycatcher | Myiagra inquieta | ⚠️ WEAK | 0.152 | ✅ Correct species at 0.152; top was Australian Raven 0.340 |
| 56 | White-winged Triller | Lalage tricolor | ❌ FAIL | 0.000 | Top: Australian Reed Warbler 0.165 |
| 57 | Black-faced Cuckooshrike | Coracina novaehollandiae | ✅ PASS | 0.993 | ✅ Perfect match |
| 58 | Grey Fantail | Rhipidura albiscapa | ✅ PASS | 0.746 | ✅ Correct (BirdNET uses "Gray" spelling) |
| 59 | Rufous Fantail | Rhipidura rufifrons | ❌ FAIL | 0.000 | No detections |
| 60 | Golden-headed Cisticola | Cisticola exilis | ✅ PASS | 0.968 | ✅ Correct species, consistent |

---

## Scoring Notes & Caveats

### Potential False Positives (3 cases)
BirdNET's species list doesn't perfectly align with all Australian taxa, creating some false matches:

1. **Little Pied Cormorant (#7)** — Scored PASS via word "little" matching "Little Corella". The cormorant itself was NOT in BirdNET's detection output. True result: likely FAIL.
2. **Australian Kestrel (#12)** — Scored via genus match ("falco" in "Falco peregrinus"). BirdNET detected Peregrine Falcon, not Kestrel. May indicate BirdNET doesn't model cenchroides separately.
3. **Australian Hobby (#13)** — Scored PASS via "australian" matching "Australian Magpie". True result: FAIL — Magpie was completely unrelated top hit.

**Corrected pass rate (removing false positives): 16–17 / 56 = 28.6–30.4%**

### Taxonomy Mismatches (not errors, just naming differences)
- **Silver Gull** — BirdNET uses updated genus *Chroicocephalus* vs old *Larus*. Still correct.
- **Grey Fantail / Grey-crowned Babbler** — BirdNET uses American spelling "Gray". Still correct.

### Strong Performers (conf > 0.9)
- White-bellied Sea Eagle: 0.999 (22 chunks — outstanding)
- Red-tailed Black Cockatoo: 0.999 (7 chunks)
- Australian Hobby*: 0.993 (false positive)
- Black-faced Cuckooshrike: 0.993
- Horsfield's Bronze-Cuckoo: 0.994
- Brown Honeyeater: 0.986 (10 chunks)
- Fan-tailed Cuckoo: 0.979
- Golden-headed Cisticola: 0.968
- Common Bronzewing: 0.965
- Crested Pigeon: 0.965

### Consistent Failures (no detections at all)
Many species returned zero detections, suggesting BirdNET may not model them or the audio quality/duration was insufficient:
- Pacific Heron, Australian White Ibis, Swamp Harrier, Black-shouldered Kite
- Australian King-Parrot, Superb Parrot, Musk Lorikeet, Pink Cockatoo, Yellow-tailed Black Cockatoo, Little Lorikeet
- Macleay's Honeyeater, Red-browed Finch, Shining Bronze-Cuckoo
- Diamond Dove, Peaceful Dove, Varied Sittella, Black-faced Monarch, Rufous Fantail

---

## Implications for Wild Echo

### What BirdNET does well (Batch 2 species)
- Iconic/distinctive callers: sea eagles, large cockatoos, cuckoos, pigeons with unique calls
- Sonically distinct species: bronze-cuckoos, bronzewings, cisticolas, cuckooshrikes

### Where BirdNET struggles (Batch 2 species)
- **Waterbirds/waders** — herons, ibis, pelican, cormorants all failed. These are quiet or infrequent callers.
- **Parrots (many)** — only 2/8 pass. Lorikeets, king-parrots, cockatoos with complex/variable calls not modelled well.
- **Shorebirds** — 0% pass rate. Calls are often outside BirdNET's training data focus.
- **Quiet passerines** — monarch, sittella, triller all failed.

### Recommendation
For Wild Echo deployment, BirdNET confidence thresholds should be calibrated per category:
- High-confidence species (eagles, large cockatoos, cuckoos): threshold 0.7+ is appropriate
- Medium-confidence: honeyeaters, passerines: 0.3–0.5 threshold
- Consider supplementing BirdNET with secondary models or call libraries for waterbirds and parrots

---

## Combined Benchmark Summary (Batch 1 + Batch 2)

*Note: Combined results pending Batch 1 final report. Batch 2 alone shows 33.9% pass rate.*

| Batch | Species | Tested | PASS | WEAK | Pass Rate |
|-------|---------|--------|------|------|-----------|
| Batch 2 (this) | 60 | 56 | 19 | 5 | 33.9% |
| Batch 1 | ~50 | TBD | TBD | TBD | TBD |
| **Combined** | **~110** | **TBD** | **TBD** | **TBD** | **TBD** |

---

*Generated by Wild Echo BirdNET AU Benchmark Subagent — 2026-05-14*  
*Audio source: iNaturalist research-grade observations, Australia (place_id=6744)*  
*BirdNET version: birdnetlib (TensorFlow Lite CPU)*
