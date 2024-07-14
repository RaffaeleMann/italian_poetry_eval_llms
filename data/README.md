#  Italian Wikisource Poetry Dataset

This folder contains two datasets of poetry texts extracted from the Italian Wikisource:

1. `wikisource_it_poetry_wksrc_api.tsv`
   This file contains poetry texts extracted from the Italian Wikisource using the Wikisource API. It includes all poems that were successfully retrieved through the API from the poetry category.

2. `wikisource_it_poetry_v1.0.tsv`
   This file contains poetry texts from the Italian Wikisource obtained through HTML scraping. It includes poems from pages that did not return a text via the API method. This approach ensures a more comprehensive collection of poems, capturing those that might have been missed or were not accessible through the API.


## Data Collection Methods

- API Extraction: Used for `wikisource_it_poetry_wksrc_api.tsv`, leveraging the Wikisource API to efficiently collect readily available texts.
- HTML Scraping: Employed for `wikisource_it_poetry_v1.0.tsv`, to gather texts from pages where the API method was unsuccessful, ensuring a more complete dataset.

These complementary approaches aim to provide a comprehensive collection of Italian poetry from Wikisource, combining the efficiency of API calls with the thoroughness of direct web scraping.

## File Format

Both files are in TSV (Tab-Separated Values) format, allowing for easy parsing and analysis.

## Usage

These datasets can be used for various natural language processing tasks, literary analysis, or as a resource for Italian poetry studies.

## Note

Please be aware of and respect Wikisource's terms of use and copyright policies when using this data.
