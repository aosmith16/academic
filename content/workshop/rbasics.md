+++
date = 2020-04-22T00:00:00  # Schedule page publish date.

title = "R basics: a practical introduction to R"
time_start = ""
time_end = ""
abstract = ""
abstract_short = ""
event = "College of Forestry Workshop"
# event_url = ""
location = ""

# Is this a selected talk? (true/false)
selected = false

# Projects (optional).
#   Associate this talk with one or more of your projects.
#   Simply enter the filename (excluding '.md') of your project file in `content/project/`.
# projects = ["deep-learning"]

# Links (optional).
url_pdf = "https://github.com/aosmith16/r-basics-workshop/raw/master/r_basics_workshop_handout.pdf"
url_slides = ""
url_video = ""
url_code = "files/rbasics/r_basics_workshop_script.r"

# Does the content use math formatting?
math = true

# Does the content use source code highlighting?
highlight = true

# Featured image
# Place your image in the `static/img/` folder and reference its filename below, e.g. `image = "example.jpg"`.
[header]
image = ""
caption = ""

+++

This two-hour workshop focuses on introducing R through a worked example.  The scientific goal is to perform a simple statistical analysis on a set of data using R.  While working towards that goal, students will learn how to read three different types of datasets into R, check the datasets and do basic data manipulations, and graph the data.  The workshop will demonstrate some common coding techniques as well as some of the pitfalls that the R beginner faces, such as working with factors and missing values.

We will spend a fair amount of time talking about R help throughout the workshop - where you can find it, how to search for it, and, in particular, how to use the documentation within R. In my experience, knowing how to work with datasets in R and knowing where to look for help can take you pretty far into the world of R.

If you want to run the code you can download the three datasets used in the workshop: [the TXT file](/files/rbasics/temp.txt), [the CSV file](/files/rbasics/spring resp.csv), and [the XLSX file](/files/rbasics/fall resp.xlsx).

I provide an R script that we'll run code from during the workshop as well as  a PDF document.  The PDF is a written version of the workshop, including code and output, to be used as a reference.  Make sure you save the R script as a file ending in `.R` and not as a text document.  You may need to set it to "All Files" and manually add `.R` when saving.

### Interactive tutorials

In addition to the materials above, I have converted the workshop material into four interactive tutorials.  This goes through the information given in the PDF in smaller pieces while you can code interactively.  

The four tutorials are designed to be done in order, but this is not strictly necessary.  Here are the topics covered in the entire workshop series:

- **Tutorial 1: Getting started with R/RStudio**  
After a brief introduction to RStudio, this tutorial focuses on the help documentation available in R and elsewhere and the working directory.  
- **Tutorial 2: Reading data into R**   
You will learn to read three different types of datasets into R and then work on combining them.  You will also learn about installing add-on packages for the first time.
- **Tutorial 3: Factors and missing values**  
Learn about factors in R and how R deals with missing values.  This tutorial also talks about making new variables and saving a dataset as a CSV.
- **Tutorial 4: Graphical data exploration and analysis**  
The last tutorial introduces some basic graphical data exploration using **ggplot2** prior to analysis and, finally, the two-sample analysis.

You have the option to do the first two tutorials online via your browser.  

<a href="https://aosmith.shinyapps.io/part1_rbasics_getting_started/">Tutorial 1: Getting started with R/RStudio</a>  
<a href="https://aosmith.shinyapps.io/part2_rbasics_reading_data/">Tutorial 2: Reading data into R</a>

If you already know a little bit about using R via RStudio, all four tutorials can be run on your own computer.  To do this you will need to have package **learnr** installed (`install.packages("learnr")`). 

Click on a tutorial listed below and save the file as a .Rmd when the download window opens.  Make sure you save it in the same folder as you saved the three workshop datasets.  Open this saved Rmd file with RStudio and click the `Run Document` button at the top to start the tutorial.

<a href="/files/tutorials/part1_getting_started.Rmd" download="tutorial1_rbasics_getting_started.Rmd">Tutorial 1: Getting started with R/RStudio</a>  
<a href="/files/tutorials/part2_reading_data.Rmd" download="tutorial2_rbasics_reading_data.Rmd">Tutorial 2: Reading data into R</a>  

*This work is licensed under a Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International License.*
