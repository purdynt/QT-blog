# QT-blog
Data led blog discussing patterns in the quantity and type of kills in Quentin Tarantino movies. 
This data-led blog aims to give a complete analysis of both on and off screen kills in Quentin Tarantino's films. A director who is typically known for his unique storytelling and cinematography, along side his infamously striking take on violence, data based upon this distinct fatalities within his movies offers a fresh insight onto his projects. 

Within this blog, we look to analyse the kill counts from Tarantino's initial 9 movies where he has exclusively directed in the wake of his announcement for is 10th and final movie. Although individually he has already released 10; Kill Bill Vol 1 and Kill Bill Vol 2, are considered to be one singular film despite being released as two seperate films. Amongst those films, this project includes all other major Tarantino directed films- such as Inglourious Basterds, Django Unchained, Pulp Fiction, and others to be broken down by a varying categories:

- Kill Count and IMDb ratings over time
- Top 20 killers and their fate
- Gender break down of killers
- Gender break down of deaths
- Types of kills by body count
  
Adopting a multitude of data visualisation methods and contextual reasoning, this blog provides information about how Tarantino uses death and ways of dying within his films, equally how he treats methods of dying within the context of the film. 

Regardless of whether you are a Tarantino fan, a film student or simply just interested in stylised fatalities in cinema, this blog should provide you with insight into how one of this generations most infamous directors plays with death within his movies.

# Getting Started 
## Prerequisites

Before installing or running this project, ensure you have the following prerequisites installed:

- **Operating System:** Windows 10 / macOS / Linux
- **Python:** 3.8 or higher
- **Libraries:**
  - `pandas`
  - `matplotlib`
  - `seaborn`
  - `numpy`
  - `jupyter` (for running notebooks)
  - `selenium` (for automated web scraping)
  - `webdriver-manager` (to manage ChromeDriver automatically)



1. Clone this repository to your local machine using Git: https://github.com/purdynt/QT-blog.git
   `bash`
2. Launch Jupyter Notebook with:
```bash```
jupyter notebook

3. Navigate into the project folder :

All code is done on Jupyter Notebook, so this needs to be opened.
Once this has been opened, run notebooks in specific order:
 1. Run: Project Data Collection and Cleaning.ipynb 
This file contains all the webscraping, data cleaning and data reshaping. It does save it all to csv files which have also been uploaded into the repository. 
 2. Run: Data Presentation_22.ipynb
This file contains all the code for the data presentation such as pie chart, line graphs and bar charts.

### Insights and Limitations
-Kill counts include both on screen but equally off screen or implied death.
-Character's personal kill counts may be inaccurate given the descriptions do not direclty say whether kills were assisted or not-this could be prevelant specifically in Inglourious Basterds.
-IMDb ratings vary over time 

# Sources of webscraping
- IMdb for ratings data: https://www.imdb.com/list/ls069398589/
- Kills data: https://listofdeaths.fandom.com/wiki/Quentin_Tarantino
Within this, due to variation in browser structure, each movie was webscraped individually, hence:
 - https://listofdeaths.fandom.com/wiki/Reservoir_Dogs
 - https://listofdeaths.fandom.com/wiki/Pulp_Fiction
 - https://listofdeaths.fandom.com/wiki/Jackie_Brown
 - https://listofdeaths.fandom.com/wiki/Death_Proof
 - https://listofdeaths.fandom.com/wiki/Kill_Bill
 - https://listofdeaths.fandom.com/wiki/Inglourious_Basterds
 - https://listofdeaths.fandom.com/wiki/Django_Unchained
 - https://listofdeaths.fandom.com/wiki/The_Hateful_Eight
 - https://listofdeaths.fandom.com/wiki/Once_Upon_a_Time..._in_Hollywood







