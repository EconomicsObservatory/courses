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

  - 🥾 Hiker - best suited for those who have created some nicer-looking charts before, trialing various tools, but didn't really approach the subject in a structured way.
  - 👟 Trail runner - best suited for those who can cruise through basic functions such as setting up coding environments and we can focus on the visualisation part straight away
  - 🗻 Mountaineer - best suited for those who have spent a bivouac debugging data scraper running overnight

You will gain the skills and tools needed to create excellent charts. The course will also signpost additional resources to develop the ideas further, allowing participants to gain confidence in their own abilities and teach others. The latter stages of the course will delve deeper into the current information representation and science communication theory, exploring more advanced data visualisation methods.


## 🕒 Schedule
| Time | Section | Details |
| ---- | ---- | ---- |
| 09.00 - 09.30 |  | Welcome coffee. Checking computer set ups. |
| 09.30 - 10.30 | 1 | Charts as data – introducing Vega-Lite |
| 10.30 - 11.00 | _Break_ | _Coffee/tea (team available to fix bugs)_ |
| 11:00 - 12.30 | 2 | My first website – GitHub, HMTL, CSS and JavaScript |
| 12.30 - 13.15 | _Lunch_ | _Lunch (team available to fix bugs)_ |
| 13.15 - 14.15 | 3 | Programming – APIs, if statements, and loops. |
| 14.15 - 15.15 | 4 | Advanced visualisations – beyond two dimensions |
| 15:15 - 15:30 | _Break_ | _Coffee/tea (team available to fix bugs)_ |
| 15.30 - 16.30 | 5 | Scraping – fetching data with Python |


## Session 1: Charts as data

The day starts with ‘The Good, The Bad and The Ugly’ of charts as we briefly discuss charts to make <a href="https://www.playfairprize.com/william-playfair"> data pioneers </a> shudder. In this session analysts build a chart as a JSON specification. These files contain information on where to find the data, and how the axes should look. These chart instructions are themselves a type of data: so they are shareable, replicable and verifiable.

**Resources:**
- Including data, three ways: [chart1_data_inline.json](1/chart1_data_inline.json), [chart2_data_linked.json](1/chart2_data_linked.json) and [chart3_data_from_api.json](1/chart3_data_from_api.json)

## Session 2: Building a live web site
By now participants have a live chart ready to embed. Next, they build their own website, discovering the simple tools that allow this. We make a live site (GitHub Pages) before creating a space for visualisations and adding some text description (HTML). This site is briefly beautified and personalised (CSS) before we finally embed the charts built in session 1 (JavaScript).

**Resources:**
- A template to use for your website: [example_1.html](2/example1.html)
- Three options for CSS Stylesheets, to customise your website:
	1. [example_1.css](2/example1.css): a clean and full example with all the work done for you
	2. [example_2.css](2/example2.css): a minimal example containing instructions to help you style the website
	3. [example_3.css](2/example3.css): a more complex example, placing charts and descriptions side-by-side 

## Session 3: Fetching data from APIs

Here we introduce APIs more formally, running through their strengths and pitfalls as sources of data. We also meet some workhorses of programming—if statements and loops—allowing us to batch download data. By the end of this third session, participants will have embedded another chart into their site, this time powered by an API. When new data are released, their chart will update – fully automatically.

## Session 4: Advanced visualisations – beyond two dimensions

By this stage participants have a live site and can update a long list of data series at the click of a button. Session 4 adds interactivity and new dimensions to charts. If time permits, participants can also begin to make choropleth maps (if not we have a video for this). By the end of session 4, the websites will start to come alive, with dropdown menus, hover tools and scrollers adding dynamism to the data.

**Resources**
- Three advanced chart examples:
	- Scatter Plots: [example_advanced1.json](4/example_advanced1.json) and [example_advanced2.json](4/example_advanced2.json),
	- A basic map:  [example_advanced3.json](4/example_advanced3.json)
- Further examples, increasing in complexity: [more_example_charts](4/more_example_charts/)

## Session 5:	Scrapers – fetching data programmatically

Sometimes there is no API is available and there is no obvious source of data in a clean format. Here we turn to scraping. Participants will embed a chart that uses a scaped data source. This brings together all our tools: Python and JavaScript, then HTML and CSS. The day finishes with tidying up participants’ websites, meaning everyone goes home with a page they can be proud of and a host of new skills.

**Resources**
- Basic Scraping - Extracting data from Wikipedia
	- [Google Colab Notebook](https://colab.research.google.com/drive/10kUr4WWFIQYT8A3OShUmeOJPiM62V6o4?usp=sharing)
	- Example Scraped Data: g7_summits.csv](5/g7_summits.csv) 
	- Example Chart Scraped Data: [chart_g7_meeting_hosts.json](5/example_charts/chart_g7_meeting_hosts.json)
- Advanced Scraping - HTML scraping
	- [Google Colab Notebook](https://colab.research.google.com/drive/1G_1LEeKJBECRMe7ucgddFM2TO0MbWzUe?usp=sharing)
	- Example Scraped Data: [top_words.csv](5/top_words.csv)
	- Example Chart Scraped Data: [chart_eco_top_words](5/example_charts/chart_eco_top_words.json)

## Pre-requisites
No prior coding experience is required. However, participants’ laptops will need to be set up to allow:
- Access to a personal GitHub account, accessible via Google Chrome.
- Access to Google Colaboratory, accessible via a working Google account.
- Visual Studio Code downloaded to desktop, or accessible online as a back-up option (see set-up video and slides).


#### 🎮 Action points

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

#### 🔴 ECO Visualisation Guidelines

Head over to our **[ECOvisualisations](https://github.com/EconomicsObservatory/ecovisualisations)** repository for all [Economics Observatory](https://www.economicsobservatory.com) charts sorted by article. We try to follow industry best-practices in data visualisation and try to establish our very own visualisation guidelines for all chart types. You can read about these, as well as the tools we use in [**📐visualisation guidelines**](https://github.com/EconomicsObservatory/ECOvisualisations/tree/main/guidelines).  

## 🖇️ Pre-requisites
We don't require any prior knowledge of programming or data science, other than high-school level mathematics and statistics. However, it helps us speed up things on the day if you do some preparation before the class:

- Take a look at [Google Colab](https://colab.research.google.com/)
- Take a look at [Visual Studio Code (*VSCode*) Online](https://vscode.dev/)

#### 🎮 Action points

- Set up a [*Google* account](https://accounts.google.com/signup/v2/createaccount)  
  If you already have a *Google* account, but would be using using *Colab* for the first time, you will need to accept their specific terms and conditions for *Colab*. You can do this after setting up a [new workbook in *Colab*](https://colab.research.google.com/#create=true).

🐘 *If you know what you are doing, you are also welcome to use any `python` distribution, such as [Jupyter](https://jupyter.org/), [Anaconda](https://www.anaconda.com/) or [PyCharm](https://www.jetbrains.com/pycharm/).

🦏 **If you *really* know what you are doing, just use the [`datascience-notebook`](https://hub.docker.com/r/jupyter/datascience-notebook) [Docker](https://www.docker.com/) image. Also, this course might not be for you 🙃

## 🔮 Tools & Software
We don't require any prior downloaded software for the masterclass (* You may use *any* text editor already installed on your system. You might already have [Sublime Text](https://www.sublimetext.com/), [Notepad++](https://notepad-plus-plus.org/) or [Atom](https://github.com/atom/atom/releases/tag/v1.60.0) on your system. The default *Notepad* in Windows is inadequate, as it is difficult to  format indents in it. However, we will conduct the common coding experience for the class in [*VSCode*](https://code.visualstudio.com/)). It helps us speed up things on the day if you do some preparation before the class:

- Take a look at [Visual Studio Code (*VSCode*) Desktop](https://code.visualstudio.com/docs)
- Take a look at the [Vega-Lite Visualisation Grammar](https://vega.github.io/vega-lite/) and the [Vega-Lite Example Gallery](https://vega.github.io/vega-lite/examples/)
  - Vega-Lite is based on the [Grammar of Graphics](https://www.springer.com/gp/book/9780387245447) by [Leland Wilkinson](https://en.wikipedia.org/wiki/Leland_Wilkinson), which is the basis of the [ggplot2](https://ggplot2.tidyverse.org/) package in `R` and the [Altair](https://altair-viz.github.io/) package in `python`. It is also the basis of the [Vega](https://vega.github.io/vega/) visualisation grammars, which [Vega-Lite](https://vega.github.io/vega-lite/) is a simplification of.

#### 🎮 Action points

- [Download and install *VSCode*](https://code.visualstudio.com/) for your operating system
  - If you cannot download/install *VSCode*, you can use the [`VSCode Online`](https://vscode.dev/) version in your browser
- Install the [Live Server](https://marketplace.visualstudio.com/items?itemName=ritwickdey.LiveServer) plugin for *VSCode*  
- Test that the [Simple Bar Chart](https://vega.github.io/editor/#/examples/vega-lite/bar) example in the [Vega Editor](https://vega.github.io/editor/) works in your browser
  - If you get blank screen at first, try clicking on the `Fulscreen` button in the top right corner of the right pane of the editor

🐘 *If you know what you are doing, you are welcome to use *any* text editor, provided that you also know how to establish a live server with `ptyhon`, such as [`SimpleHTTPServer`](https://www.pythonforbeginners.com/modules-in-python/how-to-use-simplehttpserver) or [`wutch`](https://www.linkedin.com/pulse/introducing-wutch-python-based-live-server-vagiz-duseev/).  
🦏 *If you *really* know what you are doing, you are also welcome to skip the these steps and use an all-in-browser development environment like [*Codepen*](https://codepen.io/)

## 📊 Datasets
**BYOD: We encourage you to Bring Your Own Data to the masterclass**.   
It can be data about everything, the financial report from the the last quarter or your sales logbook from your small coffee shop. It can be in any format `CSV, Excel, Stata, Matlab, JSON, etc.`  - or even just a table from a website, up to a cumbersome `API` call, we'll work with it.


If you want to look beyond, these data repositories are widely used by the community  
- https://huggingface.co/datasets  
- https://visualdata.io/discovery  
- https://paperswithcode.com/datasets  

#### 🎮 Action points

- If you **BYOD**, the	targeted complexity should be around `1000 data points` in at least `3 dimensions`. Say you have a small shop and you have sales data about `3` products – this counts as `3` dimensions: the `sales value` (time series), the `time` (record date) and the `product` (name). Even better if you have this for different `cities` – a `4`th dimension.

🐘 *If you know what you are doing, convert your data into `JSON` format or just ping us the link to **any `API`** that you would like to explore a day before the class.  

🦏 If you *really* know what you are doing, send us a link to your `*.ipynb` file or *Colab notebook* with any questions related to it a day before the class.

### Dataset Finders
 
Similar to how [Google Scholar](https://scholar.google.com/) works, [Google Dataset Search](https://toolbox.google.com/datasetsearch) lets you find datasets wherever they are hosted, whether it’s a publisher’s site, a digital library, or an author’s web page. It’s a phenomenal dataset finder, and it contains over 25 million datasets.

[Kaggle](https://www.kaggle.com/) provides a vast container of datasets, sufficient for the enthusiast to the expert.

The [UCI Machine Learning Repository](https://archive.ics.uci.edu/) at [UCI](https://www.uci.edu/) provides an up to date resource for open-source datasets.

[VisualData](https://www.visualdata.io/): Discover computer vision datasets by category; it allows searchable queries.

[CMU Libraries](https://guides.library.cmu.edu/machine-learning/datasets
)): Discover high-quality datasets thanks to the collection of Huajin Wang, at [CMU](https://www.cmu.edu/).

The [The Big Bad NLP Database](https://datasets.quantumstat.com/) contains datasets for various natural language processing tasks, created and curated by [Quantum Stat](https://quantumstat.com/).

Even more:  
[V7 | Alberto Rizzoli](https://www.v7labs.com/blog/best-free-datasets-for-machine-learning)  
[TowardsAI | Stacy Stanford, Roberto Iriondo, Pratik Shukla](https://pub.towardsai.net/best-datasets-for-machine-learning-data-science-computer-vision-nlp-ai-c9541058cf4f)  

#### 🔴 ECO Data Guidelines 
While all of our chart data are published under their respective article subfolders in **[ECOvisualisations](https://github.com/EconomicsObservatory/ecovisualisations)**, we also operate the [Economics Observatory Data Hub](https://www.economicsobservatory.com/data-hub), where you will find interactive tools and visualisations to easily load data from a number of sources in a unified format. Whenever possible, we try to follow a [TIDY](http://vita.had.co.nz/papers/tidy-data.pdf) format and you can read about our data zen in [**📐data guidelines**](https://github.com/EconomicsObservatory/ECOdataHUB/tree/main/guidelines). 

## 🚀 Takeaways

### 1.  Personal webpage
- GitHub account with a repository created to serve as your personal webpage, configured, styled and formatted
### 2. Data portfolio
- `3` interactive data visualisations including one chart with an interactive element and another one with *live* data served from an API or scraped from a website.
### 3. A new skillset
- The language of data *is* visualisation and by the end of this course you will have learnt how to introduce yourself in this new language.