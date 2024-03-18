# Web-Scrapping using Beautifulsoup

Web scrapping is one of a method that we can use to collecting the data from internet. In this project, we will try to scrap Indonesian exchanged rate from www.exchange-rates.org. To do this we will only use a couple default library from python and BeautifulSoup.

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
