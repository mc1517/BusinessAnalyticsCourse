# BusinessAnalyticsCourse
This is a repository to organize the teaching material for a new course at Monash University, to be jointly taught by Di Cook, Rob Hyndman and Souhaib Ben Taieb.

##  Topics

* What is statistical learning?
* Types of models: regression, classification, unsupervised
* Model estimation: numerical optimization
* Model assessment and selection: predictive accuracy
* Resampling methods: bootstrap, permutation, cross-validation, bagging
* Regression: splines, additive models, ridge regression, variable selection, lasso
* High dimension, low sample size: principal components, partial least squares, regularization
* Supervised classification: logistic regression, neural networks, trees, forests, support vector machines, ensembles
* Unsupervised classification: hierarchical clustering, k-means, self-organizing maps, model-based clustering
* Cleaning, exploring and visualizing data

## Tentative agenda

* Week 1. (Jul 27) Introduction and R boot camp (Rob & Souhaib)
  - Lecture 1:  What is Business Analytics? Show case of R.
  - Lab 1: R exercises
  - Lecture 2: Introduction to R programming

* Week 2. (Aug 3) Business Analytics and Statistical Learning. Ch2. (Rob & Souhaib)
  - Lecture 3: More on R and statistical learning. 
  - Lab 2: 
  - Lecture 4: Assessing model accuracy. Bias-variance tradeoff

  Content: 
    - Statistics? Machine learning? data mining? data science? Analytics? 
    - The four V’s of big data/data science
    - Analytics and data science jobs: “By 2018, the US could face a shortage of up to 190.000 workers with analytical skills” McKinsey

* Week 3. (Aug 10) Regression for prediction. Ch3 (Rob)
  - Lecture 5: Review of linear regression, matrix formulation
  - Lab 3:
  - Lecture 6: Subset selection, LOOCV 

* Week 4. (Aug 17) Resampling. Ch5 (Rob)
  - Lecture 7: Cross-validation
  - Lab 4: 
  - Lecture 8: Bootstrap

* Week 5. (Aug 24) Dimension reduction. Ch6,10. (Rob and Souhaib)
  - Lecture 9: PCA
  - Lab 5:
  - Lecture 10: PLS

* Week 8. (Aug 31) Classification. Ch4,8 (Souhaib & Di)
  - Lecture 11: LDA
  - Lab 6:
  - Lecture 12: Trees

* Week 6. (Sep 7) Visualization. Own lecture notes. (Di)
  - Lecture 15: Basic data plots, categorical/numeric variables, facetting
  - Lab 8:
  - Lecture 16: Data cleaning
* Week 7. (Sep 14) Visualization. Own lecture notes. (Di)
  - Lecture 17: Plotting geographic data
  - Lab 9:
  - Lecture 18: Plotting multivariate data
  
* Week 9. (Sep 21) Classification. Ch4,9. (Souhaib & Di)
  - Lecture 13: k-NN
  - Lab 7:
  - Lecture 14: SVM

* Week 10. (Oct 5) Advanced classification. Ch8. (Di & Souhaib)
  - Lecture 19: Bagging
  - Lab 10:
  - Lecture 20: Boosting, random forests

* Week 11. (Oct 12) Advanced regression. Ch6. (Di & Souhaib)
  - Lecture 21: Regularization
  - Lab 11:
  - Lecture 22: Shrinkage

* Week 12. (Oct 17) Clustering. Ch10. (Souhaib & Di)
  - Lecture 23: k-means
  - Lab 12:
  - Lecture 24: hierarchical clustering
  
## Textbook: 

James, Witten, Hastie, Tibshirani, An Introduction to Statistical Learning and Applications in R, Springer, 2013 (pdf available at http://www-bcf.usc.edu/~gareth/ISL/)
          
### Additional Reading: 
  
  *  Xie, Yihui
        Dynamic Documents with R and knitr
        Chapman and Hall/CRC
        2013
        http://yihui.name/knitr/
                      
  * Wickham, Hadley
        ggplot2: Elegant Graphics for Data Analysis
        Springer
        2009
        http://ggplot2.org/
        
  * Cook, Swayne
        Interactive and Dynamic Graphics for Data Analysis: With Examples Using R and GGobi
        Springer
        2007
        http://www.ggobi.org/book/
        
  * Chang, Winston
        R Graphics Cookbook
        O'Reilly
        2013
        http://www.cookbook-r.com/Graphs/
        
  * Grolemund, Garret
        Hands-On Programming with R
        O'Reilly
        2014
        https://github.com/garrettgman
        
  * Journal articles/web links:
      Analyzing the housing bubble in San Francisco http://vita.had.co.nz/papers/bay-area-blues.pdf
      
      .... 

## Software:
* R/RStudio (these packages with all the dependencies)
  - ggplot2, scales, stringr, plyr, dplyr, tidyr, reshape2, GGally, dichromat, magrittr, munsell, RColorBrewer, colorspace, wordcloud, vcd, gridExtra, hexbin, ggdendro, shiny, ggvis, ggsubplot
  - MASS, e1071, caret, randomForest, kohonen, cluster, fpc, mclust, rpart, nnet, nlme, vegan, penalizedLDA, PPTree, class, FNN, RSNNS, DMwR
  - mvtnorm, mvnormtest, HH, ICSNP, matrixStats, schoRsch, Matrix, psych
  - lubridate, tm, tuneR, caTools, maps, ggmap, maptools, shapefiles, sp, ggmap, rworldmap
  - rmarkdown, knitr, devtools, roxygen2, profr
  - gwidgets, RGtk2, MissingDataGUI
  - foreign, jsonlite, curl, RCurl, rvest, Rcpp, XML, twitteR
  - xtable
  - classifly, clusterfly, meifly, LCA, LDAvis, nullabor

* Weka ? -- perhaps just mention that software other than R exists. It is too much to get them to learn more than one language in this unit.
      
## Approach to teaching R? 

Use Rmarkdown lecture notes like http://dicook.github.io/stat585/, and this should help students get comfortable with R themselves. (Ignore the ugly web site design!)

and material at this site: http://www.stat.iastate.edu/ccgs/short-courses/
        
## Rmarkdown slides

Use RStudio, create a new project in your git directory (BusinessAnalyticsCourse), and open the slides/1-intro.Rmd. 

On the interface you should see a "knitHTML" button. Click this to compile and preview the slides.
