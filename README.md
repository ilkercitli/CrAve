# CrAve
**CR · AVE · α — Validity reporting for behavioral researchers**

CrAve is a free, browser-based tool that generates publication-ready validity and reliability tables for confirmatory factor analysis (CFA). No installation. No login. No data leaves your browser.

---

## What it does

CrAve computes and reports the indices that JASP, AMOS, and jamovi do not automatically provide in APA format:

- **Cronbach's α** — at construct and dimension level
- **Composite Reliability (CR)** — computed from standardized factor loadings
- **Average Variance Extracted (AVE)** — convergent validity
- **Fornell-Larcker criterion** — discriminant validity
- **HTMT** — heterotrait-monotrait ratio of correlations (approximation)
- **APA-formatted tables** — paste directly into Word
- **Methods section text** — auto-generated, ready for your manuscript

---

## Who is it for

Researchers in organizational behavior, management, psychology, and related fields who use structural equation modeling (SEM) or CFA and need to report measurement model validity in their manuscripts.

---

## How to use

1. Open the tool in your browser
2. Enter your constructs, dimensions, and items
3. Enter standardized factor loadings (λ) from your AMOS / LISREL / jamovi output
4. Enter Cronbach's α values from your reliability analysis
5. Enter inter-construct correlations (for Fornell-Larcker and HTMT)
6. Click **Generate tables and report**
7. Copy tables directly into Word — copy report text into your manuscript

---

## Live tool

[https://ilkercitli.github.io/CrAve](https://ilkercitli.github.io/CrAve)

---

## Thresholds used

| Index | Threshold | Reference |
|---|---|---|
| Cronbach's α | ≥ .70 | Nunnally (1978) |
| AVE | ≥ .50 | Fornell & Larcker (1981) |
| CR | ≥ .70 | Hair et al. (2019) |
| HTMT | < .85 (strict) / < .90 | Henseler et al. (2015) |
| Fornell-Larcker | √AVE > all correlations | Fornell & Larcker (1981) |

---

## References

Fornell, C., & Larcker, D. F. (1981). Evaluating structural equation models with unobservable variables and measurement error. *Journal of Marketing Research, 18*(1), 39–50.

Hair, J. F., Risher, J. J., Sarstedt, M., & Ringle, C. M. (2019). When to use and how to report results of PLS-SEM. *European Business Review, 31*(1), 2–24.

Henseler, J., Ringle, C. M., & Sarstedt, M. (2015). A new criterion for assessing discriminant validity in variance-based structural equation modeling. *Journal of the Academy of Marketing Science, 43*(1), 115–135.

Nunnally, J. C. (1978). *Psychometric theory* (2nd ed.). McGraw-Hill.

---

## Note on HTMT

HTMT values in CrAve are approximated as r / √(AVE₁ × AVE₂). This is a conservative estimate. For exact HTMT, compute from the full item-level correlation matrix in R or jamovi.

---

## Citation

If you use CrAve in your research, please cite it as:

> Çitli, İ. İ. (2025). *CrAve: A browser-based tool for CFA validity reporting* [Web application]. https://ilkercitli.github.io/CrAve

---

## License

© İhsan İlker Çitli. All rights reserved. This tool may be used freely for academic and research purposes. Modification and redistribution are not permitted without written permission.
