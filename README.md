<div align="left"><img src="https://raw.githubusercontent.com/EconomicsObservatory/ECOvisualisations/main/guidelines/logos/eco-bg-dark.png" width="800"/></div>

# ✨ The language of (economic) data is visualisation ✨ 
An interactive masterclass by the **Economics Observatory**

[![GitHub license](https://img.shields.io/badge/license-MIT-blue.svg)](https://github.com/EconomicsObservatory/ecovisualisations/blob/main/LICENSE)

[**Website**](https://www.economicsobservatory.com/)
| [**Data Hub**](https://www.economicsobservatory.com/data-hub)
| [**Chart Examples**](https://richarddavies.io/charts)
| [**Data**](https://github.com/EconomicsObservatory/ECOdataHUB)
| [**Attendance sheet**](https://docs.google.com/spreadsheets/d/14F9BDCAYbULdZr5ecsEf7mygkuisYC-VW0nb87PS8ek/edit#gid=0)

Welcome to our interactive data masterclass. At the **Economics Observatory (ECO)** we believe that the future of effective science communication is a blend of data and text. Dashboards without context are too cluttered and text without explanatory graphics is difficult to grasp.

In our day-to-day work at ECO, we use data to amplify and distil the messages of our articles. Making charts clear and eye-catching, while also ensuring that the underlying data are transparent and replicable, is critical to what we do. This masterclass is designed to capture and share that workflow.

## 🏔️ Scope

Our data visualisation masterclass will take you from a being complete beginner to someone capable of designing and building stunning charts using cutting-edge tools, connected to live data. The course is designed to highlight the advantages and some caveats of using data visualisation for communicating information to a wide and diverse audience. It will also introduce some of our guiding principles for displaying data, focusing on transparency and how to select appropriate tools and methods for different datasets and contexts.

Throughout the course, we will offer and support 3 routes up the data mountain:

  - **🥾 Hiker** - the gentlest route, for those with no coding experience who simply want to build some nice-looking charts in a modern way.
  - **👟 Trail runner** - - slightly more stretching, for those who find the hike quick to complete and would like to build on their visualisation skills.
  - **🗻 Mountaineer** - - harder but rewarding. for participants who would like a taste of cutting-edge tools and techniques.

You will gain the skills and tools needed to create excellent charts. The course will also signpost additional resources to develop the ideas further, allowing you to gain confidence in your own abilities and even teach others. The latter stages of the course will delve deeper into the theory, exploring more advanced methods for data access and visualisation.

## 🛠️ Pre-requisites
No prior coding experience is required. However, participants’ laptops will need to be set up to allow:
- Access to a personal `GitHub` account, accessible via Google Chrome.
- Access to `Google Colaboratory`, accessible via a working Google account.
- `Visual Studio Code` downloaded to desktop, or accessible online as a back-up option (see set-up video and slides).

## 🕒 Schedule
| Time          | Section | Details                                             |
| ------------- | ------- | --------------------------------------------------- |
| 09.00 - 09.30 |         | Welcome coffee. Checking computer set ups.          |
| 09.30 - 10.30 | 1       | Charts as data – introducing Vega-Lite              |
| 10.30 - 11.00 | _Break_ | _Coffee/tea (team available to fix bugs)_           |
| 11:00 - 12.30 | 2       | My first website – GitHub, HMTL, CSS and JavaScript |
| 12.30 - 13.15 | _Lunch_ | _Lunch (team available to fix bugs)_                |
| 13.15 - 14.15 | 3       | Programming – APIs, if statements, and loops.       |
| 14.15 - 15.15 | 4       | Advanced visualisations – beyond two dimensions     |
| 15:15 - 15:30 | _Break_ | _Coffee/tea (team available to fix bugs)_           |
| 15.30 - 16.30 | 5       | Scraping – fetching data with Python                |

## Session 1: Charts as data

The day starts with an introduction from the **Economics Observatory Data Team**. In this session analysts build a chart as a ‘JSON specification’ (the modern way). These files contain information on where to find the data, and how the axes should look. These chart instructions are _themselves_ a type of data: they are shareable, replicable and verifiable.

**Resources:**
- We have prepared three example files highlighting the ‘charts as data’ principle, including the underlying data we want to display, delivered into your chart in three ways:
	1. Inline: [s1_chart1.json](1/s1_chart1.json)
	2. Linked: [s1_chart2.json](1/s1_chart2.json)
	3. API: [s1_chart3.json](1/s1_chart3.json)
- Slides: [1_Charts_as_data.pdf](1/1_Charts_as_data.pdf)
- We have also prepared 5 very simple datasets to try using with Vega-lite.
	- 👟[s1_example_data](1/s1_example_data)

✅ **Checkpoint:** By the end of this session, you will have seen all three JSON types, and will have added one of these files to your personal GitHub repository.
## Session 2: Building a live web site
By now you have a live chart (your JSON file) ready to embed into your website. But first you need to build a site to host it. We will show you the simple tools that allow this. First, we make a live site (`GitHub Pages`), before creating a space for visualisations and adding some text description (`HTML`). This site is briefly beautified and personalised (`CSS`) before we finally embed the charts built in session 1 (`JavaScript`).

**Resources:**
- A template to use for your website: [s2_example1.html](2/s2_example1.html)
- Three options for CSS Stylesheets, to customise your website:
	1. [🥾 s2_example1.css](2/s2_example1.css): a clean and full example with all the work done for you
	2. [👟 s2_example2.css](2/s2_example2.css): a minimal example containing instructions to help you style the website
	3. [🗻 s2_example3.css](2/s2_example3.css): a more complex example, placing charts and descriptions side-by-side 
- Two example charts, to start your website:
	1. [s2_chart1.json](2/s2_chart1.json): a simple bar chart showing the human development index (HDI) for 21 countries
	2. [s2_chart2.json](2/s2_chart2.json): 1. an interactive scatter plot, showing Vega-Lite's potential
- Slides: [2_Building_your_first_website.pdf](2/2_Building_your_first_website.pdf)

✅ **Checkpoint:** By the end of this session, you will have your own website, with its own customised text and design. Your website will have at least three stunning charts.

## Session 3: Fetching data from APIs

Here we introduce APIs more formally, running through their strengths and pitfalls as sources of data. We also meet some workhorses of programming—if statements and loops—allowing us to batch download data. By the end of this third session, you will have embedded another chart into their site, this time powered by an API. When new data are released, their chart will update – fully automatically.

**Resources**
- This session starts to introduce you to coding in the `Python` language. We will use the online code editor `Google Colab` for this.
	- [s3_workbook.ipynb](https://colab.research.google.com/github/EconomicsObservatory/courses/blob/main/3/s3_workbook.ipynb) is an example that you can start with. This link takes you to the `Colab` user interface, where you will have to select `Save a copy in drive` in order to be able to make edits.
- Two examples of using data from APIs:
	1. The Economics Observatory API
		-  [🥾s3_chart1.json](3/s3_chart1.json): A dynamic chart specification showing French unemployment using ECO API data
		-  [👟s3_chart2.json](3/s3_chart2.json): A template for making charts with the ECO API
	2. FRED API:
		- [🥾s3_data_FRED-DGS10.json](3/s3_data_FRED-DGS10.json): Bond-yield data downloaded directly from FRED
		- [🥾s3_chart3.json](3/s3_chart3.json): A chart specification using data from the FRED API uploaded to GitHub
		-  [👟s3_chart4.json](3/s3_chart4.json): A template for making charts with cached FRED data 
- Slides: [s3_Accessing_data_programmatically.pdf](3/s3_Accessing_data_programmatically.pdf)
	
✅ **Checkpoint:** By the end of this session, you will have explored Python as a way to batch download data, and will have embedded one more chart into your website (displaying data accessed via Python).
## Session 4: Advanced visualisations – beyond two dimensions

By this stage you have a live site and can update a long list of data series at the click of a button. Session 4 adds interactivity and new dimensions to charts. If time permits, we can also begin to explore choropleth maps (if not, we have a video for this). By the end of session 4, the websites will start to come alive, with dropdown menus, hover tools and scrollers adding dynamism to the data.

**Resources**
- Four advanced chart examples:
	- Scatter Plots: 
		- [🥾 s4_chart1.json](4/s4_chart1.json)
        - [👟 s4_chart2.json](4/s4_chart2.json)
	-  Maps:  
		- [👟 s4_chart3.json](4/s4_chart3.json)
		- [🗻 s4_chart4.json](4/s4_chart4.json) 
- Further examples, increasing in complexity: 
	- [🗻 s4_more_example_charts](4/s4_more_example_charts/)
- Slides: [4_Advanced_visualisations.pdf](4/4_Advanced_visualisations.pdf)

✅ **Checkpoint:** By the end of this session, you will have explored a range of interactive and multi-dimension charts, and added at least one of them to your website. This is a change to explore and edit, helping your page to come alive.

## Session 5:	Scrapers – fetching data programmatically

Sometimes there is no API is available and there is no obvious source of data in a clean format. Here we turn to scraping. Participants will embed a chart that uses a scaped data source. This brings together all our tools: `Python` and `JavaScript`, then `HTML` and `CSS`. The day finishes with tidying up participants’ websites, meaning everyone goes home with a page they can be proud of and a host of new skills.

**Resources**
- An advanced notebook, introducing scraping
	-  [🗻 Session_5_Scraping.ipynb](https://colab.research.google.com/github/EconomicsObservatory/courses/blob/main/5/Session_5_Scraping.ipynb)
- An example of scraped data: [s5_eco_words.csv](5/s5_eco_words.csv)
- A chart using the scraped data: [s5_chart1.json](5/s5_chart1.json)
- Slides: [s5_scraping_data.pdf](5/s5_scraping_data.pdf)

✅ **Checkpoint:** By the end of this session, you will have seen Python in action again – this time to scrape data from an external website like Wikipedia. You will also have added one last chart to your website, displaying data accessed via a scraper.
## 🚀 Takeaways

#### 1.  Personal webpage
- GitHub account with a repository created to serve as your personal webpage, configured, styled and formatted.
#### 2. Data portfolio
- 6 charts from a wide range of data sources – including batch downloads, an API, and a web scraper – embedded into your personal page. At least one higher-dimension/interactive visualisation added too.
#### 3. A new skillset
- The language of data _is_ visualisation. By the end of this course you will have learnt how to introduce yourself in this new language.

##### 🎮 Action points

- Please think about what you might include on your webpage and what data you might use. You can use any data you like, but we will also provide example datasets for you to use.
- If you would like to create a specific chart, we can help you build it – but consider the range of possibilities in the [Vega-Lite Example Gallery](https://vega.github.io/vega-lite/examples/).


### 🗂️ Resources

- [Heroes and heroines](https://www.playfairprize.com/william-playfair)   
Biographies of some key figures in data, past and present.
- [Nightingale Magazine](https://www.playfairprize.com/william-playfair)  
The publication of the [Data Visualization Society](https://www.datavisualizationsociety.org/)
  - [Finding the perfect blend of text and data](https://www.youtube.com/watch?v=eypYInYEVlA)  
    A talk by Dénes Csala at the Data Visualization Society's Outlier 2023 Conference
- [MDN Starters guide](https://www.playfairprize.com/william-playfair)  
  A superb intro to HTML, CSS and JavaScript from [Mozilla](https://www.mozilla.org/en-US/?v=1).
- [W3Schools](https://www.w3schools.com/)  
  An equally superb intro to HTML, CSS and JavaScript from the [World Wide Web Consortium](https://www.w3.org/).

