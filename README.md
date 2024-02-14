<div align="left"><img src="https://raw.githubusercontent.com/EconomicsObservatory/ECOvisualisations/main/guidelines/logos/eco-bg-dark.png" width="800"/></div>

# ✨ The language of (economic) data is visualisation ✨ 
An interactive masterclass by the **Economics Observatory**

[![GitHub license](https://img.shields.io/badge/license-MIT-blue.svg)](https://github.com/EconomicsObservatory/ecovisualisations/blob/main/LICENSE)

[**Website**](https://www.economicsobservatory.com/)
| <ins>[**Courses**](https://github.com/EconomicsObservatory/courses)</ins>
| [**Visualisations**](https://github.com/EconomicsObservatory/ECOvisualisations)
| [**Data**](https://github.com/EconomicsObservatory/ECOdataHUB)
| [**API**](https://github.com/EconomicsObservatory/api)
|

Welcome to our interactive data masterclass. At the **Economics Observatory** we believe that the future of effective science communication is a blend of data and text. Dashboards without context are too cluttered and text without explanatory graphics is difficult to grasp. Therefore, we have partnered with educators from leading institutions across teh country to be able to offer masterclasses in [Writing](/writing) and [Data](/data).

In our day-to-day work the **Economics Observatory**, we use data to amplify and distil the messages of our articles. Making charts clear and eye-catching, while also ensuring that the underlying data are transparent and replicable, is critical to what we do. This masterclass is designed to capture and share that workflow.

## 🏔️ Scope

Our data visualisation masterclass will take you from a being complete beginner to someone capable of designing and building stunning charts using cutting-edge tools, connected to live data. The course is designed to highlight the advantages and some caveats of using data visualisation as the main channel for communicating (economic) information to a wide and diverse audience. It will also introduce some of our guiding principles on visualisation, focusing on transparency and how to select appropriate tools and methods for different datasets and contexts.

Throughout the course, we will offer and support 3 routes up the data mountain:

  - **🥾 Hiker** - best suited for those who have created some nicer-looking charts before, trialing various tools, but didn't really approach the subject in a structured way.
  - **👟 Trail runner** - best suited for those who can cruise through basic functions such as setting up coding environments and we can focus on the visualisation part straight away
  - **🗻 Mountaineer** - best suited for those who have spent a bivouac debugging data scraper running overnight

You will gain the skills and tools needed to create excellent charts. The course will also signpost additional resources to develop the ideas further, allowing participants to gain confidence in their own abilities and teach others. The latter stages of the course will delve deeper into the current information representation and science communication theory, exploring more advanced data visualisation methods.

## Pre-requisites
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

The day starts with an introduction from the **Economics Observatory Data Team**. In this session analysts build a chart as a `JSON` specification. These files contain information on where to find the data, and how the axes should look. These chart instructions are themselves a type of data: so they are shareable, replicable and verifiable.

**Resources:**
- Including data, delivered into your chart in three ways: 
	1. [chart1_data_inline.json](1/chart1_data_inline.json)
	2. [chart2_data_linked.json](1/chart2_data_linked.json)
	3. [chart3_data_from_api.json](1/chart3_data_from_api.json)

## Session 2: Building a live web site
By now participants have a live chart ready to embed. Next, they build their own website, discovering the simple tools that allow this. We make a live site (`GitHub Pages`) before creating a space for visualisations and adding some text description (`HTML`). This site is briefly beautified and personalised (`CSS`) before we finally embed the charts built in session 1 (`JavaScript`).

**Resources:**
- A template to use for your website: [example1.html](2/example1.html)
- Three options for CSS Stylesheets, to customise your website:
	1. [🥾 example1.css](2/example1.css): a clean and full example with all the work done for you
	2. [👟 example2.css](2/example2.css): a minimal example containing instructions to help you style the website
	3. [🗻 example3.css](2/example3.css): a more complex example, placing charts and descriptions side-by-side 

## Session 3: Fetching data from APIs

Here we introduce APIs more formally, running through their strengths and pitfalls as sources of data. We also meet some workhorses of programming—if statements and loops—allowing us to batch download data. By the end of this third session, participants will have embedded another chart into their site, this time powered by an API. When new data are released, their chart will update – fully automatically.

**Resources**
- This session starts to introduce you to coding in `python` language. We will use the online code editor `Google Colab` for this.
	- [3_workbook.ipynb](https://colab.research.google.com/github/EconomicsObservatory/courses/blob/main/3/3_workbook.ipynb) is an example that you can start with. This link takes you to the `Colab` user interface, where you will have to select `Save a copy in drive` in order to be able to make edits.
- Downloaded data files
	- [data_FRED-DGS10.json](3/data_FRED-DGS10.json)
	- [data_FRED-PCEPI.json](3/data_FRED-PCEPI.json)
- Chart specification files:
	- [chart_FRED-DGS10.json](3/chart_FRED-DGS10.json)
	- [chart_FRED-PCEPI.json](3/chart_FRED-PCEPI.json)

## Session 4: Advanced visualisations – beyond two dimensions

By this stage participants have a live site and can update a long list of data series at the click of a button. Session 4 adds interactivity and new dimensions to charts. If time permits, participants can also begin to make choropleth maps (if not we have a video for this). By the end of session 4, the websites will start to come alive, with dropdown menus, hover tools and scrollers adding dynamism to the data.

**Resources**
- Three advanced chart examples:
	- Scatter Plots: 
		- [🥾 example_advanced1.json](4/example_advanced1.json)
        - [👟 example_advanced2.json](4/example_advanced2.json)
	- A basic map:  
		- [👟 example_advanced3.json](4/example_advanced3.json)
- Further examples, increasing in complexity: 
	- [🗻 more_example_charts](4/more_example_charts/)

## Session 5:	Scrapers – fetching data programmatically

Sometimes there is no API is available and there is no obvious source of data in a clean format. Here we turn to scraping. Participants will embed a chart that uses a scaped data source. This brings together all our tools: `Python` and `JavaScript`, then `HTML` and `CSS`. The day finishes with tidying up participants’ websites, meaning everyone goes home with a page they can be proud of and a host of new skills.

**Resources**
- Basic Scraping - Extracting data from Wikipedia
	- [👟 Session_5_Scraping_basic.ipynb](https://colab.research.google.com/github/EconomicsObservatory/courses/blob/main/5/Session_5_Scraping_basic.ipynb) - opens in `Colab`
	- Example Scraped Data: [g7_summits.csv](5/g7_summits.csv) 
	- Example Chart Scraped Data: [chart_g7_meeting_hosts.json](5/example_charts/chart_g7_meeting_hosts.json)
- Advanced Scraping - HTML scraping
	- [🗻 Session_5_Scraping_advanced.ipynb](https://colab.research.google.com/github/EconomicsObservatory/courses/blob/main/5/Session_5_Scraping_advanced.ipynb) - opens in `Colab`
	- Example Scraped Data: [top_words.csv](5/top_words.csv)
	- Example Chart Scraped Data: [chart_eco_top_words.json](5/example_charts/chart_eco_top_words.json)

## 🚀 Takeaways

#### 1.  Personal webpage
- GitHub account with a repository created to serve as your personal webpage, configured, styled and formatted
#### 2. Data portfolio
- 6 charts from a wide range of data sources – including batch downloads, an API, and a web scraper – embedded into your personal page. At least one higher-dimension/interactive visualisation added too.
#### 3. A new skillset
- The language of data *is* visualisation and by the end of this course you will have learnt how to introduce yourself in this new language.

##### 🎮 Action points

- Please think about what you might include in your portfolio and what data you might use. You can use any data you like, but we will also provide some datasets for you to use.
- If you would like to create a specific chart, we can help you build it - but consider the range of possibilities in the [Vega-Lite Example Gallery](https://vega.github.io/vega-lite/examples/). 


### Resources

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

