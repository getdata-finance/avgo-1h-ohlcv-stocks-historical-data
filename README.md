# AVGO 1h OHLCV US stocks Historical Data — Free Sample

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE) [![Dataset rows](https://img.shields.io/badge/full_dataset-12_396_rows-blue)](https://getdata.finance/datasets/avgo) [![Updated](https://img.shields.io/badge/weekly_update-every_Saturday_8am_UTC-green)](https://getdata.finance) [![Full data on getdata.finance](https://img.shields.io/badge/download-getdata.finance-orange)](https://getdata.finance/datasets/avgo)

### -> [**Download the full AVGO dataset on getdata.finance**](https://getdata.finance/datasets/avgo)

**AVGO 1h OHLCV stocks historical data** — ultra high-quality 1h OHLCV for **Broadcom**. Clean `datetime, open, high, low, close, volume` CSV for backtesting, algorithmic trading and quantitative research.

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

- **Ultra high-quality 1h OHLCV** for **Broadcom** (US stocks)
- **Clean CSV schema** — `datetime, open, high, low, close, volume` (no gaps in formatting)
- **Free evaluation sample** on GitHub (`1h`) · **11 timeframes** on [getdata.finance](https://getdata.finance/datasets/avgo) · **12,396** `1h` rows in the full archive
- Built for **backtesting**, **algorithmic trading** and **quantitative finance** workflows
- **Weekly refresh** — [getdata.finance](https://getdata.finance) every **Saturday, 8am UTC+0**; GitHub `1h` sample updated in sync

> **Sample on GitHub** · `AVGO_1h.csv` (889 rows, `2026-03-23` -> `2026-09-22`, 85.59 KB). **Full archive on [getdata.finance](https://getdata.finance/datasets/avgo)** — **12,396** `1h` rows (full `1m`: 111,138), **11 timeframes**, `2011-05-09` -> `2026-09-22`.

## Download sample

**[AVGO_1h.csv](https://github.com/getdata-finance/avgo-1h-ohlcv-stocks-historical-data/blob/main/AVGO_1h.csv)** on GitHub ([raw CSV](https://raw.githubusercontent.com/getdata-finance/avgo-1h-ohlcv-stocks-historical-data/main/AVGO_1h.csv)) · [GitHub Releases](https://github.com/getdata-finance/avgo-1h-ohlcv-stocks-historical-data/releases)

## GitHub Pages

Interactive chart & stats: **[https://getdata-finance.github.io/avgo-1h-ohlcv-stocks-historical-data/](https://getdata-finance.github.io/avgo-1h-ohlcv-stocks-historical-data/)**

Full archive & live chart on getdata.finance: **[https://getdata.finance/datasets/avgo](https://getdata.finance/datasets/avgo)**

## Sample vs full dataset

| | **Sample (this repo)** | **Full dataset ([getdata.finance](https://getdata.finance/datasets/avgo))** |
|---|--:|---|
| Instrument | Broadcom · US stocks | Broadcom · US stocks |
| Timeframes | `1h` (sample) | **11** — 1m · 3m · 5m · 15m · 30m · 1H · 4H · 12H · 1D · 3D · 1W |
| 1h rows | 889 | **12,396** |
| Size | 85.59 KB | full ZIP on [getdata.finance](https://getdata.finance/datasets/avgo) |
| Period | `2026-03-23` -> `2026-09-22` | `2011-05-09` -> `2026-09-22` |
| File | `AVGO_1h.csv` | ZIP on [getdata.finance](https://getdata.finance/datasets/avgo) |
| Coverage report | — | [AVGO coverage](https://getdata.finance/coverage/avgo) |
| Updates | Weekly (Saturday, 8am UTC+0) — GitHub sample | Weekly (Saturday, 8am UTC+0) — all timeframes |

## Timeframes on GetData

This GitHub repository ships a **`1h` evaluation sample** only. On **[getdata.finance](https://getdata.finance/datasets/avgo)**, each full asset archive is delivered as a ZIP with **11 gap-free OHLCV timeframes** (one CSV per timeframe):

**1m · 3m · 5m · 15m · 30m · 1H · 4H · 12H · 1D · 3D · 1W**

GitHub = `1h` sample · [getdata.finance](https://getdata.finance/datasets/avgo) = all **11** timeframes above for the same instrument.

## Weekly updates

- **[getdata.finance](https://getdata.finance)** — Full datasets are updated every Saturday, 8am UTC+0.
- **GitHub (this repo)** — GitHub samples are refreshed weekly (every Saturday, 8am UTC+0), in sync with getdata.finance.

When a new `1h` sample is published on GitHub, the README, chart preview and CSV reflect the latest week of data.

## Data preview

First and latest rows from the GitHub sample **`AVGO_1h.csv`**:

**First rows**

| datetime | open | high | low | close | volume |
| --- | --- | --- | --- | --- | --- |
| 2026-03-23T13:00:00+00:00 | 319.92 | 333.11 | 319.92 | 333.02 | 5682 |
| 2026-03-23T14:00:00+00:00 | 333.02 | 335.46 | 331.08 | 333.02 | 10237 |
| 2026-03-23T15:00:00+00:00 | 333.02 | 334.78 | 328.45 | 328.62 | 8678 |
| 2026-03-23T16:00:00+00:00 | 328.62 | 331.13 | 328.43 | 329.66 | 8602 |
| 2026-03-23T17:00:00+00:00 | 329.66 | 330.86 | 328.25 | 330.85 | 7012 |

**Last rows**

| datetime | open | high | low | close | volume |
| --- | --- | --- | --- | --- | --- |
| 2026-09-22T15:00:00+00:00 | 362.64 | 363.4 | 361.76 | 362.98 | 3540 |
| 2026-09-22T16:00:00+00:00 | 362.98 | 363.66 | 361.83 | 363.22 | 3664 |
| 2026-09-22T17:00:00+00:00 | 363.22 | 364.65 | 363.05 | 364.28 | 3386 |
| 2026-09-22T18:00:00+00:00 | 364.28 | 364.69 | 363.54 | 364.16 | 3576 |
| 2026-09-22T19:00:00+00:00 | 364.16 | 366.35 | 364.04 | 364.62 | 4625 |

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

df = pd.read_csv('AVGO_1h.csv', parse_dates=['datetime'])
df.set_index('datetime', inplace=True)
print(df.describe())
```

### backtrader

```python
import backtrader as bt
import pandas as pd

df = pd.read_csv('AVGO_1h.csv', parse_dates=['datetime'])
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

df = pd.read_csv('AVGO_1h.csv', parse_dates=['datetime'])
close = df.set_index('datetime')['close']
fast, slow = vbt.MA.run(close, 10), vbt.MA.run(close, 50)
entries = fast.ma_crossed_above(slow)
exits = fast.ma_crossed_below(slow)
pf = vbt.Portfolio.from_signals(close, entries, exits, init_cash=10_000, freq='1h')
print(pf.stats())
```

## Download full data

The complete **AVGO** archive on **[getdata.finance](https://getdata.finance/datasets/avgo)** includes **11 OHLCV timeframes** (1m · 3m · 5m · 15m · 30m · 1H · 4H · 12H · 1D · 3D · 1W) — **12,396** rows at `1h`, plus all other timeframes in the same ZIP.

**[-> Get the full AVGO dataset on getdata.finance](https://getdata.finance/datasets/avgo)**

---
*GetData · AVGO 1h OHLCV sample on GitHub · Full historical data on [getdata.finance](https://getdata.finance/datasets/avgo)*
