# Multi-Agent-Reinforcement-Learning-GRU-for-Time-Series-Forecasting
This project implements: A Gated Recurrent Unit (GRU) for time-series prediction and Multiple reinforcement learning agents that dynamically modify input features

Dataset: Daily Delhi Climate, predicting the next-day values of:Temperature, Humidity, Wind speed, Pressure

Each feature is controlled by an independent agent that learns to improve predictions by adjusting inputs.

Instead of feeding raw data directly into the model:
→ Agents modify the input sequence before prediction
→ The GRU predicts the next timestep
→ Agents receive rewards based on prediction accuracy

Features:
Multi-feature time series forecasting

Custom GRU implementation (from scratch using NumPy)

Multi-agent system (1 agent per feature)

Reinforcement learning using REINFORCE algorithm

Feature-wise normalization and scaling

Reward shaping based on prediction error
