# Asian Options Pricing Project

This project explores various methods for pricing Asian options, focusing on the following approaches:

## Project Overview

This project involves the evaluation and comparison of different methodologies for pricing Asian options. The methods explored include:

1. **Monte Carlo Simulation under Black-Scholes Model**:
   - **Methodology**: Uses random sampling to simulate the price paths of the underlying asset.
   - **Advantages**: Simple to implement and provides reduced variance results.
   - **Limitations**: Assumes constant volatility, which might not be realistic in volatile markets.

2. **Partial Differential Equations (PDE)**:
   - **Methodology**: Solves PDEs to compute option prices for various strike prices.
   - **Advantages**: Faster computation and provides option prices for all possible strike prices.
   - **Limitations**: Can be complex to solve for non-standard conditions.

3. **Monte Carlo Simulation under Heston Model**:
   - **Methodology**: Accounts for stochastic volatility, making the model more realistic.
   - **Advantages**: Captures market dynamics better with varying volatility.
   - **Limitations**: More complex to implement and requires significant computational power.

## Key Findings

- **Monte Carlo under Black-Scholes**:
  - Provides accurate results with very reduced variance but may not handle volatile markets well.

- **PDE Approach**:
  - Offers quick and comprehensive option pricing but can be mathematically intensive.

- **Monte Carlo under Heston**:
  - More realistic for market conditions with fluctuating volatility but requires more resources.

## Conclusion

This study highlights the importance of choosing the appropriate pricing model based on market conditions and computational resources. The comparison between Monte Carlo and PDE approaches under the Black-Scholes model and between Black-Scholes and Heston models under Monte Carlo simulations provides insights into their respective strengths and 
