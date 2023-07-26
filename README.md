# data-collection-challenge

This repository contains a Jupyter Notebook (`mars_weather.ipynb`) to visualize the minimum temperature and pressure data on Mars for various terrestrial date and export the data to a CSV file. Each data visualization is presented as a bar graph, with each bar representing the minimum temperature (in Celsius) or pressure (in Pascals) recorded on a specific terrestrial date. This repository also contains a Jupyter Notebook that parses the Mars Daily News webpage for news article previews.

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
- It was collected by the [InSight Lander](https://mars.nasa.gov/insight/mission/overview/), which is part of NASA's [Discovery Program](https://discovery.nasa.gov/), and scraped using `BeautifulSoup` and `splinter`.
- The news article previews are sourced from [Mars Daily News](https://mars.nasa.gov/rss/api/?feed=weather&category=insight&feedtype=json&ver=1.0).
