# Open Research for Wildlife & Ecology: Hands-on Workshop

## Nordic Early-Career Researchers

### May 12th 2026

### Schedule

Timings may change on the day due to participants needs and the timing of the canteen. Change this without pulling


| Time | Session | Focus |
|------------------------|------------------------|------------------------|
| **08:30–09:00** | Coffee! | Waking up |
| 09:00–09:15 | Welcome + why open workflows matter | Transparency, reproducibility, collaboration, examples from ecology |
| 09:15–10:00 | What is a reproducible research project? | Folder structure, raw vs processed data, scripts, documentation |
| 10:00–10:15 | Break |  |
| 10:15–12:00 | GitHub without fear (or an appropriate amount of fear!) | Repositories, commits, push/pull, README files |
| 12:00–13:00 | Lunch |  |
| 13:00–14:15 | Hands-on 1: make your first reproducible project | Create RStudio project, add folders, README, script, commit changes |
| 14:15–14:45 | Quarto for transparent reporting | From script to report; code, text, figures, tables |
| 14:45–15:00 | Break |  |
| 15:00–15:45 | Collaboration workflows | Issues, branches, pull requests, project handover, common mistakes |
| 15:45–16:15 | Sharing data and code responsibly | Licences, metadata, sensitive ecological data, what can/cannot be open |
| 16:15–16:30 | Wrap-up + Nordic community | Next steps, buddy system, SORTEE/open science community links |

## Pre-workshop requirements

### Install software

- Latest version of **R**\
  *(use the newest version you can — some universities restrict updates)*
- Latest version of **RStudio Desktop**
- **Git**
  - Windows: <https://git-scm.com/download/win>
  - Mac: <https://git-scm.com/download/mac>

### Create a GitHub account

- <https://github.com>

### Connect Git to your computer (in RStudio)

``` r
install.packages("usethis") 

usethis::use_git_config(user.name = "Your Name", user.email = "your@email.com") 

usethis::git_sitrep() # Check that everything is set up correctly
```
