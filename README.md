# Stock Market Indicators
A small Python library with most the common stock market indicators.

## Requirements
* Pandas
* Numpy

## Installation
Clone or download the indicators.py file into your project directory.


## Usage
Import the module:
import indicators

The functions in this library accept the data in Pandas DataFrame format. The data should contain OPEN, HIGH, LOW, CLOSE and VOLUME columns. See the comments for each function for the list of required columns. Their default names are hardcoded in functions' params, however you may supply your own column names, if they are different. Sometimes you would also need to provide periods over which to calculate the indicator values. However, for all of them the default (recommended) values are pre-assigned.

## List of implemented techinical indicators
* Exponential moving average (EMA)
* Moving Average Convergence/Divergence Oscillator (MACD)
* Accumulation Distribution (A/D)
* On Balance Volume (OBV)
* Price-volume trend (PVT)
* Average true range (ATR)
* Bollinger Bands
* Chaikin Oscillator
* Typical Price
* Ease of Movement
* Mass Index
* Average directional movement index
* Money Flow Index (MFI)
* Negative Volume Index (NVI)
* Positive Volume Index (PVI)
* Momentum
* Relative Strenght Index (RSI)
* Chaikin Volatility (CV)
* William's Accumulation/Distribution
* William's % R
* TRIX
* Ultimate Oscillator

## License
GNU General Public License
