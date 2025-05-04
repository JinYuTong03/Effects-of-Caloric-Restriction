# Effects of Caloric Restriction on Sleep Quality Across Gender in Adults

## Study Overview

This repository contains the analysis code and results for our research on the effects of a 25% caloric restriction (CR) intervention on sleep quality over a two-year period. The study uses data from the CALERIE™ Phase 2 randomized controlled trial to examine how caloric restriction impacts sleep quality and whether these effects differ by gender.

## Research Questions

Our study investigated three key research questions:

1. Does caloric restriction (CR) have a significant effect on sleep quality over a two-year period?
2. Does gender modify the effect of CR on sleep quality?
3. Does weight change mediate the relationship between CR and sleep quality?

## Dataset

The analysis used publicly available CALERIE™ Phase 2 data, which included:
- 220 healthy volunteers randomized in a 2:1 ratio (CR vs. ad libitum diet)
- Sleep quality measured via Pittsburgh Sleep Quality Index (PSQI)
- Data collected at baseline, 12 months, and 24 months
- Key demographic variables including gender, age, and BMI

## Key Findings

1. **Main Effect of CR on Sleep Quality**: We found no statistically significant direct effect of CR on sleep quality over the two-year intervention period (p=0.084).

2. **Gender as a Modifier**: Gender did not significantly modify the relationship between CR and sleep quality over time.

3. **Weight Change as a Mediator**: 
   - Weight change significantly mediated the relationship between CR and sleep quality overall (Sobel test: Z = -2.13, p = 0.033)
   - Gender-stratified analysis revealed notable differences:
     - In females: significant mediation effect (Z = -2.28, p = 0.023)
     - In males: no significant mediation effect (Z = -0.376, p = 0.707)

## Significance

Our findings suggest that CR improves sleep quality primarily through weight reduction, especially in women. The negative association between weight loss and PSQI scores indicates that as body weight decreases, sleep quality improves. However, this mediation effect was not observed in men, implying that other mechanisms may influence the relationship between CR and sleep quality in males.

## Repository Contents

- `rcode.Rmd`: R code used for statistical analysis
- `Result.html`: Rcode with figures and tables in HTML format
- `Final Report.pdf`: Full research paper

## Methods

We employed several statistical approaches to address our research questions:

1. **Generalized Estimating Equations (GEE)**: Used to evaluate the main effect of CR on sleep quality over time and assess gender as a potential modifier
2. **Traditional Mediation Analysis**: Applied to evaluate the indirect effects of CR on sleep quality via weight change
3. **Sobel Test**: Used to test the statistical significance of the indirect path

## Authors

- Ruyue Wang
- Yutong Jin

## Acknowledgments

We acknowledge the CALERIE™ research team for providing the publicly available data used in this analysis.
