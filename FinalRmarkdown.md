Final
================
Daven Lammi
2025-10-28

# ABSTRACT

# BACKGROUND

# STUDY QUESTION and HYPOTHESIS

## Questions

How does age, poverty level, and sex each influence an individual’s
susceptibility to asthma?

## Hypothesis

There will be a significant correlation between asthma and age, asthma
and poverty level, but not a very significant correlation between asthma
and sex.

## Possible Visualizations/ Test Statistic

barplot and t-test

## Barplot

``` r
library(ggplot2)

age <- data.frame(category = c(" 0-4", " 5-11", "12-17", "18-24", "25-34", "35-64", "65+"), value = c(1.4, 2.4, 2.0, 3.8, 6.4, 11.5, 27.1))

ggplot(age, aes(x = category, y = value)) +
  geom_bar(stat = "identity", fill = "darkred") + # stat="identity" uses y-values directly
  labs(title = "Asthma Deaths By Age",x = "Age (Years)",y = "Asthma-Related Deaths Per Million")
```

![](FinalRmarkdown_files/figure-gfm/age%20and%20deaths-1.png)<!-- -->

## Prediction

# METHODS

# DISCUSSION

## Interpretation - fill in analysis

## Interpretation - fill in analysis/plot

# CONCLUSION

# REFERENCES

3.  ChatGPT. OpenAI, version Jan 2025. Used as a reference for functions
    such as plot() and to correct syntax errors. Accessed 2025-10-28.
