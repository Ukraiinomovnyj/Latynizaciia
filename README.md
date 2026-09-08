# Ukrainian Latynytsia — A Phonemic Latin Orthography for the Ukrainian Language

[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.19544126.svg)](https://doi.org/10.5281/zenodo.19544126)
[![License: CC BY 4.0](https://img.shields.io/badge/License-CC%20BY%204.0-blue.svg)](https://creativecommons.org/licenses/by/4.0/)

**Ukrainian Latynytsia** (Ukrainian: *латинка* / *латиниця*) is a complete Latin
alphabet for writing the Ukrainian language. Unlike passport transliteration or
ISO romanization, it is designed as a full orthographic system built on one
principle: **one phoneme, one letter.**

The system is a structural mirror of the Ukrainian Cyrillic alphabet — every
function of Cyrillic has an exact Latin counterpart, so conversion in either
direction is lossless and predictable. It uses **32 active letters, two rules,
zero digraphs** for native phonemes, and a single dead key (the trema) for
everyday typing.

## Overview

This white paper presents a phonemic Latin script for the Ukrainian language,
designed as a structural mirror of the Cyrillic alphabet. The system maps each
Ukrainian phoneme to exactly one Latin letter or diacritical variant, achieving
zero digraphs for native phonemes. Two mechanisms handle palatalization and
iotation: the trema (¨) on vowels and the apostrophe (') after consonants. The
haček (ˇ) marks three sibilant phonemes (č, š, ž) that represent independent
sounds rather than palatalized variants. The script uses 32 active letters with
2 reserved (Q, W) for future use. The affricate cluster šč represents щ [ʂtʂ],
following the same logic as dž = дж and dz = дз. This is a technical proposal,
not a political manifesto — it offers a ready-made orthographic tool should the
need arise.

## Key design decisions

- **One phoneme, one letter.** No digraphs for native Ukrainian phonemes.
  Palatalization, iotation and the sibilants are handled by three diacritic
  mechanisms rather than letter combinations.
- **Structural symmetry with Cyrillic.** я / ю / є / ьо → ä / ü / ë / ö,
  ь → apostrophe, ї → ï. A speaker's intuition carries over directly, and
  automatic Cyrillic-to-Latin conversion stays reversible.
- **Minimal diacritics.** Only two: the trema (¨) and the haček (ˇ). Every trema
  letter (ä, ö, ü, ë, ï) already exists on German, French and Nordic layouts.
- **Reassigned letters.** X = х [x], H = г [ɦ], G = ґ [g], following Czech and
  broad international transcription practice.
- **щ as a cluster.** Ukrainian щ [ʂtʂ] is treated as two phonemes (ш + ч) and
  written šč, which distinguishes Ukrainian from Russian щ [ɕː].

## Contents

- **[`ukrainian-latynytsia-v4.md`](ukrainian-latynytsia-v4.md)** — the full white
  paper, in Ukrainian: motivation and historical context, a review of existing
  romanization and transliteration systems, the design principles, the complete
  32-letter alphabet with IPA values, verification tables, literary samples, and
  a comparison with the Polish and Czech models.
- **Read online:** <https://ukraiinomovnyj.github.io/Latynizaciia/> — the same
  document with an added English overview.

## Citing

Archived releases are on Zenodo. Please cite the concept DOI, which always
resolves to the latest version:

> Ukraiinomovnyj. *Ukrainian Latynytsia: A Phonemic Latin Orthography for the
> Ukrainian Language* (v4.0). Zenodo. <https://doi.org/10.5281/zenodo.19544126>

The DOI for the v4.0.0 release specifically is
[10.5281/zenodo.22665403](https://doi.org/10.5281/zenodo.22665403). Machine-readable
citation metadata is in [`CITATION.cff`](CITATION.cff).

## License

© 2025 Ukraiinomovnyj. Released under the
[Creative Commons Attribution 4.0 International License](https://creativecommons.org/licenses/by/4.0/)
(CC BY 4.0): share and adapt for any purpose, including commercially, with
appropriate credit.
