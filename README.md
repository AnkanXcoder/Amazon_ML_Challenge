# Amazon ML Challenge
## Business Entity Resolution

A machine learning project for identifying matching business records across three independent and noisy data sources.

## Problem

The same business can appear differently across sources because of:

- Typos and abbreviations
- Different capitalization and punctuation
- Address formatting differences
- Missing address components
- Legal suffix variations
- Alternative business names

The goal is to find **all Source 2 and Source 3 records that match each Source 1 entity**.

```text
Source 1 Record
      ↓
Candidate Generation
      ↓
Possible Matches
      ↓
Similarity Features
      ↓
Matching Model
      ↓
Match / No Match
      ↓
Final Entity Mapping
