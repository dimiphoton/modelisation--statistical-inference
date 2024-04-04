# inference and modelling



# introduction


 understand that modeling is [Build, compute, critique, repeat] (./nb01-box-loop.ipynb)

 in this notebook are introduced:
 - log likelihood
 - mcmc sampling with emcee
 - *corner plot* with corner 

<br> Reading: Blei, [Build, Compute, Critique, Repeat](http://www.cs.columbia.edu/~blei/fogm/2020F/readings/Blei2014.pdf), 2014 [Section 1]<br>

# 2. miscs

- numpy [ notebook](./nb02-tables.ipynb)
- Data wrangling [notebook](./nb03-data-wrangling.ipynb)
- Visualization [sidenotes](./pdf/lec03-sidenotes.pdf)
- Plots [notebook](./nb04-plots.ipynb)
-  Visualizing high-dimensional data [[notebook](./nb05-high-dimensional-data.ipynb)] [Ten Simple Rules for Better Figures](https://journals.plos.org/ploscompbiol/article/file?id=10.1371/journal.pcbi.1003833&type=printable), 2014

# 3. modeling



## Bayesian probabilistic modeling [[sidenotes](./pdf/lec04-sidenotes.pdf)]

![symbols](https://revbayes.github.io/tutorials/intro/figures/graphical_model_legend.png)

Latent variable models [[notebook](./nb06-latent-variable-models.ipynb)]
Gelman et al, [Bayesian workflow](https://arxiv.org/abs/2011.01808), 2020 [Sections 1 and 2]
Blei, [Build, Compute, Critique, Repeat](http://www.cs.columbia.edu/~blei/fogm/2020F/readings/Blei2014.pdf), 2014 [Sections 2 and 3] |
| October 24 | Lecture 5: Expectation-Minimization [[sidenotes](./pdf/lec05-sidenotes.pdf)]<br>`nb07`: Expectation-Maximization [[notebook](./nb07-em.ipynb)]<br>Reading: Dempster et al, [Maximum Likelihood from Incomplete Data via EM](https://www.jstor.org/stable/2984875), 1977 |
| October 31 | Homework 1: [Explore the Argo data](https://github.com/glouppe-teaching/dats0001-hw1) |
| November 7 | Lecture 6: Variational inference [[sidenotes](./pdf/lec06-sidenotes.pdf)]<br>`nb08`: ADVI [[notebook](./nb08-advi.ipynb)]<br>Reading: Kucukelbir et al, [Automatic Differentiation Variational Inference](https://arxiv.org/abs/1603.00788), 2016  |
| November 14 | Lecture 7: Markov Chain Monte Carlo [[sidenotes](./pdf/lec07-sidenotes.pdf)]<br>`nb09`: Markov Chain Monte Carlo [[notebook](./nb09-mcmc.ipynb)]<br>Reading: Gelman et al, [Bayesian Data Analysis, 3rd](http://www.stat.columbia.edu/~gelman/book/BDA3.pdf), 2021 [Chapter 11] |
| November 21 | Lecture 8: Model criticism<br>`nb10`: Model checking [[notebook](./nb10-model-checking.ipynb)]<br>`nb11`: Model comparison [[notebook](./nb11-model-comparison.ipynb)]<br>Reading: Gelman et al, [Bayesian Data Analysis, 3rd](http://www.stat.columbia.edu/~gelman/book/BDA3.pdf), 2021 [Chapters 6 and 7] |
| November 28 | _No class_ |
| November 28 | Homework 2: [Random walks of Argo floats](https://github.com/glouppe-teaching/dats0001-hw2) |
| December 5  | _No class_ |
| December 12 | Lecture 9: Wrap-up case study<br>`nb12`: Space Shuttle Challenger disaster [[notebook](./nb12-space-shuttle-disaster.ipynb)]<br>Reading: Cam Davidson-Pilon, [Bayesian Methods for Hackers](https://camdavidsonpilon.github.io/Probabilistic-Programming-and-Bayesian-Methods-for-Hackers/#contents), 2015 [Chapter 2]  |
| Decembber 12 | Homework 3: [Posterior inference over random walks](https://github.com/glouppe-teaching/dats0001-hw3) | 
| Decembber 17-21 | Exam-at-home | 

## Homeworks

- Homework 1: [Explore the Argo data](https://github.com/glouppe-teaching/dats0001-hw1) (due by October 31)
- Homework 2: [Random walks of Argo floats](https://github.com/glouppe-teaching/dats0001-hw2) (due by November 28)
- Homework 3: [Posterior inference over random walks](https://github.com/glouppe-teaching/dats0001-hw3) (due by December 12)
- Exam-at-home: TBD (sent on December 17, due by December 21)