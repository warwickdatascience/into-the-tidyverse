# Into the Tidyverse

_Session material and solutions for the Into the Tidyverse course taught by WDSS_

Spotted a mistake, dead link, or have suggestions for improvements? Report these [here](https://github.com/warwickdatascience/into-the-tidyverse/issues/new)

Navigation:

* [FAQs](#faqs)
* [About This Repository](#about-this-repository)
* [About the Course](#about-the-course)
* [Getting Started](#about-the-course)
* [Quick Access to Resources](#quick-access-to-resources)
* [Session Summaries](#session-summaries)
* [Additional Content](#additional-content)
* [Help](#help)
* [Contact](#contact)

## FAQs

### The Tidy-what?

The tidyverse is a collection of tools for the programming language R used for working with data. It was designed from the ground up to have a clear and consistent design philosophy, making it as easy as possible to learn how to work with data. From data importing, to cleaning, and visualisation to modelling, the tidyverse has you covered. If you are looking for a way to step up from tools such as Excel, Tableau, and PowerBI with as little difficulty as possible, the tidyverse welcomes you.

### What are the prerequisites for the course?

Nothing but a passion to learn!

## About This Repository

This repository contains slides, exercise sheets, and solution sheets for WDSS's course, 'Into the Tidyverse'. The material is aimed at anyone new to R or even programming in general. The repository is designed to be completely self-contained, with any images and data used in the presentations or exercises included in each session's data folder. You can use the navigation links below to find relevant resources and below that, a few words of guidance can be found.

## About the Course

'Into the Tidyverse' does exactly what it says on the tin. This is an intensive 5-week course which aims to take someone from a coding-zero to tidyverse-hero in as little time as possible. Each session is composed of a rapid-fire presentation introducing different elements of the tidyverse as well as an exercise sheet to help consolidate the ideas presented in the slideshow.

For more information on the structure and contents of this course, please take a look at the following [introductory presentation](https://github.com/warwickdatascience/into-the-tidyverse/raw/master/Course%20Summary.pptx).

The contents of the teaching sessions are designed to be dense so don't worry if everything seems a bit intimidating. It takes far too long to memorise the exact function calls and parameter names of a new programming language, and so we don't make any attempt to teach this. Instead, the goal of this course is to have a scan through the tidyverse landscape and point out some of the key landmarks. Since the contents of the presentations are so dense, they become a good reference guide. Then, all you need to do is remember where to find those landmarks and look up the specifics of what you are trying to do as you go. This is often how real junior programmers work and you shouldn't be ashamed of doing so too; in fact I'd argue that it is one of the best ways to learn.

My main word of guidance is 'practice'. Practice, practice, practice. You can read through these slides as many times as your heart disires and it is likely most of it will soon be forgotten. Instead, scan through the presentations so you know what tools are available and where to find them and then get straight onto the exercise sheets. If you reach a hurdle, have a look back through the slides. Wash, rinse, repeat and soon you'll by a tidyverse star!

## Getting Started

This course will use an editor called RStudio. You have two options:

1. Download and install first [R](https://www.r-project.org/) and then [RStudio](https://rstudio.com/) on your local machine
2. Sign up for [RStudio Cloud](https://rstudio.cloud/)

I would advise the former if you have install rights on your computer. It is slightly more faffy to setup than the latter option but will be more stable in the long-run. If you have any trouble with this, [give me a shout](#general-help).

## Quick Access to Resources

Below you can find links to the content for each session. Our material is all ready to go and we will add links for each session at the beginning of the week.

Note, that when attempting to download data for a given session, your browser may attempt to open CSVs directly. If this is the case, either right-click and select 'save as' or use `ctrl-S` to save a local copy.

### Session One

* [Video](https://www.youtube.com/watch?v=axTOsjiXf1U)

* [Presentation](https://warwickdatascience.github.io/into-the-tidyverse/resources/session_one/session_one_presentation.html)

* [Exercises](https://warwickdatascience.github.io/into-the-tidyverse/resources/session_one/session_one_exercises.nb.html#/)

* [Solutions](https://warwickdatascience.github.io/into-the-tidyverse/resources/session_one/session_one_solutions.nb.html#/)


### Session Two

* [Video](https://youtu.be/j9ih_9A4eS4)

* [Presentation](https://warwickdatascience.github.io/into-the-tidyverse/resources/session_two/session_two_presentation.html)

* [Data](https://github.com/warwickdatascience/into-the-tidyverse/tree/master/resources/session_two/data)

* [Exercises](https://warwickdatascience.github.io/into-the-tidyverse/resources/session_two/session_two_exercises.nb.html#/)

* [Solutions](https://warwickdatascience.github.io/into-the-tidyverse/resources/session_two/session_two_solutions.nb.html#/)


### Session Three

* [Video](https://youtu.be/qaxuDRAXNAI)

* [Presentation](https://warwickdatascience.github.io/into-the-tidyverse/resources/session_three/session_three_presentation.html)

* [Data](https://github.com/warwickdatascience/into-the-tidyverse/tree/master/resources/session_three/data)

* [Exercises](https://warwickdatascience.github.io/into-the-tidyverse/resources/session_three/session_three_exercises.nb.html#/)

* [Solutions](https://warwickdatascience.github.io/into-the-tidyverse/resources/session_three/session_three_solutions.nb.html#/)


### How to complete the homework using R notebooks? - [Video](https://youtu.be/4AEf44rLjV0)

## Session Summaries

### Session 1

* Understanding R, RStudio, and the tidyverse
* Basic scatter plots
* Exploring datasets
* Using aesthetics
* Faceted plots

### Session 2

* Using R as a calculator
* Objects and functions
* Reading CSV files
* Reading Excel, SAS, SPSS, and STATA files
* Creating line plots

### Session 3

* Using R for statistics
* Comparisons and Boolean operators
* Manipulating datasets
* Grouped dataframes
* Piping

### Session 4

* Tidy data
* Pivoting data
* Uniting and separating columns
* Relational data

### Session 5

* Saving plots and dataframes
* Statistical transformations
* Positional adjustments
* Coordinate systems
* Theming

## Help

### Importing Datasets

To import a dataset from this repository, you will first need to download it. You can do this by clicking on one of the data links above. Then select the file of interest. You should then be taken to a page showing a preview of the file. Select `raw` from the top menu. This will open a pure text version of the file. Right-click or use `crtl-S` to save the file to someone on your hard drive.

You can then import this into R by setting your working directory to either the folder containing the file or a directory containing it and then specifying the correct relative path. 

If you are use RStudio cloud, you will need to open the `Files` panel and select `upload` to add the file to your workspace.

### General Help

If you are taking this course through WDSS, your first port of call for any issues is your mentor. They will be able to handle the majority of issues and can elevate any particulary troublesome or important ones.

If you are self-teaching, feel free to reach out to Tim Hargreaves (the content author) on [LinkedIn](https://www.linkedin.com/in/tim-hargreaves/).

## Contact

This course was written and initially taught by [Tim Hargreaves](https://www.linkedin.com/in/tim-hargreaves/). 

The current course directory is [Kasia Kobalczyk](https://www.linkedin.com/in/katarzyna-kobalczyk/). 

For general enquires, reach out to hello@warwickdatascience.com.

### Socials

* [Facebook](https://rebrand.ly/wdss-facebook)
* [LinkedIn](https://rebrand.ly/wdss-linkedin)
* [Instagram](https://rebrand.ly/wdss-instagram)
* [YouTube](https://rebrand.ly/wdss-youtube)

