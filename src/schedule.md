# Semester Schedule

## Week 1 (August 19th)
- Wednesday: first day of class
	- Introductions, zoom, slack, github, R & RStudio
	- For next time:
		- [Getting Started with GitHub](https://tyler-frazier.github.io/dsbook/gitstart.html)
		- [Getting Started with R & RStudio](https://tyler-frazier.github.io/dsbook/rstart.html)
			- install R & RStudio
- Friday:
	- Introduction to Agent-Based Modeling for Complex and Adaptive Social and Economic Systems
	- For next time
		- [Getting Started with R & RStudio](https://tyler-frazier.github.io/dsbook/rstart.html)
			- Creating and Plotting Objects
			- Creating a More Complicated Plot while also creating and then using a Data Frame
			- Challenge Question
			- Create a markdown file that includes your deliverables and a brief explanation about your plots; include a link to this file on your GitHub index page

## Week 2 (August 24st)
- Monday:
	- Introduction to Agent-Based Modeling for Complex and Adaptive Social and Economic Systems 
	- Working with GitHub Desktop
	- For next time
		- [Projecting, Plotting and Labelling Administrative Subdivisions](https://tyler-frazier.github.io/dsbook/describe.html#projecting-plotting-and-labelling-administrative-subdivisions)
- Wednesday:
	- Review selected locations, discuss computational limits of R relative to population and development data science methods
	- For next time
		- [Extracting Populations from a Raster and Aggregating to each Unit](https://tyler-frazier.github.io/dsbook/describe.html#extracting-populations-from-a-raster-and-aggregating-to-each-unit)
- Friday: add/drop period ends

## Week 3 (August 31st)
- Monday:
	- Project 1, Part 1 - site selection. [Creating a Geometric Bar Plot with your Simple Feature object](https://tyler-frazier.github.io/dsbook/describe.html#creating-a-geometric-bar-plot-with-your-simple-feature-object)
		- Select a location. Produce a spatial statistical description of your selected areas administrative subdivisions. Also produce an a accompanying geometric bar plot that also describes the population of your selected administrative subdivisions.
		- Select a subdivision from within your initially selectected location that will be the bases for your agent-based model.  Set the boundary of your selected location such that the aggregate population is between 250,000 and 400,000 persons.  
		- Return to the previous exercise and repeat it, although this time produce the spatial statistical description and accompanying geometric barplot for your newly selected, higher resolution focus area with its increased scale.
		- Do your best to include all administrative subdivisions available.  If a simple feature object that describes higher resolution administrative subdivisions in their disaggregate (i.e. adm2, adm3 or adm4) is not available from GADM, check other source (geoBoundaries).  Additionally, if higher resolution administrative subdivisions are not available, include all of the bordering subdivisions when generating your newly created units spatial description and accompanying bar plot.
- Wednesday:
	- Project 1, Part 1 - site selection. [Creating a Geometric Bar Plot with your Simple Feature object](https://tyler-frazier.github.io/dsbook/describe.html#creating-a-geometric-bar-plot-with-your-simple-feature-object)
	- Project 1, Part 1 - define *de facto* settlement boundaries.  [De facto description of human settlements and urban areas](https://tyler-frazier.github.io/dsbook/defacto_descript.html)
		- Continue by further investigating your site for selection by defining *de facto* settlement boundaries.   
- Friday:
	- Project 1, Part 1 - site selection. [Creating a Geometric Bar Plot with your Simple Feature object](https://tyler-frazier.github.io/dsbook/describe.html#creating-a-geometric-bar-plot-with-your-simple-feature-object)
	- Project 1, Part 1 - define *de facto* settlement boundaries.  [De facto description of human settlements and urban areas](https://tyler-frazier.github.io/dsbook/defacto_descript.html)
		- Continue by further investigating your site for selection by defining *de facto* settlement boundaries.  
		- Increase the scope of your investigation by adding an additional administrative unit or applying the previous exercise to the parent administrative subdivision.
		- Stretch goal: apply Zipf's law

## Week 4 (September 7th) 
- Monday:
	- Project 1, Part 1 continued (Accessibility 1)
- Wednesday:
	- Project 1, Part 2 [Accessibility 2 - Transport Systems](https://tyler-frazier.github.io/dsbook/transport_health.html)
- Friday:
	- Project 1, Part 2 [Accessibility 2 - Transport Systems](https://tyler-frazier.github.io/dsbook/transport_health.html)
	- Project 1, Part 2 [Accessibility 3 - Topography](https://tyler-frazier.github.io/dsbook/topography.html) (optional stretch goal)


## Week 5 (September 14th)
- Monday:
	- Project 1, Parts 1,2 & 3 - workshop 
		- measures of access 
- Wednesday:
	- Project 1, Parts 1,2 & 3 - workshop
		- system description and analysis  
- Friday:
	- Data Science Insights: Select and then investigate a new and interesting data science method. Write a brief introduction to the method including describing how it functions as well as one or two applications that relate to population, human development and/or agent-based modelling. Post your 1-2 page insight piece to your GitHub Pages site and be sure to link it back to your index. Be prepared to make a 4-6 minute presentation on your data science/agent-based modelling insight during class.
- Saturday
	- Project 1 due: please include the following
		-  Geometric bar plots that describe the population distribution of the political subdivisions associated with your selected location.  Include a justification for your selection and a basic description with your plot.
		-  Plot of the de facto settlement boundaries with geometric measures of population and density for all locations.  Include linear descriptions of all transportation facilities.  Also, include a description and analysis of the system of settlements that populate your selected location.
		-  Provide an analysis of the system of settlements sizes and relative location to one another.
		-  Provide an analysis of the transportation network and its capacity to facilitate access across your selected area.

## Week 6 (September 21st)
- Monday:
	- Class cancelled - ill 
- Wednesday:
	- Begin project 2: lecture, generating synthetic populations for use in agent-based models - theory and methods
- Friday:
	- Continue project 2: lecture, generating synthetic populations for use in agent-based models - methods and implementation

## Week 7 (September 28th)
- Monday:
	- Project 2: generating synthetic populations
		- Visit the [DHS data](https://dhsprogram.com/data/available-datasets.cfm) site, and select a standard DHS survey dataset to obtain.
		- Register with DHS and login.  Review the [DHS video](https://dhsprogram.com/data/Access-Instructions.cfm) on how to create a new project, request access to DHS data for your selected study area, and to provide a description of your research (study) area.
		- Post your study description, including your research question, research design and data analysis plan to your GitHub page and link it to you index.  The study description should be more than 300 but not less than 2500 characters in length.
		- Select a recent standard DHS survey and download the household and individual datasets.  Using the stata format (.dta) for import to RStudio typically works fine.

- Wednesday:
	- Project 2: generating synthetic populations
		- Review: 
			- DHS report 
			- questionnaire
			- survey design
			- .DO file 
		- Import households survey from DHS dataset
		- Identify:
			- Survey weights
			- Number of household members
			- Location of your selected research area
			- Gender of household members  
			- Age of household members
		- Post results to your GitHub pages site and link in your index
 
- Friday:
	- Import your DHS data
	- Identify predictor variables within your dataset
	- Stretch goal: import DHS cluster GPS coordinates and randomly distribute

## Week 8 (October 5th)
- Monday:
	- Clean DHS survey data for use
	- Randomly locate each survey observation using a spatial distribution
	- Convert and join predicted household locations with DHS household data
- Wednesday:
	- Review stretch goal progress
	- Review methods for cleaning DHS data based on each select household survey 
- Friday:
	- Review survey design 
	- Transform survey weights
	- Specify model

## Week 9 (October 12th)
- Monday:
	- Project 2 
- Wednesday:
	- Project 2 
- Friday:
	- Data Science Insights: Select and then investigate a new and interesting data science method. Write a brief introduction to the method including describing how it functions as well as one or two applications that relate to population, human development and/or agent-based modelling. Post your 1-2 page insight piece to your GitHub Pages site and be sure to link it back to your index. __No class presentation at this time__
	- Project 2 due 

## Week 10 (October 19th)
- Monday:
	- Project 3 
- Wednesday:
	- Project 3 
- Friday:
	- Project 3 

## Week 11 (October 26th)
- Monday:
	- Project 3 
- Wednesday:
	- Project 3 
- Friday:
	- Data Science Insights
- Saturday
	- Project 3 due 

## Week 12 (November 2nd)
- Monday:
	- Final Project 
- Wednesday:
	- Final Project
- Friday:
	- Final Project

## Week 13 (November 9th)
- Monday: 
	- Final Project
- Wednesday:
	- Final Project
- Friday: last day of class
	- Data Science Knowledge Creation 

## Final





