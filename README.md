# Simple Moving Average (SMA) Crossover Strategy

This project implements a **Simple Moving Average (SMA) Crossover** trading strategy using Python and Jupyter Notebook.  
It plots a price chart along with SMA lines and generates **Buy** and **Sell** signals based on crossover events.

## Strategy Overview
- The strategy calculates **two SMAs**:
  - **Short-term SMA** (3-day)
  - **Long-term SMA** (5-day)
- **Buy Signal** → When the short-term SMA crosses **above** the long-term SMA.
- **Sell Signal** → When the short-term SMA crosses **below** the long-term SMA.

---

## Example Chart
The notebook generates a chart showing:
- Price data
- Short-term SMA
- Long-term SMA
- Buy and Sell signal markers
---

## ⚙ How to Use
1. Install required dependencies:
   ```bash
   pip install pandas matplotlib
