# Pricing Exotic Options with Monte Carlo Simulation

This repository contains Python code for pricing exotic options using Monte Carlo simulation. Exotic options are financial derivatives with more complex features than standard European or American options. This project aims to provide a flexible framework for simulating and pricing these options.

## Table of Contents

- [Introduction](#introduction)
- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
- [Examples](#examples)
- [Contributing](#contributing)
- [License](#license)

## Introduction

Monte Carlo simulation is a powerful numerical method used to estimate the value of financial derivatives. This repository focuses on using Monte Carlo techniques to price various exotic options, such as Asian options, Barrier options, and Lookback options.

## Features

- Simulate underlying asset price paths using Geometric Brownian Motion (GBM).
- Price Asian options (both arithmetic and geometric average).
- Price Barrier options (up-and-out, down-and-out, up-and-in, down-and-in).
- Price Lookback options (fixed and floating strike).
- Flexible framework for adding new types of exotic options.
- Uses variance reduction techniques for improved accuracy.

## Installation

To use this code, you'll need Python 3.x and the following packages:
- numpy
- scipy
- matplotlib

You can install the required packages using pip:

```bash
pip install numpy scipy matplotlib
