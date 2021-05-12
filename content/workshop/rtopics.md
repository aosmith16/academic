+++
date = 2021-03-30T00:00:00  # Schedule page publish date.

title = "Advanced R topics working sessions"
time_start = ""
time_end = ""
abstract = ""
abstract_short = ""
event = "College of Forestry class"
event_url = "https://aosmith16.github.io/spring-r-topics/materials.html"
location = ""

# Is this a selected talk? (true/false)
selected = false

# Projects (optional).
#   Associate this talk with one or more of your projects.
#   Simply enter the filename (excluding '.md') of your project file in `content/project/`.
# projects = ["deep-learning"]

# Links (optional).
url_pdf = ""
url_slides = ""
url_video = ""
url_code = ""

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

Welcome to FES/FOR 505, Advanced R Topics. This is an informal "working session" class for students wanting to get a little extra practice in R.  The class was designed so students work together through material in real time.  Each class is 1.5-2 hours.

Topics covered:   
Week 01: [Introduction to Git/GitHub](https://aosmith16.github.io/spring-r-topics/materials.html#week-1-introducing-git-and-github)  
Week 02: [Build a personal website with **distill** and **postcards**](https://aosmith16.github.io/spring-r-topics/materials.html#week-2-create-a-distill-website)  
Week 03: [Deploy website using GitHub Pages](https://aosmith16.github.io/spring-r-topics/materials.html#week-3-more-on-distill-articles-and-deploy-website)  
Week 04: [Explore **gt** for making tables](https://aosmith16.github.io/spring-r-topics/materials.html#week-4-intro-to-display-tables-with-gt)  
Week 05: [**gt** flair: colors, images, and themes](https://aosmith16.github.io/spring-r-topics/materials.html#week-5-gt-flair-colors-images-and-themes)    
Week 06: [Learn to write functions in R](https://aosmith16.github.io/spring-r-topics/materials.html#week-6-writing-functions-in-r)  
Week 07: [More Git: collaborators, merge conflicts, and pull requests](https://aosmith16.github.io/spring-r-topics/materials.html#week-7-more-git-and-github)  
Week 08: [Interactive graphics and tables](https://aosmith16.github.io/spring-r-topics/materials.html#week-8-using-interactive-elements-in-static-html-documents)     
Week 09: [Reproducible examples with **reprex**](https://aosmith16.github.io/spring-r-topics/materials.html#week-9-reproducible-examples-with-reprex)      
Week 10: [GitHub issues](https://aosmith16.github.io/spring-r-topics/materials.html#week-10-github-issues)    

Materials for the class, including the slides, are [here](https://aosmith16.github.io/spring-r-topics/materials.html). Slides are written out in a longer format for students who wanted to work through the material on their own. Press "P" after opening slides to see any additional presenter notes.

## Software and R packages

This class was held spring 2021, using **R 4.0.4** and **RStudio 1.4**.  

The R packages, with version numbers, used in the working sessions. The relevant weeks are in parentheses:

**distill v. 1.2** (*Week 2*)  
**postcards v. 0.2.0** (*Week 2*)  
**devtools v. 2.3.2** (*Week 2*)  
**fontawesome v. 0.1.0** (not 0.2.0; *Week 2*)  
**gt v. 0.2.2**  (*Week 4*)  
**webshot v. 0.5.2** (*Week 4*)  
**dplyr v. 1.0.5** (*Week 4*)  
**tidyr v. 1.1.3** (*Week 5*)  
**usethis v. 2.0.1** (*Week 7*)  
**gh v. 1.2.1** (*Week 7*)  
**htmlwidgets v. 1.5.3** (*Week 8*)  
**ggplot2 v. 3.3.3** (*Week 8*)  
**palmerpenguins v. 0.1.0** (*Week 8*)  
**plotly v. 4.9.3** (*Week 8*)   
**DT v. 0.18** (*Week 8*)  
**leaflet v. 2.0.4.1** (*Week 8*)  
**dygraphs v. 1.1.1.6** (*Week 8*)  
**flexdashboard v. 0.5.2** (*Week 8*)  
**reprex v. 2.0.0** (*Week 9*)  
**datapasta v. 3.1.0** (*Week 9*)  

Installation code for current versions:
```
install.packages(c("distill", "postcards", "devtools", "fontawesome", 
                   "gt", "webshot", "dplyr", "tidyr", "usethis",
                   "gh", "htmlwidgets", "ggplot2", "palmerpenguins",
                   "plotly", "DT", "leaflet", "dygraphs", "flexdashboard",
                   "reprex", "datapasta"))
```

*This work is licensed under a Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International License.*
