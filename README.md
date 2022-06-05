# Introduction

This directory contains Bing image-scraping software forked from https://github.com/hardikvasa/google-images-download

# Requirements

Python 3.8 or later with all [requirements.txt](https://github.com/Equitable-Surveillance/web_scraping_images/master/requirements.txt) dependencies installed, including `selenium`. To install run:
```bash
$ pip install -r requirements.txt
```

# Install
```bash
$ git clone https://github.com/Equitable-Surveillance/web_scraping_images
$ cd web_scraping_images
$ pip install -r requirements.txt
```

# Run

1. Install/update Chrome: https://www.google.com/chrome/

2. Install/update chromedriver: https://chromedriver.chromium.org/

3. Run. Download up to `--limit` images supplying either a `--url`:
 ```bash
$ python3 bing_scraper.py --url 'https://www.bing.com/images/search?q=flowers' --limit 10 --download --chromedriver /Users/jai/Downloads/chromedriver
```

or `--search` terms. Images are saved to `./images`. Note that error-producing images may be skipped.
```bash
$ python bing_scraper.py --search 'police gun' --limit 10 --download --chromedriver ./chromedriver

```

# Cite

See https://github.com/hardikvasa/google-images-download.
