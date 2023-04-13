# FinTechChallenge6 5

This project uses both the NASDAQ (Json) and Alpaca API to get various security and crypto curency prices.   A sample portfolio is then created which is then run through a monte carlo simulation to assess if someone can retire.

## Technologies

The project uses Python 3, Alpaca API, Json,  NumPy, Pandas and Jupter/JupterNoteBook

---

## Installation Guide

Project can be cloned from github - git@github.com:bankeiyotaku/FinTechChallenge5.git

Project requires alpaca trade API.   

To install from shell:

pip install alpaca-trade-api

---

## Usage

Open financial_planning_tools.ipynb in JupypterLab to review.

Project directory must include .env file with the following variables.

#Nasdaq

NASDAQ_API_KEY = "YOURAPIKEY"


#Alpaca

ALPACA_ENDPOINT = "https://paper-api.alpaca.markets"

ALPACA_API_KEY = "KEY HERE"

ALPACA_SECRET_KEY = "KEY HERE"



---

## Contributors

This project was done for the FinTech bootcamp course.  This is Eugene Mesgar's version.

---

## License

No license
