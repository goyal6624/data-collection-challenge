# data-collection-challenge

This repository contains a Python script to visualize the minimum temperature and pressure data on Mars for various terrestrial dates. The data is presented as a bar graph, where each bar represents the minimum temperature (in Celsius) recorded on a specific terrestrial date. It also gets news article previews from Mars Daily News.

## Usage

1. Clone the repository to your local machine
2. Ensure you have the following Python packages installed:
    - `pandas`
    - `matplotlib`
    - `requests`
    - `bs4`
    - `splinter`
    - `selenium`
3. Ensure you have `chromedriver` installed and added to your system's environment variables, and a compatible version of Google Chrome installed
4. Run a Jupyter Notebook of your choosing (`mars_news.ipynb` or `mars_weather.ipynb`)

## Acknowledgments

- The data used in this visualization is sourced from [NASA's Mars Climate Database](https://mars.nasa.gov/insight/weather/).
- It was collected by the [InSight Lander](https://mars.nasa.gov/insight/mission/overview/), which is part of NASA's [Discovery Program](https://discovery.nasa.gov/).
- The news article previews are sourced from [Mars Daily News](https://mars.nasa.gov/rss/api/?feed=weather&category=insight&feedtype=json&ver=1.0).