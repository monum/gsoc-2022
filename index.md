# Google Summer of Code with the Mayor's Office of New Urban Mechanics (City of Boston)

Below, you will find a list of ideas we have for a Google Summer of Code contributors for the **summer of 2022**. Thank you for your consideration!

## Guidance for Applications and Project Proposals

You can find guidance for applications and your project proposals **[here](https://monum.github.io/gsoc-2022/guidance)**.

## Ideas List for 2022

### 1. Improved Translation for the City's 311 App with Machine Learning

In 2010, our office launched the City of Boston's [311 app](https://311.boston.gov/) (one of the first in the nation). The app allows residents to report an array on non-emergency issues (such as potholes) with their smartphones. Historically, the app has only been offered in English, and we have done some of the preliminary work to provide it in other languages. This is a very important issue to address, since up to 33% of the city does not speak English.

[Inspired by the City of San José](https://medium.com/swlh/better-language-translation-through-machine-learning-everything-i-wish-i-knew-6-months-ago-8fa212fb1731), we would like to build an API-accessible service that improves the translation of text from residents reporting issues through the 311 app. The translation service would be based on a custom, trained model using vocabulary frequently associated with City services. 

The ideal outcome would be having an API endpoint that would accept text from a 311 request and return translated text that could be easily understood by our City operations teams. We would also like to be able to benchmark the progress of this translation service against more general translation services.

We give this project a **medium to hard** level of difficulty. The project can be completed in **350 hours**.

This project will require intermediate experience with machine learning, building and training models with text classification, natural language processing, and Python. It will also require intermediate experience with building web service APIs with with a web framework like Flask, Django etc.

The mentors for the project will include two Program Directors at the Mayor's Office of Urban Mechanics, including one who served as a Google Summer of Code mentor at Code for America in 2011 and the City of Boston in 2021.

### 2. Dashboard for Equity in City Infrastructure

At the Mayor's Office of New Urban Mechanics, we are focused on helping City departments create innovative services that are accessible, equitable, and delightful. We would like to build a tool that helps City departments keep track of infrastructure investments, as they strive to make them more equitable.

Throughout Boston, City government repairs broken sidewalks, installs benches, builds new libraries, and creates new parks. These examples only represent a slice of the enormous investment the City makes in core infrastructure that serves residents. A key question remains: **how equitable are these investments?** For example, are sidewalks repaired at the same rate and the same scale across neighborhoods? Does one neighborhood have more benches per sq.ft or per capita than another neighborhood? Do parks in one neighborhood have more or less amenities than parks on the other side of the city?

We would like to build a web-based dashboard that keeps track of these investments and helps City departments reach their equity goals. The dashboard will use frequently updated open data to help users analyze and visualize trends in infrastructure investments. The dashboard will include a map-based view of several types of infrastructure investments and a variety of charts for users to spot trends over time. 

We give this project a **medium** level of difficulty. The project can be completed in **175 hours**.

This project will require intermediate experience with GIS and web mapping platforms, data visualization frameworks (e.g., D3), data analysis tools (e.g., R), and JavaScript/HTML/CSS.

The mentors for the project will include two Program Directors at the Mayor's Office of Urban Mechanics, including one who served as a Google Summer of Code mentor at Code for America in 2011 and the City of Boston in 2021.

### 3. Building a Tool for Collecting Crowdsourced Ideas on Interactive Maps

As a research and development office in city government, we support several community engagement efforts that seek to collect and share feedback from residents on various City initiatives. Many of these engagement efforts are citywide and revolve around geospatial questions, such as:

- Where should the City install new benches?
- Where is your favorite public art? Where would you like to see a new piece of public art?
- Where would you like to see a new community compost bin?

Based on this need, we would like to build a tool that lets users deploy interactive maps that crowdsource ideas from residents. When a resident starts using the tool, they will be greeted with a prompt (e.g., "Where should the City install new benches?") and a map-based interface that lets them drag markers to a desired location. Once the marker is placed correctly, the resident can provide more details about the location with a pop-up form. 

There should also be an option to showcase all of the other ideas that have been collected. Frequently, residents are eager to see ideas from their neighbors and across the city. This means that the tool should display a map with submitted ideas. (Each idea will need administrative approval before being displayed on the website.)

Simplicity is key for this tool. The interactive maps should be easy to customize and based on a flexible configuration that defines the title, the basemap, marker colors, and other design details. Installing new versions of the app should also be simple. The app should be serverless, using a cloud-based data store. The front-end of the app should be a static web page that can be deployed on Cloudflare Pages, Netlify, or GitHub Pages.

Finally, accessibility is also a major concern. The tool should follow W3C accessibility guidelines and should use responsive web design. Moreover, the contributor should keep in mind that the text for the tool may need to be translated into several languages, a key consideration for the configuration.

We give this project a **medium** level of difficulty. The project may take **175 hours** or **350 hours** depending on the number of features built.

This project will require intermediate experience with GIS and web mapping platforms, advanced experience with JavaScript/HTML/CSS, and intermediate experience with building serverless apps. In particular, contributors should be comfortable interacting with RESTful APIS and using cloud-based data stores (such as SimpleDB).

The mentors for the project will include two Program Directors at the Mayor's Office of Urban Mechanics, including one who served as a Google Summer of Code mentor at Code for America in 2011 and the City of Boston in 2021.

### 4. Web Interface for Urban Tree Canopy Detection Using Satellite and Aerial Imagery

The City of Boston's Parks Department maintains a comprehensive data set on trees in Boston. However, it's a manual and laborious process to get the data (such as  conducting site visits for tree counts) on a regular basis. Last summer, a student built a Boston-specific model to identify trees from aerial imagery; it was based on [Deep Forest](https://github.com/weecology/DeepForest), a machine learning library for tree crown detection. 

This year, we would like to operationalize this project for the Parks Department. Right now, the machine learning model runs on Google Colab, which has proven difficult for staff at the Parks Department to learn. They need a simple web interface that allows for the upload of updated imagery and subsequent analysis.

We would also like to explore ways to find more insights from the aerial imagery. For example, we would also like to look at the feasibility of determining tree health and the variety of tree species across the city.

The ideal outcome would be **1)** the creation of a simple web interface for the Parks Department to upload new aerial imagery for analysis, and **2)** the ability to the Parks Department to generate a list of statistics on tree counts and tree healthto ensure that it continues to plants trees in an equitable manner across the city.

We give this project a **medium** level of difficulty. The project can be completed in **175 hours**.

This project will require intermediate experience with Python, machine learning (in particular TensorFlow and training models with imagery), interacting with RESTful APIs, and limited experience with JavaScript, HTML, and CSS.

The mentors for the project will include two Program Directors at the Mayor's Office of Urban Mechanics, including one who served as a Google Summer of Code mentor at Code for America in 2011 and the City of Boston in 2021.
