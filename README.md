# GEOFABRIK REGION DOWNLOAD

[![License](https://img.shields.io/badge/license-MIT-blue.svg)](LICENSE)

## Description

The Geofabrik PBF Downloader and Merger Script is a versatile and user-friendly Python tool that simplifies the acquisition and merging of geographic data in PBF format from the popular OpenStreetMap data provider, Geofabrik (https://download.geofabrik.de/). This script permits users to efficiently download and merge pbf files of one or several countries, and their neighboring data, optimizing the data acquisition and merging process.


## Table of Contents

- [Installation](#installation)
- [Usage](#usage)
- [Features](#features)
- [License](#license)
- [Contact](#contact)
- [Acknowledgments](#references)

## Installation

1. Ensure you have Python 3.x installed on your system.
2. Ensure you have anaconda installed to download osmium
3. Install required libraries:
    pip install requests beautifulsoup4 tqdm
4. Install Osmium, you will need Anaconda (https://anaconda.org/):
   conda install -c conda-forge osmium-tool

## Usage

1. Open a terminal or command prompt and navigate to the project directory.
2. Run the script: 
    python geo_script.py
3. Follow the on-screen prompts to select a region, countries, and initiate the download and merging process.

or

1. Open jupyternotebook
2. Run the first cell if you donìt have the required libraries
3. Run second Cell to run the script

## Features

- Choose from a variety of available regions on Geofabrik's website.
- Select one or multiple countries of interest.
- Automatic inclusion of neighbouring countries
- Removal of undesired countries from the list of countries to download and merge
- Automatically download the latest PBF files for chosen countries, including neighboring countries, into a new folder.
- Seamlessly merge all downloaded PBF files using the osmium tool.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Contact

For questions or feedback, feel free to reach out via email: ivoteruggi@hotmail.com

## Acknowledgments

This project includes Country Borders data from [Geodatasource](https://www.geodatasource.com).
