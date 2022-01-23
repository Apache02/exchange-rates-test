# Currency exchange ratios example

    This is not actual currency rates!!! Don't use it in real projects!!!
    
    
API сервисы, которые отдают курсы обмена валют в формате JSON.

1. Bank.

    Single endpoint: [/bank/exchange_rates.json](https://apache02.github.io/exchange-rates-test/bank/exchange_rates.json)

2. Crypto market.

    Available markets:
    * BTC: [/crypto/BTC.json](https://apache02.github.io/exchange-rates-test/crypto/BTC.json)
    * USD: [/crypto/USD.json](https://apache02.github.io/exchange-rates-test/crypto/USD.json)

3. Some service

    Endpoint template: /service/{from}_{to}.json
    
    Examples:
    * [/service/USD_EUR.json](https://apache02.github.io/exchange-rates-test/service/USD_EUR.json)
    * [/service/USD_GBP.json](https://apache02.github.io/exchange-rates-test/service/USD_GBP.json)
    * [/service/USD_RUB.json](https://apache02.github.io/exchange-rates-test/service/USD_RUB.json)
    * [/service/USD_UAH.json](https://apache02.github.io/exchange-rates-test/service/USD_UAH.json)
