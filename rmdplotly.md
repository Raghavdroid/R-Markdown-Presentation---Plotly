---
  title: "markdown and plotly"
date: "September 7th 2020"
output: html_document
---
  
  ```{r setup, include=FALSE}
knitr::opts_chunk$set(echo = TRUE)
```

```{r}
library(plotly)
data("volcano")
plot_ly(z=volcano, type="surface")
```
```{r}
plot_ly(x=time(presidents), y=presidents, type="bar")
```
