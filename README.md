# IV_Weizi_He
Overview This repository contains a replication study of the effects of compulsory school attendance on education and earnings. Differing from the original study "Does Compulsory School Attendance Affect Schooling and Earnings?" by Angrist and Krueger (1990), this project utilizes data from the1970 and 1980 U.S. population censuses. Data Source The study analyzes a 5% sample of the total population from each census year, providing a comprehensive overview across different decades. The data is sourced from publicly accessible census records. Data Analysis Cohort Analysis: The study examines cohorts born in the 1970s, and 1980s, offering a broader temporal perspective compared to the original study. Sample Size: Utilizing a 5% sample size ensures a balance between data manageability and representativeness. Methodology Instrumental Variables (IV) Analysis: Following the methodology of the original paper, IV analysis is employed to estimate the causal effects of compulsory schooling. Comparative Approach: By comparing different cohorts and utilizing data from different decades, the study aims to provide insights into the evolving impact of education policies over time. Replication Details Figures and Tables: The study replicates key figures and tables from the original research, adjusted for the new data set. Extended Analysis: Beyond replication, the study conducts additional analyses to explore trends not covered in the original research. Accessing the Study The full code and methodology, along with a detailed explanation, are available in this repository. For a step-by-step walkthrough of the analysis, refer to the provided Jupyter notebooks. Collaborative Environment To facilitate collaboration and transparency, an interactive version of the study is available on Google Colab. This platform allows researchers to view, run, and modify the code in a shared environment.
\documentclass{article}
\usepackage{hyperref}
\begin{document}
\title{\textbf{Does Compulsory School Attendance Affect Schooling and Earnings?} \\
\footnotesize \textsuperscript{ }\href{https://www.nber.org/papers/w3572}{Joshua D. Angrist and Alan B. Krueger, National Bureau of Economic Research, 1991}}
\maketitle
\begin{itemize}
\item \textbf{Objective:} Analyze the effect of compulsory school attendance laws on education levels and earnings.
\item \textbf{Methodology \& Instrument:} Using birth season as an instrumental variable, the paper examines the relationship between school start age, compulsory schooling, and educational outcomes.
\item \textbf{Reason:} Season of birth creates variations in education that can estimate the impact of compulsory schooling on education and earnings.
\item \textbf{Data:} Data from US Census and National Bureau of Economic Research, focusing on individuals born between 1930 and 1959.
\item \textbf{Results:} Indicates that compulsory schooling increases educational attainment and earnings, with substantial returns for those compelled to attend school longer than desired.
\end{itemize}
\end{document}
