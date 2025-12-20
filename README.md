# Higher Diploma in Science - Data Analytics
******

## Applied Statistics - Assessment

This repository was created as part of the [Applied Statistics](https://www.atu.ie/courses/higher-diploma-in-science-data-analytics) assessment module for the course in the [Higher Diploma in Data Analytics](https://www.atu.ie/courses/higher-diploma-in-science-data-analytics). This README has been written with [Github's Documentation On READMEs](https://docs.github.com/en/repositories/managing-your-repositorys-settings-and-features/customizing-your-repository/about-readmes) in mind. [[1]](#1) This assesment is using the [assessment instructions](https://github.com/ianmcloughlin/applied-statistics/blob/main/assessment/assessment.md) to demonstrate the skills developed in the course in data analysis and visualization. [[2]](#2) You can find more about [writing in Mark Down in GitHub's documentation](https://docs.github.com/en/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax). [[3]](#3)

![Statistic](images/image_statistic_01.webp)

## About This Assessment

This assessment is designed to evaluate your understanding and practical application of statistical concepts through hands-on simulation and analysis. The problems focus on probability, the behavior of sampling distributions, hypothesis testing, and comparisons of means using t-tests and ANOVA.

## Use of This Assessment

This assesssment is useful for demonstrating some of the skills developed for analysis, programming and data visualization using Jupyter Notebook (Python).

## Assessment Overview

The notebook is divided into **four main problems**, each addressing a key statistical concept:

1. **Extending the Lady Tasting Tea**
2. **Normal Distribution**
3. **t-Tests and Type II Errors**
4. **ANOVA**

All analyses are reproducible and include clear explanations, visualizations, and conclusions.

### Libraries Used

- **NumPy** – numerical computation and simulation.
- **Math** – mathematical functions from the standard library.
- **SciPy** – statistical tests (t-tests, ANOVA).
- **Matplotlib** – data visualization.

### Problem 1: Extending the Lady Tasting Tea

- Extend the classic Lady Tasting Tea experiment.
- Simulate outcomes to estimate probabilities and interpret results in the context of hypothesis testing.
- Understand how experimental design affects the likelihood of observing extreme outcomes by chance.

### Problem 2: Normal Distribution

- Generate large sets of samples from the standard normal distribution.
- Compare sample and population standard deviations.
- Explore how sample size influences the variability and estimation of standard deviation.

### Problem 3: t-Tests

- Simulate independent samples with varying mean differences.
- Conduct t-tests to determine statistical significance.
- Investigate how type II error rates change as the true difference between populations increases.

### Problem 4: ANOVA

- Generate multiple independent samples with different means.
- Perform a one-way ANOVA and pairwise t-tests.
- Understand why ANOVA is preferred when comparing more than two groups to control for error rates.

### Overall Conclusion

This assessment explored fundamental concepts in applied statistics through a series of simulation-based problems implemented in Python. Across all four problems, the focus was on understanding hypothesis testing, probability, sampling variability, error rates, and appropriate methods for comparing group means, supported by both numerical results and visualizations.

**In Problem 1**, the extended Lady Tasting Tea experiment demonstrated how experimental design influences statistical evidence. By increasing the number of cups, the probability of achieving a perfect result by chance decreased substantially, strengthening the evidence against the null hypothesis. This problem highlighted how more stringent designs naturally reduce false positives and improve the interpretability of extreme outcomes without relying solely on stricter significance thresholds.

**In Problem 2**, examined sampling variability by comparing the sample standard deviation (ddof = 1) and population standard deviation (ddof = 0) across many small samples. The simulations showed that the sample standard deviation provides a less biased estimate of the true population variability for small sample sizes. Visualizing the distributions reinforced the importance of bias correction and illustrated how both estimators converge as sample size increases.

**In Problem 3**, simulations were used to investigate Type II errors in independent two-sample t-tests. The results clearly demonstrated the relationship between effect size and statistical power: when the true mean difference was small, the probability of failing to reject a false null hypothesis was high, but this probability decreased steadily as the mean difference increased. This problem emphasized the practical importance of effect size and sample size in experimental design and hypothesis testing.

**In Problem 4**, compared one-way ANOVA with multiple pairwise t-tests for analyzing differences among more than two groups. ANOVA successfully detected overall differences in group means while controlling the Type I error rate. Boxplots provided an intuitive visual confirmation of the underlying differences, and follow-up t-tests identified specific group contrasts. This reinforced why ANOVA is the preferred primary method when comparing multiple group means.

Overall, these problems collectively demonstrate how simulation, visualization, and formal statistical testing work together to support sound statistical reasoning. The assessment highlights best practices in experimental design, hypothesis testing, and interpretation of results, illustrating how thoughtful application of statistical methods leads to more reliable and meaningful conclusions in data analysis.

## How to Use This Repository

**1. Clone or download the repository:**
   ```
   git clone <https://github.com/RodrigoDMU/applied_statistics_assessment>

   cd applied_statistics_assessment
    ```

**2. Install required libraries:**
   ```
    pip install numpy scipy matplotlib
    ```
**3. Open the Jupyter Notebook**

Then open the [problems.ipynb](https://github.com/RodrigoDMU/applied_statistics_assessment/blob/main/problems.ipynb) notebook file and run the cells sequentially.

- Each problem is clearly divided into sections.
- Explanations are written directly below the relevant code.

## References

<a id="1">[1]</a> About READMEs. Availible: https://docs.github.com/en/repositories/managing-your-repositorys-settings-and-features/customizing-your-repository/about-readmes 

<a id="2">[2]</a> Assessment Instructions: Winter 25/26. Availible: https://github.com/ianmcloughlin/applied-statistics/blob/main/assessment/assessment.md 

<a id="3">[3]</a> Basic writing and formatting syntax. Availible: https://docs.github.com/en/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax 

## Author

**Rodrigo De Martino Ucedo:**
 I am currently studying Higher Diploma in Science Data Analytics at Atlantic Technological University. For more information or questions, please contact me on GitHub or add me on [LinkedIn](https://www.linkedin.com/in/rdmdemartino/).
*****
last commit on 20/12/2025.