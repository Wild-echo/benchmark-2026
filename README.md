# Wild Echo Benchmark Report — May 2026

**BirdNET Australian Species Detection: Field Evaluation**
Published: May 27, 2026 | Version: 2.1

## Overview

This repository contains the full benchmark report and frozen datasets from Wild Echo's evaluation of BirdNET acoustic AI model performance on Australian bird species in real-world field conditions.

## Key Findings

- BirdNET detected 42/104 tested Australian species (40.4% coverage)
- Precision varies significantly by species group
- Threatened species detection rates documented
- Model improvement trajectory charted across versions

## Contents

```
benchmark-report-v2.1.pdf                        ← Full report (start here)
benchmark-report.md                               ← Source markdown
datasets/
  birdnet-au-benchmark-2026-05-14.md             ← Primary dataset
  birdnet-au-benchmark-batch2-2026-05-14.md      ← Batch 2 dataset
  birdnet-au-benchmark-v2-2026-05-14.md          ← v2 analysis
charts/
  chart1_precision_coverage.png
  chart2_species_coverage.png
  chart3_model_improvement.png
  chart4_threatened_species.png
CHECKSUMS.md                                      ← SHA256 integrity hashes
```

## Methodology

Tests conducted using Wild Echo Sentinel hardware in Australian field conditions. Audio recordings processed through BirdNET v2.4. Species list drawn from eBird AU checklist. Full methodology detailed in the PDF report.

## Dataset Integrity

Datasets frozen 2026-05-26. SHA256 checksums in `CHECKSUMS.md`. This repository preserves v2.1 as the immutable baseline. Future versions will be tagged (v2.2+).

## About Wild Echo

Wild Echo is an AI-powered passive acoustic monitoring platform for biodiversity, biosecurity, and hive health detection.

- Website: https://wildecho.app
- Contact: info@wildecho.app
