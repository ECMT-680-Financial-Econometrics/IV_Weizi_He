\documentclass[final]{beamer}
\usepackage[size=a0,scale=1.4]{beamerposter}
\usetheme{Berlin}
\usecolortheme{rose}
\usepackage{graphicx, amssymb, epstopdf, setspace, url, natbib, semtrans, comment, pdfpages, enumerate, float, tocloft, caption, fancyhdr, rotating, lscape, pdflscape, lipsum, pbox, amsmath, tabularray, longtable, threeparttablex, threeparttable, subcaption}
\usepackage[english]{babel}
\usepackage{tikz}
\renewcommand{\thetable}{\arabic{table}}
\renewcommand{\thefigure}{\arabic{figure}}
\setbeamercolor{highlighted block}{fg=black, bg=yellow}
\title{\Huge OLS and 2SLS Regression Analysis on Census Data}
\author{\Large Your Name}
\institute{\Large Institution Name}
\date{\Large\today}
\begin{document}
\begin{frame}[t]
\begin{block}{}
\centering
\maketitle
\end{block}

\begin{columns}[T]
\begin{column}{.32\textwidth}
    \begin{block}{\Huge Introduction}
    \Large
    Overview of the census data analysis using OLS and 2SLS regressions to explore the relationship between education and weekly wage.
    \end{block}

    \begin{block}{\Huge Data Cleaning}
    \Large
    Description of the data cleaning process for census data from the 1970s and 1980s, including handling missing values.
    \end{block}

    \begin{block}{\Huge OLS Regression Analysis}
    \Large
    Summary of OLS regression findings, emphasizing the impact of education on weekly wage for the 1970s and 1980s datasets.
    \end{block}
\end{column}

\begin{column}{.32\textwidth}
    \begin{block}{\Huge 2SLS Regression Analysis}
    \Large
    Explanation of the 2SLS regression approach and its application to the census data, including the creation of dummy variables and predictions of education.
    \end{block}

    \begin{block}{\Huge Results and Discussion}
    \Large
    Discussion of the analysis results, highlighting the differences in findings between OLS and 2SLS regressions and across decades.
    \end{block}

    \begin{block}{\Huge Figures and Tables}
    \Large
    Placeholders for figures and tables generated from the analysis. Include descriptions and interpretations.
    \[
    \text{Insert figures and tables here.}
    \]
    \end{block}
\end{column}

\begin{column}{.32\textwidth}
    \begin{block}{\Huge Conclusions}
    \Large
    Conclusions drawn from the regression analyses, including the implications of the findings and suggestions for future research.
    \end{block}

    \begin{block}{\Huge References}
    \Large
    List of references and data sources utilized in the analysis.
    \end{block}

    \begin{block}{\Huge Appendix}
    \Large
    Additional analyses, code snippets, or detailed statistical outputs supporting the main findings.
    \end{block}