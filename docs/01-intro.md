---
title: "Course Title"
output: html_document
---

# Introduction 

## Motivation
This course will cover interesting topics.

**Target Audience:**  
The course is intended for interesting people interested in interesting topics.

**Curriculum:**  
The curriculum will cover guidelines of ITN and other words that it might think are misspelled like Informatics or genomic or TCGA or TCIA or TCPA or HTAN


```r
#adding some test code to style
library(tidyverse)
```

```
## ── Attaching packages ─────────────────────────────────────── tidyverse 1.3.0 ──
```

```
## ✓ ggplot2 3.3.3     ✓ purrr   0.3.4
## ✓ tibble  3.1.0     ✓ dplyr   1.0.4
## ✓ tidyr   1.1.2     ✓ stringr 1.4.0
## ✓ readr   1.4.0     ✓ forcats 0.5.1
```

```
## ── Conflicts ────────────────────────────────────────── tidyverse_conflicts() ──
## x dplyr::filter() masks stats::filter()
## x dplyr::lag()    masks stats::lag()
```

```r
mtcars %>%select(mpg , cyl) %>%
  filter(cyl>4) %>%
    head()
```

```
##                    mpg cyl
## Mazda RX4         21.0   6
## Mazda RX4 Wag     21.0   6
## Hornet 4 Drive    21.4   6
## Hornet Sportabout 18.7   8
## Valiant           18.1   6
## Duster 360        14.3   8
```


