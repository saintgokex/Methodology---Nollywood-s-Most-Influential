# Methodology---Nollywood-s-Most-Influential
## Introduction
Hey there! Welcome to our methodology breakdown for the Nollywood's Most Influential Data Project. This document walks you through how we gathered, cleaned, and visualized our data to uncover the most influential actors in Nollywood.

We'll dive into how we scraped info from Wikipedia, did some research on the richest actors, checked out Instagram followers, and tidied up our data for analysis. Our goal? To give you a clear picture of what goes into determining an actor's influence in the Nollywood scene.

So, buckle up! We're about to take you behind the scenes of our data journey and show you how we arrived at our findings in a professional, no-nonsense manner.


## Methodology
### Data Gathering

**1. List of Highest Grossing Nigerian Films:** Utilized web scraping techniques with BeautifulSoup to extract data from a Wikipedia table consisting of 111 rows. The table provides crucial information on the highest-grossing Nigerian films, forming the foundation of our analysis.
![](https://github.com/saintgokex/Methodology---Nollywood-s-Most-Influential/blob/20e10f4f846dfd197249e9cf9f45cc8490da8a4d/nollywood%20-%20py.png)

**2. Research on Top 20 Richest Actors:**
Conducted research to compile data on the top 20 richest actors in Nollywood, including their net worth and career start year. This information offers insights into the financial standing and longevity of prominent actors within the industry.


**3. Social Media Following on Instagram:**
Gathered data on social media following, specifically on Instagram, for the actors under review. This metric serves as an indicator of each actor's digital influence and audience engagement.

### Data Cleaning
**1. Highest Grossing Nigerian Films Table:**

- Removed special characters surrounding domestic gross figures in the "Domestic Gross" column to ensure consistency and accuracy.
- Split entries in the "Director(s)" column to isolate individual directors for proper aggregation.
- Duplicated movies with multiple directors to ensure each row corresponds to a single director, facilitating accurate analysis.
![](https://github.com/saintgokex/Methodology---Nollywood-s-Most-Influential/blob/20e10f4f846dfd197249e9cf9f45cc8490da8a4d/dirty%20data%20view.png)    ![](https://github.com/saintgokex/Methodology---Nollywood-s-Most-Influential/blob/20e10f4f846dfd197249e9cf9f45cc8490da8a4d/clean%20data%20view.png)
  
**2. Net Worth Table:**
- Eliminated "M" from social media follower counts to standardize the format.
- Converted social media follower counts from decimal numbers to actual values in millions for ease of interpretation.

  ![](https://github.com/saintgokex/Methodology---Nollywood-s-Most-Influential/blob/20e10f4f846dfd197249e9cf9f45cc8490da8a4d/net%20worth.png)
  ![](https://github.com/saintgokex/Methodology---Nollywood-s-Most-Influential/blob/20e10f4f846dfd197249e9cf9f45cc8490da8a4d/net%20worth%20-%20clean.png)
**3. Awards Table:**
- Filled down actors' names to ensure consistency and completeness across the dataset.
  ![](https://github.com/saintgokex/Methodology---Nollywood-s-Most-Influential/blob/20e10f4f846dfd197249e9cf9f45cc8490da8a4d/amvca%20awards.png)
  ![](https://github.com/saintgokex/Methodology---Nollywood-s-Most-Influential/blob/20e10f4f846dfd197249e9cf9f45cc8490da8a4d/amvca%20awards%20cleaned.png)

### Data Visualization

**1. Column and Bar Charts:**
- Replaced y and x axes with descriptive labels to enhance readability and comprehension.
- Implemented a color scheme where all columns and bars are shaded grey, with the focal data points highlighted in blue to draw attention.
- Eliminated gridlines to minimize visual clutter and focus audience attention on essential data points.
  
**2. Other Charts:**
- Aligned titles to the left of each chart to guide the audience's attention and facilitate sequential reading.
- Organized charts in a logical sequence to guide the audience through the data storytelling process, starting from general overviews and progressively narrowing the focus.
- Strategically positioned a gauge chart titled "Funke Akindele's Domestic Gross" at the conclusion of the visualization to subtly emphasize her significance within the dataset.
