# R to Python: An Overview  

## Introduction 

Over the next nine lessons, you will learn about the programming language R!

## Objectives

By the end of this lesson you will be able to 

* [ ] Explain why a data scientist might want to know both R and Python 
* [ ] List common misconceptions about all things R vs Python
* [ ] Identify parallel packages in a data scientist's workflow between R and Python

## R 


* [ ] Explain why a data scientist might want to know both R and Python 
- Better to know more than one language
- Just like plumber wants different tools, so do you
- Both R and Python were developed for different reasons, so going to have differences
- As learn to be bilingual, going to have moments where "but thats not how you do it in Python"
- Yes, because that is not Python 

* [ ] List common misconceptions about all things R vs Python
- R, though turing complete, is specialized for people who work with numbers
- Langauge of academics and because of that often can find more out there stuff faster
- In additon to that, it's very fast to chomp through data
- and hope you find that it's fast to write and read (especially getting into tidyverse) new exciting

* [ ] Identify parallel packages in a data scientist's workflow between R and Python
- Having been through all of FIS now, you know a lot more about programming
- While a beginner at R, notice as you work thorugh this material how much faster it was than week 1 of FIS
- As when you start first job, at this point want to lead with your strengths
- Already have an idea of python world
- Going to try to build that knowledge as scaffolding
- Eventually you will stop thinking of things like "dplyr is the pandas of R"
- and important to throw away that thinking when we are done because they are quite different
- This process will also be helpful if you ever also learn Julia 

- Start with narrative of what your typical ds workflow looks like
- introduce narrative 
- log on to computer, want to clean some data and convert tips 
- might fire up jupyter notebooks from command line
- Choose that you want a python 3 notebook 
- then once running, start analysis by importing in the good ol boys
- grab pandas for panel data
- load in matplot lib or seaborn for visualzing 
- Then you load a csv, make a couple of manipulations
- save both your images and manipulated data

* Python Code 

- What does this look like in R?
- still log on with goal of answering quetions (in this case with LR) 
- instead of jupyter notebook (that does do R), intead open up RStudio IDE.
- Instead of icking python 3 file, reach for RMarkdown file
- insead of import pandas, now go for library(dplyr) ggplot2 
- still do some manipulations we'll see
- save it out 

* R Code 

TABLE HERE OF THE TRANSLATION 

- Just have the terms here and don't have to get code.
- Hopefully can get an idea of what is going on in the R code, though not know name for it.
- New symbolys, the <- sign , no .methods
- Going to build up to understanding this in next few lessons 



As you navigate the world of data science you probably have noticed that Python isn't the only programming language that people use to do their job.
In addition to Python, many people use a programming language called R in their daily workflows.
R, being a completely differnt programming language than Python,
