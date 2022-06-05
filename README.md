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
<img src="https://user-images.githubusercontent.com/26833433/75287228-dcf2ca80-57ce-11ea-9557-cc13abaff453.jpg" width="">

# Cite

See https://github.com/hardikvasa/google-images-download.

## About Us

Ultralytics is a U.S.-based particle physics and AI startup with over 6 years of expertise supporting government, academic and business clients. We offer a wide range of vision AI services, spanning from simple expert advice up to delivery of fully customized, end-to-end production solutions, including:
- **Cloud-based AI** systems operating on **hundreds of HD video streams in realtime.**
- **Edge AI** integrated into custom iOS and Android apps for realtime **30 FPS video inference.**
- **Custom data training**, hyperparameter evolution, and model exportation to any destination.

For business inquiries and professional support requests please visit us at https://www.ultralytics.com. 

## Contact

**Issues should be raised directly in the repository.** For business inquiries or professional support requests please visit https://www.ultralytics.com or email Glenn Jocher at glenn.jocher@ultralytics.com. 
