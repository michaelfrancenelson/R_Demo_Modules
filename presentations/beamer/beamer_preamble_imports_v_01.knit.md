---
title: "importing files in the preamble"
subtitle:  "Guide version 1"
date: "2020-03-03 09:04:27 -0500"
output:
  beamer_presentation:
    pandoc_args: !expr paste0(here::here('css', 'beamer.yaml'))
header-includes:
  \input{C:/Users/michaelnelso/git/R_Demo_Modules/css/headers_tikz.tex}
---

# Input commands from external tex file

knitr can't process newcommands with arguments properly, they must be defined in an external tex file and then imported.

\input{C:/Users/michaelnelso/git/R_Demo_Modules/css/newcommands.tex}

# new command within Rmd file
\newcommand{\atest} { and seven years ago }
\atest

# new command from imported tex file

This should plot a logo in the southeast corner of the slide.

\logoSoutheast{C:/Users/michaelnelso/git/R_Demo_Modules/images/iClicker_logo.png}
