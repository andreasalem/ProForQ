
## Programming for Quantitative Analysis

This is the companion website for the final project within the course *4,796: Skills: Programming for Quantitative Analysis*, taught by Prof. Valladares‑Esteban.
The project which has been submitted from my part revolves around the use of Python for empirical economic research, i.e., econometrics, or the quantitative analysis of actual economic phenomena.

<font size="5">Table of Contents</font>  

1. [Introduction to Impact Evaluation](#introduction)


2. [Technical Set-Up](#setup)


3. [Randomized Field Experiments](#RCT)  



4. [Difference in Differences](#DinD)  
&nbsp;&nbsp;&nbsp;4.1 [Theory](#theory1)  
&nbsp;&nbsp;&nbsp;4.2 [Example](#example1)



5. [Regression Discontinuity](#RDD)  
&nbsp;&nbsp;&nbsp;5.1 [Theory](#theory2)  
&nbsp;&nbsp;&nbsp;5.2 [Example](#example2)  




6. [Instrumental Variables](#IV)  
&nbsp;&nbsp;&nbsp;6.1 [Theory](#theory3)  
&nbsp;&nbsp;&nbsp;6.2 [Example](#example3) <br/>
&nbsp;&nbsp;&nbsp;6.3 [Simulation](#simulation) 



7. [Limitations of RCTs](#limitations)  



8. [Conclusion and discussion](#conclusion_and_discussion)










<font size="5">3&nbsp;&nbsp; Randomized  Field  Experiments: An Empirical Method to Make Causal Claims</font>


<br>
<br>


<div style="text-align:center">
<img src="https://raw.githubusercontent.com/Helgone/ProForQ/master/Linear_Regressiom.png" title="Anatomy of a Matplotlib figure" class="center" width="250">
</div>

<img src="https://render.githubusercontent.com/render/math?math=\begin{table}[!htbp] \centering \setlength{\tabcolsep}{1pt}
  \parbox[t]{10cm}{\centering \textsc{Table 3—Main Experimental Results} \\ (\textit{OLS regressions})}
  \label{} 
\scriptsize 
\begin{tabular}{@{\extracolsep{1pt}}lcccccc} 
\\[-1.8ex]\hline 
\hline \\[-1.8ex] 
\\[-1.8ex] & \multicolumn{3}{c}{\shortstack{Dependent variable:\\ Revenues per four-week period}} & \multicolumn{3}{c}{\shortstack{Dependent variable:\\ Shifts per four-week period}} \\ 
\cline{2-4}  \cline{5-7}
\\[-1.8ex] & (1) & (2) & (3) & (4) & (5) & (6)\\
\hline \\[-1.8ex] 
\parbox[t]{3cm}{Observations are \\ restricted to} & \parbox[t]{2cm}{\centering Messengers \\ participating in \\ experiment}  & \parbox[t]{2cm}{\centering All \\ messengers at \\ Veloblitz} & \parbox[t]{2cm}{\centering All \\ messengers at \\ Flash and \\ Veloblitz} & \parbox[t]{2cm}{\centering Messengers \\ participating in \\ experiment} & \parbox[t]{2cm}{\centering All \\ messengers at \\ Veloblitz} & \parbox[t]{2cm}{\centering All \\ messengers at \\ Flash and \\ Veloblitz} \\ 
  & & & & & & \\ 
 Treatment dummy & 1,033.560$^{***}$ & 1,094.496$^{***}$ & 1,035.8$^{***}$ & 3.986$^{***}$ & 4.083$^{***}$ & 3.435$^{***}$ \\ 
  & (326.854) & (297.844) & (297.14) & (1.0253) & (0.9416) & (0.941) \\ 
  & & & & & & \\ 
 \parbox[t]{3cm}{Dummy for nontreated \\ at Veloblitz}   &  &  & $-$54.40 &  &  & $-$0.628 \\ 
  &  &  & (407.436) &  &  & (1.526) \\ 
  & & & & & & \\ 
 Treatment period 1 & $-$210.972 & $-$370.619 & $-$264.76 & $-$1.275 & $-$1.570 & $-$0.716 \\ 
  & (497.2502) & (334.086) & (239.86) & (1.716) & (1.207) & (0.99467) \\ 
  & & & & & & \\ 
 Treatment period 2 & $-$574.712 & $-$656.233$$ & $-$650.48$^{**}$ & $-$2.561$$ & $-$2.631$^{**}$ & $-$2.216$^{**}$ \\ 
  & (545.675) & (357.929) & (284.93) & (1.862) & (1.259) & (1.0855) \\ 
  & & & & & & \\ 
Individual fixed effects & Yes & Yes & Yes & Yes & Yes & Yes \\ 
\textit{R} squared & 0.740 & 0.786 & 0.753 & 0.694 & 0.740 & 0.695 \\
\textit{N} & 124 & 190 & 386 & 124 & 190 & 386 \\ 
\hline 
\hline \\[-1.8ex] 
\multicolumn{5}{l} {\parbox[t]{11cm}{ \textit{Note:} Robust standard errors, adjusted for clustering on messengers, are in parentheses. \
 *** Indicates significance at the 1-percent level. \\
 ** Indicates significance at the 5-percent level. \\
 \text{*} Indicates significance at the 10-percent level.}} \\
  \textit{Source:} Own calculations.
\end{tabular} 
\end{table}
">


### Literature

Markdown is a lightweight and easy-to-use syntax for styling your writing. It includes conventions for

```markdown
Syntax highlighted code block

# Header 1
## Header 2
### Header 3

- Bulleted
- List

1. Numbered
2. List


[Link](url) and ![Image](src)
```

For more details see [GitHub Flavored Markdown](https://guides.github.com/features/mastering-markdown/).

### Jekyll Themes

Your Pages site will use the layout and styles from the Jekyll theme you have selected in your [repository settings](https://github.com/Helgone/ProForQ/settings/pages). The name of this theme is saved in the Jekyll `_config.yml` configuration file.

