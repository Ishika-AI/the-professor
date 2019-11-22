# Deribit Trading Bot

## Install

```
npm install
```

## Config

Copy `.env.sample` and name it `.env`. Replace variables inside with your api key details. Preferably create a subaccount and use that. Use `ENV=test` for using the test api and `ENV=anything_else` for live.

Removing `TIMEFRAME` defaults to 3 minute timeframe.
Removing `INSTRUMENTNAME` defaults to `BTC-PERPETUAL`.

## Run

```
npm start
```

## Liability

Use at your own risk if you're going to use real money. This is not battle hardened and fully tested and I accept no responsibility for any monetary losses incurred from using this software.