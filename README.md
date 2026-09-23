# EURGBP 12h OHLCV Forex Historical Data — Free Sample

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE) [![Dataset rows](https://img.shields.io/badge/full_dataset-8_173_rows-blue)](https://getdata.finance/datasets/eurgbp) [![Updated](https://img.shields.io/badge/weekly_update-every_Saturday_8am_UTC-green)](https://getdata.finance) [![Full data on getdata.finance](https://img.shields.io/badge/download-getdata.finance-orange)](https://getdata.finance/datasets/eurgbp)

### -> [**Download the full EURGBP dataset on getdata.finance**](https://getdata.finance/datasets/eurgbp)

**EURGBP 12h OHLCV forex historical data** — ultra high-quality 12h OHLCV for **Euro / British Pound**. Clean `datetime, open, high, low, close, volume` CSV for backtesting, algorithmic trading and quantitative research.

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

- **Ultra high-quality 12h OHLCV** for **Euro / British Pound** (Forex)
- **Clean CSV schema** — `datetime, open, high, low, close, volume` (no gaps in formatting)
- **Free evaluation sample** on GitHub (`12h`) · **11 timeframes** on [getdata.finance](https://getdata.finance/datasets/eurgbp) · **8,173** `12h` rows in the full archive
- Built for **backtesting**, **algorithmic trading** and **quantitative finance** workflows
- **Weekly refresh** — [getdata.finance](https://getdata.finance) every **Saturday, 8am UTC+0**; GitHub `12h` sample updated in sync

> **Sample on GitHub** · `EURGBP_12h.csv` (290 rows, `2026-03-23` -> `2026-09-23`, 29.20 KB). **Full archive on [getdata.finance](https://getdata.finance/datasets/eurgbp)** — **8,173** `12h` rows (full `1m`: 5,322,800), **11 timeframes**, `2012-05-23` -> `2026-09-23`.

## Download sample

**[EURGBP_12h.csv](https://github.com/getdata-finance/eurgbp-12h-ohlcv-forex-historical-data/blob/main/EURGBP_12h.csv)** on GitHub ([raw CSV](https://raw.githubusercontent.com/getdata-finance/eurgbp-12h-ohlcv-forex-historical-data/main/EURGBP_12h.csv)) · [GitHub Releases](https://github.com/getdata-finance/eurgbp-12h-ohlcv-forex-historical-data/releases)

## GitHub Pages

Interactive chart & stats: **[https://getdata-finance.github.io/eurgbp-12h-ohlcv-forex-historical-data/](https://getdata-finance.github.io/eurgbp-12h-ohlcv-forex-historical-data/)**

Full archive & live chart on getdata.finance: **[https://getdata.finance/datasets/eurgbp](https://getdata.finance/datasets/eurgbp)**

## Sample vs full dataset

| | **Sample (this repo)** | **Full dataset ([getdata.finance](https://getdata.finance/datasets/eurgbp))** |
|---|--:|---|
| Instrument | Euro / British Pound · Forex | Euro / British Pound · Forex |
| Timeframes | `12h` (sample) | **11** — 1m · 3m · 5m · 15m · 30m · 1H · 4H · 12H · 1D · 3D · 1W |
| 12h rows | 290 | **8,173** |
| Size | 29.20 KB | full ZIP on [getdata.finance](https://getdata.finance/datasets/eurgbp) |
| Period | `2026-03-23` -> `2026-09-23` | `2012-05-23` -> `2026-09-23` |
| File | `EURGBP_12h.csv` | ZIP on [getdata.finance](https://getdata.finance/datasets/eurgbp) |
| Coverage report | — | [EURGBP coverage](https://getdata.finance/coverage/eurgbp) |
| Updates | Weekly (Saturday, 8am UTC+0) — GitHub sample | Weekly (Saturday, 8am UTC+0) — all timeframes |

## Timeframes on GetData

This GitHub repository ships a **`12h` evaluation sample** only. On **[getdata.finance](https://getdata.finance/datasets/eurgbp)**, each full asset archive is delivered as a ZIP with **11 gap-free OHLCV timeframes** (one CSV per timeframe):

**1m · 3m · 5m · 15m · 30m · 1H · 4H · 12H · 1D · 3D · 1W**

GitHub = `12h` sample · [getdata.finance](https://getdata.finance/datasets/eurgbp) = all **11** timeframes above for the same instrument.

## Weekly updates

- **[getdata.finance](https://getdata.finance)** — Full datasets are updated every Saturday, 8am UTC+0.
- **GitHub (this repo)** — GitHub samples are refreshed weekly (every Saturday, 8am UTC+0), in sync with getdata.finance.

When a new `12h` sample is published on GitHub, the README, chart preview and CSV reflect the latest week of data.

## Data preview

First and latest rows from the GitHub sample **`EURGBP_12h.csv`**:

**First rows**

| datetime | open | high | low | close | volume |
| --- | --- | --- | --- | --- | --- |
| 2026-03-23T12:00:00+00:00 | 0.86538 | 0.86589 | 0.86323 | 0.86511 | 210271.71564 |
| 2026-03-24T00:00:00+00:00 | 0.86511 | 0.86632 | 0.86428 | 0.86559 | 115675 |
| 2026-03-24T12:00:00+00:00 | 0.86559 | 0.86645 | 0.86489 | 0.8662 | 151732 |
| 2026-03-25T00:00:00+00:00 | 0.8662 | 0.86733 | 0.8653 | 0.86559 | 100843 |
| 2026-03-25T12:00:00+00:00 | 0.86559 | 0.86685 | 0.86478 | 0.86564 | 128436 |

**Last rows**

| datetime | open | high | low | close | volume |
| --- | --- | --- | --- | --- | --- |
| 2026-09-21T00:00:00+00:00 | 0.85727 | 0.85809 | 0.85723 | 0.85777 | 63871 |
| 2026-09-21T12:00:00+00:00 | 0.85777 | 0.85795 | 0.85718 | 0.85748 | 59470 |
| 2026-09-22T00:00:00+00:00 | 0.85748 | 0.85816 | 0.85683 | 0.85788 | 86118 |
| 2026-09-22T12:00:00+00:00 | 0.85788 | 0.8583 | 0.85709 | 0.85792 | 76932 |
| 2026-09-23T00:00:00+00:00 | 0.85792 | 0.85833 | 0.85791 | 0.8583 | 16950 |

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
pf = vbt.Portfolio.from_signals(close, entries, exits, init_cash=10_000, freq='12h')
print(pf.stats())
```

## Download full data

The complete **EURGBP** archive on **[getdata.finance](https://getdata.finance/datasets/eurgbp)** includes **11 OHLCV timeframes** (1m · 3m · 5m · 15m · 30m · 1H · 4H · 12H · 1D · 3D · 1W) — **8,173** rows at `12h`, plus all other timeframes in the same ZIP.

**[-> Get the full EURGBP dataset on getdata.finance](https://getdata.finance/datasets/eurgbp)**

---
*GetData · EURGBP 12h OHLCV sample on GitHub · Full historical data on [getdata.finance](https://getdata.finance/datasets/eurgbp)*
