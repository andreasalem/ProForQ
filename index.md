
## Programming for Quantitative Analysis

This is the companion website for the final project within the course
<br>
<center><b> 4,796: Skills: Programming for Quantitative Analysis</b> </center> 
<br>

taught by Prof. Valladares‑Esteban. The project which has been submitted from my part revolves around the use of Python for empirical economic research. The main body of the project is in the Jupyter Notebook file contaning the code (avaiable [here](https://drive.google.com/file/d/1OyeJwH-Cn8hIyM4XL908_16mdTRTqwLM/view?usp=share_link) for download). This website serves to extend certain explanations and enrich the project with extra material not present in the Notebook file.

  
<font size="5">Table of Contents</font>  <br>

1. Introduction to Impact Evaluation <br>

  
2. Technical Set-Up <br>


3. Randomized Field Experiments  <br>
&nbsp;&nbsp;&nbsp;3.1 [Table 1](#theory3.1)


4. Difference in Differences <br>
&nbsp;&nbsp;&nbsp;4.1 [Table 2](#theory4.1)  

<br>
<br>

<font size="5">1&nbsp;&nbsp; Introduction to Impact Evaluation</font> 

Here are three useful websites for who wants to learn more about what impact evaluation in the real world looks like:

  - [J-PAL](https://www.povertyactionlab.org/)
  - [Innovations for Poverty Action (IPA)](https://www.poverty-action.org/)
  - [Evidence for Policy Design (EPoD)](https://epod.cid.harvard.edu/)

Furthermore, a brief slide presentation about this Project's results and notions such as causal and treatment effect or experimental vs. quasi-experimental methods, can be found [here](https://drive.google.com/file/d/1wLGLdM-eqB6dY3IgULX0Ds9pDRy8hepl/view?usp=share_link).

<br>

<font size="5">2&nbsp;&nbsp; Technical Set-Up</font>

The .ipynb file with the main body of the project is also available at [this link](https://drive.google.com/file/d/1OyeJwH-Cn8hIyM4XL908_16mdTRTqwLM/view?usp=share_link). We recomend opening the file in the local Jupyter Notebook server, since the rendering could be different on other platforms (such as Google Collab, nbviewer, etc.). We also remind everyone to modify the current working directory at the beginning of the .ipynb file in order to run the entire script correctly. Finally, also the `pip install` command may has to be run for some packages. 

All four datasets used in the project can be found [here](https://drive.google.com/drive/folders/1q3aiDwpnYftsc19urJdJ2wYaSeHpkwc1?usp=share_link).

<br>

<font size="5">3&nbsp;&nbsp; Randomized  Field  Experiments: An Empirical Method to Make Causal Claims</font>


<br>
<br>

<a id='theory3.1'></a>
**3.1** 

<div style="text-align:center">
<img src="https://raw.githubusercontent.com/Helgone/ProForQ/master/Table1.png" class="center" width="1950">
</div>


<p align="justify">
As we can see from the table, the authors estimate three different models per outcome. What changes across models? First of all the data used in the calculations is different in each model. Regressions (1) and (4) are based only on the data of groups A and B (participating messengers) at Veloblitz. Due to the random assignment of the participating messengers, and due to the fact that both groups served once as a control and once as a treatment group, these two regressions allow for a clear isolation of the treatment effect of the 25% increase of the commission rate on total revenues and on the number per shifts.
</p>


<p align="justify">
Regressions (2) and (5) instead, compare the experimental treatment group at Veloblitz with all other messengers at Veloblitz, not only with the experimental control group. This means that now the treatment dummy compares the treated with the whole group of untreated messengers at Veloblitz. Concerning total revenues, regression (2) again finds a large and significant treatment effect on total revenues of roughly CHF 1,000; concerning shifts, regression (5) also practically
replicates the results from regression (2), finding that the treated group works on average four shifts more than the control group.
</p>

<p align="justify">
Finally, regressions (3) and (6) use observations from all messengers at Veloblitz plus messengers at Flash, another messenger service in Zürich. Thus, the data used for these last two models is combined with the full records from a second messenger service operating in the same market, with which Veloblitz’s total daily revenues are strong correlated. This is done for investigating any effect that the experiment might have had on the nonparticipating messengers at Veloblitz, and
helps to control for demand variations over time. In fact, the treatment dummy in these last two regression still measures something different than before: it measures whether the treated group at Veloblitz behaved differently relative to messengers at Flash. Furthermore, the inclusion of a new dummy variable for the whole non-treated group at Veloblitz (i.e., non-participating messengers plus the control), also allows to measures whether the experiment had an effect on the whole nontreated group at Veloblitz by comparing this group with Flash messenger. The point estimate on this last dummy is in both (3) and (6) small and insignificant, suggesting that the wage increase had no effect on the nontreated group at Veloblitz. This result suggests that the experiment did not constrain the opportunities for working for the nontreated group at Veloblitz (and is consistent with the hypothesis of permanent existence of unfilled shifts). Finally, in both these models, the treatment dummy is significant and of similar size as in the previous regressions.
</p>

<br>

<font size="5">4&nbsp;&nbsp; Difference in Differences</font>

<br>
<br>

<a id='theory4.1'></a>
**4.1** 

<div style="text-align:center">
<img src="https://raw.githubusercontent.com/Helgone/ProForQ/master/Table_2.png" class="center" width="700">
</div>


### Literature

Fehr, E., & Goette, L. (2007). Do Workers Work More if Wages Are High? Evidence from a Randomized Field Experiment. *American Economic Review*, 97 (1): 298-317.

Almond, D., Doyle, J., Kowalski, A. & Williams, H. (2010). Estimating marginal returns to
medical care: Evidence from at-risk newborns. *Quarterly Journal of Economics*, 125 (2): 591-634.

Angrist, J. & Krueger, A. (1991). Does Compulsory School Attendance Affect Schooling and Earnings? *The Quarterly Journal of Economics*, vol. 106(4), pages 979-1014.

Card, D., & Krueger, A. (1994). Minimum Wages and Employment: A Case Study of the Fast-Food Industry in New Jersey and Pennsylvania: Reply. *The American Economic Review*, 90(5), 1397-1420.

### License

<p><img src="https://i.creativecommons.org/l/by-nc/4.0/80x15.png" alt="alt text" title="Creative Commons Licence" /> This work is licensed under a <a href="http://creativecommons.org/licenses/by-nc/4.0/">Creative Commons Attribution-NonCommercial 4.0 International License</a>.</p>




