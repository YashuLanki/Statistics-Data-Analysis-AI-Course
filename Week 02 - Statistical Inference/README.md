# Estimating Population Parameters with Confidence Intervals: Bank Marketing Data

AIT 530 assignment — statistical inference: point estimates, 95% confidence intervals, and how sample size and variability affect estimates of a population mean and proportion.

Treats the 45,211 clients in the [UCI Bank Marketing dataset](https://doi.org/10.24432/C5K306) as the population, so every estimate can be checked against the true value. One random sample of 500 clients estimates the mean age at 41.1 years (95% CI 40.2–42.0, true 40.9) and the share who subscribe to a term deposit at 13.2% (95% CI 10.2–16.2%, true 11.7%). Repeating the sampling 1,000 times at sizes from 30 to 5,000 shows interval widths shrinking with 1/√n. The *t*-interval for the mean stays near 95% coverage at every size, while the Wald interval for the rare "subscribed" outcome drops to about 87% at n = 30 (the Wilson interval does better). The report ends with inferences, assumptions, limitations, and why sample size and variability matter for training and evaluating AI models.

- [`Bank_Marketing_Statistical_Inference.ipynb`](./Bank_Marketing_Statistical_Inference.ipynb) — the full notebook: dataset selection, point estimates, confidence intervals, sample-size simulations, inferences and assumptions, summary, and references.
- [`bank_data/`](./bank_data) — the UCI Bank Marketing dataset (`bank-full.csv` and its `bank-names.txt` description).
- `Assignment.docx` — original assignment instructions (not tracked in git).
- `script.md` — narration script for the video presentation (not tracked in git).
