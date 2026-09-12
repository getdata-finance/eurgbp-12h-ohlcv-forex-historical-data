# EURGBP 12h OHLCV Forex Historical Data — Free Sample

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE) [![Dataset rows](https://img.shields.io/badge/full_dataset-8_156_rows-blue)](https://getdata.finance/datasets/eurgbp) [![Updated](https://img.shields.io/badge/weekly_update-every_Saturday_8am_UTC-green)](https://getdata.finance) [![Full data on getdata.finance](https://img.shields.io/badge/download-getdata.finance-orange)](https://getdata.finance/datasets/eurgbp)

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
- **Free evaluation sample** on GitHub (`12h`) · **11 timeframes** on [getdata.finance](https://getdata.finance/datasets/eurgbp) · **8,156** `12h` rows in the full archive
- Built for **backtesting**, **algorithmic trading** and **quantitative finance** workflows
- **Weekly refresh** — [getdata.finance](https://getdata.finance) every **Saturday, 8am UTC+0**; GitHub `12h` sample updated in sync

> **Sample on GitHub** · `EURGBP_12h.csv` (289 rows, `2026-03-12` -> `2026-09-11`, 29.85 KB). **Full archive on [getdata.finance](https://getdata.finance/datasets/eurgbp)** — **8,156** `12h` rows (full `1m`: 5,322,800), **11 timeframes**, `2012-05-23` -> `2026-09-11`.

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
| 12h rows | 289 | **8,156** |
| Size | 29.85 KB | full ZIP on [getdata.finance](https://getdata.finance/datasets/eurgbp) |
| Period | `2026-03-12` -> `2026-09-11` | `2012-05-23` -> `2026-09-11` |
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
| 2026-03-12T12:00:00+00:00 | 0.86079 | 0.86163 | 0.85997 | 0.86111 | 132207 |
| 2026-03-13T00:00:00+00:00 | 0.86111 | 0.86347 | 0.86025 | 0.86344 | 98560 |
| 2026-03-13T12:00:00+00:00 | 0.86344 | 0.86364 | 0.86108 | 0.86118 | 121543.09047 |
| 2026-03-15T12:00:00+00:00 | 0.86118 | 0.86257 | 0.8609 | 0.86221 | 13959.36885 |
| 2026-03-16T00:00:00+00:00 | 0.86221 | 0.86396 | 0.86147 | 0.86341 | 83345 |

**Last rows**

| datetime | open | high | low | close | volume |
| --- | --- | --- | --- | --- | --- |
| 2026-09-09T12:00:00+00:00 | 0.85874 | 0.85951 | 0.85783 | 0.85861 | 78717 |
| 2026-09-10T00:00:00+00:00 | 0.85861 | 0.85912 | 0.85837 | 0.85867 | 57527 |
| 2026-09-10T12:00:00+00:00 | 0.85867 | 0.85998 | 0.85855 | 0.85941 | 103810 |
| 2026-09-11T00:00:00+00:00 | 0.85941 | 0.85967 | 0.8581 | 0.85838 | 76792 |
| 2026-09-11T12:00:00+00:00 | 0.85838 | 0.85849 | 0.85706 | 0.85724 | 91412 |

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

The complete **EURGBP** archive on **[getdata.finance](https://getdata.finance/datasets/eurgbp)** includes **11 OHLCV timeframes** (1m · 3m · 5m · 15m · 30m · 1H · 4H · 12H · 1D · 3D · 1W) — **8,156** rows at `12h`, plus all other timeframes in the same ZIP.

**[-> Get the full EURGBP dataset on getdata.finance](https://getdata.finance/datasets/eurgbp)**

---
*GetData · EURGBP 12h OHLCV sample on GitHub · Full historical data on [getdata.finance](https://getdata.finance/datasets/eurgbp)*
