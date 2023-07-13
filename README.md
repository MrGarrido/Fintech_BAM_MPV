# Fintech_BAM_MVP
This repository was created as part of the MSc BAM for Fintech and served as a proof of concept 

## This MVP uses two APIs 
    - Binance 
    - Yahoo Finance

### Binance 
This API is used to retrieve the actual market value of the crypto portfolio of the user 

### Yahoo Finance
The Stock portfolio is randomly generated, but the Yahoo Finance API is used to get the closing price of the Stocks 

## Randomized Personal Finance Data 
The randomization is done with the following budget in euros:
    - Crypto 5K€
    - Stocks 20K€

The banking data is also randomized

    - Fixed monthly income of 3K€
    - Expenses:
        - Food: Normally spend a mean of 80€ in food per week (SD 20%)
        - Shopping: mean of 200€ a month
        - Going Out: mean of 150€ to go out (SD 10%)
        - Transport: mean of 150€ in transport a month

In order to run the dashboard, you should clone the repo and follow these simple steps:

MUST HAVE DOCKER INSTALLED and opened 

Then on the terminal: 
cd flask-volt-dashboard
docker-compose up --build 

The app runs locally at http://localhost:5085/

- For MAC/Windows, without Docker consult the open-source documentation of https://github.com/app-generator/flask-volt-dashboard

- Special thanks to App Generator for allowing this template to be open source
