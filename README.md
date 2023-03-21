# Web-Scrapping using Beautifulsoup

This project was developed as one of the capstone projects of the Algorithm Academy Data Analytics Specialization. The expected deliverables from this project are to do a simple web scraping to get information. I'll also make use of a simple flask dashboard to display my scrap results and visualizations.

## Dependencies

- beautifulSoup4
- pandas
- flask
- matplotlib


## Rubics

- Environment preparation. 
- Finding the right key to scrap the data  & Extracting the right information.
- Creating data frame & Data wrangling. 
- Creating a tidy python notebook as a report. 
- Implement it on flask dashboard.


## What You Need to Do

* Please try scraping the questions below using `beautiful soup` in your notebook first.
* You can clone this repo.
* Please open the notebook template on this capstone and fill it according to the instructions. Make sure you provide the required analysis on the notebook.
* The files in this repo are skeletons which can be used to build a simple flask dashboard.
* Please fill in the blanks.
* Fill in the `scrap` function with the scraping process that you have done in your notebook.

```python
table = soup.find(___)
tr = table.find_all(___)
```

* Fill in this section to save the results of the scrap that you made into a dataframe.

```python
df = pd.DataFrame(name of your tupple, columns = (name of the columns))
```

* Finally, you can use the `scrap` function by filling in the following section with the web link that you scraped.

```python
df = scrap(___) #insert url here
```

### The Final Mission

In capstone project , you can choose one of these questions to work on:

1. US Dollar exchange rate data to IDR (Indonesian Rupiah) from `https://www.exchange-rates.org/history/IDR/USD/T`

    * From that page search for `daily price`, and `date`
    * Create a plot of the movement of the USD exchange rate
    
2. Film data released in 2019 from `imdb.com/search/title/?release_date=2019-01-01,2019-12-31`

    * From the Page search for `title` , `imdb rating` , `metascore` and `votes`
    * Make plots of the 7 most popular films of 2019.


Happy learning! 
