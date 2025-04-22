# Christopher T. Kenny

I am a PhD candidate in Government at Harvard University. In Fall 2025, I will join [Princeton DDSS](https://ddss.princeton.edu/) as a Postdoctoral Research Associate. I research redistricting, elections, and the uses and usability of census data. I am a founding member and co-PI of the [ALARM Project](https://alarm-redist.org/). In 2022, I was a fellow at the [Election Law Clinic at Harvard Law School](https://www.hlselectionlaw.org/), where I developed [RPV Near Me](https://www.rpvnearme.org/) [(source code)](https://github.com/electionlawclinic/rpvnearme). 

This readme is mostly a table of contents for my GitHub repositories (and some others that I contribute to). For more information on my research, see my [website](https://christophertkenny.com/research.html) or [CV](https://christophertkenny.com/cv/kenny_cv.pdf). Find me on  [Twitter](https://twitter.com/Chris_T_Kenny), [Bluesky](https://bsky.app/profile/chriskenny.bsky.social), or [Threads](https://www.threads.net/@chris_t_kenny).

## Packages on CRAN

These are packages that are stable and usable. They are on CRAN and in are in regular use.

| Package | Description |
| ------- | ----------- |
| [redist](https://alarm-redist.org/redist/)                  | Tools for redistricting sampling. Used frequently in research and litigation. |
| [redistmetrics](https://alarm-redist.org/redistmetrics/)    | Measures and metrics for assessing redistricting plans |
| [geomander](https://christophertkenny.com/geomander/)       | Spatial tools designed for interfacing election data, precincts, and census  data |
| [PL94171](https://corymccartan.com/PL94171/)                | Read in [PL 94-171 Census](https://www.census.gov/programs-surveys/decennial-census/about/rdo/summary-files.html) data, the redistricting files. |
| [censable](https://christophertkenny.com/censable/)         | Download the most frequently used demographic data and categories from the Census Bureau API.|
| [ggredist](https://alarm-redist.org/ggredist/)              | ggplot2 extensions and color palettes for election mapping.|
| [tinytiger](https://alarm-redist.org/tinytiger/)            | A developer-oriented interface to TIGER/Line Shapefiles. (You probably want to use Kyle Walker's [tigris](https://github.com/walkerke/tigris) unless you're doing R :package: development.) |
| [cvap](https://christophertkenny.com/cvap/)                 | Work with the US Census Bureau's [Citizen Voting Age Population Special Tabulations](https://www.census.gov/programs-surveys/decennial-census/about/voting-rights/cvap.html).  |
| [ppmf](https://christophertkenny.com/ppmf/)                 | Read in US Census Bureau Privacy Protected Microdata Files. |
| [divseg](https://christophertkenny.com/divseg/)             | Compute diversity and segregation indices. |
| [dots](https://christophertkenny.com/dots/)                 | Create dot density maps in R. |
| [congress](https://christophertkenny.com/congress/)         | An R interface to the [Congress.gov API](https://github.com/LibraryOfCongress/api.congress.gov/). |
| [feltr](https://github.com/christopherkenny/feltr)          | Work with the [Felt API](https://feltmaps.notion.site/Getting-Started-With-The-Felt-API-69c8b02b7d8e436daa657a04a2dbaffa) so you can upload or read spatial data within existing workflows in R. |
| [apportion](https://christophertkenny.com/apportion/)       | Allocate seats based on population vectors by various different methods. |
| [jot](https://christophertkenny.com/jot/)                   | A GitHub friendly approach to saving and sharing statistics needed for writing papers in Quarto/RMarkdown. |
| [name](https://christophertkenny.com/name/)                 | Collected tools for working with pattern-based column names. |
| [crayons](https://christophertkenny.com/crayons/)           | Some ggplot2 extensions for color palettes based on Crayola crayons. |
| [gptzeror](https://christophertkenny.com/gptzeror)          | An R interface to the [GPTZero API](https://gptzero.me/) for identifying so-called AI written text. |
| [bskyr](https://christophertkenny.com/bskyr/)               | Use the [Bluesky Social HTTP API (XRPC)](https://atproto.com/specs/xrpc) in R. |
| [planscorer](https://christophertkenny.com/planscorer/)     | Score redistricting plans via the [PlanScore API](https://github.com/PlanScore/PlanScore/blob/main/API.md).|
| [alarmdata](https://alarm-redist.org/alarmdata/)            | Work with data generated from [ALARM Project](https://alarm-redist.org/) projects. |
| [palette](https://christophertkenny.com/palette/)           | Use a `palette` class which adds pretty console color printing. | 
| [baf](https://christophertkenny.com/baf/)                   | Load Census Bureau block assignment files and block equivalency files. |
| [redistverse](https://alarm-redist.org/redistverse/)        | Load in the whole `redist` family at once. |
| [opengraph](https://github.com/christopherkenny/opengraph)  | Parse Open Graph Protocol metadata |
| [flexoki](https://github.com/christopherkenny/flexoki)      | Use Steph Ango's [flexoki](https://github.com/kepano/flexoki) palettes in ggplot |
| [typr](https://github.com/christopherkenny/typr)            | Compile Typst documents from R. |

## Packages under development

These are packages that are actively under development and have not yet made it onto CRAN for one reason or another. 
- Stable packages should give correct results, but may need a bit of work tightening up documentation or handling errors better. 
- Mostly stable packages should give correct results, but have features left to implement or have R CMD Check issues. 
- Experimental packages are entirely under development but will *someday* be good for wider use. 
- No promises packages are also entirely under development but I make no guarantees to their usefulness, but hey it _might_ be better than nothing. Send me a tweet, email, or open an issue if you want to ask about specific features in these.

| Package | Description | Lifecycle | 
| ------- | ----------- | --------- | 
| [redistio](https://github.com/christopherkenny/redistio) | An interactive redistricting app run locally in Shiny | ![Static Badge](https://img.shields.io/badge/lifecycle-stable-green) | 
| [ei](https://iqss-research.github.io/ei/)              | Run ecological inference models in R. This is a project with Shusei Eshima and Gary King to update Gary King and Molly Robert's original ei package from a decade ago.| ![Static Badge](https://img.shields.io/badge/lifecycle-mostly_stable-aquamarine) |
| [vf](https://github.com/christopherkenny/vf) | Read in publicly available voter files in R. | ![Static Badge](https://img.shields.io/badge/lifecycle-no_promises-red) |

## Quarto and RMarkdown

### Journal Templates

These are templates for journal submissions. These each modify a LaTeX template to let you write papers in a journal's submission style from Quarto or RMarkdown.

| Template | Type | Journal(s) |
| -------- | ---- | ---------- |
| [annual-reviews](https://github.com/christopherkenny/annual-reviews) | Quarto | [Annual Reviews](https://www.annualreviews.org/) |
| [apsr](https://github.com/christopherkenny/apsr) | Quarto | [American Political Science Review](https://www.cambridge.org/core/journals/american-political-science-review) | 
| [cambridge-medium](https://github.com/christopherkenny/cambridge-medium) | Quarto | [Political Analysis](https://www.cambridge.org/core/journals/political-analysis), [Political Science Research and Methods](https://www.cambridge.org/core/journals/political-science-research-and-methods), [British Journal of Political Science](https://www.cambridge.org/core/journals/british-journal-of-political-science), [Annals of Actuarial Science](https://www.cambridge.org/core/journals/annals-of-actuarial-science), [Network Science](https://www.cambridge.org/core/journals/network-science) |
| [nature](https://github.com/christopherkenny/nature) | Quarto | [Springer Nature Journals](https://www.springernature.com/gp/products/journals) |
| [pnas](https://github.com/christopherkenny/pnas) | Quarto | [PNAS](https://www.pnas.org/) (for Research Articles) | 
| [pnas-si](https://github.com/christopherkenny/pnas-si) | Quarto | [PNAS](https://www.pnas.org/) (for Supporting Information) | 
| [science](https://github.com/christopherkenny/rticles) | rticles | [Science](https://www.science.org/), [Science Advances](https://www.science.org/journal/sciadv) |
| [scientific-data](https://github.com/christopherkenny/scientific-data) | Quarto | [Scientific Data](https://www.nature.com/sdata/) (for Data Descriptors) | 
| [perspectives](https://github.com/christopherkenny/perspectives) | Quarto | [Perspectives on Politics](https://www.cambridge.org/core/journals/perspectives-on-politics) |

### Non-journal Quarto Templates

These are Quarto extensions which are not designed for submissions to academic journals.

| Extension | Description |
| --------- | ----------- | 
| [tufte](https://github.com/christopherkenny/tufte) | Provides a Tufte-style document for Quarto using Typst, based on [nogula/tufte-memo](https://github.com/nogula/tufte-memo) |
| [ctk-article](https://github.com/christopherkenny/ctk-article) | A general purpose academic article template for Quarto using Typst |
| [ctk-memo](https://github.com/christopherkenny/ctk-memo) | A general purpose memo template to aesthetically match `ctk-article` |
| [cv](https://github.com/christopherkenny/quarto-cv) | A CV template using shortcodes from Quarto and Typst-powered YAML reading and formatting|
| [projector](https://github.com/christopherkenny/projector) | A Quarto extension for making slides with [Polylux](https://github.com/andreasKroepelin/polylux)|
| [harvard-diss](https://github.com/christopherkenny/harvard-diss) | A Quarto extension for writing a Harvard GSAS dissertation with a Typst backend |

### Quarto Extensions (Filters)

These are non-template extensions that can be added to any Quarto document.

| Extension | Type | Description |
| --------- | ---- | ----------- |
| [wordcount](https://github.com/christopherkenny/wordcount) | filter | inserts a word count within a document in place of the placeholder `{{wordcount}}` or `{{wordcountref}}`|
| [typst-function](https://github.com/christopherkenny/typst-function) | filter | inserts a Typst function in the place of a div or span |
| [spellcheck](https://github.com/christopherkenny/spellcheck) | filter | runs Hunspell on render, printing mispelled words to the console |

## Other Repos

| Repo | Description |
| ---- | ----------- | 
| [christopherkenny.github.io](https://github.com/christopherkenny/christopherkenny.github.io) | Home to the Quarto files that generate [my personal website](https://christophertkenny.com/).
| [christopherkenny](https://github.com/christopherkenny/christopherkenny) | Home of the readme that you are currently reading. |
| [chicago](https://github.com/christopherkenny/chicago) | An example workflow for combining city election data and census demographic data using `geomander` and `censable` |
| [redist_workshop](https://github.com/christopherkenny/redist_workshop) | A workshop taught with Tyler Simko at Harvard University on using `redist` for research. | 
| [royale](https://github.com/christopherkenny/royale)  | ![Static Badge](https://img.shields.io/badge/lifecycle-stable-green) An R package for accessing the [API](https://developer.clashroyale.com/#/) for the game [Clash Royale](https://supercell.com/en/games/clashroyale/). |
| [clash](https://github.com/christopherkenny/clash)  | ![Static Badge](https://img.shields.io/badge/lifecycle-stable-green) An R package for accessing the [API](https://developer.clashofclans.com/#/) for the game [Clash of Clans](https://supercell.com/en/games/clashofclans/). |
| [styler.quote](https://github.com/christopherkenny/styler.quote) | ![Static Badge](https://img.shields.io/badge/lifecycle-stable-green) A third party extension to styler that modifies the tidyverse style guide to use correct quotes in R (the single `'` rather than captilized version `"`) |
| [luigg](https://github.com/christopherkenny/luigg) | ![Static Badge](https://img.shields.io/badge/lifecycle-mostly_stable-aquamarine) An R package with ggplot2 extensions for a Mario-style pipe bar graph and color schemes based on Mario games. |
| [acronames](https://github.com/christopherkenny/acronames) | ![Static Badge](https://img.shields.io/badge/lifecycle-mostly_stable-aquamarine) An R package for creating initialisms based on lists of words you want to use. | 
| [parrot](https://github.com/christopherkenny/parrot) | ![Static Badge](https://img.shields.io/badge/lifecycle-mostly_stable-aquamarine) An R package for including party parrots in RMarkdown. | 
| [ppmf_data](https://github.com/christopherkenny/ppmf_data) | Compressed versions of Census Privacy Protected Microdata Files | 
| [cvap_data](https://github.com/christopherkenny/cvap_data) | Preprocessed versions of Census CVAP data, usable with `cvap` |
| [universe](https://github.com/christopherkenny/universe) | Packages list for generating my [r-universe](https://christopherkenny.r-universe.dev/builds). I don't keep this super updated, but it has the big packages that are a pain to build from source from GitHub. | 
| [conf](https://github.com/christopherkenny/conf) | Links to public conference slides |
| [legend-dynasty](https://github.com/christopherkenny/legend-dynasty) | A series of automatically generated tables to a quarto website |
| [bsky-cran-bot](https://github.com/christopherkenny/bskyr-cran-bot) | A time-based Bluesky Social bot powered by [`bskyr`](https://christophertkenny.com/bskyr/) and run on GitHub Actions |
| [mt-enumeration](https://github.com/christopherkenny/mt-enumeration) | Enumeration of all whole county plans with 1 person deviation in Montana for the 2020 cycle |

If there are other *public* repos that aren't listed here that aren't forks, they are probably either newer than this Table of Contents, too small to be useful, not supported but I don't want to delete them, or course-related. If you see something that you're interested in knowing more about, send me a tweet or email or just open an issue in the repo.
