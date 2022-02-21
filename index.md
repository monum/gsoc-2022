## Ideas List for Google Summer of Code from the Mayor's Office of New Urban Mechanics (City of Boston)

Below, you will find a list of ideas we have for a Google Summer of Code student for the summer of 2022. 

**You can find guidance for applications and your project proposals [here](https://monum.github.io/gsoc-ideas-2022/guidance)**.

Thank you for your consideration!

### 1. Improved Translation for the City's 311 App with Machine Learning

In 2010, our office launched the City of Boston's [311 app](https://311.boston.gov/) (one of the first in the nation). The app allows residents to report an array on non-emergency issues (such as potholes) with their smartphones. Historically, the app has only been offered in English, and we have done some of the preliminary work to provide it in other languages. This is a very important issue to address, since up to 33% of the city does not speak English.

[Inspired by the City of San José](https://medium.com/swlh/better-language-translation-through-machine-learning-everything-i-wish-i-knew-6-months-ago-8fa212fb1731), we would like to build an API-accessible service that improves the translation of text from residents reporting issues through the 311 app. The translation service would be based on a custom, trained model using vocabulary frequently associated with City services. 

The ideal outcome would be having an API endpoint that would accept text from a 311 request and return translated text that could be easily understood by our City operations teams. We would also like to be able to benchmark the progress of this translation service against more general translation services.

We give this project a **medium to hard** level of difficulty.

This project will require intermediate experience with machine learning, building and training models with text classification, natural language processing, and Python. It will also require intermediate experience with building web service APIs with with a web framework like Flask, Django etc.

The mentors for the project will include two Program Directors at the Mayor's Office of Urban Mechanics, including one who served as a Google Summer of Code mentor at Code for America in 2011.
