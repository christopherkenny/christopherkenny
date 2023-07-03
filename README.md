# Christopher T. Kenny

I am a PhD candidate in Government at Harvard University. I research redistricting, elections, and the uses and usability of census data. I am a core member of the [ALARM Project](https://alarm-redist.org/). In 2022, I was a fellow at the [Election Law Clinic at Harvard Law School](https://www.hlselectionlaw.org/). 

This readme is mostly a table of contents for my GitHub repositories (and some others that I contribute to). For more information on my research, see my [website](https://christophertkenny.com/research.html) or [CV](https://christophertkenny.com/CV.html). [Find me on Twitter!](https://twitter.com/Chris_T_Kenny)

## Packages on CRAN

These are packages that are stable and usable. They are on CRAN and in are in regular use (by at least me).

| Package | Description |
| ------- | ----------- |
| [redist](https://alarm-redist.org/redist/)              | Tools for redistricting sampling. Used frequently in research and litigation. |
| [redistmetrics](https://alarm-redist.org/redistmetrics/)| Measures and metrics for assessing redistricting plans |
| [geomander](https://christophertkenny.com/geomander/)   | Spatial tools designed for interfacing election data, precincts, and census  data |
| [PL94171](https://corymccartan.com/PL94171/)            | Read in [PL 94-171 Census](https://www.census.gov/programs-surveys/decennial-census/about/rdo/summary-files.html) data, the redistricting files. |
| [censable](https://christophertkenny.com/censable/)     | Download the most frequently used demographic data and categories from the Census Bureau API.|
| [ggredist](https://alarm-redist.org/ggredist/)          | ggplot2 extensions and color palettes for election mapping.|
| [tinytiger](https://alarm-redist.org/tinytiger/)        | A developer-oriented interface to TIGER/Line Shapefiles. (You probably want to use Kyle Walker's [tigris](https://github.com/walkerke/tigris) unless you're doing R :package: development.) |
| [cvap](https://christophertkenny.com/cvap/)             | Work with the US Census Bureau's [Citizen Voting Age Population Special Tabulations](https://www.census.gov/programs-surveys/decennial-census/about/voting-rights/cvap.html). |
| [ppmf](https://christophertkenny.com/ppmf/)             | Read in US Census Bureau Privacy Protected Microdata Files. |
| [divseg](https://christophertkenny.com/divseg/)         | Compute diversity and segregation indices. |
| [dots](https://christophertkenny.com/dots/)             | Create dot density maps in R. |
| [congress](https://christophertkenny.com/congress/)     | An R interface to the [Congress.gov API](https://github.com/LibraryOfCongress/api.congress.gov/). |
| [apportion](https://christophertkenny.com/apportion/)   | Allocate seats based on population vectors by various different methods. |
| [jot](https://christophertkenny.com/jot/)               | A GitHub friendly approach to saving and sharing statistics needed for writing papers in Quarto/RMarkdown. |
| [name](https://christophertkenny.com/name/)             | Collected tools for working with pattern-based column names. |
| [crayons](https://christophertkenny.com/crayons/)       | Some ggplot2 extensions for color palettes based on Crayola crayons. |
| [gptzeror](https://christophertkenny.com/gptzeror)      | An R interface to the [GPTZero API](https://gptzero.me/) for identifying so-called AI written text. |

## Packages under development

These are packages that are actively under development and have not yet made it onto CRAN for one reason or another. 
- Stable packages should give correct results, but may need a bit of work tightening up documentation or handling errors better. 
- Mostly stable packages should give correct results, but have features left to implement or have R CMD Check issues. 
- Experimental packages are entirely under development but will *someday* be good for wider use. 
- No promises packages are also entirely under development but I make no guarantees to their usefulness, but hey it _might_ be better than nothing. Send me a tweet, email, or open an issue if you want to ask about specific features in these.

| Package | Description | Lifecycle | 
| ------- | ----------- | --------- | 
| [alarmdata](https://alarm-redist.org/alarmdata/)       | Work with data generated from [ALARM Project](https://alarm-redist.org/) projects. | ![Static Badge](https://img.shields.io/badge/lifecycle-stable-green) |
| [redistverse](https://alarm-redist.org/redistverse/)   | Load in the whole redist family at once. | ![Static Badge](https://img.shields.io/badge/lifecycle-stable-green) |
| [planscorer](https://christophertkenny.com/planscorer/)| Score redistricting plans via the [PlanScore API](https://github.com/PlanScore/PlanScore/blob/main/API.md). | ![Static Badge](https://img.shields.io/badge/lifecycle-mostly_stable-aquamarine) |
| [ei](https://iqss-research.github.io/ei/)              | Run ecological inference models in R. This is a project with Shusei Eshima and Gary King to update Gary King and Molly Robert's original ei package from a decade ago.| ![Static Badge](https://img.shields.io/badge/lifecycle-mostly_stable-aquamarine) |
| [feltr](https://github.com/christopherkenny/feltr)     | Work with the [Felt API](https://feltmaps.notion.site/Getting-Started-With-The-Felt-API-69c8b02b7d8e436daa657a04a2dbaffa) so you can upload or read spatial data within existing workflows in R. | ![Static Badge](https://img.shields.io/badge/lifecycle-experimental-orange) |
| [vf](https://github.com/christopherkenny/vf) | Read in publicly available voter files in R. | ![Static Badge](https://img.shields.io/badge/lifecycle-no_promises-red) |
| [redistio](https://github.com/christopherkenny/redistio) | A poor man's version of Dave's Redistricting App run in Shiny | ![Static Badge](https://img.shields.io/badge/lifecycle-no_promises-red) | 

## Quarto and RMarkdown Templates

These are templates for journal submissions. These each modify a LaTeX template to let you write papers in a journal's submission style from Quarto or RMarkdown.

| Template | Type | Journal(s) |
| -------- | ---- | ---------- |
| [apsr](https://github.com/christopherkenny/apsr) | Quarto | [American Political Science Review](https://www.cambridge.org/core/journals/american-political-science-review) | 
| [cambridge-medium](https://github.com/christopherkenny/cambridge-medium) | Quarto | [Political Analysis](https://www.cambridge.org/core/journals/political-analysis), [Political Science Research and Methods](https://www.cambridge.org/core/journals/political-science-research-and-methods), [British Journal of Political Science](https://www.cambridge.org/core/journals/british-journal-of-political-science), [Annals of Actuarial Science](https://www.cambridge.org/core/journals/annals-of-actuarial-science), [Network Science](https://www.cambridge.org/core/journals/network-science) |
| [scientific-data](https://github.com/christopherkenny/scientific-data) | Quarto | [Scientific Data](https://www.nature.com/sdata/) (for Data Descriptors) | 
| [pnas](https://github.com/christopherkenny/pnas) | Quarto | [PNAS](https://www.pnas.org/) (for Research Articles) | 
| [science](https://github.com/christopherkenny/rticles) | rticles | [Science](https://www.science.org/), [Science Advances](https://www.science.org/journal/sciadv) |

## Other Repos

| Repo | Description |
| ---- | ----------- | 
| [christopherkenny.github.io](https://github.com/christopherkenny/christopherkenny.github.io) | Home to the Quarto files that generate [my personal website](https://christophertkenny.com/).
| [christopherkenny](https://github.com/christopherkenny/christopherkenny) | Home of the readme that you are currently reading. |
| [chicago](https://github.com/christopherkenny/chicago) | An example workflow for combining city election data and census demographic data using `geomander` and `censable` |
| [redist_workshop](https://github.com/christopherkenny/redist_workshop) | A workshop taught with Tyler Simko at Harvard University on using `redist` for research. | 
| [royale](https://github.com/christopherkenny/royale)  | ![Static Badge](https://img.shields.io/badge/lifecycle-stable-green) An R package for accessing the [API](https://developer.clashroyale.com/#/) for the game [Clash Royale](https://supercell.com/en/games/clashroyale/). |
| [styler.quote](https://github.com/christopherkenny/styler.quote) | ![Static Badge](https://img.shields.io/badge/lifecycle-stable-green) A third party extension to styler that modifies the tidyverse style guide to use correct quotes in R (the single `'` rather than captilized version `"`) |
| [luigg](https://github.com/christopherkenny/luigg) | ![Static Badge](https://img.shields.io/badge/lifecycle-mostly_stable-aquamarine) An R package with ggplot2 extensions for a Mario-style pipe bar graph and color schemes based on Mario games. |
| [acronames](https://github.com/christopherkenny/acronames) | ![Static Badge](https://img.shields.io/badge/lifecycle-mostly_stable-aquamarine) An R package for creating initialisms based on lists of words you want to use. | 
| [parrot](https://github.com/christopherkenny/parrot) | ![Static Badge](https://img.shields.io/badge/lifecycle-mostly_stable-aquamarine) An R package for including party parrots in RMarkdown. | 
| [ppmf_data](https://github.com/christopherkenny/ppmf_data) | Compressed versions of Census Privacy Protected Microdata Files | 
| [cvap_data](https://github.com/christopherkenny/cvap_data) | Preprocessed versions of Census CVAP data, usable with `cvap` |
| [universe](https://github.com/christopherkenny/universe) | Packages list for generating my [r-universe](https://christopherkenny.r-universe.dev/builds). I don't keep this super updated, but it has the big packages that are a pain to build from source from GitHub. | 

If there are other *public* repos that aren't listed here that aren't forks, they are probably either newer than this Table of Contents, too small to be useful, not supported but I don't want to delete them, or course-related. If you see something that you're interested in knowing more about, send me a tweet or email or just open an issue in the repo.
