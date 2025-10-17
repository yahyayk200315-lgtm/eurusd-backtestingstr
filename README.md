# eurusd-backtestingstr
Data-driven EUR/USD trading automation based on Goldbach zone logic and Fair Value Gaps.
🔹 Project Title:

Goldbach FVG Zone Trading Strategy Automation

🔹 Description:

This project automates the Goldbach FVG Zone strategy — a data-driven approach to trading the EUR/USD pair. It identifies Fair Value Gaps (FVGs) within predefined Goldbach zones, determines directional bias based on the London session price structure, and executes simulated entries during the New York session.

The script uses historical data to backtest and validate the strategy, applying key parameters such as:

Session bias detection: Long or short bias based on London session behavior

Goldbach FVG detection: Valid FVGs forming within 0.111–0.17 or 0.83–0.89 of the zone

Entry timing: Between 6 PM and 10 PM PKT

Risk-to-Reward ratio: 1:3 with dynamic stop-loss placement

🔹 Features:

Automated FVG detection using candle data

Session-based bias logic

Backtesting using CSV historical data (eurusd.csv)

Customizable parameters (time windows, AXR lookback, RR ratio)

Modular Python code for easy modification and future improvements

🔹 Tech Stack:

Language: Python (Jupyter Notebook)

Libraries: pandas, numpy, matplotlib, datetime

Data Source: Historical EUR/USD CSV

🔹 Goal:

To build a fully automated and backtestable version of the Goldbach FVG Zone strategy — bridging manual trading logic with data science tools for enhanced precision and performance evaluation.
