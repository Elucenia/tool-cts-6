<!-- ELUCENIA technical documentation · cts-6 · en · no clinical/professional/rights approval -->

# CTS-6 (carpal tunnel syndrome)

[conditions, sources and permissions](https://elucenia.org/en/tools/cts-6)

## How to use

Use the tool in the portal or open index.html through a local HTTP server. Select the language, complete the fields and calculate.

## Inputs and units

### Numbness predominantly or exclusively in the median nerve distribution

`dorm`

### Nocturnal numbness

`noturna`

### Thenar muscle atrophy and/or weakness

`atrofia`

### Positive Phalen test

`phalen`

### Loss of two-point discrimination (\> 6 mm)

`dpp`

### Positive Tinel sign over the carpal tunnel

`tinel`

## Method edition

CTS-6/Graham 2006: 6 weighted carpal tunnel criteria; clinical examination

## Documented formula

Sum present items: median-nerve-distribution numbness 3.5; nocturnal numbness 4; thenar atrophy/weakness 5; positive Phalen 5; loss of two-point discrimination 4.5; positive Tinel 4. Total 0–26.

## Limits and population

Graham’s 2006 development used expert consensus and case histories combining clinical criteria; validation described in the abstract compared model probabilities with judgments from another panel. That design does not by itself establish performance against electrophysiological testing in every clinical population. The six-item score, its cutoff and age range must be checked in the full method.

## References

- [Graham B et al. Development and validation of diagnostic criteria for carpal tunnel syndrome. J Hand Surg Am, 2006.](https://doi.org/10.1016/j.jhsa.2006.03.005)

- [Graham B. The value added by electrodiagnostic testing in the diagnosis of carpal tunnel syndrome. J Bone Joint Surg Am, 2008.](https://doi.org/10.2106/JBJS.G.01362)

## Reproduce the technical tests

Run node test.cjs in the root directory of this repository to repeat the recorded synthetic cases. Original inputs, expectations and tolerances are preserved. Technical tests do not constitute clinical validation.

```sh
node test.cjs
```

tool.json contains sources, edition and review scope. examples.json retains synthetic inputs and expectations; results.json records the obtained results.

[Record and references](../tool.json) · [JavaScript code](../calculator.js) · [Reference cases](../examples.json) · [results.json](../results.json)

## Review and conditions of use

Independent clinical review has not been performed.

This interface is an authorial translation, not an official or certified edition. Independent clinical review, professional language review and instrument rights clearance have not been performed.

Formula or classification result. Interpretation, care and applicability depend on professional assessment and the selected source.

## License and attribution

Apache-2.0 applies only to ELUCENIA code. Rights to instruments, publications, translations and data remain with their respective holders. Preserve LICENSE and NOTICE.

ELUCENIA · Felipe Guedes · Copyright © 2026

## Documented results

The information below preserves the method outputs for synthetic examples. It does not constitute independent clinical validation.

### 1

Low probability of carpal tunnel syndrome (below about 25%)

Consider alternative diagnoses (cervical radiculopathy, polyneuropathy).


### 2

Intermediate probability (between about 25% and 80%)

Electroneuromyography has more value in this range.


### 3

Intermediate probability (between about 25% and 80%)

Electroneuromyography has more value in this range.


### 4

High probability of carpal tunnel syndrome (about 80% or more)

In this range, electroneuromyography rarely changes the clinical diagnosis.

