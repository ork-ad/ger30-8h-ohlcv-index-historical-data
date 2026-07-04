# GER30 8h OHLCV Index Historical Data — Free Sample

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE) [![Dataset rows](https://img.shields.io/badge/full_dataset-587_rows-blue)](https://ork.ad/) [![Updated](https://img.shields.io/badge/weekly_update-every_Sunday-green)](https://ork.ad/) [![Full data on ork.ad](https://img.shields.io/badge/download-ork.ad-orange)](https://ork.ad/)

### → [**Download the full GER30 dataset on ork.ad**](https://ork.ad/)

**GER30 8h OHLCV Stock index historical data** — ultra high-quality 8h OHLCV for **Germany 30 (DAX)**. Global cash and extended index sessions — Asia, Europe and US coverage, not US-hours only. Clean `time, open, high, low, close, volume` CSV for backtesting, algorithmic trading and quantitative research.

## Table of contents

- [Why this dataset?](#why-this-dataset)
- [Download sample CSV](#download-sample)
- [GitHub Pages preview](#github-pages)
- [Sample vs full dataset](#sample-vs-full-dataset)
- [Timeframes on ork.ad](#timeframes-on-orkad)
- [Weekly updates](#weekly-updates)
- [Data preview](#data-preview)
- [Schema](#schema)
- [Code examples](#code-examples)
- [Download full data on ork.ad](#download-full-data)

## Why this dataset?

- **Ultra high-quality 8h OHLCV** for **Germany 30 (DAX)** (Stock index)
- **Global cash and extended index sessions — Asia, Europe and US coverage, not US-hours only**
- **Clean CSV schema** — `time, open, high, low, close, volume` (no gaps in formatting)
- **Free evaluation sample** on GitHub (`8h`) · **13 timeframes** on [ork.ad](https://ork.ad/) · **587** `8h` rows in the full archive
- Built for **backtesting**, **algorithmic trading** and **quantitative finance** workflows
- **Weekly refresh** — [ork.ad](https://ork.ad/) every **Sunday**; GitHub `8h` sample updated in sync

> **Sample on GitHub** · `GER30_8h.csv` (562 rows, `2025-10-02` → `2026-07-02`). **Full archive on [ork.ad](https://ork.ad/)** — **587** `8h` rows (~0.04 MB), **13 timeframes** (``1m`, `3m`, `5m`, `15m`, `30m`, `1H`, `2H`, `4H`, `8H`, `12H`, `16H`, `1D`, `1W``), `2025-09-22` → `2026-07-02`.

## Download sample

**[GER30_8h.csv](https://github.com/ork-ad/ger30-8h-ohlcv-index-historical-data/blob/main/GER30_8h.csv)** on GitHub ([raw CSV](https://raw.githubusercontent.com/ork-ad/ger30-8h-ohlcv-index-historical-data/main/GER30_8h.csv)) · [GitHub Releases](https://github.com/ork-ad/ger30-8h-ohlcv-index-historical-data/releases) when the release workflow is active.

## GitHub Pages

Interactive chart & stats: **[https://ork-ad.github.io/ger30-8h-ohlcv-index-historical-data/](https://ork-ad.github.io/ger30-8h-ohlcv-index-historical-data/)**

## Sample vs full dataset

| | **Sample (this repo)** | **Full dataset ([ork.ad](https://ork.ad/))** |
|---|--:|---|
| Instrument | Germany 30 (DAX) · Stock index | Germany 30 (DAX) · Stock index |
| Timeframes | `8h` (sample) | **13** — `1m`, `3m`, `5m`, `15m`, `30m`, `1H`, `2H`, `4H`, `8H`, `12H`, `16H`, `1D`, `1W` |
| 8h rows | 562 | **587** |
| Size | 0.04 MB | ~0.04 MB |
| Period | `2025-10-02` → `2026-07-02` | `2025-09-22` → `2026-07-02` |
| File | `GER30_8h.csv` | ZIP on [ork.ad](https://ork.ad/) |
| Updates | Weekly (Sunday) — GitHub sample | Weekly (Sunday) — all timeframes |

## Timeframes on ork.ad

This GitHub repository ships a **`8h` evaluation sample** only. On **[ork.ad](https://ork.ad/)**, each full asset archive is delivered as a ZIP with **13 gap-free OHLCV timeframes** (one CSV per timeframe):

**1m** · **3m** · **5m** · **15m** · **30m** · **1H** · **2H** · **4H** · **8H** · **12H** · **16H** · **1D** · **1W**

GitHub = `8h` sample · [ork.ad](https://ork.ad/) = all **13** timeframes above for the same instrument.

## Weekly updates

- **[ork.ad](https://ork.ad/)** — Full datasets on ork.ad are updated every Sunday.
- **GitHub (this repo)** — GitHub samples are refreshed weekly (every Sunday), in sync with ork.ad.

When a new `8h` sample is published on GitHub, the README, chart preview and CSV reflect the latest week of data.

## Data preview

First and latest rows from the GitHub sample **`GER30_8h.csv`**:

**First rows**

| time | open | high | low | close | volume |
| --- | --- | --- | --- | --- | --- |
| 2025-10-02T16:00:00Z | 24481.825 | 24521.835 | 24473.325 | 24487.715 | 13698.0 |
| 2025-10-03T00:00:00Z | 24487.715 | 24563.75 | 24469.775 | 24505.75 | 13782.0 |
| 2025-10-03T08:00:00Z | 24505.75 | 24510.275 | 24365.24 | 24425.774 | 36579.0 |
| 2025-10-03T16:00:00Z | 24425.774 | 24426.24 | 24358.774 | 24412.14 | 19746.0 |
| 2025-10-06T00:00:00Z | 24412.14 | 24457.34 | 24286.34 | 24343.34 | 20600.0 |

**Last rows**

| time | open | high | low | close | volume |
| --- | --- | --- | --- | --- | --- |
| time | open | high | low | close | volume |
| 2026-07-01T08:00:00Z | 25076.3 | 25118.31 | 24904.3 | 25078.32 | 119908.0 |
| 2026-07-01T16:00:00Z | 25078.32 | 25109.97 | 25054.46 | 25066.72 | 20743.0 |
| 2026-07-02T00:00:00Z | 25066.72 | 25168.93 | 24970.16 | 25128.78 | 53369.0 |
| 2026-07-02T08:00:00Z | 25128.78 | 25685.28 | 25113.76 | 25578.26 | 141460.0 |

## Schema

```text
time,open,high,low,close,volume
```

## Code examples

### pandas

```python
import pandas as pd

df = pd.read_csv('GER30_8h.csv', parse_dates=['time'])
df.set_index('time', inplace=True)
print(df.describe())
print(df.resample('1h').agg({'open': 'first', 'high': 'max',
                              'low': 'min', 'close': 'last', 'volume': 'sum'}).head())
```

### backtrader

```python
import backtrader as bt
import pandas as pd

df = pd.read_csv('GER30_8h.csv', parse_dates=['time'])
df.set_index('time', inplace=True)

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

df = pd.read_csv('GER30_8h.csv', parse_dates=['time'])
close = df.set_index('time')['close']
fast, slow = vbt.MA.run(close, 10), vbt.MA.run(close, 50)
entries = fast.ma_crossed_above(slow)
exits = fast.ma_crossed_below(slow)
pf = vbt.Portfolio.from_signals(close, entries, exits, init_cash=10_000, freq='8h')
print(pf.stats())
```

## Download full data

The complete **GER30** archive on **[ork.ad](https://ork.ad/)** includes **13 OHLCV timeframes** (`1m`, `3m`, `5m`, `15m`, `30m`, `1H`, `2H`, `4H`, `8H`, `12H`, `16H`, `1D`, `1W`) — **587** rows at `8h`, plus all other timeframes in the same ZIP.

**[→ Get the full GER30 dataset on ork.ad](https://ork.ad/)**

---
*GetData · GER30 8h OHLCV sample on GitHub · Full historical data on [ork.ad](https://ork.ad/) · 2026-07-04 UTC*