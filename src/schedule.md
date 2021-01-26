# Semester Schedule

## Week 1 (...)
- Wednesday: first day of class
	- Introductions 
	  	- Zoom, Slack & Blackboard
	  	- GitHub, Markdown & Webstorm
	  	- Homebrew (Mac) & Chocolatey (Windows)
	  	- R & RStudio
	  	- Python & PyCharm 
	- For next time:
	  	- [Getting Started with Homebrew or Chocolatey](https://tyler-frazier.github.io/dsbook/manager.html)
		- [Getting Started with GitHub, Markdown & Webstorm](https://tyler-frazier.github.io/dsbook/gitstart.html)
- Friday:
	- Introduction to Agent-Based Modeling for Complex and Adaptive Social and Economic Systems (1)
	- Vignette using homebrew or chocolatey
  	- Vignette using GitHub, Markdown & Webstorm (1)
	- For next time:
		- [Getting Started with R & RStudio](https://tyler-frazier.github.io/dsbook/rstart.html)
		- [Getting Started with Python & PyCharm](https://tyler-frazier.github.io/dsbook/pystart.html)

## Week 2 (...)
- Monday:
	- Introduction to Agent-Based Modeling for Complex and Adaptive Social and Economic Systems (2)
	- Vignette using R & RStudio (1)
	- Vignette using Python & PyCharm (1)
	- For next time:
		- ...
- Wednesday:
  - Introduction to Agent-Based Modeling for Complex and Adaptive Social and Economic Systems (3)
  	- Vignette using R & RStudio (2)
	- Vignette using Python & PyCharm (2)
	- For next time:
		- ...
- Friday: add/drop period ends
  	- Vignette using R & RStudio (3)
	- For next time:
		- ...

## Week 3 (...)
- Monday:
	- Project 1, Part 1 - site selection. [Creating a Geometric Bar Plot with your Simple Feature object](https://tyler-frazier.github.io/dsbook/describe.html#creating-a-geometric-bar-plot-with-your-simple-feature-object)
		- Select a location. Produce a spatial statistical description of your selected areas administrative subdivisions. Also produce an a accompanying geometric bar plot that also describes the population of your selected administrative subdivisions.
		- Select a subdivision from within your initially selected location that will be the bases for your agent-based model.  Set the boundary of your selected location such that the aggregate population is between 250,000 and 400,000 persons.  
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

## Week 4 (...) 
- Monday:
	- Project 1, Part 1 continued (Accessibility 1)
- Wednesday:
	- Project 1, Part 2 [Accessibility 2 - Transport Systems](https://tyler-frazier.github.io/dsbook/transport_health.html)
- Friday:
	- Project 1, Part 2 [Accessibility 2 - Transport Systems](https://tyler-frazier.github.io/dsbook/transport_health.html)
	- Project 1, Part 2 [Accessibility 3 - Topography](https://tyler-frazier.github.io/dsbook/topography.html) (optional stretch goal)


## Week 5 (...)
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

## Week 6 (...)
- Monday:
	- Class cancelled - ill 
- Wednesday:
	- Begin project 2: lecture, generating synthetic populations for use in agent-based models - theory and methods
- Friday:
	- Continue project 2: lecture, generating synthetic populations for use in agent-based models - methods and implementation

## Week 7 (...)
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

## Week 8 (...)
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
	- Distribute households at adm0 & adm1
	- Join spatial and survey data

## Week 9 (...)
- Monday:
	- Join spatial and survey data
	- estimate error
	- analyze adm1 data
	- disaggregate from households to persons
- Wednesday:
	- Train, test & predict 
- Friday:
	- Data Science Insights: Select and then investigate a new and interesting data science method. Write a brief introduction to the method including describing how it functions as well as one or two applications that relate to population, human development and/or agent-based modelling. Post your 1-2 page insight piece to your GitHub Pages site and be sure to link it back to your index. __No class presentation at this time__
- Sunday:
	- Project 2 deliverable is due on Sunday October 25th.  Please upload and provide a link from your GitHub index to a 3 to 4 page project report that analyzes the synthetic household and person population you generated. Include arguments that address the following aspects from your work.
		-  Provide a written description of your selected household survey including the number of household and person observations as well as the variables in your source data.
		-  Provide a written description of your spatially located households at the adm0 level of your selected location, including how you located each household, generated the household structure including demographic attributes of persons, and the percent error calculated.  If you faced computational issues at the adm0 level when attempting to pivot from households to persons, describe those limitations.
		-  Provide a written description of your spatially located households at the adm1 or adm2 level of your selected location, again including how you located each household, generated the household structure including demographic attributes of persons, and the percent error calculated.  Further analyze your synthetically generated households and persons with regard to percent error.  Do you think this population is more or less accurate than the one generated at the adm0 level? What could you have done to improve your measures of accuracy?
		- When compared to a randomly generated synthetic population that describes the demographic attributes of households and persons, does yours more closely approximate reality? How is yours an improvement over a synthetic population that was generated in accordance with complete spatial randomness?  Generate plots and incorporate results from your work as evidence in support of an argument that the synthetic population you generated is a good approximation of the reality that existed in your selected location at that given time.

## Week 10 (...)
- Monday:
	- Project 3
		- Import de facto settlement boundaries from project 1
		- Import synthetic households and persons from project 2 
- Wednesday:
	- Project 3
		- Create voronoi tesselations
		- Introduce gravity model 
- Friday:
	- Project 3 

## Week 11 (...)
- Monday:
	- Project 3 
- Wednesday:
	- Project 3 
- Friday:
	- Data Science Insights

## Week 12 (...)
- Monday:
	- Project 3 
- Wednesday:
	- Project 3
- Friday:
	- Project 3

## Week 13 (...)
- Monday: 
	- Project 3
- Wednesday:
	- Final Project
- Friday: last day of class
	- Data Science Knowledge Creation 

## Final
- Your final project write up (for project 3) is due on Tuesday November 24th by 5PM.  Please upload and provide a link from your GitHub index to a 3 to 4 page project report that analyzes migration and movement at your selected location. Include analysis that addresses the following.
	-  Provide a written description of the analysis you conducted of the gravity model for London.  Additionally, incorporate the Garcia et al. paper into your description while introducing your the migration data for your selected country.  Supplement your introduction with spatial plots that describe in/out migration by adminsitrative subdivision.
	- Produce an origin-destination matrix and include a portion of it as an exhibit in your write-up.  Be sure to identify the number of rows in your data frame while also including the following.
		- Names of origin and destination administrative subdivisions
		- Distances between all locations
		- Migration flows between all locations
		- An additional variable that describes all origin and destinations to be used for further specification of a gravity model (one option you could use is to select night-time lights from WorldPop)
		- Geometric description of all origin and destination center points
	- Describe your OD matrix and how it is used to model migration across the administrative subdivisions that comprise your selected location.
	- Produce an animation of migration and elaborate on how your OD matrix and gravity model could be integrated with your simulation.  
		- How would you modify the number of points departing from each origin?
		- How would you modify the time variable? What scale is the temporal dimension at this level?
		- How would the gravity model update these attributes in order to produce a different simulation of migration that more closely approximates reality?
	- At the level of your selected, higher resolution administrative subdivision (where you produced defacto descriptions of settlements), use the center points of each settlement to produce a tesselation of voronoi polygons.  Similar to your analysis of the higher level administrative subdivisions, address the following.
		- How would you produce an OD matrix of these higher resolution entities?  Which variables would you include?  Are you lacking any data that would improve upon your model results?
		- How would you modify the number of points departing from each origin? How would you determine each points destination?
		- How would you modify the time variable? What scale is the temporal dimension at this level?
		- How would the gravity model update these attributes in order to produce a different simulation of migration?
		- How would you go about integrating migration and transport activities at the differing geospatial and temporal scales of these hierarchical levels?