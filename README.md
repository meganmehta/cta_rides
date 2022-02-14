# CS 424 Project 1 - Subway

This code repository contains an app.R file along with a set of .tsv files. The app.R file contains all of the code needed to run this project while the 

To run this project locally, make sure to clone this repo on your computer in whatever location you choose. Here are some simple steps below: 

```
cd 
git clone https://github.com/meganmehta/cta_rides.git
```
Along with cloning this repo, make sure to download [R](https://www.r-project.org/ ) (v 4.1.2) and [R Studio](https://www.rstudio.com/products/rstudio/download/ )(v 2021.09).

Once you have R and R Studio downloaded, open this project file in R Studio. You can do this by setting the working directory, as shown below: 
![Session -> Set Working Directory -> Choose Directory](https://github.com/meganmehta/cta_rides/blob/main/documentation1.jpg)

After the working directory is set, open the app.r file within R Studio. This file contians all of the code in this project. 
Files with extension .tsv are the data files used to create these visualizations and are from [this](https://data.cityofchicago.org/Transportation/CTA-Ridership-L-Station-Entries-Daily-Totals/5neh-572f) dataset from the Chicago Data Portal. 

Before running this application, make sure that all necessary packages/libraries are downloaded. To check what libraries are currently added, type the command
`installed.packages()` in the R Studio Console. If some packages are missing, use 'install.packages("package-name-here")' to install the remaining ones necessary. 
All of the needed libraries are listed at the top of the app.R file. 

After that, you should be good to run the project. Click the 'Run App' button on the right. 
![](https://github.com/meganmehta/cta_rides/blob/main/documentation2.jpg). 

An additional window will pop up with the visualization and you're all set! 
