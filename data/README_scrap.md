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
| Session |    Time     |                Topic                 |Tool|
| :-----: | :---------: | :----------------------------------: | :----------------------------------:|
|    0    | 09:00-09:30 |               Setting up             ||
|    1    | 09:30-10:30 |            Charts as data  |Vega-editor|<!-- / Only browser / vega editor           | //charting principles 30 min //30 min charts as data Vega (just show, no code-along) //3 ways of data embed - hard coded, csv, api url -->
|  Break  | 10:30-11:00 |             Coffee break             ||
|    2    | 11:00-12:30 |      Building your first website |VSCode|
 |  Break  | 12:30-13:15 |             Lunch break              |BYOD!|<!-- - 3 embedded charts / 3 ways (even if using our provided csv/api) - but pretty boilerplate - -->
|    3    | 13:15-14:15 |        Acessing data programatically|Google Colab|
|    4    | 14:15-15:15 |        Advanced visualisations| VSCode/Vega-editor|
|  Break  | 15:15-15:30 |             Coffee break             ||
|    5    | 15:30-16:30 | Data scraping | |
|    6    | 16:30-17:00 | Epilogue||

## 2
(there is wiggle room here) out of the box html that just works and has a chart on the page - embeddign in 2 wass - direct json in jsvascript, link to json file (this is difficult, needs a lot of config for vega embed and files)  - needs good template files - need to try out the process on the codespace saving files + css - 3 tiers - CSS templates with CSS comments for instructions - including how to publish on github
HTML
CSS
point out script
JSON - references Vega Lite specs
Two spec: simple bar chart or alike + real chart we made recently
Go to Vega eidtor, look at  another spec, bring it into VSCode, save over chart 1
Then abserve the page changing
Then bring in anotehr spec and create  a 3rd chart
back to vega editor, create their own spec, bring it into the envrionment, embed as a 3 chart
3 simple datasets / eco api
FULL RAW link to the file itslef in the datsets fodler - README
We need to create 5 datasets/ 3-4 dimensions, 20 adatapoints each max - nice labels / NICE TO HAVE - more, real-world data

TODO - Finn/Josh Beefing up the comments / Simple datasets
TODO - Denes / datasets linking onto README

## 2-3 break
ANY CHART ANY DATA - BYOD - lets convince 3-4 people 

TODO - Charlie should sned out an alert for BYOD? 2 days before?

Customising to your needs
Intro to Colab? - already in the video

## 3
python in dekstop/codespace, but it needs setup) - Slides - here we will need a precise intructions on how to copy paste files between the systems      | 20 min slides / 40 min coding !
Default Colab Colab links only, NO ipynb FILES
Embed one more chart - custom data, not prepackaged example / introduce python for loops and if statements

Python examples need creating from scratch
General intro section / vairabels/operations/colab interface Markdown comments
IF statement
For loop - with dummy data
Data strcutures - list dictionayr - translated into JSON array/object but the syntax stays the same
Load csv data with pandas
Loop through loading multiple datasets - merging them toegether
Basic pandas transformation -referenceing columns, rows, replacing nulls, erorrs, strings edits, cerating new columns, summarization/groupby
Stick to CSV
ANother JSON file that they can embed into their website
  Then a chart spec json.
  Data source csv
  Chart spec needs to references the data source csv

TODO - Denes start and defined structure / pregenerated file export for hte looped dataset
TODO - Josh - fill with content FOR example

## 4
what is section 1 now / streamline the reaminign of section 1 / code-along examples for 3 and 4 D visuals - e.g. scatter plot with circle sizes or colors, tier 2 - 4D tooltip/shape, trellis/ tier 3 - map, parallel cordinates or something exotic - these are difficult, so lots' of examples on every level / data transformations / aggregate/calculated variable and join for the geojson

Several types of "advanced" visualisation - more example 9-10 - each doing a differnet function / add toolip / add shape/color/ format axes /add legend /map 
They edit their chart type in the vega editor
- they go back to the python part edit their data
- go back HTML part and emebd chart

TODO - Select advanced visualisation types/pregenerate a JSON specs 
TODO defining the cases for "Advanced viz"
TODO doing the examples Finn

(5th chart)


## 5
table / wikipedia / observatory site - nicely commented jupyter notebook for scraping wikipedia / tier 2 - bs4, understadning html srouce code and reverse engineering the structure - rbing 5 very nice examples site  / tier 3 just show and tell on how does this work for hte case of a large project - Finns - 
Notebook

TODO - Finn/Josh - Colab notebook with comments read_html + bs4 + /Selenium code or presnetation (10 min)

outcome is  chart where the data is via a scraper (6 charts in total) - the top of the visualisation climbing wall/different routes

## 📑 Syllabus

### Session 1 - Charts as data

General comments
Tiers within each section / color code it! let's call it the //climbing the visualisation hill!!

### Session 2 - Building your first website

`Coordinated by: Prof Richard Davies`  
  
🔖 In the first session we introduce HTML, CSS and JavaScript as you build and style your first website. You will also embed your first automated and interactive charts.

#### a.	Introduction + building blocks

-	Motivation   
What is good Data Science? Where does it sit? Principles.
- Web building blocks: HTML, CSS and JS  
(visualisations are _just 🌟 fancy 🌟 websites_ built from components)
- Building your first interactive web site
- [GitHub](https://github.com/) pages
- Introduction 

#### b.	Charting principles
- The good the bad and the ugly
- History
- Good charting guide
- Making two live and interactive charts
- Introduction to charting libraries

#### 🎮 Action points

- ▶️ Please watch [this introductory video](https://youtu.be/Sv-O9uwWd7M )
- Set up your own [GitHub](https://github.com/) account at `username` and repository at `username.github.io`. For example, Richard’s account is `RDEconomist`, so his special repository is `RDEconomist.github.io`. Repositories are like an on-line folder and you can, in general, name them as you wish. But this is a special case, which must be exactly your username. This special repository becomes your website which GitHub hosts for you, *free of charge*. After taking these steps, your GitHub should look like [this](https://github.com/eco-demo-student).
- Create a demo `index.html` page in your repository and add 3 sentences about yourself.:
  -  Why are you here?
  -  What is your level experience?
  -  What would you like to learn?
-  You should end up with something like [this](https://eco-demo-student.github.io/).


### Session 3 - Accessing data programatically

`Coordinated by: Dr Dénes Csala`  

🔖 In our third session we turn the coding up a notch and access data from the web - including websites but also dedicated data transfer interfaces - *API*s, discussing the benefits, pitfalls and debugging. Visualisations are the language of data for 🧑‍🦲 *humans*, while APIs are the language of data for 🤖 *computers*.

#### a. Introduction to data formats

- `python`
  - `python` dictionaries and lists
  - `pandas` - not this one 🐼, 
  but the excellent [`Python Data Analysis Library`](https://pandas.pydata.org/)
- `JavaScript`
  - `JSON` JavaScript Objects and Arrays

#### b. Automated data access 🧙

- `ECO API` - the Economics Observatory's API
- Introductory web scraping with `pandas` `read_html`
- Advanced web scraping with `BeautifulSoup`
- Browser automation with `Selenium`

### Session 4 - Advanced visualisations

`Coordinated by: Dr Dénes Csala`  

🔖 The last session of the day is an introduction to data visualisation principles and data models. We will also set some time aside to work on your personal data projects.

#### a.	The language of data – the grammar of graphics

- Visual encodings
- The visualization zoo 🦒🦣🦘🦥
  -  Introduction to chart types
  - Which chart to use when
- Data storytelling with interactive charts
- Basic principles of machine learning

#### b.	Data project

To finish off your course, you will work individualy or in small groups to create a data visualisation portfolio piece. You will be able to choose from a number of datasets, or you can bring your own data (see the **BYOD** section below). Our team be on hand to help you with any questions you might have.

Your finished portfolio should include a formatted and styled GitHub page with a short description of your project and 3 embedded visualisations. You will also be able to present your work to the rest of the class.  

You may end up with something like [this](https://economicsobservatory.github.io/courses/data/html/portfolio_sample/).

Ideally, your portfolio should include at least `3 charts`:
- One example chart that we used in the class, but has a slight modification and an interactive component - this could be a legend, a tooltip, a slider, a dropdown, etc.
-	A chart with automated data loading through an API or web scraping
-	A chart about a topic that you especially care about

### Session 5 - Data scraping

`Coordinated by: Finn McEvoy`  

🔖 The last session of the day is an introduction to data visualisation 

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


=======
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
| Session |    Time     |                Topic                 |Tool|
| :-----: | :---------: | :----------------------------------: | :----------------------------------:|
|    0    | 09:00-09:30 |               Setting up             ||
|    1    | 09:30-10:30 |            Charts as data  |Vega-editor|<!-- / Only browser / vega editor           | //charting principles 30 min //30 min charts as data Vega (just show, no code-along) //3 ways of data embed - hard coded, csv, api url -->
|  Break  | 10:30-11:00 |             Coffee break             ||
|    2    | 11:00-12:30 |      Building your first website |VSCode|
 |  Break  | 12:30-13:15 |             Lunch break              |BYOD!|<!-- - 3 embedded charts / 3 ways (even if using our provided csv/api) - but pretty boilerplate - -->
|    3    | 13:15-14:15 |        Acessing data programatically|Google Colab|
|    4    | 14:15-15:15 |        Advanced visualisations| VSCode/Vega-editor|
|  Break  | 15:15-15:30 |             Coffee break             ||
|    5    | 15:30-16:30 | Data scraping | |
|    6    | 16:30-17:00 | Epilogue||

## 2
(there is wiggle room here) out of the box html that just works and has a chart on the page - embeddign in 2 wass - direct json in jsvascript, link to json file (this is difficult, needs a lot of config for vega embed and files)  - needs good template files - need to try out the process on the codespace saving files + css - 3 tiers - CSS templates with CSS comments for instructions - including how to publish on github
HTML
CSS
point out script
JSON - references Vega Lite specs
Two spec: simple bar chart or alike + real chart we made recently
Go to Vega eidtor, look at  another spec, bring it into VSCode, save over chart 1
Then abserve the page changing
Then bring in anotehr spec and create  a 3rd chart
back to vega editor, create their own spec, bring it into the envrionment, embed as a 3 chart
3 simple datasets / eco api
FULL RAW link to the file itslef in the datsets fodler - README
We need to create 5 datasets/ 3-4 dimensions, 20 adatapoints each max - nice labels / NICE TO HAVE - more, real-world data

TODO - Finn/Josh Beefing up the comments / Simple datasets
TODO - Denes / datasets linking onto README

## 2-3 break
ANY CHART ANY DATA - BYOD - lets convince 3-4 people 

TODO - Charlie should sned out an alert for BYOD? 2 days before?

Customising to your needs
Intro to Colab? - already in the video

## 3
python in dekstop/codespace, but it needs setup) - Slides - here we will need a precise intructions on how to copy paste files between the systems      | 20 min slides / 40 min coding !
Default Colab Colab links only, NO ipynb FILES
Embed one more chart - custom data, not prepackaged example / introduce python for loops and if statements

Python examples need creating from scratch
General intro section / vairabels/operations/colab interface Markdown comments
IF statement
For loop - with dummy data
Data strcutures - list dictionayr - translated into JSON array/object but the syntax stays the same
Load csv data with pandas
Loop through loading multiple datasets - merging them toegether
Basic pandas transformation -referenceing columns, rows, replacing nulls, erorrs, strings edits, cerating new columns, summarization/groupby
Stick to CSV
ANother JSON file that they can embed into their website
  Then a chart spec json.
  Data source csv
  Chart spec needs to references the data source csv

TODO - Denes start and defined structure / pregenerated file export for hte looped dataset
TODO - Josh - fill with content FOR example

## 4
what is section 1 now / streamline the reaminign of section 1 / code-along examples for 3 and 4 D visuals - e.g. scatter plot with circle sizes or colors, tier 2 - 4D tooltip/shape, trellis/ tier 3 - map, parallel cordinates or something exotic - these are difficult, so lots' of examples on every level / data transformations / aggregate/calculated variable and join for the geojson

Several types of "advanced" visualisation - more example 9-10 - each doing a differnet function / add toolip / add shape/color/ format axes /add legend /map 
They edit their chart type in the vega editor
- they go back to the python part edit their data
- go back HTML part and emebd chart

TODO - Select advanced visualisation types/pregenerate a JSON specs 
TODO defining the cases for "Advanced viz"
TODO doing the examples Finn

(5th chart)


## 5
table / wikipedia / observatory site - nicely commented jupyter notebook for scraping wikipedia / tier 2 - bs4, understadning html srouce code and reverse engineering the structure - rbing 5 very nice examples site  / tier 3 just show and tell on how does this work for hte case of a large project - Finns - 
Notebook

TODO - Finn/Josh - Colab notebook with comments read_html + bs4 + /Selenium code or presnetation (10 min)

outcome is  chart where the data is via a scraper (6 charts in total) - the top of the visualisation climbing wall/different routes

## 📑 Syllabus

### Session 1 - Charts as data

General comments
Tiers within each section / color code it! let's call it the //climbing the visualisation hill!!

### Session 2 - Building your first website

`Coordinated by: Prof Richard Davies`  
  
🔖 In the first session we introduce HTML, CSS and JavaScript as you build and style your first website. You will also embed your first automated and interactive charts.

#### a.	Introduction + building blocks

-	Motivation   
What is good Data Science? Where does it sit? Principles.
- Web building blocks: HTML, CSS and JS  
(visualisations are _just 🌟 fancy 🌟 websites_ built from components)
- Building your first interactive web site
- [GitHub](https://github.com/) pages
- Introduction 

#### b.	Charting principles
- The good the bad and the ugly
- History
- Good charting guide
- Making two live and interactive charts
- Introduction to charting libraries

#### 🎮 Action points

- ▶️ Please watch [this introductory video](https://youtu.be/Sv-O9uwWd7M )
- Set up your own [GitHub](https://github.com/) account at `username` and repository at `username.github.io`. For example, Richard’s account is `RDEconomist`, so his special repository is `RDEconomist.github.io`. Repositories are like an on-line folder and you can, in general, name them as you wish. But this is a special case, which must be exactly your username. This special repository becomes your website which GitHub hosts for you, *free of charge*. After taking these steps, your GitHub should look like [this](https://github.com/eco-demo-student).
- Create a demo `index.html` page in your repository and add 3 sentences about yourself.:
  -  Why are you here?
  -  What is your level experience?
  -  What would you like to learn?
-  You should end up with something like [this](https://eco-demo-student.github.io/).


### Session 3 - Accessing data programatically

`Coordinated by: Dr Dénes Csala`  

🔖 In our third session we turn the coding up a notch and access data from the web - including websites but also dedicated data transfer interfaces - *API*s, discussing the benefits, pitfalls and debugging. Visualisations are the language of data for 🧑‍🦲 *humans*, while APIs are the language of data for 🤖 *computers*.

#### a. Introduction to data formats

- `python`
  - `python` dictionaries and lists
  - `pandas` - not this one 🐼, 
  but the excellent [`Python Data Analysis Library`](https://pandas.pydata.org/)
- `JavaScript`
  - `JSON` JavaScript Objects and Arrays

#### b. Automated data access 🧙

- `ECO API` - the Economics Observatory's API
- Introductory web scraping with `pandas` `read_html`
- Advanced web scraping with `BeautifulSoup`
- Browser automation with `Selenium`

### Session 4 - Advanced visualisations

`Coordinated by: Dr Dénes Csala`  

🔖 The last session of the day is an introduction to data visualisation principles and data models. We will also set some time aside to work on your personal data projects.

#### a.	The language of data – the grammar of graphics

- Visual encodings
- The visualization zoo 🦒🦣🦘🦥
  -  Introduction to chart types
  - Which chart to use when
- Data storytelling with interactive charts
- Basic principles of machine learning

#### b.	Data project

To finish off your course, you will work individualy or in small groups to create a data visualisation portfolio piece. You will be able to choose from a number of datasets, or you can bring your own data (see the **BYOD** section below). Our team be on hand to help you with any questions you might have.

Your finished portfolio should include a formatted and styled GitHub page with a short description of your project and 3 embedded visualisations. You will also be able to present your work to the rest of the class.  

You may end up with something like [this](https://economicsobservatory.github.io/courses/data/html/portfolio_sample/).

Ideally, your portfolio should include at least `3 charts`:
- One example chart that we used in the class, but has a slight modification and an interactive component - this could be a legend, a tooltip, a slider, a dropdown, etc.
-	A chart with automated data loading through an API or web scraping
-	A chart about a topic that you especially care about

### Session 5 - Data scraping

`Coordinated by: Finn McEvoy`  

🔖 The last session of the day is an introduction to data visualisation 

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
