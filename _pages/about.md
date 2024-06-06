---
permalink: /
title: "About me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

Yuan Wang received the B.E. and Ph.D. degrees in automation science from Northeastern University, China, in 2013 and 2019, respectively. He was a Post-Doctoral Fellow with the School of Data Science, The Chinese University of Hong Kong, Shenzhen (CUHK-Shenzhen), Shenzhen, China. He is currently a Senior Engineer with the Shenzhen Research Institute of Big Data, Shenzhen.

Research Interests
======
1. Mixed-Integer Linear Programming
2. Mathematical Optimization Solver Development
3. Production Planning and Scheduling
4. Reinforcement Learning
5. Air Traffic Flow Management


Publication
======
1. Wang Y, Cai W, Tu Y, Mao J. Reinforcement-Learning-Informed Prescriptive Analytics for Air Traffic Flow
Management[J]. IEEE Transactions on Automation Science and Engineering, 2023. (SCI 检索，JCR2 区，
TOP 期刊)
2. Wang Y, Zhang ZX, Nan X, Xiaodong Luo. Feasibility Convex Successive Approximation for 0-1 Mixedinteger Linear Programming[J]. Informs Journal on Computing (Major Revision)
3. Wang Y, Luo X, Zhang F, et al. GPU-based model predictive control for continuous casting spray cooling
control system using particle swarm optimization[J]. Control Engineering Practice, 2019, 84(3): 349-364.
(SCI 检索，JCR2 区)
4. Wang Y, Luo X, Song Y, et al. Simultaneous reconstruction of the surface heat flux and the source term
in 3D linear parabolic problem by modified conjugate gradient method[J]. Mathematical Methods in the
Applied Sciences, 2017, 40(8): 2847-2858. (SCI 检索，JCR1 区)
5. Wang Y, Luo X, Yu Y, et al. Evaluation of heat transfer coefficients in continuous casting under large disturbance by weighted least squares Levenberg-Marquardt method[J]. Applied Thermal Engineering, 2017,
111: 989-996. (SCI 检索，JCR1 区，TOP 期刊)
6. Wang Y, Luo X, Yu Y, et al. Optimal control of twoffdimensional parabolic partial differential equations
with application to steel billets cooling in continuous casting secondary cooling zone[J]. Optimal Control
Applications and Methods, 2016, 37(6): 1314-1328. (SCI 检索，JCR2 区)
7. Wang Y, Luo X, Li S. Optimal control method of parabolic partial differential equations and its application
to heat transfer model in continuous cast secondary cooling zone[J]. Advances in Mathematical Physics,
2015, 2015. (SCI 检索，JCR3 区)
8. Luo X, Xie Q, Wang Y, et al. Estimation of heat transfer coefficients in continuous casting under large
disturbance by Gaussian kernel particle swarm optimization method[J]. International Journal of Heat and
Mass Transfer, 2017, 111(5): 1087-1097. (SCI 检索，JCR1 区, TOP 期刊)
9. Yu Y, Luo X, Wang Y, et al. Estimation of boundary condition of two-dimensional nonlinear PDE with
application to continuous casting[J]. Computers & Mathematics with Applications, 2020, 80(12): 3082- 3097. (SCI 检索，JCR2 区, TOP 期刊)
10. Cui H, Luo X, Wang Y. Scheduling of steelmaking-continuous casting process using deflected surrogate
Lagrangian relaxation approach and DC algorithm[J]. Computers & Industrial Engineering, 2020, 140(10):
106-119. (SCI 检索，JCR1 区, TOP 期刊)
11. Cui H, Luo X, Wang Y. Scheduling of steelmaking-continuous casting process with different processing
routes using effective surrogate Lagrangian relaxation approach[J]. International Journal of Production Research, 2021: 1-26. (SCI 检索，JCR1 区, TOP 期刊)
12. Zhang Z, Wang Y, Liu C. Multihoming effect on the two-sided platform of second-hand cars[J]. Computers
& Industrial Engineering, 2023, 179: 109160. (SCI 检索，JCR1 区, TOP 期刊)
13.  Qian X, Mao J, Wang Y, et al. A column generation-based framework for ATFM incorporating a userdriven prioritization process[J]. Transportmetrica B: Transport Dynamics, 2023, 11(1): 1642-1663. (SCI
检索，JCR3 区)
14. Zhang Z, Wang Y. New-arrival or second-hand? A direct-to-consumer business model for electric vehicles
in the sustainable transportation[J]. Energy Reports, 2023, 10: 3035-3038. (SCI 检索，JCR2 区)
15. Wang H, Luo X, Wang Y. Identification of heat transfer coefficients in continuous casting by a GPUbased improved comprehensive learning particle swarm optimization algorithm[J]. International Journal of
Thermal Sciences, 2023, 190: 108284. (SCI 检索，JCR1 区)


Project 
------
The main configuration file for the site is in the base directory in [_config.yml](https://github.com/academicpages/academicpages.github.io/blob/master/_config.yml), which defines the content in the sidebars and other site-wide features. You will need to replace the default variables with ones about yourself and your site's github repository. The configuration file for the top menu is in [_data/navigation.yml](https://github.com/academicpages/academicpages.github.io/blob/master/_data/navigation.yml). For example, if you don't have a portfolio or blog posts, you can remove those items from that navigation.yml file to remove them from the header. 

Create content & metadata
------
For site content, there is one markdown file for each type of content, which are stored in directories like _publications, _talks, _posts, _teaching, or _pages. For example, each talk is a markdown file in the [_talks directory](https://github.com/academicpages/academicpages.github.io/tree/master/_talks). At the top of each markdown file is structured data in YAML about the talk, which the theme will parse to do lots of cool stuff. The same structured data about a talk is used to generate the list of talks on the [Talks page](https://academicpages.github.io/talks), each [individual page](https://academicpages.github.io/talks/2012-03-01-talk-1) for specific talks, the talks section for the [CV page](https://academicpages.github.io/cv), and the [map of places you've given a talk](https://academicpages.github.io/talkmap.html) (if you run this [python file](https://github.com/academicpages/academicpages.github.io/blob/master/talkmap.py) or [Jupyter notebook](https://github.com/academicpages/academicpages.github.io/blob/master/talkmap.ipynb), which creates the HTML for the map based on the contents of the _talks directory).

**Markdown generator**

I have also created [a set of Jupyter notebooks](https://github.com/academicpages/academicpages.github.io/tree/master/markdown_generator
) that converts a CSV containing structured data about talks or presentations into individual markdown files that will be properly formatted for the Academic Pages template. The sample CSVs in that directory are the ones I used to create my own personal website at stuartgeiger.com. My usual workflow is that I keep a spreadsheet of my publications and talks, then run the code in these notebooks to generate the markdown files, then commit and push them to the GitHub repository.

How to edit your site's GitHub repository
------
Many people use a git client to create files on their local computer and then push them to GitHub's servers. If you are not familiar with git, you can directly edit these configuration and markdown files directly in the github.com interface. Navigate to a file (like [this one](https://github.com/academicpages/academicpages.github.io/blob/master/_talks/2012-03-01-talk-1.md) and click the pencil icon in the top right of the content preview (to the right of the "Raw | Blame | History" buttons). You can delete a file by clicking the trashcan icon to the right of the pencil icon. You can also create new files or upload files by navigating to a directory and clicking the "Create new file" or "Upload files" buttons. 

Example: editing a markdown file for a talk
![Editing a markdown file for a talk](/images/editing-talk.png)

For more info
------
More info about configuring Academic Pages can be found in [the guide](https://academicpages.github.io/markdown/). The [guides for the Minimal Mistakes theme](https://mmistakes.github.io/minimal-mistakes/docs/configuration/) (which this theme was forked from) might also be helpful.
