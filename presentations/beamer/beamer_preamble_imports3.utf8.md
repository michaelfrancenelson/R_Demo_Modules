---
title: "importing files in the preamble"
subtitle:  "Session 1"
date: "2020-03-02 14:53:42 -0500"
output:
  beamer_presentation
header-includes:
  # \usepackage{tikz}
  \input{C:/Users/michaelnelso/git/R_Demo_Modules/css/headers_tikz.yaml}
---
\input{cmd.tex}

# new command

\pltLogo{"C:/Users/michaelnelso/git/R_Demo_Modules/images/test/iClicker_logo.png"}
<!-- \pltLogo{C:/Users/michaelnelso/git/R_Demo_Modules/images/test/iClicker_logo.png} -->


# new slide
<!-- \input{cmd.tex} -->
<!-- \atest{abc} -->


<!-- \newcommand{\pltc}{ -->
<!--   \vfill -->
<!--   \begin{tikzpicture}[remember picture,overlay] -->
<!--      \node[xshift=-2cm,yshift=1cm] at (current page.south east)% -->
<!--      { -->
<!--        \includegraphics[height=0.25in]{C:/Users/michaelnelso/git/R_Demo_Modules/images/test/iClicker_logo.png} -->
<!--      }; -->
<!--    \end{tikzpicture} -->
<!-- } -->

<!-- \newcommand{\pltc}{ -->
<!--   \vfill -->
<!--   \begin{tikzpicture}[remember picture,overlay] -->
<!--      \node[xshift=-2cm,yshift=1cm] at (current page.south east)% -->
<!--      { -->
<!--        \includegraphics[height=0.25in]{\eval{r here::here("images", "test", "iClicker_logo.png")} -->
<!--      }; -->
<!--    \end{tikzpicture} -->
<!-- } -->

<!-- \pltc -->

<!-- \newcommand{\bt}[1]{\textbf{'#1'}} -->

<!-- \NewDocumentCommand{\myref}{>{\SplitArgument{2}{,}}m}{% -->
<!--   \myrefaux#1% -->
<!-- } -->
<!-- \newcommand{\myrefaux}[3]{% -->
<!--     \begin{textblock*}{100mm}(0.07\textwidth,.93\textheight) -->
<!--       {\footnotesize #1, {\em #2}, #3} -->
<!--     \end{textblock*} -->
<!-- } -->


<!-- \newcommand{\fillcol}{green!20} -->
<!-- \newcommand<>{\boxto}[2]{ -->
<!-- \only#3{% -->
<!--   \tikz%[remember picture with id=#1] -->
<!--   \draw[line width=1pt,fill=#2,rectangle,rounded corners] (1,1) rectangle (2,2); -->
<!--   }% -->
<!-- } -->


<!-- \newcommand<>{\abc}[1]{"abc#1"} -->

<!-- \newcommand\reverseconcat[3]{#1} -->
<!-- \newcommand{\reverseconcat}[3]{"#3#2#1"} -->
<!-- \reverseconcat{A}{B}{C} -->


<!-- \input{C:/Users/michaelnelso/git/R_Demo_Modules/css/headers_tikz.yaml} -->
<!-- \iClick -->

# a
<!-- \newcommand{\click} -->
<!-- { -->
<!--  \vfill -->
<!--    \begin{tikzpicture}[remember picture,overlay] -->
<!--      \node[xshift=-2cm,yshift=1cm] at (current page.south east)% -->
<!--      { -->
<!--        \includegraphics[height=0.25in]{"C:/Users/michaelnelso/git/R_Demo_Modules/images/test/iClicker_logo.png"} -->
<!--      }; -->
<!--    \end{tikzpicture} -->
<!-- } -->

<!-- \newcommand{\click}[1] -->
<!-- { -->
<!--   \includegraphics#1 -->
<!-- } -->

<!-- \click{"C:/Users/michaelnelso/git/R_Demo_Modules/images/test/iClicker_logo.png"} -->
<!-- \click{"C:/Users/michaelnelso/git/R_Demo_Modules/images/test/iClicker_logo.png"} -->

<!-- # b -->
<!-- \newcommand{\iClick}[1] -->
<!-- { -->
<!--  \vfill -->
<!--    \begin{tikzpicture}[remember picture,overlay] -->
<!--      \node[xshift=-2cm,yshift=1cm] at (current page.south east) -->
<!--      { -->
<!--        \includegraphics[height=0.25in]{#1} -->
<!--      }; -->
<!--    \end{tikzpicture} -->
<!-- } -->

<!-- \iClick{"C:/Users/michaelnelso/git/R_Demo_Modules/images/test/iClicker_logo.png"} -->


<!-- \newcommand{\iClick} -->
<!-- { -->
<!--  \vfill -->
<!--    \begin{tikzpicture}[remember picture,overlay] -->
<!--      \node[xshift=-2cm,yshift=1cm] at (current page.south east)% -->
<!--      { -->
<!--        \includegraphics[height=0.25in]{../../images/test/iClicker_logo.png} -->
<!--      }; -->
<!--    \end{tikzpicture} -->
<!-- } -->