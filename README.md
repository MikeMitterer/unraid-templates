# unraid-templates

Unraid Community Applications template repository by [Mike Mitterer](https://github.com/MikeMitterer).

## Apps

| App | Description | Source | Image |
|---|---|---|---|
| **StockInfo** | Stock and ETF quotes via REST API (JSON) with Vue dashboard, SQLite cache and periodic refresh. Data sources: Yahoo Finance (yfinance), justETF, OpenFIGI. | [MikeMitterer/stockinfo](https://github.com/MikeMitterer/stockinfo) | [mangolila/stockinfo](https://hub.docker.com/r/mangolila/stockinfo) |

## Support

Please use the GitHub Issues of the respective app's source repository, e.g.
[stockinfo/issues](https://github.com/MikeMitterer/stockinfo/issues).

## Manual installation (without Community Applications)

```bash
mkdir -p /boot/config/plugins/dockerMan/templates-user
wget -O /boot/config/plugins/dockerMan/templates-user/my-stockinfo.xml \
  https://raw.githubusercontent.com/MikeMitterer/unraid-templates/master/templates/stockinfo.xml
```

Then add the container via Docker → Add Container and select the `stockinfo` template.

## License

[MIT](LICENSE)
