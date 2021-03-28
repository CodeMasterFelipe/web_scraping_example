# Web Scrapping Example

The intension for this repo its to show how you will go about doing web scraping using ***spliter*** in python.

## Setup

#### Step One - Get Chrome Driver:

Use this link to download the [crome driver](https://chromedriver.chromium.org/downloads). Download the corresponding version that matches your Chrome Browser. On the folder [web_driver](./web_drivers) I already have the chromedriver version 89 for Mac and Mac m1.

#### Step Two - Set Up Your Computer to Use the Chrome Driver:

[Spliter guide](https://splinter.readthedocs.io/en/latest/drivers/chrome.html). I will only cover MacOS in here.

- Install [homebrew](https://brew.sh/) if its not already installed.
- Run this on terminal ```brew cask install chromedriver``` or ```brew install chromedriver```
- For Apple M1 **Only**: on the terminal: ```export PATH=/usr/local/bin:$PATH```

#### Step Three - Set up Python Environment:

Only if using [Anaconda](https://www.anaconda.com/) as your python environment manager:

- If you dont have yet a environment with conda, run the following
  - ```conda create -n <name> python=3.8``` <name> can be anything you like, like this ```conda create -n web_scrape python=3.8```
- Activate conda environment:
  - ```conda activate <name>```
- Go to the folder for this repo, using ```cd .../web_scraping_example``` and run the following to install all the python packages needed.
  - ```python -m pip install -r requirements.txt```
- When done run ```jupyter notebook``` and go thru the web_scrapping_google_search.ipynb



