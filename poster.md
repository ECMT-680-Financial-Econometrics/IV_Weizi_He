\documentclass[final]{beamer}
\usepackage[size=a0,scale=1.4]{beamerposter}
\usetheme{Berlin}
\usecolortheme{rose}

\usepackage{graphicx, amssymb, epstopdf, setspace, url, natbib, semtrans, comment, pdfpages, enumerate, float, tocloft, caption, fancyhdr, rotating, lscape, pdflscape, lipsum, pbox}
\usepackage[english]{babel}
\newcommand\fnote[1]{\captionsetup{font=footnotesize}\caption*{#1}}
\DeclareGraphicsRule{.tif}{png}{.png}{`convert #1 `dirname #1`/`basename #1 .tif`.png}
\usepackage{verbatim, multirow, threeparttable, colortbl, chngcntr, ragged2e, booktabs, tabularx, amsmath}
\newcommand{\btVFill}{\vskip0pt plus 1filll}
\newcommand{\sym}[1]{\rlap{#1}}
\DeclareMathOperator*{\Max}{Max}
\DeclareMathOperator*{\E}{\mathbb{E}}
\usepackage{tabularray}
\usepackage{longtable}
\usepackage{threeparttablex}
\usepackage{threeparttable}
\usepackage[font=small,labelfont=bf]{caption} 

%\renewcommand{\thesection }{\Roman{section}.} 
%\renewcommand{\thesubsection}{\thesection\Alph{subsection}.}
\usepackage{tikz}

\usepackage{tabularray}
\usepackage[titletoc, title]{appendix}
\usepackage{etoolbox}
\patchcmd{\appendices}{\quad}{: }{}{}

\usepackage{textcase}
\usepackage[tablename=Table]{caption}
%\DeclareCaptionTextFormat{up}{\MakeTextUppercase{#1}}
%\captionsetup[table]{
    %labelsep=newline,
    %justification=centering,
    %textformat=up,}
\usepackage[figurename=Figure]{caption}
%\DeclareCaptionTextFormat{up}{\MakeTextUppercase{#1}}
%\captionsetup[figure]{
    %labelsep=newline,
    %justification=centering,
    %textformat=up,}
\usepackage{bbm}   

\usepackage{subcaption}

\renewcommand{\thetable}{\arabic{table}}
\setcounter{table}{0}
\renewcommand{\thefigure}{\arabic{figure}}
\setcounter{figure}{0}

% Custom style for highlighted blocks
\setbeamercolor{highlighted block}{fg=black, bg=yellow} 

\title{\Huge Research Report Title (Generated Using PlusMind ChatGPT)} % Very large title
\author{\Large Author Name} % Larger author name
\institute{\Large Texas A\&M University} % Larger institute name
\date{\Large\today} % Larger date

% Clearing the default footline
\setbeamertemplate{footline}{} 

\begin{document}
\begin{frame}[t]

% Title at the top
\begin{block}{}
\centering
\maketitle
\end{block}

\begin{columns}[T] % align columns at the top

% Column 1
\begin{column}{.32\textwidth}
    \begin{block}{\Huge Abstract} % Very large section title
    \Large % Larger main text
    Short Summary of the report.
    \normalsize (Content generated using PlusMind ChatGPT. Editable on www.plusmind.ai)
    \end{block}

    \vspace{1cm} % Add vertical space

    \begin{block}{\Huge Introduction} % Very large section title
    \Large % Larger main text
    M. Jahangir Alam
    Outline the purpose and scope of the report. Provide a brief summary of the project idea you're addressing. State the hypotheses or questions you intend to answer.
    \normalsize (Content generated using PlusMind ChatGPT. Editable on www.plusmind.ai)
    \end{block}

    \vspace{1cm} % Add vertical space

    \begin{block}{\Huge Literature Review} % Very large section title
    \Large % Larger main text
    Summarize relevant theories and previous research related to your topic. Identify
