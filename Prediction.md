---
title: "Prediction"
author: "Maxine(Diandian) Yi"
date: "September 12, 2019"
output: html_document
---

```{r setup, include=FALSE}
knitr::opts_chunk$set(echo = TRUE)
library(kableExtra)
```

## Model prediction
### Use decision tree algorithm with SMOTE

```{r prediction, echo=FALSE}
text_tbl <- data.frame(
  Class = c("0", "1"),
  Count = c(139142,3262
  )
)

kable(text_tbl) %>%
  kable_styling(bootstrap_options = c("striped", "hover", "condensed"))
