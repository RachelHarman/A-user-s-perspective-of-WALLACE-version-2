From data to maps to stats" A user's vignette of Wallace

Description:

We have used the R-based GUI platform Wallace to model the distribution of a few species for peer-reviewed publications. 
We greatly appreciate the time and effort that the authors have put into creating the Wallace platform. 
Their work has exceedingly shortened the learning curve for those new to species distribution models (SDM).

However, as users of the platform, we thought that a more thorough vignette from an outside perspective would be useful. 
The vignette provided by the authors as well as the information provided in Wallace itself is exceedingly helpful, but there are a lot of aspects that are not covered. 
Here, we attempt to bring together a how-to-tutorial, reasoning, and next steps into one place.

This vignette not only leads the user through Wallace, but also some ways to use the information. 
Examples include steps to remove collinear variables, code to make high quality maps in R, and di-rections to analyze differences between maps through QGIS and R code. 
It is important to note that the information here is one workable way to make species distribution models with Wallace and Maxent. 
There are many other ways to interpret the data and make the maps. Throughout the full procedure, keep the life history of your organism and the questions that you are asking in mind.
Additionally, this vignette gives additional helpful information. Look for three note inserts throughout the vignette! 
The first one is a red box termed “Stop and Think!”. These boxes give some information and resources to help you make a decision about what parameters to use in your model based on the life history of your individual species or the questions that you are asking. 
Remember, do not just use the default settings or settings that you saw in a published journal because someone else did it! 
The second insert is a yellow box named “User Insights”. These boxes give helpful hints on troubleshooting, when to save, and problems that users have come across. 
The blue box inserts, “Terms to Know” highlights some important words and provide definitions and some references. 
The purple box, “Stats Chat”, is an insert that points out some statistic concepts and pros and cons about different statistical methods. 
Lastly, the brown box, “Resources”, includes helpful references.

This vignette was created using version Wallace 2. The most up-to-date version at the time of creating this vignette was in May and June 2024. 
The R platform used was version 4.4.1 also the most up-to-date version at the time.

Potential audience:

We hope that this vignette is used by researchers for their own work as well as a lesson plan for students. 
We provide enough background information that this vignette can be used in high school advanced biology, non-majors or majors undergraduate courses, or with graduate students. 
Although experts in the field may find some of the information to be standard, we believe that experts would also utilize this vignette to shorten their learning curve of SMDs and add distribution modeling to their own skill set.

What is included in GitHub:

- The pdf of the vignette. The current version is 01. This is a beta version of the vignette and is currently being tested for completeness.
- Files for projecting. There are three file folders named Americas, Africa, and Asia that represent the third of the world in which these continents are located.
  Each folder has three documents, a .shx, .shp, and .dpf. All three documents must be uploaded into Wallace to project the potential distribution to other locations.

