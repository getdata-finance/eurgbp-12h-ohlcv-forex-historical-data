# EURGBP 12h OHLCV Forex Historical Data — Free Sample

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE) [![Dataset rows](https://img.shields.io/badge/full_dataset-8_090_rows-blue)](https://getdata.finance/datasets/eurgbp) [![Updated](https://img.shields.io/badge/weekly_update-every_Saturday_8am_UTC-green)](https://getdata.finance) [![Full data on getdata.finance](https://img.shields.io/badge/download-getdata.finance-orange)](https://getdata.finance/datasets/eurgbp)

### -> [**Download the full EURGBP dataset on getdata.finance**](https://getdata.finance/datasets/eurgbp)

**EURGBP 12h OHLCV forex historical data** — ultra high-quality 12h OHLCV for **EURGBP**. 24/5 market coverage — Asia, Europe and US sessions with institutional-style FX candles. Clean `datetime, open, high, low, close, volume` CSV for backtesting, algorithmic trading and quantitative research.

## Table of contents

- [Why this dataset?](#why-this-dataset)
- [Download sample CSV](#download-sample)
- [GitHub Pages preview](#github-pages)
- [Sample vs full dataset](#sample-vs-full-dataset)
- [Timeframes on GetData](#timeframes-on-getdata)
- [Weekly updates](#weekly-updates)
- [Data preview](#data-preview)
- [Schema](#schema)
- [Code examples](#code-examples)
- [Download full data on getdata.finance](#download-full-data-on-getdata)

## Why this dataset?

- **Ultra high-quality 12h OHLCV** for **EURGBP** (Forex)
- **24/5 market coverage — Asia, Europe and US sessions with institutional-style FX candles**
- **Clean CSV schema** — `datetime, open, high, low, close, volume` (no gaps in formatting)
- **Free evaluation sample** on GitHub (`12h`) · **9 timeframes** on [getdata.finance](https://getdata.finance/datasets/eurgbp) · **8,090** `1m` rows in the full archive
- Built for **backtesting**, **algorithmic trading** and **quantitative finance** workflows
- **Weekly refresh** — [getdata.finance](https://getdata.finance) every **Saturday, 8am UTC+0**; GitHub `12h` sample updated in sync

> **Sample on GitHub** · `EURGBP_12h.csv` (345 rows, `2025-12-23` -> `2026-07-31`). **Full archive on [getdata.finance](https://getdata.finance/datasets/eurgbp)** — **8,090** `1m` rows (~0.79 MB), **9 timeframes** (1m · 3m · 5m · 15m · 30m · 1H · 12H · 3D · 1W), `2012-05-23` -> `2026-07-31`.

## Download sample

**[EURGBP_12h.csv](https://github.com/getdata-finance/eurgbp-12h-ohlcv-forex-historical-data/blob/main/EURGBP_12h.csv)** on GitHub ([raw CSV](https://raw.githubusercontent.com/getdata-finance/eurgbp-12h-ohlcv-forex-historical-data/main/EURGBP_12h.csv)) · [GitHub Releases](https://github.com/getdata-finance/eurgbp-12h-ohlcv-forex-historical-data/releases)

## GitHub Pages

Interactive chart & stats: **[https://getdata-finance.github.io/eurgbp-12h-ohlcv-forex-historical-data/](https://getdata-finance.github.io/eurgbp-12h-ohlcv-forex-historical-data/)**

Full archive & live chart on getdata.finance: **[https://getdata.finance/datasets/eurgbp](https://getdata.finance/datasets/eurgbp)**

## Sample vs full dataset

| | **Sample (this repo)** | **Full dataset ([getdata.finance](https://getdata.finance/datasets/eurgbp))** |
|---|--:|---|
| Instrument | EURGBP · Forex | EURGBP · Forex |
| Timeframes | `12h` (sample) | **9** — 1m · 3m · 5m · 15m · 30m · 1H · 12H · 3D · 1W |
| 1m rows | 345 | **8,090** |
| Size | 0.04 MB | ~0.79 MB |
| Period | `2025-12-23` -> `2026-07-31` | `2012-05-23` -> `2026-07-31` |
| File | `EURGBP_12h.csv` | ZIP on [getdata.finance](https://getdata.finance/datasets/eurgbp) |
| Coverage report | — | [EURGBP coverage](https://getdata.finance/coverage/eurgbp) |
| Updates | Weekly (Saturday, 8am UTC+0) — GitHub sample | Weekly (Saturday, 8am UTC+0) — all timeframes |

## Timeframes on GetData

This GitHub repository ships a **`12h` evaluation sample** only. On **[getdata.finance](https://getdata.finance/datasets/eurgbp)**, each full asset archive is delivered as a ZIP with **9 gap-free OHLCV timeframes** (one CSV per timeframe):

**1m** · **3m** · **5m** · **15m** · **30m** · **1H** · **12H** · **3D** · **1W**

GitHub = `12h` sample · [getdata.finance](https://getdata.finance/datasets/eurgbp) = all **9** timeframes above for the same instrument.

## Weekly updates

- **[getdata.finance](https://getdata.finance)** — Full datasets are updated every Saturday, 8am UTC+0.
- **GitHub (this repo)** — GitHub samples are refreshed weekly (every Saturday, 8am UTC+0), in sync with getdata.finance.

When a new `12h` sample is published on GitHub, the README, chart preview and CSV reflect the latest week of data.

## Data preview

First and latest rows from the GitHub sample **`EURGBP_12h.csv`**:

**First rows**

| datetime | open | high | low | close | volume |
| --- | --- | --- | --- | --- | --- |
| 2025-12-23T00:00:00+00:00 | 0.87265 | 0.87291 | 0.8712 | 0.87272 | 83621 |
| 2025-12-23T12:00:00+00:00 | 0.87272 | 0.87295 | 0.87095 | 0.87233 | 94500.393917263 |
| 2025-12-24T00:00:00+00:00 | 0.87233 | 0.87265 | 0.87149 | 0.87213 | 77451 |
| 2025-12-24T12:00:00+00:00 | 0.87213 | 0.87251 | 0.87108 | 0.87112 | 93234.4922919768 |
| 2025-12-26T00:00:00+00:00 | 0.87234 | 0.87401 | 0.87165 | 0.87348 | 91836.3340690627 |

**Last rows**

| datetime | open | high | low | close | volume |
| --- | --- | --- | --- | --- | --- |
| 2026-07-29T12:00:00+00:00 | 0.85336 | 0.85566 | 0.8523 | 0.85495 | 114827.5878592004 |
| 2026-07-30T00:00:00+00:00 | 0.85495 | 0.85542 | 0.85335 | 0.85433 | 86943 |
| 2026-07-30T12:00:00+00:00 | 0.85433 | 0.8558 | 0.85219 | 0.85322 | 111146 |
| 2026-07-31T00:00:00+00:00 | 0.85322 | 0.85375 | 0.85241 | 0.85313 | 107840 |
| 2026-07-31T12:00:00+00:00 | 0.85313 | 0.85374 | 0.85143 | 0.85189 | 126328 |

## Schema

| Column | Description |
| --- | --- |
| `datetime` | Bar open timestamp (UTC, ISO-8601). |
| `open` | Opening price of the candlestick bar. |
| `high` | Highest price during the bar. |
| `low` | Lowest price during the bar. |
| `close` | Closing price of the candlestick bar. |
| `volume` | Tick volume (number of price updates) during the bar. |

```text
datetime,open,high,low,close,volume
```

## Code examples

### pandas

```python
import pandas as pd

df = pd.read_csv('EURGBP_12h.csv', parse_dates=['datetime'])
df.set_index('datetime', inplace=True)
print(df.describe())
print(df.resample('1h').agg({'open': 'first', 'high': 'max',
                              'low': 'min', 'close': 'last', 'volume': 'sum'}).head())
```

### backtrader

```python
import backtrader as bt
import pandas as pd

df = pd.read_csv('EURGBP_12h.csv', parse_dates=['datetime'])
df.set_index('datetime', inplace=True)

class PandasData(bt.feeds.PandasData):
    params = (('datetime', None), ('open', 'open'), ('high', 'high'),
              ('low', 'low'), ('close', 'close'), ('volume', 'volume'))

cerebro = bt.Cerebro()
cerebro.adddata(PandasData(dataname=df))
# cerebro.addstrategy(YourStrategy)
# cerebro.run()
```

### vectorbt

```python
import pandas as pd
import vectorbt as vbt

df = pd.read_csv('EURGBP_12h.csv', parse_dates=['datetime'])
close = df.set_index('datetime')['close']
fast, slow = vbt.MA.run(close, 10), vbt.MA.run(close, 50)
entries = fast.ma_crossed_above(slow)
exits = fast.ma_crossed_below(slow)
pf = vbt.Portfolio.from_signals(close, entries, exits, init_cash=10_000, freq='1min')
print(pf.stats())
```

## Download full data

The complete **EURGBP** archive on **[getdata.finance](https://getdata.finance/datasets/eurgbp)** includes **9 OHLCV timeframes** (1m · 3m · 5m · 15m · 30m · 1H · 12H · 3D · 1W) — **8,090** rows at `1m`, plus all other timeframes in the same ZIP.

**[-> Get the full EURGBP dataset on getdata.finance](https://getdata.finance/datasets/eurgbp)**

---
*GetData · EURGBP 12h OHLCV sample on GitHub · Full historical data on [getdata.finance](https://getdata.finance/datasets/eurgbp) · 2026-08-05 UTC*
