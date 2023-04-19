# 📱 The Impact of Virtual Interaction on Well-Being During the COVID-19 Pandemic

## Introduction
> How much did virtual interactions positively impact our well-being as substitutes for face-to-face interaction during the height of the COVID-19 pandemic?

Humans have a fundamental need for social connection. A vast literature strongly implicates face-to-face interaction as the gold standard for socialization. However, the COVID-19 pandemic sharply brought these ubiquitous in-person interactions to an end for several months. How effective, then, were the surrogate forms of virtual interaction which we adopted in the interim in serving the same function? We aimed to answer this question with two preregistered behavioral studies.

All studies used largely identically formatted scripts. Data cleaning and analysis were handled by separate `.Rmd` files for each study as described below.

## File Structure
```
virtual-interaction-well-being/
├─ study1/
│  ├─ prolific/
│  │  ├─ data/
│  │  ├─ figures/
│  │  ├─ scripts/
...
├─ study1_pilot/
│  ├─ princeton/
│  │  ├─ data/
│  │  ├─ figures/
│  │  ├─ scripts/
│  │  ...
│  ├─ uchicago/
│  │  ├─ data/
│  │  ├─ figures/
│  │  ├─ scripts/
...
├─ study2/
│  ├─ personproject/
│  │  ├─ scripts/
│  │  ├─ data/
│  │  ├─ figures/
...
├─ study2_pilot/
│  ├─ data/
│  ├─ figures/
│  ├─ scripts/
├─ virtual-interaction-well-being.Rproj
```

## Study 1

We recruited a sample of *N* = 999 participants through Prolific who 

[`study1-clean_wrangle.Rmd`][1]: R Markdown script for cleaning Study 1 data. <br>
[`study1_analyze.Rmd`][2]: R Markdown script for analyzing and plotting Study 1 data.


## Study 2

[`study2-clean_wrangle.Rmd`][3]: R Markdown script for cleaning Study 2 data. <br>
[`study2-analyze.Rmd`][4]: R Markdown script for analyzing and plotting Study 2 data.

## Supplement

[`study1_pilot_princeton-clean_wrangle.Rmd`][5]: R Markdown script for cleaning Study 1 pilot data (Princeton).<br>
[`study1_pilot_princeton-analyze.Rmd`][6]: R Markdown script for analyzing and plotting Study 1 pilot data (Princeton).

[`study1_pilot_uchicago-clean_wrangle.Rmd`][5]: R Markdown script for cleaning Study 1 pilot data (UChicago).<br>
[`study1_pilot_uchicago-analyze.Rmd`][6]: R Markdown script for analyzing and plotting Study 1 pilot data (UChicago).

[`study2_pilot-clean_wrangle.Rmd`][5]: R Markdown script for cleaning Study 2 pilot data (Person Project).<br>
[`study2_pilot-analyze.Rmd`][6]: R Markdown script for analyzing and plotting Study 2 pilot data (Person Project).

[1]: https://github.com/1nathanliang/virtual_interaction_covid/main/S1_clean-wrangle.Rmd
[2]: https://github.com/1nathanliang/virtual_interaction_covid/main/S1_analyze.Rmd
[3]: https://github.com/1nathanliang/virtual_interaction_covid/main/S2_clean-wrangle.Rmd
[4]: https://github.com/1nathanliang/virtual_interaction_covid/main/S2_analyze.Rmd
[5]: https://github.com/1nathanliang/virtual_interaction_covid/main/S0_clean-wrangle.Rmd
[6]: https://github.com/1nathanliang/virtual_interaction_covid/main/S0_analyze.Rmd
