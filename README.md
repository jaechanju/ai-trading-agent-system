# AI Multi-Agent Trading System

## Overview

This system is designed to replicate discretionary trading decisions using modular agents.

Instead of relying on a single indicator, it combines multiple perspectives:

* technical structure
* market flow
* financing risk
* AI-based forecasting

The final decision is made through a portfolio manager (PM) layer.

---

## Why This Exists

Discretionary trading works.

However, it is:

* difficult to scale
* difficult to verify
* difficult to reproduce

This system translates trading intuition into structured, repeatable decision processes.

---

## Architecture

### 1. Technical Agent

* Trend, momentum, breakout conditions
* EMA-based filters
* Structure signals

### 2. KRX Flow Agent

* Program trading
* Foreign flow
* Market breadth

### 3. Financing Risk Agent

* Leverage and positioning risk
* Market stress signals

### 4. Kronos AI Agent

* Time-series forecasting
* Expected return estimation
* Probability outputs

### 5. PM Decision Layer

* Aggregates all agent outputs
* Produces:

  * final opinion (BUY / PASS / AVOID)
  * conviction score
  * position sizing suggestion

---

## Example Output

<img width="1563" height="886" alt="5" src="https://github.com/user-attachments/assets/77660c75-29df-46ce-a14d-72ece7bed19e" />
<img width="1500" height="832" alt="4" src="https://github.com/user-attachments/assets/7654bc13-ecb3-45e1-b031-8c12fb198338" />
<img width="1594" height="767" alt="1" src="https://github.com/user-attachments/assets/579998a7-d151-4392-8e5b-a0e9e46e4c59" />
<img width="1560" height="794" alt="3" src="https://github.com/user-attachments/assets/01293aa2-3588-4158-a375-dc3b48458a30" />
<img width="1553" height="582" alt="2" src="https://github.com/user-attachments/assets/263ce312-bd05-4a35-b518-e447e8d7712f" />


---

## Performance Snapshot

Performance metrics will be updated as more trades are accumulated.

## Key Idea

Markets are not driven by a single signal.

They are driven by:

* structure
* flow
* positioning

This system attempts to model that interaction.

---

## Future Work

* Expand trading universe
* Improve agent weighting logic
* Add volatility regime filter
* Automate data ingestion

---

## Related Repositories

- [Quant Research Notes](https://github.com/jaechanju/quant-research-notes)
- [Alpha Signal Library](https://github.com/jaechanju/alpha-signal-library)
- [Trading Risk Management](https://github.com/jaechanju/trading-risk-management)
- [Ratio Spread Strategy](https://github.com/jaechanju/ratio-spread-strategy)
- [Scalping Strategy](https://github.com/jaechanju/scalping-strategy)
