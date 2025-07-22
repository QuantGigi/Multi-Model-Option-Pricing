# Option Pricing Engine (Object-Oriented)

This repository contains a modular and extensible **option pricing engine** built in Python using an **object-oriented approach**. The project currently supports multiple stochastic models and pricing methods, focused on **vanilla options**.

## Features

- **Supported Models**:
  - Black-Scholes (constant volatility)
  - Heston (stochastic volatility)
  - SABR (stochastic volatility with skew)
  - Vasicek (stochastic interest rates)
  
- **Pricing Methods**:
  - Monte Carlo Simulation
  - Closed-form (when available, e.g. Black-Scholes)

- **Design**:
  - Object-oriented structure for clarity and extensibility
  - Easy to plug in additional models

- Basic unit testing available for key components
- Ready-to-use Jupyter notebooks for demonstration

## Work in Progress

This is not necessarily the final version. The architecture is designed to allow **easy integration of new models, methods, or option types** (e.g. barrier, Asian, American with LSMC, etc.).

Feel free to contribute or suggest improvements !
