# unraid-templates

Unraid Community Applications templates by [MangoLila](https://www.mangolila.at/).
Maintained by [Mike Mitterer](https://github.com/MikeMitterer).

## Apps

| App | Description | Source | Image |
|---|---|---|---|
| **StockInfo** | Stock and ETF quotes via REST API (JSON) with Vue dashboard, SQLite cache and periodic refresh. Data sources: Yahoo Finance (yfinance), justETF, OpenFIGI. | [MikeMitterer/stockinfo](https://github.com/MikeMitterer/stockinfo) | [mangolila/stockinfo](https://hub.docker.com/r/mangolila/stockinfo) |
| **StockPortfolio** | Portfolio management in the browser: valuation, price charts and rebalancing. Accounts and portfolios are stored in the container; prices come from a separate StockInfo API. | [MikeMitterer/stockportfolio](https://github.com/MikeMitterer/stockportfolio) | [mangolila/stockportfolio](https://hub.docker.com/r/mangolila/stockportfolio) |

## Support

Please use the GitHub Issues of the respective app's source repository, e.g.
[stockinfo/issues](https://github.com/MikeMitterer/stockinfo/issues).

## Installation

Install the apps through **Apps / Community Applications** in the Unraid web
interface. For StockPortfolio, install StockInfo first.

Each app's Unraid guide covers settings, data, updates and an optional test
installation of the published template:
[StockInfo](https://github.com/MikeMitterer/stockinfo/blob/master/unraid/README.md) ·
[StockPortfolio](https://github.com/MikeMitterer/stockportfolio/blob/master/unraid/README.md).
Never download a template over an existing `my-<name>.xml`: Unraid stores the
saved container settings in that file.

## License

[MIT](LICENSE)
