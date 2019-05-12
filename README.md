# Exploratory Data Analysis with Quandl WIKI Continuous Futures
The following is a project (implemented in a Jupyter Notebook environment) which generates visualisations and analyses of commodity data sourced from the [Quandl Wiki Continuous Futures API](https://www.quandl.com/data/CHRIS-Wiki-Continuous-Futures). It was heavily inspired by [this post](https://www.wallstreetoasis.com/forums/project-advice-on-commodities-trading) on Wall Street Oasis, which proposes an analytics-based application for physical commodity trading.

![App Screenshot](https://github.com/NicholasTanWeiHong/eda-quandl-futures/blob/master/images/calendar-spreads.png "App Screenshot")

## Description of Project

This project leverages on the Quandl API for Continuous Futures to import, manipulate and analyse commodity-focused data series. On the basis of these manipulations, I make simple conjectures about the state of specific energy markets (such as Brent Crude Oil) and run basic inferential analyses with fundamental data from [Investing.com](https://www.investing.com/).

On further inspection, there appears to be a strong basis for the development of this framework in [Dash](https://github.com/plotly/dash) for live charting and analysis. Future plans will mostly involve the implementation of these same concepts in a Dash App environment.

## Future Plans
* Adding a section on crack spreads (E.g. Brent-RBOB Gasoline, Brent-Fuel Oil, Brent-Gasoil Spreads)
* Developing the project in Dash to generate live graphs for each spread under analysis
* Implementing technical indicators for each spread in Dash (E.g. RSI, MACD, Bollinger Bands)
* Parsing the web for freight rates between two specified locations
* Deducing if specific arbs (E.g. Physical Location Arbs) are open with a Dash app
* Deployment of the Dash application on Heroku etc.
