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
- [License](#license)

## Installation Instructions
1. Clone the repository from GitHub.
2. Install required dependencies using `pip install -r requirements.txt`.
3. Open `main_notebook.ipynb` in Jupyter Notebook.

## Usage
Open `main_notebook.ipynb` and run each cell sequentially to perform analysis on meme virality factors.

## Files Description
- `main_notebook.ipynb`: Contains the analysis code and results interpretation.
- `data.csv`: Dataset containing meme features and virality indicators.

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

## Credits
- Data sourced from Reddit API.
- Sentiment analysis conducted using TextBlob and Transformers.
- Emotion distribution analysis using Transformers.
- Statistical tests implemented with scikit-learn.

## Contact Information
For any questions or feedback, contact me at:
- Email: yourname@email.com
- GitHub: github.com/yourusername

## Additional Notes
- Ensure an active internet connection for data retrieval from Reddit API.
- Execution time may vary depending on the size of the dataset and computational resources.

## License
This project is licensed under the MIT License - see the LICENSE file for details.
