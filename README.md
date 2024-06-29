# Identifying Factors Influencing Meme Virality

## Description
This project explores factors influencing meme virality by comparing two groups of memes sourced from Reddit, r/memes: viral (high upvotes) and non-viral (low upvotes). The analysis covers multiple features including `author_karma`, `author_comment_karma`, `author_account_age_days`, `comments`, and `title_length`. Additionally, sentiment analysis was conducted on meme titles and text extracted from images using Tesseract OCR. Sentiment analysis with TextBlob and emotion distribution analysis with transformers were performed to understand the emotional content of the memes. Statistical tests such as t-tests and chi-squared tests were employed to identify significant differences between the viral and non-viral groups. Furthermore, Pearson correlation tests were conducted to examine correlations between the features and meme virality.

## Table of Contents
- [Installation Instructions](#installation-instructions)
- [Usage](#usage)
- [Files Description](#files-description)
- [Dependencies](#dependencies)
- [Credits](#credits)
- [Contact Information](#contact-information)
- [Additional Notes](#additional-notes)

## Installation Instructions
1. Clone the repository from GitHub.
2. Install required dependencies using pip install or conda.
3. Open `main_notebook.ipynb` in Jupyter Notebook.

## Usage
Open `main_notebook.ipynb` and run each cell sequentially to first collect the data (it can also be found in the csv files attached), then import it and perform analysis on meme virality factors. The code provides both numerical analysis, as well as graphical representations, such as plots.

## Plots:
- Scatter plots;
- Bar charts;
- Histograms;
- QQ plots (to check for normality);
  
For detailed visual insights, refer to the plots in `main_notebook.ipynb`. They all have corresponding titles and a legend, to ensure clarity for the user.

## Files Description
- `main_notebook.ipynb`: Contains all the code and results interpretation.
- `top_memes.csv`: Original dataset containing top memes data.
- `top_memes_cleaned.csv`: Cleaned version of `top_memes.csv` after preprocessing.
- `non_viral_memes.csv`: Original dataset containing non-viral memes data.
- `non_viral_memes_cleaned.csv`: Cleaned version of `non_viral_memes.csv` after preprocessing.
- `image_features.csv`: CSV file containing extracted features from meme images.

## Image Folders
- `viral_images/`: Folder containing images of viral memes.
- `non_viral_images/`: Folder containing images of non-viral memes.
  
## Dependencies
- Python 3.7+
- pandas 1.2.3
- numpy 1.19.5
- matplotlib 3.4.2
- seaborn 0.11.1
- scikit-learn 0.24.2
- nltk 3.6.5
- textblob 0.15.3
- transformers 4.6.0
- torch 1.8.1
- pytesseract 0.3.8
- praw 7.4.0
- tensorflow 2.7.0
- keras 2.8.0

## Credits
- Data sourced from Reddit API.

## Contact Information
For any questions or feedback, contact me at:
- Email: d.cernetchi@student.vu.nl
- GitHub: github.com/dianapascalabc

## Additional Notes
- Ensure an active internet connection for data retrieval from Reddit API.
- Execution time may vary depending on the size of the dataset and computational resources.

