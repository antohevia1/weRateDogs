# Content: We Rate Dogs
## Project: Wrangle and Analyze Data

### Install

This project requires **Python 3.7.6** and the following Python libraries installed:

- [Tweepy](https://tweepy.readthedocs.io/en/v3.5.0/)
- [Requests](https://www.pythonforbeginners.com/requests/using-requests-in-python)
- [json](https://docs.python.org/2/library/json.html)
- [io](https://docs.python.org/2/library/io.html)
- [bs4](https://www.crummy.com/software/BeautifulSoup/bs4/doc/)
- [os](https://docs.python.org/2/library/os.html)
- [time](https://docs.python.org/2/library/time.html)
- [re](https://docs.python.org/3/library/re.html)
- [NumPy](http://www.numpy.org/)
- [Pandas](http://pandas.pydata.org)
- [matplotlib](http://matplotlib.org/)
- [scikit-learn](http://scikit-learn.org/stable/)

You will also need to have software installed to run and execute a [Jupyter Notebook](http://ipython.org/notebook.html)

If you do not have Python installed yet, it is highly recommended that you install the [Anaconda](https://repo.anaconda.com/archive/) distribution of Python, which already has the above packages and more included. Specify the python version by running:

```bash
conda install python=3.7.6 anaconda=custom
```

### Code

Template code is provided in the `weRateDogs.ipynb` notebook file.



## Data

The dataset that we will be wrangling (and analyzing and visualizing) is the tweet archive of Twitter user @dog_rates, also known as WeRateDogs. WeRateDogs is a Twitter account that rates people's dogs with a humorous comment about the dog. These ratings almost always have a denominator of 10. The numerators, though? Almost always greater than 10. 11/10, 12/10, 13/10, etc. Why? Because "they're good dogs Brent." WeRateDogs has over 4 million followers and has received international media coverage.
I have added a compressed file (data.zip) with image-predictions.tsv, which contains a NN prediction of dog breeds from tweets pictures, and tweepyAPI.txt, the data obtained after wrangling the @dog_rates Twitter account with tweepy.
