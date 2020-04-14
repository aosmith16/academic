+++
date = 2020-04-03T00:00:00  # Schedule page publish date.

title = "Graphics with ggplot2"
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
url_pdf = "https://github.com/aosmith16/ggplot2-graphics-workshop/blob/master/graphics_with_ggplot2_workshop_handout.pdf"
url_slides = ""
url_video = ""
url_code = "https://raw.githubusercontent.com/aosmith16/ggplot2-graphics-workshop/master/graphics_with_ggplot2_script.r"

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

This two-hour workshop focuses on introducing students to the **ggplot2** package in R for making graphics. 

The first half of the workshop focuses on learning the syntax and terminology used in ggplot2 while making a series of simple, exploratory plots with a built in dataset.  The goal of this section is to expose students to many different kinds of graphs as well as cover some of the common pitfalls folks run into when first using **ggplot2**.

In the second half of the workshop we focus on controlling the overall appearance of a graphic when making “publication-ready” plots.  We'll go through the code to create two fairly complicated graphics, building each one layer by layer so students can see how the plot changes with each addition.  Students will also see some data manipulation to *reshape* a dataset prior to plotting, which is often necessary when plotting data with **ggplot2**.   

I provide an R script that we'll run code from during the workshop as well as a PDF document.  The PDF is a written version of the workshop, including code and output, to be used as a reference.

### Interactive tutorials

In addition to the materials above, I have converted the workshop material into three interactive tutorials that can be run on your own computer.  To use this you will need to have package **learnr** installed (`install.packages("learnr")`).  

Click on a tutorial listed below and save the file as a .Rmd when the download window opens.  Open this saved Rmd file with RStudio and click the `Run Document` button at the top to start the tutorial.

<a href="/files/tutorials/part1_ggplot2_basics.Rmd" download="tutorial1_ggplot2_basics.Rmd">Tutorial 1: ggplot2 basics</a>  
<a href="/files/tutorials/part2.1_polishing_raw_data.Rmd" download="tutorial2_ggplot2_appearance.Rmd">Tutorial 2: controlling plot appearance</a>  
<a href="/files/tutorials/part2.2_polishing_results.Rmd" download="tutorial3_ggplot2_appearance_legend.Rmd">Tutorial 3: controlling plot appearance with a legend</a>  
