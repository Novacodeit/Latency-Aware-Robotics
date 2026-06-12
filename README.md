# Latency-Aware-Robotics
Research implementation of Differentiable Model Predictive Control for robust cyber-physical robotic systems

Overview
​This repository contains the official implementation and research artifacts for Latency-Aware Adaptive Control via Differentiable Model Predictive Control (MPC).
​In many Cyber-Physical Systems (CPS), communication delays and computational latency significantly degrade control performance and stability. This project introduces a framework that leverages differentiable optimization to explicitly account for varying latency, allowing the controller to adapt in real-time to shifting system dynamics and timing constraints.
Key Features
​Differentiable MPC: Built using PyTorch and JAX for gradient-based optimization.
​Robust Adaptation: Real-time parameter estimation to mitigate the impact of latency-induced uncertainty.
​Simulation Framework: A modular environment setup to test controllers under synthetic latency distributions.
​Performance Analytics: Tools for plotting convergence, tracking error, and stability margins.
Getting Started
​Prerequisites
​Ensure you have the following installed:
​Python 3.10+
​Required Simulation Engine: MuJoCo
​Core Library,e.g., CasADi or PyTorch


