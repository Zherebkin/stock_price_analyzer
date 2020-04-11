# stock_price_analyzer
##Plan:
* Identify libraries that will be needed during development
* Collect stock price data over time
* Write a script
* Build and analyze a chart

As for the first point, you will have to install libraries such as: csv, numpy, scikit-learn and matplotlib.
```
pip install csv
```
```
pip install numpy
```
```
pip install scikit-learn
```
```
pip install matplotlib
```
CSV will allow you to read data from files with stock prices, which we will receive in the future.
NumPy will be the main tool for processing and counting data
Scikit learn will be needed in building and implementing a mathematical model for evaluating stock price behavior.
Matplotlib is required for plotting.

Price data is planned to be taken from Yahoo finance (or from Google finance), since there you can download csv files for any time intervals, of many companies.

## The script will consist of three parts:
* Extract and organize data from a csv file
* The analytical part, where the whole logic of evaluating price behavior will be
* Plotting

The main mathematical model I decided to choose the method of support vectors, as this is something that I could at least somehow figure out and it really shows the result better than “at random”. Despite the fact that this method is often used to classify objects, it can also be used to approximate a specific sequence using a regression version of the same method.