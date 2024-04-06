# Hull-White Model Calibration for ATM Caplets and Caps

## Project Overview

This project focuses on the intricate task of calibrating the Hull-White model to at-the-money (ATM) caplet market implied volatilities. Through a meticulous process that involves both theoretical and simulation-based approaches, we aim to bridge the gap between model predictions and market observations. Our endeavor is not just an academic exercise but a deep dive into the dynamics of fixed income derivatives, exploring the nuances of the Hull-White model and its practical applications in today's financial markets.

## Objectives

The primary objectives of this project are as follows:

- **Data Acquisition:** Securely download ATM cap data that serves as the foundation for our calibration process.
- **Model Implementation:** Develop a theoretical closed-form pricing function specific to the Hull-White model.
- **Simulation Verification:** Create a Monte-Carlo simulation-based function to verify the consistency of cap pricing with the closed-form solution.
- **Model Calibration:** Calibrate the Hull-White model to the ATM caplet market data by minimizing the sum of squared pricing errors across model parameters.

## Methodology

The project is structured around a series of MATLAB functions, each tailored to accomplish specific tasks within the model calibration process:

1. **Black Cap Pricing:** Conversion of Bloomberg Market Implied Vol into Dollar Price.
2. **HW Model Implementation:** Including Caplets pricing based on Zero-Bond (ZB) put Pricing, Cap price aggregation from Caplets, analytical solutions and Monte Carlo simulations for ZB and ZB put pricing.
3. **Optimization Framework:** A specialized function designed to optimize the Hull-White model parameters by comparing model-generated cap prices with market prices.

## Expected Deliverables

The culmination of this project will be a comprehensive package comprising:

- **Source Code:** Clean, bug-free, and well-commented MATLAB source code embodying the project's analytical and simulation frameworks.
- **Executive Summary:** A concise yet detailed report summarizing the project's motivation, implementation strategy, results, and analysis. This report will include tables and graphs comparing model-generated volatilities with market-implied volatilities, alongside a critical discussion on model limitations and fit quality.

## Project Schedule

The project is segmented into stages, each with specific functions and due dates:

- **Stage 1:** Implementation of initial pricing and conversion functions, due by April 1.
- **Stage 2:** Development of cap pricing, analytical solutions, and Monte Carlo simulations for ZB and ZB puts, due by April 8.
- **Stage 3:** Calibration and optimization of the Hull-White model to market data, due by April 15.

Final submissions are due by April 22, at midnight.

## Collaboration and Flexibility

This project is designed as a collaborative exercise, encouraging creativity and intelligent problem-solving. Participants are urged to make justified modeling assumptions, clearly documenting their rationale to foster a robust and transparent calibration process.

## Limitations and Expectations

The executive report is restricted to 15 pages, focusing exclusively on discussions and graphical analyses. It is expected to be a professional, insightful document that refrains from including source code.

## Conclusion

By undertaking this project, we aim to not only enhance our understanding of the Hull-White model and its applications but also contribute to the broader field of fixed income derivatives analysis. This project offers a unique blend of theoretical finance and practical application, challenging participants to apply their knowledge creatively and effectively.
