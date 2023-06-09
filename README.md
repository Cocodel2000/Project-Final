# Project

Data management project:

We were both motivated by the stock markets are we are in the master « Banking and asset management”. We find it super interesting but sometimes quite complex to people not really in the finance world. Our goal was to create a web-application allowing people to have many tools to help them answer the dynamic question “What should I do with this particular stock : Buy, Keep or Sell ?”. It requires some knowledge for sure, but we really wanted to be beginner friendly. 

We are not aiming at giving recommendations, as it is not our role. We want to provide the user with tools allowing him/her to create his/hers own opinion on what he/she should do. As many stock information providers already exist, we don’t want to simply be a copy of them. We used different sources of data such as Yahoo finance API + webscrapping, AlphaVantage, Finhubb, … We did both simple API data collection and some webscrapping allowing us to parse the data we needed. This led us to the data cleaning and representation. We had to sometimes change the format of the data collected in order to be able to use them for calculation, representation, etc.

It would be too long to explain everything we did with the data but you can have a look at our code if needed. It is very well organized and easy to understand where every info is. On the Home page of our app, you will also have explanation on what you could expect on every pages. 

For the modelling, we decided to compare the results of a simple model the “EMA” VS a more complex ones. In finance, is it not always the difficult one that is the best predictor of the future as stock market are uncertain and every piece of information can change everything. 

Regarding our research question, it is quite difficult to arrive at a specific conclusion as our question is dynamic (change for every stock) and personal (change for every user according to his/her risk aversion and personal beliefs). We think we provided tools to give hints, such as the analysts’ recommendations, our predictive models, the news, the surprise sentiment regarding actual EPS vs the estimated one, the rest is mostly giving information on historical data. 

Our goal was really to launch the app and be deployed publicly using streamlit cloud. Unfortunately, after hours spent trying to make it work, we didn't manage to. Thus, you will need to deploy it locally. It is quite easy. First you need to download all packages used. You can find the list on the requirements.txt file. To properly launch the app, we recommend to download our files in a repository on your computer. Then on anaconda prompt use:

- cd "path to your file"
- once you are on the right folder write : streamlit run "file name".py (should launch the app directly in your browser)
