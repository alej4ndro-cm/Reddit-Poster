# University Ripple Poster

This project, housed in the `Reddit` root folder, contains a script (`uni_ripple_poster.ipynb`) that automates the process of posting to various university-related subreddits on Reddit, inviting students to join Ripplematch. The script reads university names and potential subreddit names from files, and posts a predefined message to these subreddits.

## Table of Contents
1. [Getting Started](#getting-started)
2. [Usage](#usage)
3. [Dependencies](#dependencies)
4. [File Structure](#file-structure)
5. [Contributing](#contributing)

## Getting Started

### Prerequisites

- Python 3.9.6
- `praw` library for interacting with Reddit
- `docx` library for reading Word documents
- `csv` library for handling CSV files

### Installing

- Install the required libraries using pip:
  ```bash
  pip install praw python-docx

## Usage
1. Update the Reddit credentials in uni_ripple_poster.ipynb.
2. Specify the paths to the input and output files.
3. Run the script in a Jupyter Notebook environment

## Dependencies
- praw: Python Reddit API Wrapper
- python-docx: Python library for creating and updating Microsoft Word (.docx) files.

## File Structure
The project has the following file structure:

Reddit</br>
│</br>
├── content.docx </br>
├── list_of_universities.docx</br>
├── list_of_universities.csv</br>
├── universities_with_potential_subreddits.csv</br>
├── uni_ripple_poster.ipynb</br>
├── README.md</br>
└── .gitignore</br>

### Contributing
Feel free to fork this project and make your own changes. Pull requests are welcome.


