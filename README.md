# Web Mining and Applied NLP (44-620)

## Requests, JSON, and NLP

### Student Name: Naiema Elsaadi


This exercise illustrates how to access web-hosted APIs, get back a response in JSONLinks to an external site, format, and extract the information we need from the JSON. Accessing APIs is a key skill for data analysts. We can use web APIs to get stock data, weather data, and much more. We'll use an API to access song lyrics or poems in this exercise. We don't care which API - there are many kinds and they change regulary. The skills being demonstraded are
<br>(a) make an API request 
<br>(b) find the information we need in the returned response. 

## Introduction

This Python project aims to analyze the sentiment of song lyrics using natural language processing (NLP) techniques. By leveraging the power of spaCy and its TextBlob extension, the project extracts lyrics from various songs, processes them, and calculates polarity scores to determine whether the lyrics convey positive, negative, or neutral sentiments.

### Features
- Retrieve song lyrics from the lyrics.ovh API.
- Perform sentiment analysis on song lyrics.
- Output polarity scores to assess the overall sentiment of the songs.


## Task Breakdown:
1. Task 1: Get Started
- Copy the base repository to your GitHub account.
- Clone your repository to your local machine.
2. Task 2: Open Notebook and Complete Tasks
- Add a clickable link to your GitHub repo in the Markdown introduction.
- Use Markdown headings for each question number.
- Complete the provided tasks in the Jupyter notebooks.
- Execute the notebooks, commit, and push changes to GitHub.
3. Task 3: Export to HTML and Finalize Repo
- Execute each notebook.
- Export each notebook to HTML format.
- Commit and push the HTML files along with the executed notebooks.

## Requirements

<br>Markdown introduction with name and clickable link is required.
<br>Markdown Section Headings for each Question are required. 
<br>Execute your code before exporting HTML and pushing notebooks. (See FAQ for help.)  
<br>Unexecuted code is not eligible for credit.

## Prerequisites
Before running the project, ensure you have the following prerequisites:

- Git
- Github
- Python 3.10+ installed
- VS studio Code
- juypterlab
- anaconda prompt (miniconda3) or windows PowerShell
- Required Python libraries (e.g., numpy) installed in your active environment

## Getting Started

- Before we begin, make sure you have the necessary dependencies installed in your Python environment. 
- If you haven't already, you'll need to install spaCy and spaCy NLP  using the following command:
<br>`python -m pip install requests`
<br>`python -m pip install spacy`
<br>`python -m pip install spacytextblob`
- Install them into our active virtual environment.
- Use an import statement in our Python. 
- Spelling and capitalization matters 
- The typical approach is to:
1. Create a virtual environment
2. Activate the virtual environment
3. Install into the active virtual environment (e.g. `python -m pip install spacy`)
4. In your Python, import it (e.g. `from spacytextblob.spacytextblob import SpacyTextBlob`)
5. spaCy Import Error:
<br> Go to the `pyvenv.cfg` file in the Virtual environment folder
<br> Set the `include-system-site-packages` to `true` and save the change
<br> Reactivate the virtual environment.

## Before we start 

` Create and activate a Python virtual environment. `
<br>` Address any errors you get running this code cell by installing the necessary packages into your active Python environment.`
<br>` Before starting the project, try all these imports FIRST`
<br>import json
<br>import pickle
<br>import requests
<br>import spacy
<br>from spacytextblob.spacytextblob import SpacyTextBlo
<br>print('All prereqs installed.')
<br>!pip list

## How to Run

<b><br> Follow these steps to run the project:  </b></br>

1. Get the starter repo into your GitHub account.
2. Clone down your repo to your local machine,
3. Start up Jupyter lab (or Jupyter Notebook),
4. Make edits to Markdown cells and Python code cells
5. Run the Python scripts provided in the `src` directory to analyze song lyrics and view polarity scores.
6. Explore the results and gain insights into the emotional content of your favorite songs!
7. Add and commit your changes using Git
8. Push your commit up to the GitHub repo.
9. Export your notebook as HTML (a web page) for submission using the menu



## Installation

Instructions for installing any dependencies or software needed to run the project. Include commands for installing packages or setting up environments.

To use the notebooks in this repository, follow these steps:

1. Clone the repository to your local machine:
git clone Repo
2. Navigate to the project directory:
cd file
3. Create a virtual environment (optional but recommended):
python -m venv venv
4. Activate the virtual environment:
 For Windows:
venv\Scripts\activate
5. Install the required packages:
pip install -r requirements.txt
6. Launch Jupyter Lab:
jupyter lab
7. Open the desired notebook and execute the code cells.



## Data Source 

The source of the repository for this project is available at:[GitHub Repository]( https://github.com/wmnlp-materials/json-sentiment)


## Contact

For any questions, feedback, or inquiries, you can reach out to me via  [My GitHub Repository](https://github.com/NaiemaElsaadi/Json-sentiment)


## Acknowledgments

Special thanks to the Web Mining and Applied NLP (44-620) course instructor Dr. Case for her guidance and support throughout the project.

## Reference

https://spacy.io/
<br>https://spacy.io/usage/spacy-101
<br>https://spacy.io/usage
<br>https://pypi.org/project/lyricsgenius/
<br>https://github.com/public-apis/public-apis
<br>https://lyricsovh.docs.apiary.io/#reference/0/lyrics-of-a-song/search?console=1





