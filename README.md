# MSFT 3m OHLCV US stocks Historical Data — Free Sample

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE) [![Dataset rows](https://img.shields.io/badge/full_dataset-405_324_rows-blue)](https://getdata.finance/datasets/msft) [![Updated](https://img.shields.io/badge/weekly_update-every_Saturday_8am_UTC-green)](https://getdata.finance) [![Full data on getdata.finance](https://img.shields.io/badge/download-getdata.finance-orange)](https://getdata.finance/datasets/msft)

### -> [**Download the full MSFT dataset on getdata.finance**](https://getdata.finance/datasets/msft)

**MSFT 3m OHLCV stocks historical data** — ultra high-quality 3m OHLCV for **Microsoft**. Clean `datetime, open, high, low, close, volume` CSV for backtesting, algorithmic trading and quantitative research.

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

- **Ultra high-quality 3m OHLCV** for **Microsoft** (US stocks)
- **Clean CSV schema** — `datetime, open, high, low, close, volume` (no gaps in formatting)
- **Free evaluation sample** on GitHub (`3m`) · **11 timeframes** on [getdata.finance](https://getdata.finance/datasets/msft) · **405,324** `3m` rows in the full archive
- Built for **backtesting**, **algorithmic trading** and **quantitative finance** workflows
- **Weekly refresh** — [getdata.finance](https://getdata.finance) every **Saturday, 8am UTC+0**; GitHub `3m` sample updated in sync

> **Sample on GitHub** · `MSFT_3m.csv` (16,507 rows, `2026-03-26` -> `2026-09-25`, 1.50 MB). **Full archive on [getdata.finance](https://getdata.finance/datasets/msft)** — **405,324** `3m` rows (full `1m`: 634,891), **11 timeframes**, `2011-05-09` -> `2026-09-25`.

## Download sample

**[MSFT_3m.csv](https://github.com/getdata-finance/msft-3m-ohlcv-stocks-historical-data/blob/main/MSFT_3m.csv)** on GitHub ([raw CSV](https://raw.githubusercontent.com/getdata-finance/msft-3m-ohlcv-stocks-historical-data/main/MSFT_3m.csv)) · [GitHub Releases](https://github.com/getdata-finance/msft-3m-ohlcv-stocks-historical-data/releases)

## GitHub Pages

Interactive chart & stats: **[https://getdata-finance.github.io/msft-3m-ohlcv-stocks-historical-data/](https://getdata-finance.github.io/msft-3m-ohlcv-stocks-historical-data/)**

Full archive & live chart on getdata.finance: **[https://getdata.finance/datasets/msft](https://getdata.finance/datasets/msft)**

## Sample vs full dataset

| | **Sample (this repo)** | **Full dataset ([getdata.finance](https://getdata.finance/datasets/msft))** |
|---|--:|---|
| Instrument | Microsoft · US stocks | Microsoft · US stocks |
| Timeframes | `3m` (sample) | **11** — 1m · 3m · 5m · 15m · 30m · 1H · 4H · 12H · 1D · 3D · 1W |
| 3m rows | 16,507 | **405,324** |
| Size | 1.50 MB | full ZIP on [getdata.finance](https://getdata.finance/datasets/msft) |
| Period | `2026-03-26` -> `2026-09-25` | `2011-05-09` -> `2026-09-25` |
| File | `MSFT_3m.csv` | ZIP on [getdata.finance](https://getdata.finance/datasets/msft) |
| Coverage report | — | [MSFT coverage](https://getdata.finance/coverage/msft) |
| Updates | Weekly (Saturday, 8am UTC+0) — GitHub sample | Weekly (Saturday, 8am UTC+0) — all timeframes |

## Timeframes on GetData

This GitHub repository ships a **`3m` evaluation sample** only. On **[getdata.finance](https://getdata.finance/datasets/msft)**, each full asset archive is delivered as a ZIP with **11 gap-free OHLCV timeframes** (one CSV per timeframe):

**1m · 3m · 5m · 15m · 30m · 1H · 4H · 12H · 1D · 3D · 1W**

GitHub = `3m` sample · [getdata.finance](https://getdata.finance/datasets/msft) = all **11** timeframes above for the same instrument.

## Weekly updates

- **[getdata.finance](https://getdata.finance)** — Full datasets are updated every Saturday, 8am UTC+0.
- **GitHub (this repo)** — GitHub samples are refreshed weekly (every Saturday, 8am UTC+0), in sync with getdata.finance.

When a new `3m` sample is published on GitHub, the README, chart preview and CSV reflect the latest week of data.

## Data preview

First and latest rows from the GitHub sample **`MSFT_3m.csv`**:

**First rows**

| datetime | open | high | low | close | volume |
| --- | --- | --- | --- | --- | --- |
| 2026-03-26T13:30:00+00:00 | 366.07 | 366.11 | 365.06 | 365.17 | 455 |
| 2026-03-26T13:33:00+00:00 | 365.17 | 365.31 | 364.37 | 364.91 | 420 |
| 2026-03-26T13:36:00+00:00 | 364.91 | 367.02 | 364.91 | 366.53 | 531 |
| 2026-03-26T13:39:00+00:00 | 366.53 | 367.68 | 365.78 | 367.42 | 588 |
| 2026-03-26T13:42:00+00:00 | 367.42 | 367.45 | 366.26 | 367.26 | 576 |

**Last rows**

| datetime | open | high | low | close | volume |
| --- | --- | --- | --- | --- | --- |
| 2026-09-25T19:45:00+00:00 | 515.46 | 516.01 | 515.21 | 515.61 | 397 |
| 2026-09-25T19:48:00+00:00 | 515.61 | 515.69 | 514.78 | 515.41 | 577 |
| 2026-09-25T19:51:00+00:00 | 515.41 | 516.15 | 515.39 | 516.03 | 341 |
| 2026-09-25T19:54:00+00:00 | 516.03 | 516.36 | 515.58 | 516.21 | 664 |
| 2026-09-25T19:57:00+00:00 | 516.21 | 516.27 | 515.02 | 515.68 | 419 |

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

df = pd.read_csv('MSFT_3m.csv', parse_dates=['datetime'])
df.set_index('datetime', inplace=True)
print(df.describe())
```

### backtrader

```python
import backtrader as bt
import pandas as pd

df = pd.read_csv('MSFT_3m.csv', parse_dates=['datetime'])
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

df = pd.read_csv('MSFT_3m.csv', parse_dates=['datetime'])
close = df.set_index('datetime')['close']
fast, slow = vbt.MA.run(close, 10), vbt.MA.run(close, 50)
entries = fast.ma_crossed_above(slow)
exits = fast.ma_crossed_below(slow)
pf = vbt.Portfolio.from_signals(close, entries, exits, init_cash=10_000, freq='3min')
print(pf.stats())
```

## Download full data

The complete **MSFT** archive on **[getdata.finance](https://getdata.finance/datasets/msft)** includes **11 OHLCV timeframes** (1m · 3m · 5m · 15m · 30m · 1H · 4H · 12H · 1D · 3D · 1W) — **405,324** rows at `3m`, plus all other timeframes in the same ZIP.

**[-> Get the full MSFT dataset on getdata.finance](https://getdata.finance/datasets/msft)**

---
*GetData · MSFT 3m OHLCV sample on GitHub · Full historical data on [getdata.finance](https://getdata.finance/datasets/msft)*
