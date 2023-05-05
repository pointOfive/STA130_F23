
0. Track your hours: you will be filling out timesheets
1. [10-15 hours] Syllabus/Data Wrangling: Review and note any issues you encounter
   - Watch videos (2x speed is available)
   - Review Notebook
   - Do Homework [This is the style of homework you'll be creating -- note time required and potential edits]
   - Review Tutorial [You'll be making tutorials in this same manner]
   - Review Resources [seeing how they were leveraged to create the homework, tutorial, etc.]
2. Create your first homework/tutorial set
   - Lucie
      - The tutorial for *Visualization* should be focused around "describing distributions" using terms like skew, symmetric, unimodal, etc. I am expecting to rely primarily on the tutorial time to communicate these conceptual/conversational terminologies
      - The primary tutorial activity should follow up on the *Data Wrangling* tutorial exercise and be of the same style, using either the oly12countries data set or coffee.csv data set, or another data set that you think best lends itself to plotting and describing data distributions
   - Matthew
      - *Hypothesis Tests* will introduce (one sample) permutation p-values; and, bootstrap confidence intervals will have already been covered, so operationalizing this should be fairly comfortable as a topic for the students. Therefore, we'll also introduce the nonparametric median and the parametric t-test alternatives through their `scipy.stats` function calls. The nonparametric median test is based on the binomial distribution and the t-test is based on a normal distribution, so considering all three tests allows us to compare and contrast simulation, nonparametric, and parametric testing, with the latter two being theoretical but only the t-test requiring a parametric assumption (since the underlying binomial distribution of the median test is not an assumption, but a fact).  The video shows my treatment of this; but, I think the Tutorial should provide a follow up lecture review of how the median and t-test work and how they calculate p-values. 
      - *Two Samples* will reintroduce confidence intervals and the above hypothesis in a two-sample contexts. This is meant to provide a second pass over the hypothesis testing material at a slightly more advanced level.
   - Rohan
      - This will use `statsmodels`; but, I'd also like to see you introduce `scikit-learn` because it not only prepares students for classification but also provides an easy conversation about why `sklearn` (as a predictive machine learning library) doesn't provide any p-values or uncertainty estimation while `statsmodels` does.


|       |Topic            |Designer|Homework                        |Tutorial                         |Notebook                         |Video|Resource|
|-------|-----------------|--------|--------------------------------|---------------------------------|---------------------------------|-----|--------|
|0      |Syllabus         |        |[H1](Homework/STA130_HW_1.ipynb)|[T1](Homework/STA130_TUT_1.ipynb)|[L1](STA130_F23_Syllabus.ipynb)  |     |[HW](https://jupyter.utoronto.ca/hub/user-redirect/git-pull?repo=https%3A%2F%2Fgithub.com%2FpointOfive%2FSTA130_ProblemSet1&urlpath=rstudio%2F&branch=main)/[Tut](https://github.com/quin97/STA130_M1_Tutorial)/[Slides](https://github.com/pointOfive/STA130_Week1_Slides)/[Demo](https://jupyter.utoronto.ca/hub/user-redirect/git-pull?repo=https%3A%2F%2Fgithub.com%2FpointOfive%2FSTA130_Week1_Demo&urlpath=rstudio%2F&branch=main)|
|1      |Data Wrangling   |        |[H2](Homework/STA130_HW_2.ipynb)|[T2](Homework/STA130_TUT_2.ipynb)|[L2](Lecture/STA130_F23_C2.ipynb)|[Part1](https://play.library.utoronto.ca/watch/a3702710d99a41aaea390d46a7349c88)/[Part2](https://play.library.utoronto.ca/watch/dfb0a58bbde24227f5cbdef92fbc7410)|[HW](https://jupyter.utoronto.ca/hub/user-redirect/git-pull?repo=https%3A%2F%2Fgithub.com%2FpointOfive%2FSTA130_ProblemSet3&urlpath=rstudio%2F&branch=main)/[Tut](https://github.com/quin97/STA130_M3_Tutorial)/[Slides](https://github.com/pointOfive/STA130_Week3_Slides)/[Demo](https://jupyter.utoronto.ca/hub/user-redirect/git-pull?repo=https%3A%2F%2Fgithub.com%2FpointOfive%2FSTA130_Week3_Demo&urlpath=rstudio%2F&branch=main)|
|2      |Visualization    |Lucie   |                                |                                 |[L3](Lecture/STA130_F23_C3.ipynb)|[Part1](https://play.library.utoronto.ca/watch/24fdc1887d20fabd6e9f6c3e69b41713)/[Part2](https://play.library.utoronto.ca/watch/db3d10389920a1b9b733e1fb16d37bd3) |
|3      |Bootstrapping    |Lucie   |                                |                                 |[L4](Lecture/STA130_F23_C4.ipynb)|[Part1](https://play.library.utoronto.ca/watch/1eb7ac073b3b0af6ac94f903abe6579a)/[Part2](https://play.library.utoronto.ca/watch/885af59f1afd4253f5ce6883808d465f)/[Part3](https://play.library.utoronto.ca/watch/2d6d1325d8e28111a9ab4c509e19dbde)|
|4      |Hypothesis Tests |Matthew |                                |                                 |                                 |
|5      |Two Samples      |Matthew |                                |                                 |                                 |
|6      |Project/Review   |        |                                |                                 |                                 |
|7      |Midterm          |        |                                |                                 |                                 |
|8      |Reading Week     |        |                                |                                 |                                 |
|9      |Linear Regression|Rohan   |                                |                                 |                                 |
|10     |Multiple Regression|Rohan |                                |                                 |                                 |
|11     |Classification   |        |                                |                                 |                                 |
|12     |Review/Ethics(?) |        |                                |                                 |                                 |

