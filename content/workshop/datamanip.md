+++
date = 2020-03-25T00:00:00  # Schedule page publish date.

title = "Data Manipulation in R"
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
url_pdf = "https://github.com/aosmith16/data-manipulation-workshop/blob/master/data_manipulation_workshop_handout.pdf"
url_slides = ""
url_video = ""
url_code = "https://raw.githubusercontent.com/aosmith16/data-manipulation-workshop/master/data_manipulation_workshop_script.r"

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

An introduction to data manipulation in R via **dplyr** and **tidyr**.

This two-hour workshop is aimed at graduate students who have been introduced to R in statistics classes but haven’t had any training on how to work with data in R. 

The workshop covers how to:

- Make data summaries by group  
- Filter out rows  
- Select specific columns  
- Add new variables  
- Change the format of datasets (i.e., *reshape* datasets)  
- Join datasets together  

Along the way students learn how to use the pipe operator to chain several data manipulation steps together. Students have time to practice data manipulation and reshaping using the `babynames` dataset from package **babynames**.

I provide an R script that we'll run code from during the workshop as well as  a PDF document.  The PDF is a written version of the workshop, including code and output, to be used as a reference.

### Interactive tutorials

In addition to the materials above, I have converted the workshop material into three interactive tutorials that can be run on your own computer.  To use this you will need to have package **learnr** installed (`install.packages("learnr")`).  

Click on a tutorial listed below and save the file as a .Rmd when the download window opens.  Open this saved Rmd file with RStudio and click the `Run Document` button at the top to start the tutorial.

<a href="/files/tutorials/part2_reshaping_data.Rmd" download="tutorial2_reshape.Rmd">Tutorial 2: Reshaping</a>  
<a href="/files/tutorials/part3_joining_two_datasets.Rmd" download="tutorial3_joins.Rmd">Tutorial 3: Joins</a>
