# Package Development Masterclass

### rstudio::conf 2022

by Hadley Wickham

------------------------------------------------------------------------

:spiral_calendar: July 25 and 26, 2022\
:alarm_clock: 09:00 - 17:00\
:hotel: **TBA**

------------------------------------------------------------------------

## Overview

In this two day masterclass, you'll have the opportunity to dig deep in to package development.
Across the two days, we'll spend around 4 hours speaking about advanced package development topics, like writing testable code and producing error messages that spark joy.
We'll focus on cutting edge topics and tools that have significantly impacted the way we develop packages in the last couple of years.
However, the majority of the time will be unstructured, so you can take what you've just learned about and apply it your package, in environment where you can get help and talk things through with the tidyverse team.

## Setup

``` r
install.packages("devtools")
usethis::use_devtools()
```

## Useful links

-   [R packages book](https://r-pkgs.org/)
-   [Common questions](https://bit.ly/3aoPD70) google doc
-   [Chat on discord](https://rstd.io/discord)

## Schedule

### Day 1

| Time          | Activity                                                         | Instructor |
|:--------------|:-----------------------------------------------------------------|------------|
| 09:00 - 10:30 | [Introduction and check lists](materials/1-intro-checklists.pdf) | Hadley     |
| 10:30 - 11:00 | *Coffee break*                                                   |            |
| 11:00 - 12:30 | Test tooling and design                                          | Jenny      |
| 12:30 - 13:30 | *Lunch break*                                                    |            |
| 13:30 - 15:00 | [Writing great function docs](materials/3-function-docs.pdf)     | Hadley     |
| 15:00 - 15:30 | *Coffee break*                                                   |            |
| 15:30 - 17:00 | [Making a website with pkgdown](4-website.pdf)                   | Hadley     |

### Day 2

| Time          | Activity                          | Instructor |
|:--------------|:----------------------------------|------------|
| 09:00 - 10:30 | Informative errors with rlang     | Lionel     |
| 10:30 - 11:00 | *Coffee break*                    |            |
| 11:00 - 12:30 | Snapshot testing with testthat 3e | Jenny      |
| 12:30 - 13:30 | *Lunch break*                     |            |
| 13:30 - 15:00 | Function design                   | Hadley     |
| 15:00 - 15:30 | *Coffee break*                    |            |
| 15:30 - 17:00 | Automated checking with GHA       | Gabor      |

## Instructor

You'll learn from Hadley Wickham, Jenny Bryan, Lionel Henry, Gabor Csardi, and other members of the tidyverse team.

------------------------------------------------------------------------

![](https://i.creativecommons.org/l/by/4.0/88x31.png) This work is licensed under a [Creative Commons Attribution 4.0 International License](https://creativecommons.org/licenses/by/4.0/).
