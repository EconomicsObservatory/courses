# ✨ Modern data visualisation ✨ 
An interactive masterclass by the **Economics Observatory**

[![GitHub license](https://img.shields.io/badge/license-MIT-blue.svg)](https://github.com/EconomicsObservatory/ecovisualisations/blob/main/LICENSE)

[**Website**](https://www.economicsobservatory.com/)
| [**Data Hub**](https://www.economicsobservatory.com/data-hub)
| [**Chart Examples**](https://richarddavies.io/charts)
| [**Data**](https://github.com/EconomicsObservatory/ECOdataHUB)
| [**Attendance sheet**](https://docs.google.com/spreadsheets/d/14F9BDCAYbULdZr5ecsEf7mygkuisYC-VW0nb87PS8ek/edit#gid=0)
| [**Feedback form**](https://forms.office.com/Pages/ResponsePage.aspx?id=_epnVXfnpUKRu5RA_UO4kzKG5Nj6E8VBqOrUBslU4RtUMURJSEFTRkc1M0dRUVZQSk8zUUNJNThLVS4u)

Welcome to our masterclass. At the **Economics Observatory (ECO)** we use data to amplify and distil the messages of our articles. Making charts clear and eye-catching, but also transparent and replicable, is critical. This masterclass is designed to share that workflow. We hope to give you a taste of the huge improvements on offer as data usage in the social sciences modernises.

<br>
<br>

## 🏔️ Scope

The course will take you from a being complete beginner to someone capable of designing and building stunning charts using cutting-edge tools, connected to live data. The course is designed to highlight the advantages and some caveats of using data visualisation for communicating information to a wide and diverse audience. It will also introduce some of our guiding principles for displaying data, focusing on transparency and how to select appropriate tools and methods for different datasets and contexts.

Throughout the day we signpost additional resources to develop the ideas further, allowing you to gain confidence in your own abilities and even teach others. 

<br>
<br>

## 🛠️ Pre-requisites
No prior coding experience is required. However, participants’ laptops will need to be set up to allow:
- Access to a personal `GitHub` account, accessible via Google Chrome.
- `Visual Studio Code` downloaded to desktop, or accessible online as a back-up option (see set-up video and slides).

<br>
<br>

## 🕒 Schedule
| Time          | Section | Details                                             |
| ------------- | ------- | --------------------------------------------------- |
| 09.00 - 09.30 |         | Warm up. Checking computer set ups. Your first site |
| 09.30 - 10.30 | 1       | Charts as data – introducing Vega-Lite              |
| 10.30 - 11.00 | _Break_ |                                                     |
| 11:00 - 12.30 | 2       | My first website – GitHub, HMTL, CSS and JavaScript |
| 12.30 - 13.15 | _Lunch_ |                                                     |
| 13.15 - 14.15 | 3       | Programming – APIs, if statements, and loops.       |
| 14.15 - 15.15 | 4       | Advanced visualisations – beyond two dimensions     |
| 15:15 - 15:30 | _Break_ |                                                     |
| 15.30 - 16.30 | 5       | Transforming Data                                   |

<br>
<br>

## Session 1: Charts as data

The day starts with an introduction from the **Economics Observatory Data Team**. In this session analysts build a chart as a ‘JSON specification’ (the modern way). These files contain information on where to find the data, and how the axes should look. These chart instructions are _themselves_ a type of data: they are shareable, replicable and verifiable.

**Resources:**
- We have prepared three example files highlighting the ‘charts as data’ principle, including the underlying data we want to display, delivered into your chart in three ways:
	1. Inline ([s1_chart1.json](1/s1_chart1.json))
	2. Linked ([s1_chart2.json](1/s1_chart2.json))
	3. API: ([s1_chart3.json](1/s1_chart3.json))
- Slides: [s1_Charts_as_data.pdf](1/s1_Charts_as_data.pdf)
- We have also prepared 5 very simple datasets to try using with Vega-lite.
	- [s1_example_data](1/s1_example_data)

✅ **Checkpoint:** By the end of this session, you will have seen all three JSON types, and will have added one of these files to your personal GitHub repository.

<br>
<br>

## Session 2: Building a live web site
By now you have a live chart (your JSON file) ready to embed into your website. But first you need to build a site to host it. We will show you the simple tools that allow this. First, we make a live site (`GitHub Pages`), before creating a space for visualisations and adding some text description (`HTML`). This site is briefly beautified and personalised (`CSS`) before we finally embed the charts built in session 1 (`JavaScript`).

**Resources:**
- A template to use for your website: [s2_example1.html](2/s2_example1.html)
- Three options for CSS Stylesheets, to customise your website:
	1. A clean and full example with all the work done for you ([s2_example1.css](2/s2_example1.css):)
	2. A minimal example containing instructions to help you style the website ( [s2_example2.css](2/s2_example2.css))
	3. A more complex example, placing charts and descriptions side-by-side ([🗻 s2_example3.css](2/s2_example3.css))
- Two example charts, to start your website:
	1. A simple bar chart showing the human development index (HDI) for 21 countries ([s2_chart1.json](2/s2_chart1.json))
	2. 1. an interactive scatter plot, showing Vega-Lite's potential ([s2_chart2.json](2/s2_chart2.json))
- Slides: [s2_Building_your_first_website.pdf](2/s2_Building_your_first_website.pdf)

✅ **Checkpoint:** By the end of this session, you will have your own website, with its own customised text and design. Your website will have at least three stunning charts.

<br>
<br>

## Session 3: Fetching data from APIs

Here we introduce APIs more formally, running through their strengths and pitfalls as sources of data. We also meet some workhorses of programming—if statements and loops—allowing us to batch download data. By the end of this third session, you will have embedded another chart into their site, this time powered by an API. When new data are released, their chart will update – fully automatically.

**Resources**
- This session starts to introduce you to coding in the `Python` language. We will use the online code editor `Google Colab` for this.
	- A notebook ([s3_workbook_ECO_API.ipynb](https://colab.research.google.com/github/EconomicsObservatory/courses/blob/main/3/s3_workbook_ECO_API.ipynb)) showing the construction of a dynamic charts using the Economics Observatory API.
	- An example notebook ([s3_workbook_Loops_APIs.ipynb](https://colab.research.google.com/github/EconomicsObservatory/courses/blob/main/3/s3_workbook_Loops_APIs.ipynb) ) [s3_workbook_Loops_APIs.ipynb](https://colab.research.google.com/github/EconomicsObservatory/courses/blob/main/3/s3_workbook_Loops_APIs.ipynb)) using loops to fetch data from the FRED API.
	- A bonus notebook ( [s3_extra_python_examples.ipynb](https://colab.research.google.com/github/EconomicsObservatory/courses/blob/main/3/s3_extra_python_examples.ipynb)) with some additional context for coding with Python.
- Two examples of using data from APIs:
	1. FRED API:
		- Bond-yield data downloaded directly from FRED ([s3_data_FRED-DGS10.json](3/s3_data_FRED-DGS10.json))
		- A chart specification using data from the FRED API uploaded to GitHub ([s3_chart1.json](3/s3_chart1.json))
		- A template for making charts with cached FRED data ([s3_chart2.json](3/s3_chart2.json))
	2. The Economics Observatory API
		-  A dynamic chart specification ([s3_chart3.json](3/s3_chart3.json)) showing Australian unemployment built using the [s3_workbook_ECO_API.ipynb](https://colab.research.google.com/github/EconomicsObservatory/courses/blob/main/3/s3_workbook_ECO_API.ipynb) notebook.
- Slides: [s3_Accessing_data_programmatically.pdf](3/s3_Accessing_data_programmatically.pdf)
	
✅ **Checkpoint:** By the end of this session, you will have explored Python as a way to batch download data, and will have embedded one more chart into your website (displaying data accessed via Python).

<br>
<br>

## Session 4: Advanced visualisations – beyond two dimensions

By this stage you have a live site and can update a long list of data series at the click of a button. Session 4 adds interactivity and new dimensions to charts. If time permits, we can also begin to explore choropleth maps (if not, we have a video for this). By the end of session 4, the websites will start to come alive, with dropdown menus, hover tools and scrollers adding dynamism to the data.

**Resources**
- Four advanced chart examples:
	- Scatter Plots: 
		- A simple plot of US gun crime ([s4_chart1.json](4/s4_chart1.json))
        - A more advanced bubble plot ([s4_chart2.json](4/s4_chart2.json))
	-  Maps:  
		- GDP per capita around the world ([s4_chart3.json](4/s4_chart3.json))
		- Literacy rates in India ([🗻 s4_chart4.json](4/s4_chart4.json))
		- Household incomes by UK region ([s4_chart5.json](4/s4_chart5.json))
		- US life expectancy by state ([s4_chart6.json](4/s4_chart6.json))
		- Population by UK ITL1 region ([s4_chart7.json](4/s4_chart7.json))
		- Inactivity rate by UK ITL3 region ([s4_chart8.json](4/s4_chart8.json))

- Further examples, increasing in complexity ([🗻 s4_more_example_charts](4/s4_more_example_charts/))
- Data, for use with maps ([🗻 s4_map_data](4/map_data/))
- Slides: [s4_Advanced_visualisations.pdf](4/s4_Advanced_visualisations.pdf)

✅ **Checkpoint:** By the end of this session, you will have explored a range of interactive and multi-dimension charts, and added at least one of them to your website. This is a change to explore and edit, helping your page to come alive.

<br>
<br>

## Session 5:	Transforming Data

Cleaning and transforming data is a fundamental stage in a modern data workflow. In this session, participants will learn how to use `Python` with the `Pandas` library to manage and bring together data effectively. Fetching Indian trade data from the Economics Observatory API, participants will merge and transform the series with `Pandas` and produce an interactive chart to embed on their page. This brings together all our tools: `Python` and `JavaScript`, then `HTML` and `CSS`. The day finishes with tidying up participants’ websites, meaning everyone goes home with a page they can be proud of and a host of new skills.

**Resources**
- A notebook, introducing data transformation with `Pandas`
	-  [s5_transforming_data.ipynb](https://colab.research.google.com/github/EconomicsObservatory/courses/blob/main/5/s5_transforming_data.ipynb)
- Data, fetched and transformed during the session ([s5_indian_trade_data.csv](5/s5_indian_trade_data.csv))
- Two charts using the Indian trade data:
	- A simple line chart ([s5_chart1.json](5/s5_chart1.json) )
	- A chart with more styling applied ([s5_chart2.json](5/s5_chart2.json))
- Slides: [s5_transforming_data.pdf](5/s5_transforming_data.pdf)

✅ **Checkpoint:** By the end of this session, you will have seen Python in action again – this time to fetch, merge and transform series from the Economics Observatory API. You will also have added one last chart to your website, displaying data from this session.

<br>
<br>

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

<br>
<br>

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

