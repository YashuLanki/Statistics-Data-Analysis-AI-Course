# Probability Distributions and the Central Limit Theorem with Bike Sharing Data

AIT 530 assignment — descriptive statistics, probability distributions, probability calculations, and the central limit theorem applied to Capital Bikeshare rental and weather data.

Uses the [UCI Bike Sharing Dataset](https://doi.org/10.24432/C5W894) (731 days, 2011–2012, Washington, D.C.) to summarize and visualize the data, classify each variable as discrete or continuous with a matching distribution, and interpret a normal curve fitted to daily humidity (μ ≈ 62.8%, σ ≈ 14.2%). A binomial model gives a 26.5% chance that exactly 7 of 10 random days are working days. A Poisson model of 4 AM rentals (λ ≈ 6.35) gives 15.0% for exactly 5 rentals, and the comparison shows the real counts are overdispersed. 68.13% of days fall within one standard deviation of mean humidity, compared with 68.27% in theory. A central limit theorem simulation on right-skewed casual-rider counts shows the sample means (n = 40) forming a normal curve with standard error σ/√n, and 95% confidence intervals capture the true mean 95% of the time.

- [`Bike_Sharing_Probability_Distributions.ipynb`](./Bike_Sharing_Probability_Distributions.ipynb) — the full notebook: dataset selection, descriptive statistics and graphs, random variables and distributions, normal curve interpretation, binomial/Poisson/normal probability calculations, the central limit theorem, summary, and references.
- [`bike_data/`](./bike_data) — the UCI Bike Sharing Dataset (`day.csv`, `hour.csv`, and its `Readme.txt`).
- `Assignment.docx` — original assignment instructions (not tracked in git).
- `script.md` — narration script for the video presentation (not tracked in git).
