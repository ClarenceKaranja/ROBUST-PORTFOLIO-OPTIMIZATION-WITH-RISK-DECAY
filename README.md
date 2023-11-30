# Portfolio Optimization with Risk Decay

## Introduction

This project explores the dynamic world of portfolio optimization by incorporating the concept of risk decay over time. Traditional Mean-Variance Optimization (MVO) models assume static risk levels, but this project introduces a modification that allows for the gradual decrease in risk, aligning more closely with real-world financial dynamics.

## Objective

The main goal is to assess the impact of risk decay on portfolio performance and compare it against the traditional MVO model. The project delves into statistical analysis and visualizations to uncover any significant differences between the two approaches.

## Key Features

### 1. Custom Risk Decay Function

The project introduces a custom function that calculates risk decay over time. This function utilizes the principles of exponential decay to model the gradual reduction in risk.

### 2. Monte Carlo Simulation

A Monte Carlo Simulation is employed to simulate various portfolio scenarios. The simulation considers random weights, normalized to represent proportions of the total investment. The custom risk decay is integrated into the calculation of expected return, volatility, and Sharpe ratio.

### 3. Optimal Portfolio Identification

The simulation identifies the optimal portfolio by maximizing the Sharpe ratio. This portfolio represents an ideal balance between risk and return, considering the dynamic nature of risk over time.

## Getting Started

1. **Clone the Repository:**
   ```bash
   git clone https://github.com/clarenceKaranja/ROBUST-PORTFOLIO-OPTIMIZATION-WITH-RISK-DECAY.git
   cd portfolio-optimization-risk-decay
   ```

2. **Install Dependencies:**
   ```bash
   pip install -r requirements.txt
   ```

3. **Run the Jupyter Notebooks:**
   - Explore the notebooks to understand the methodology and results.

4. **Customize and Experiment:**
   - Feel free to modify parameters, try different decay rates, or integrate additional features.

## Results and Analysis

Check the `Results_and_Analysis.ipynb` notebook for a detailed exploration of the outcomes, statistical tests, and visualizations.

## Conclusion

This project provides insights into the dynamic nature of portfolio optimization when incorporating risk decay. The comparison with traditional MVO models sheds light on potential advantages and changes in performance over time.

Feel free to contribute, ask questions, or adapt the code for your specific needs. Happy exploring!

**Author:** Clarence Karanja
**Contact:** ClarenceKaranja@Outlook.com

---
