# Sierra Chart Custom Studies & Trading Robots

This repository contains a professional collection of custom indicators, studies, and automated trading systems (robots) designed specifically for the Sierra Chart platform.

## Overview

The project provides high-performance C++ studies and managed chart configurations to enhance technical analysis and automate trading strategies.

## Key Components

### 1. Custom Studies ([ScCustom.cpp](file:///c:/Users/HP/Desktop/ALL/Sierra/ScCustom.cpp))
A comprehensive library of technical indicators including:
- **Delta Intensity**: High-fidelity volume delta analysis.
- **Olympus Study**: A multi-indicator signal generator compatible with various trend-following strategies.
- **Volatility Analysis**: Tools for measuring candle strength, body-to-wick ratios, and engulfing patterns.

### 2. Automated Trading Robots ([ScRobots.cpp](file:///c:/Users/HP/Desktop/ALL/Sierra/ScRobots.cpp))
Robust trading logic for automated execution:
- **GoldBug**: A sophisticated trading system with built-in risk management (max loss/profit targets), simulation mode, and support for multiple entry types (Imbalance, FVG, Engulfing).
- **Order Management**: Streamlined order execution logic compatible with Sierra Chart's trading service.

### 3. Study Collections & Chart Files
Pre-configured Sierra Chart files for rapid deployment:
- **.StdyCollct**: Bundled study settings for footprint analysis, volume profiling, and automated lines.
- **.Cht**: Ready-to-use chart templates including Footprint, TPO, and specialized Renko layouts.

## Installation

1. Copy the `.cpp` files to your Sierra Chart `Data` folder.
2. Build the DLLs within Sierra Chart using **Analysis -> Build Custom Studies DLL**.
3. Move `.Cht` and `.StdyCollct` files to your `Data` folder to load the pre-configured environments.

## Technical Details
- **Language**: C++ (Sierra Chart ACSIL)
- **Architecture**: High-performance 64-bit DLLs.
- **Platform**: Sierra Chart
