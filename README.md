# Final Project repository for Harvard University's CS109B - Spring 2018:
## "Movie classification using plot descriptions"
#### Canvas Group 11

---

### Project Repository Organization:
- **data** directory - all the data we collected scraping as well as plot
transformation arrays
- **submissions** directory - project milestone and final submission documents
- **.gitignore** - self-explanatory
- **eda_and_plot_transformations.ipynb** - milestone 3 EDA plots and basic analysis as well as bag-of-words TFIDF, word2vec, and doc2vec plot transformations for modeling
- **future_work_LDA.ipynb** - notebook to explore possibilities of LDA
clustering on our dataset
- **modeling_analysis.ipynb** - primary modeling and analysis notebook
- **movie_scraper_and_prep.ipynb** - data collection and initial prep

All data descriptions, EDA, modeling, and analysis is described in details in the
final report found in the submissions directory.

### Group Members:
- Andrew Lund
- Nicholas Morgan
- Amay Umradia
- Charles Webb

---

### Navigating This Repository:
The manipulated dataframes and arrays are all saved in the `data` folder, which allows for each notebook to be run independently of the others. If you wish to follow along in the order of our report, go through the notebooks in the following order:

1) **movie_scraper_and_prep.ipynb**
2) **eda_and_plot_transformations.ipynb**
3) **modeling_analysis.ipynb**
4) **future_work_LDA.ipynb**
