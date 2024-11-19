# Portfolio Optimization: Tracking the NASDAQ-100
This was a collaborative project done in the Optimization I class at UT Austin.

## Project Overview

This project focuses on constructing an optimized index fund to closely track the NASDAQ-100 by selecting an ideal subset of stocks and assigning optimal weights to minimize tracking error. Utilizing integer programming for stock selection and linear programming for weight optimization, the goal is to create a portfolio that mirrors the index's performance. Historical return data from 2023 and 2024 were analyzed to assess both in-sample and out-of-sample tracking accuracy, leading to the recommendation of an 80-stock portfolio for optimal balance between precision and manageability.

## Contributions

- Developed integer and linear programming models using **Gurobi** and **Python** to select a specified number of stocks and calculate their weights, aiming to minimize divergence between the NASDAQ-100 and the index returns.

## Important Findings

1. **Optimal Portfolio Size of 80 Stocks**: Analysis determined that a portfolio of 80 stocks offers the best balance between minimizing tracking error and maintaining manageability. Beyond this size, the reduction in tracking error showed diminishing returns.
2. **Effective Stock Selection Using Integer Programming**: Used a similarity matrix derived from historical return correlations to ensure the portfolio captures the essential movements of the index.
3. **Minimized Tracking Error Through Weight Optimization**: Assigned optimal weights to stocks using linear programming, ensuring close alignment with the index over time.
4. **In-Sample and Out-of-Sample Validation**: Demonstrated model robustness using data from 2023 (in-sample) and 2024 (out-of-sample).
5. **Recommendation for Regular Rebalancing**: Suggested periodic rebalancing to maintain optimal tracking, especially during market volatility.

## Technologies Used

- **Programming Languages**: Python
- **Optimization Tools**: Gurobi
- **Data Analysis Libraries**: pandas, NumPy
- **Data Sources**: Historical NASDAQ-100 return data

## How to Run the Project

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/yourusername/nasdaq100-portfolio-optimization
   ```
2. Install Dependencies:
  ```bash
  pip install -r requirements.txt
  ```
3. Data Preparation:
  Use the provided scripts to preprocess historical return data for the NASDAQ-100.

4. Run the Optimization Models:
  Execute the Python scripts to perform integer and linear programming for stock selection and weight optimization.

5. Analyze Results:
  Check the output reports for tracking error metrics and model performance.

6. Future Applications
* Extended Asset Classes: Apply the optimization framework to other index funds or asset classes, such as S&P 500 or   emerging markets.
* Dynamic Rebalancing Strategies: Research the impact of more frequent rebalancing and its effect on tracking performance.
* Integration with Real-Time Data: Incorporate real-time market data to make the model adaptive to changing market conditions.

## Contact
For questions or further information, please contact:
* Email: gayathreegopi@utexas.edu
* LinkedIn: linkedin.com/in/gayathreegopi

## Acknowledgments
Special thanks to my project collaborators and mentors for their invaluable guidance.

