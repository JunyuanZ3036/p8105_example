
---
title: "Simple document"
output: html_document
knitr::knit
---

I'm an R Markdown document! 

# Section 1

Here's a **code chunk** that samples from 
a _normal distribution_:

```{r}
samp = rnorm(100)
length(samp)
```

# Section 2

I can take the mean of the sample, too!
The mean is `r mean(samp)`.