# Google Image Crawler

Are you tired of searching for images on Google and downloading them one by one? Fear not, the Google Image Crawler is here to save the day! 🌟

## What is this?

This is a simple Python script that uses the Selenium framework to download images from Google. It's easy to use and can save you a lot of time and effort. 😎

## Dependencies

To run this script, you need to have the following packages installed:

* `selenium` 🐍
* `progressbar2` 📊
* `urllib3` 🌐
* `argparse` 🤖

You can install these packages using pip. For example:

`pip3 install selenium`


## How to use?

1. Download the Chrome webdriver from [here](https://sites.google.com/a/chromium.org/chromedriver/downloads). Make sure to download the version that matches your Google Chrome version. More drivers can be found [here](https://selenium-python.readthedocs.io/installation.html).

2. Run the script using the following command:

`python3 google_crawler.py [--limit LIMIT] [--query QUERY] [--directory DIRECTORY] [--webdriver WEBDRIVER_PATH] [-all]`

Here are the options you can use:

* `--limit`: The maximum number of images to download. Default is 10.
* `--query`: The search query for the images. Default is 'nature'.
* `--directory`: The directory where the images will be saved. Default is the current directory.
* `--webdriver`: The path to the Chrome webdriver executable. Default is '/usr/bin/chromedriver'.
* `-all`: Download all images found, instead of just a limited number.

Here are some examples:

`python3 google_crawler.py --limit 5 --query cat --directory ~/Downloads --webdriver /path/to/chromedriver`


This will download 5 cat images and save them in the specified directory.

`python3 google_crawler.py --query dog --directory ~/Pictures --webdriver /path/to/chromedriver -all`


This will download all the dog images found and save them in the specified directory.

Happy crawling! 🕷️🕸️
