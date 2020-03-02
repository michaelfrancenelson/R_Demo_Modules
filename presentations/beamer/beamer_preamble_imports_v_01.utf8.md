---
title: "importing files in the preamble"
subtitle:  "Session 1"
date: "2020-03-02 15:06:02 -0500"
output:
  beamer_presentation:
    pandoc_args: !expr paste0(here::here('css', 'beamer.yaml'))
header-includes:
  \input{C:/Users/michaelnelso/git/R_Demo_Modules/css/headers_tikz.yaml}
---
\input{C:/Users/michaelnelso/git/R_Demo_Modules/css/newcommands.tex}

# new command within Rmd file
\newcommand{\atest}
{
 and seven years ago
}
\atest

# new command from imported tex file
\pltLogo{C:/Users/michaelnelso/git/R_Demo_Modules/images/test/iClicker_logo.png}


