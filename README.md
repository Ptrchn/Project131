
# Binancelinemonitor

This repository contains a Python script that allows you to check the latest prices of cryptocurrencies on Binance and send notifications using the Songline API. The script uses the Binance API to retrieve the current prices and compares them with predefined conditions to generate alerts.


## Prerequisites
Before running the script, make sure you have the following prerequisites:

Python installed on your system.
Required Python packages (python-binance and songline) installed.
An API key and secret from Binance. You can obtain these by creating an account on Binance and generating an API key.
An API token from Songline. Create an account on the Songline website and generate an API token.
## Installation

1.Clone the repository.

2.Install the required Python packages by running the following commands in your command prompt or terminal:

```bash
  pip install python-binance
  pip install songline

```
3.Update the script with your Binance API key and secret:
```bash
  api_key = 'YOUR_BINANCE_API_KEY'
  api_secret = 'YOUR_BINANCE_API_SECRET'
```

4.Update the script with your Songline API token:
```bash
  token = 'YOUR_SONGLINE_API_TOKEN'
```
## Usage
To use the script, follow these steps:

1.Run the script by executing the following command in your command prompt or terminal

```bash
python Binancelinemonitor.py
```
2.The script will start checking the prices of the specified cryptocurrencies on Binance. It will compare the prices with predefined conditions and generate alerts if the conditions are met.

3.If you want to check the price of a specific coin, enter the coin symbol in the input box and click the "Check!" button. The script will retrieve the current price and display it.

4.If you want to send the current price of a specific coin via Songline, enter the coin symbol in the input box and click the "SendLine" button. The script will retrieve the current price and send it as a notification to your Songline account.

## Customization
You can customize the script according to your needs by modifying the following variables:

mycoin1, mycoin2, mycoin3, mycoin4: Add or remove cryptocurrencies to check their prices.
namecoin1, namecoin2, namecoin3, namecoin4: Add or remove names for the corresponding cryptocurrencies.
condition: Modify the buy and sell conditions for each cryptocurrency.