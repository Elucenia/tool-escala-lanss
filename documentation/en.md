<!-- ELUCENIA technical documentation · escala-lanss · en · no clinical/professional/rights approval -->

# LANSS pain scale

[conditions, sources and permissions](https://elucenia.org/en/tools/escala-lanss)

## How to use

Use the tool in the portal or open index.html through a local HTTP server. Select the language, complete the fields and calculate.

## Inputs and units

### Does the pain feel like a strange, unpleasant sensation in the skin (pricking, tingling or electric shocks)?

`a1`

### Does the pain make the skin in the painful area look different from normal (blotchy, red or pink)?

`a2`

### Does the pain make the skin abnormally sensitive to touch (discomfort with light brushing or tight clothing)?

`a3`

### Does the pain occur suddenly in attacks without an apparent reason while at rest (electric shocks or stabbing pain)?

`a4`

### Does the pain make it feel as though the skin temperature has changed (heat or burning)?

`a5`

### Examination: allodynia (pain or discomfort when brushing cotton over the painful area compared with a normal area)

`b6`

### Examination: altered pinprick threshold (a prick with a 23G needle feels different in the painful area: more or less intense)

`b7`

## Method edition

LANSS/Bennett 2001: 5 symptoms+2 signs, total 0–24, cutoff ≥12; Brazilian Portuguese Schestatsky 2011

## Documented formula

Part A (questionnaire): items worth 5, 5, 3, 2 and 1 point. Part B (sensory examination): allodynia 5 points; altered pinprick threshold 3 points. Total 0 to 24; cutoff ≥12.

## Limits and population

LANSS combines symptoms with signs obtained through sensory examination to investigate a predominantly neuropathic mechanism in chronic pain. Examination items must not be treated as simple self-report. The cited Brazilian validation does not certify the implementation or new translations.

## References

- [Bennett M. The LANSS Pain Scale: the Leeds assessment of neuropathic symptoms and signs. Pain, 2001.](https://doi.org/10.1016/S0304-3959(00)00482-6)

- [Schestatsky P et al. Brazilian Portuguese validation of the Leeds Assessment of Neuropathic Symptoms and Signs for patients with chronic pain. Pain Med, 2011.](https://doi.org/10.1111/j.1526-4637.2011.01221.x)

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
