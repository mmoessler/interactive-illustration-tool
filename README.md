# interactive-illustration-tool

This repository contains a template to create an *interactive illustration tool*

## Motivation

<!-- general -->
The aim was to create a simple tool that meets the needs of students and teachers:

* Needs of students:
  * Intuition for abstract concepts using an interactive illustration tool.
  * Combination of verbal or mathematical expression, interactions and animations w/o audio explanations.
* Needs of teachers:
  * Easy to implement and to deploy.
  * No specific software or software framework necessary.

<!-- particular -->
An interactive illustration tool to provide intuition for otherwise abstract statistical concepts such as:

* Expected value and sample average
  * [Module 1) Bernoulli distribution and sample average](https://raw.githack.com/mmoessler/illustration-statistical-concepts/main/ber-dis-sam-ave/ber_dis_sam_ave.html)
  * [Module 2) Continuous uniform distribution and sample average](https://raw.githack.com/mmoessler/illustration-statistical-concepts/main/con-uni-dis-sam-ave/con_uni_dis_sam_ave.html)
* Simple linear regression model and OLS estimator
  * [Module 3) Sampling distribution and sample size](https://raw.githack.com/mmoessler/illustration-statistical-concepts/main/cs-lin-reg-ols-01/cs_lin_reg_ols_01.html)
  * [Module 4) Sample size and parameterization of the DGP](https://raw.githack.com/mmoessler/illustration-statistical-concepts/main/cs-lin-reg-ols-02/cs_lin_reg_ols_02.html)
  * [Module 5) Effect of Heteroskedasticitiy](https://raw.githack.com/mmoessler/illustration-statistical-concepts/main/cs-lin-reg-ols-03/cs_lin_reg_ols_03.html)
  * [Module 6) Effect of Omitted Variables](https://raw.githack.com/mmoessler/illustration-statistical-concepts/main/cs-lin-reg-ols-04/cs_lin_reg_ols_04.html)

The modules can be provided individually (see links above) or combined (see link below):

* [Interactive and animated illustration tool for statistical concepts](https://raw.githack.com/mmoessler/illustration-statistical-concepts/main/index.html)

## (Non-technical) Instructions

Instructions for creating an *interactive illustration tool* using some prepared templates can be found here,

```
https://raw.githack.com/mmoessler/interactive-illustration-tool/main/index.html
```

Note, step 4 is only relevant for the integration into [*ILIAS*](https://www.ilias.de/).

An integration for the University of Hohnheim can be found here:

```
https://ilias.uni-hohenheim.de/data/UHOH/lm_data/lm_1875758/interactive-illustration-tool/index.html
```

Underlying concept

* The tool works like a ``flip book''.

* The tool works like a ``flip book''.
* One only need to generate different numbers for different ``parameterizations'' and name them accordingly.

## (More technical) Explanations

* This tool is based on, respectively, is a static website or web app ([see, e.g., w3schools.com](https://www.w3schools.com/howto/howto_website_static.asp)).
* Advantages:
  * It does not require server-side software dependencies such as php or node to build on.
  * It is easy to ship and deploy, e.g., via *ILIAS Learning Modules HTML*, because of no server-side software dependencies.
  * I think *ILIAS Learning Modules HTML* are the most underated feature tool in ILIAS. For more information [see, e.g., iliastutorials.com](https://iliastutorials.com/html-learning-module/).
* Disadvantages:
  * No dynamic interaction, e.g. with a server-side database possible.
  * [see, e.g., geeksforgeeks.org](https://www.geeksforgeeks.org/static-vs-dynamic-website/).
* Note: ``static'' does not mean that it is not interactive. The interactive features of static webpages or web apps relies on client-sider javascript rendering. My impression is that client-side javascript rendering is getting more and more powerful.

## Licence

This project is part of the [DeLLFi](https://www.uni-hohenheim.de/en/project-dellfi) (Integrating digitalization along teaching, learning, and research) project of the University of Hohenheim and funded by [Foundation for Innovation in University Teaching](https://stiftung-hochschullehre.de/)

The materials may be used and further developed for teaching purposes with credit to the author and funding and under the terms of the license (see below).

<hr>

<a rel="license" href="http://creativecommons.org/licenses/by-nc-sa/4.0/">
<img alt="Creative Commons License" style="border-width:0" src="https://i.creativecommons.org/l/by-nc-sa/4.0/88x31.png" />
</a>

<br />

This work is licensed under a
<a rel="license" href="http://creativecommons.org/licenses/by-nc-sa/4.0/">Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International License
</a>.