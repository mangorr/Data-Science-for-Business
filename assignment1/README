Instructions
We will be doing most of the work for this class in Python. We will be using packages which include pre-canned implementations of techniques we will learn about in class. These packages have improved over time and so many versions of them exist. We want a tool that lets us specify which versions of each package we would like to use (the latest ones, most of the time). We get all of these things out of the box in one neat software package: Anaconda. It includes:

The Python language/interpreter (this what let's you run Python code)

Commonly used Python packages (pandas, scikit-learn, numpy, and many more)

An editor (aka IDE) called Spyder that makes writing code easier. It includes nice features like auto-complete, error highlighting, debugging tools, etc.

A "package manager" that gives you control over the versions of packages you use, called "Conda"

A “computational notebook” (called Jupyter) that lets you write snippets of code in a nice visual, interactive and easy-to-share format. 

 

Download the following file: https://www.dropbox.com/s/7lredokgkyxbhmg/SPY.csv?dl=1. It is a comma-separated file, containing prices for the S&P 500 ETF (SPY) from 1993 through Aug 31, 2021. The file has the following columns:

* Date: Date in YYYY-MM-DD format
* Open: Opening price
* High: The high price during the trading day
* Low: The low price during the trading day
* Close: Closing price
* Adj Close: The closing price adjusted for corporate actions (dividends and splits)
* Volume: The number of shares traded that day

Install Anaconda (https://www.anaconda.com/products/individual-d)

Run the Jupyter Notebook server, create a new Notebook and *attempt* to do the following tasks. If you are unable to do the tasks (either because you’re unfamiliar or short on time), you are still expected to read the tasks and respond to the questions below.

Tasks:

Use pandas to read in the CSV file you downloaded into a dataframe.

Create a new column called “return” containing the percent change in the stock’s price for the day, based on the “Adj Close” column (note that today’s return = the change in price from yesterday’s adjusted close to today, divided by yesterday’s adjusted close)

Count the number of NaNs in your new return column. Why do you get the number you get?

Create a new column called “std60” containing the prior 60-day rolling standard deviation of the return not including that day’s return. Count the number of NaNs in this new column.

Replace the NaNs in your “ret60” column with the median value of the non-NaN values.

Create a new column called “return_clipped” containing the same data as “return” but not exceeding 3*std_60 and not smaller than -3*std_60.


Submission: You only need to submit the following attestation. You don't need to submit any work. 

Attestation: Yes, I have installed Anacondas and created a sample Notebook. I have read through the required tasks.
