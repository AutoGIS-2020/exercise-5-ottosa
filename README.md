# Exercise-5

This week we will practice how to create **static and interactive maps using Python**. The goal of this exercise is to allow you to focus on cartographic visualization with Python, and to play around and explore different possibilities of the available visualization packages.

In this exercise, there is no ready-made Notebook-file to start with. All instructions are given in this readme.md -file and you should create all necessary files for completing the exercise yourself. Your final submission should inlcude a Jupyter Notebook-file (or a Python script file), and the output maps for problems 1 and 2 in `.png` and `.html` format stored in the **`docs`** folder (see instructions below). Finally, you will publish the maps online (problem 3).

- **Exercise 5 is due by 17:00 on Thursday the 3th of December.**

- You can gain 20 points from this exercise. 


## Problem 1: Visualize a static map (8 points)

Create a static map using the skills you leared in lesson 5. The map should contain multiple layers of data (at least two different data sets), and you should pay attention to the classification and visualization (colors, edges etc.) when creating the map. Write your code into a notebook file (`.ipynb`) or a python script file (`.py`) and store the output map(s) in `.png` format into the `docs` folder.

**Topic of the map:**
- You can either use the data sets we have already used during this course (eg. the Travel Time Matrix, or population grid), or you can select some other data set of your interest (for example, statistics in postal code areas).
- Feel free to adapt examples provided in this course! You can do further calculations based on the datasets or use the analysis outputs that we have done earlier in the course (for example, the dominance areas or travel times for shopping centers). 

**Criteria:**
- The map should have multiple layers on it (for example, the travel time matrix and the road network). Basemap is optional (use a basemap only if it adds useful information / visual touch!)
- The map should portray some kind of classification and/or an analysis output (not just the raw data).
- Consider [good cartographic practices](https://www.gislounge.com/ten-things-to-consider-when-making-a-map/) (map extent, zoom level, color choices, legend, credit data sources etc.) when plotting the map.

**Output:**
- Remember to commit the code and input data (or at least a link to input data)
- Save your map(s) as png image in the **`docs`** folder  

## Problem 2: Visualize an interactive map (10 points)

Create a nice interactive map using the skills you leared in lesson 5: interactive maps using Folium (or some other suitable package - feel free to experiment!). Write your code into a notebook file (`.ipynb`) or a python script file (.py) and store the output map(s) in `.html` format under the `docs` folder.

**Topic of the map:**
- You can select the topic of the map freely.
- This map should not be only an interactive version of your submission for problem 1 ;). Create something new!
- Feel free to adapt examples provided in this course!

**Criteria:**
- The map should have multiple layers on it and/or present an output of (simple) data analysis (something beyond plotting raw data on a map).
- Consider [good cartographic practices](https://www.gislounge.com/ten-things-to-consider-when-making-a-map/)
- The map should demonstrate skills learned during lesson 5: interactive maps and throughout this course. You can also take advantage of the [Folium example gallery](https://nbviewer.jupyter.org/github/python-visualization/folium/tree/master/examples/) for further ideas.
- Think about including additional interactive elements, such as popup text in the map.

**Output:**
- Remember to commit the code and input data (or at least a link to input data)
- Save your map(s) in .html format in the **`docs`** folder


## Problem 3: Publish your maps online (2 points)

 You should now have **ALL** your maps stored in the **`docs`** folder inside this repository
- Add links to those maps in the specific Entrance page [index.md -file](docs/index.md) that you can find in the **docs** folder. 
- There are more instructions how the links should be formatted in the [**docs/index.md -file**](docs/index.md) 
- Provide a short description of each map in the [**docs/index.md -file**](docs/index.md)
- Publish your maps with github pages (optional)
  - Go to repository settings --> Danger Zone --> Change repository visibility as public (note! your repository will be visible to anyone online)
  - Go to repository settings --> GitHub Pages --> Choose a theme (choose any team and commit changes)
  - Go to repository settings --> GitHub Pages --> Change Branch: master, folder: docs
  - the url of your maps will be `https://autoGIS-2020.github.io/exercise-5-your-github-name/filename*`
  - See instructions on **how to edit repo settings and publish contents of the docs folder using github pages** in Lesson 5.
  
**Optional, but recommended:** Share link(s) to your map(s) on Slack (Uni Helsinki students only). 
  
  
### Summary of the expected outputs

- At least 1 static map in `.png` format stored in the `docs`-folder (problem 1)
- At least 1 interactive map in `.html` format stored in the `docs`-folder (problem 2)
- All codes (`.ipynb` or `.py` -files) and input data (or links to input data) provided in this exercise-5 repository 
- Optional: Published maps at: `https://autoGIS-2020.github.io/exercise-5-YourGitHubUsername/filename*` containing online versions of your interactive and static maps (problem 3) 
- Optional: Links to the published maps stored in the [**docs/index.md -file**](docs/index.md) (problem 3)

For both maps, think a bit about the audience of the map, and pay attention to your cartographic choices. Check out [this blog post for further hints on creating good maps](https://www.gislounge.com/ten-things-to-consider-when-making-a-map/). 
  
  
 ## Exercise 5 grade and feedback: 20.0 / 20.0 points
### Grader
- sonjakoivisto
### Problem scores
- Problem 1: 10.0 / 10.0 
- Problem 2: 10.0 / 10.0 
- Problem 3: :sunny: / 0.0
### Comments
  
Handsome maps following good cartographic practices. You found good data source for Finland covid cases. It was nice that you defined the classification function yourself. To keep the colorscale constant through the different months in the interactive map, you could define bins = [class1treshold, class2treshold, so on]. Then It'd be easier to visually quickly see the differences between month without looking at the legends. Also, a tooltip would help with this. Very good work and also good base for final exercise if you wish to continue with the same theme.
  
  


