---
title: Projects

reading_time: false  # Show estimated reading time?
share: false  # Show social sharing links?
profile: false  # Show author profile?
comments: false  # Show comments?

---
This page documents the projects I have worked on over the years, especially the software. To see in more detail my analyses as a researcher/data scientist, you can go to the [Papers](/papers) section.

I consider the following packages to be my "main" packages. With them, it can be truly said that I was involved in a "end-to-end" development: I have designed them from scratch, I have mathematical expertise in the methods implemented, I have written all the code, documentations and tests. Thus, if you have any questions and/or find a bug, please open a GitHub issue or email me. 


* `kerntools` (Kernel Functions and Tools for Machine Learning Applications): This package provide tools for working (in R) with kernel methods. For instance, it implements several "non-standard" kernels and gives diagnostic tools to study kernel matrices, not only on their own, but also how thay compare to each other. It also allows the user to recover the feature importance of Support Vector Machines (SVMs) models, which was a thing that was available in Python (scikit-learn), but not in R.  You can see a complete explaination of everything `kerntools`  can do (as well of the mathematical foundations of these kernels) at its [website](https://elies-ramon.github.io/kerntools). Furthermore, it is available on [CRAN](https://cran.r-project.org/web/packages/kerntools/index.html), which is something I am very proud of. You can check the [source code](https://github.com/elies-ramon/kerntools/) in Github.

* `kernInt` (Kernel Integration of Microbiome Analysis Methods & Data): This R package was published in a [journal paper](https://www.frontiersin.org/journals/microbiology/articles/10.3389/fmicb.2021.609048/full). The underlying idea of the paper and the package was to propose a novel framework to unify supervised and unsupervised microbiome analyses, that also encompassed single-point data, spatial data, and time series. `kernInt` [source code](https://github.com/elies-ramon/kernInt) is also in GitHub.


Besides, I have also proposed modifications to other R packages:

* `sva-devel` (Surrogate Variable Analysis):  I modified the ComBat function, which adjusts data for batch effects, so it allows the user to adjust separately the training set and a test set. See [Pull Request](https://github.com/jtleek/sva-devel/pull/58) 


---
