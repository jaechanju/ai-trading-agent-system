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

(여기에 Streamlit 화면 캡처 넣기)

---

## Performance Snapshot

(간단히라도 작성)

* Average return
* Win rate
* Max drawdown

---

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
