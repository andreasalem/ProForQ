
## Programming for Quantitative Analysis

This is the companion website for the final project within the course
<br>
<center><b> 4,796: Skills: Programming for Quantitative Analysis</b> </center> 
<br>
taught by Prof. Valladares‑Esteban. The project which has been submitted from my part revolves around the use of Python for empirical economic research. The main body of the project is part of the Jupyter Notebook file contaning the code. This website serves to extend certain explanations and enrich the the project with extra material not present in the Notebook file.

<font size="5">Table of Contents</font>  

1. [Introduction to Impact Evaluation](#introduction)


2. [Technical Set-Up](#setup)

Nothing to note here.

3. [Randomized Field Experiments](#RCT)  
&nbsp;&nbsp;&nbsp;3.1 [Theory](#theory3.1)


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

<a id='theory3.1'></a>
**3.3**

<div style="text-align:center">
<img src="https://raw.githubusercontent.com/Helgone/ProForQ/master/Table1.png" class="center" width="1950">
</div>

As we can see from the table, the authors estimate three different models per outcome. What changes across models? First of all the data used in the calculations is different in each model. Regressions (1) and (4) are based only on the data of groups A and B (participating messengers) at Veloblitz. Due to the random assignment of the participating messengers, and due to the fact that both groups served once as a control and once as a treatment group, these two regressions allow for a clear isolation of the treatment effect of the 25% increase of the commission rate on total revenues and on the number per shifts.
Regressions (2) and (5) instead, compare the experimental treatment group at Veloblitz with all other messengers at Veloblitz, not only with the experimental control group. This means that now the treatment dummy compares the treated with the whole group of untreated messengers at Veloblitz. Concerning total revenues, regression (2) again finds a large and significant treatment effect on total revenues of roughly CHF 1,000; concerning shifts, regression (5) also practically
replicates the results from regression (2), finding that the treated group works on average four shifts more than the control group.
Finally, regressions (3) and (6) use observations from all messengers at Veloblitz plus messengers at Flash, another messenger service in Zürich. Thus, the data used for these last two models is combined with the full records from a second messenger service operating in the same market, with which Veloblitz’s total daily revenues are strong correlated. This is done for investigating any effect that the experiment might have had on the nonparticipating messengers at Veloblitz, and
helps to control for demand variations over time. In fact, the treatment dummy in these last two regression still measures something different than before: it measures whether the treated group at Veloblitz behaved differently relative to messengers at Flash. Furthermore, the inclusion of a new dummy variable for the whole non-treated group at Veloblitz (i.e., non-participating messengers plus the control), also allows to measures whether the experiment had an effect on the whole nontreated group at Veloblitz by comparing this group with Flash messenger. The point estimate on this last dummy is in both (3) and (6) small and insignificant, suggesting that the wage increase had no effect on the nontreated group at Veloblitz. This result suggests that the experiment did not constrain the opportunities for working for the nontreated group at Veloblitz (and is consistent with the hypothesis of permanent existence of unfilled shifts). Finally, in both these models, the treatment dummy is significant and of similar size as in the previous regressions.




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

### License

<p><img src="https://i.creativecommons.org/l/by-nc/4.0/80x15.png" alt="alt text" title="Creative Commons Licence" /> This work is licensed under a <a href="http://creativecommons.org/licenses/by-nc/4.0/">Creative Commons Attribution-NonCommercial 4.0 International License</a>.</p>




