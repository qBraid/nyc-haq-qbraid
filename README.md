# qBraid Challenge: Quantum Portfolio Optimization

## Why Think About Finance?

In light of recent financial events, like the **Fed rate cuts of 50 basis points**, the impact on **finance** is more apparent than ever. This affects our daily lives, from mortgage rates to investment portfolios. Some of the most successful **Super Investors** have built fortunes by owning just a few carefully selected stocks while managing billions of dollars. 

### Notable Super Investors:
- **Bill Ackman**: Pershing Square Capital Management [Portfolio](https://whalewisdom.com/filer/pershing-square-capital-management-l-p)
- **Dev Kantesaria**: Valley Forge Capital Management [Portfolio](https://whalewisdom.com/filer/valley-forge-advisors-llc)
- **Chris Hohn**: TCI Fund Management [Portfolio](https://whalewisdom.com/filer/childrens-investment-fund-management-uk-llp)

### Key Insights:
- **Selective Portfolios**: Super investors often hold only a few stocks in their portfolios. This goes against the traditional idea of needing many diversified holdings to minimize risk.
- **Concentration**: By focusing on just a few companies, these investors are betting on their deep research and understanding of the underlying business fundamentals.
- **Active Management**: Most of these investors take an active role in managing their portfolios, continuously adjusting based on the financial and macroeconomic environment.

## Challenges of Managing a Select Few Stocks
1. **Volatility Risk**:
   - Fewer stocks mean **higher exposure** to each stock's price movement.
   - The **volatility** of a single stock can significantly impact the overall portfolio.
   
2. **Stock-Specific Risk**:
   - Poor performance by one stock could lead to large losses, as diversification is limited.
   - **Business fundamentals** must be thoroughly understood to mitigate this risk.

3. **Market Timing**:
   - These investors often look for **undervalued stocks** or special situations that they believe will yield outsized returns.
   - **Timing the market** effectively is crucial, as concentrated portfolios can underperform during certain periods.

## Factors to Consider When Managing a Concentrated Portfolio
1. **Economic Conditions**:
   - Understand how **Fed interest rates**, inflation, and broader economic factors impact the industries of the selected companies.
   
2. **Business Fundamentals**:
   - Focus on **profitability, revenue growth, management quality**, and **industry position** of the companies.
   - Look at **long-term trends** rather than short-term market movements.

3. **Competitive Moats**:
   - Companies with **strong competitive advantages** (moats) are more likely to succeed in the long term.
   - Consider factors like **brand strength, intellectual property, network effects**, and **customer loyalty**.

4. **Valuation Metrics**:
   - Use metrics like **Price-to-Earnings (P/E)** ratio, **Price-to-Book (P/B)** ratio, **Free Cash Flow**, and **Return on Equity (ROE)** to ensure you're not overpaying for a stock.

5. **Macroeconomic Trends**:
   - Stay informed about **macroeconomic shifts** such as Fed rate changes, which affect credit markets, consumer spending, and corporate earnings.

## Challenge Requirements

In today's rapidly evolving financial landscape, the ability to optimize investment portfolios efficiently and effectively is more crucial than ever. As classical computing approaches the limits of Moore's Law, quantum computing emerges as a revolutionary technology with the potential to transform the field of financial optimization.

This hackathon challenges you to dive into the exciting intersection of quantum computing and financial technology. You'll explore how quantum algorithms can be applied to solve complex portfolio optimization problems, potentially outperforming classical methods in both speed and accuracy.

Over the course of three increasingly complex tiers, you'll implement portfolio optimization algorithms using different quantum computing paradigms, from quantum annealing to gate-based models. You'll then demonstrate the practical advantages of these quantum approaches by applying them to real-world portfolio data.

This challenge is not just about coding; it's about pushing the boundaries of what's possible in financial optimization. You'll be at the forefront of a technological revolution, working with cutting-edge quantum technologies that have the potential to reshape the financial industry.

Whether you're a quantum computing enthusiast, a fintech innovator, or simply curious about the future of technology in finance, this challenge offers a unique opportunity to develop skills that are highly sought after in both the quantum and financial sectors.

Are you ready to take a quantum leap into the future of portfolio optimization? Let's begin this exciting journey into the quantum realm of finance!



You will be evaluated based on how far you reach in the provided tiers. If you have any questions about the tiers, please ask us. You will have the option to run all of your code on quantum simulators before you do a final run on actual hardware via qBraid!

### Tier 1: Quantum Annealer-based Portfolio Optimization

Implement a portfolio optimization algorithm using a quantum annealer. Your task is to:

1. Formulate the portfolio optimization problem as a Quadratic Unconstrained Binary Optimization (QUBO) problem.
2. Implement the algorithm using a quantum annealing framework like D-Wave's Ocean SDK.
3. Demonstrate the algorithm's ability to optimize a small portfolio (e.g., 10-20 assets).

For guidance, refer to the paper "Quantum Annealer-based Portfolio Optimization" by Mphasis[3]. This paper introduces quantum annealing approaches for portfolio optimization and demonstrates their effectiveness on stock data from various indices.

*You do not need to use actual hardware for this step.*

### Tier 2: Gate-based Quantum Portfolio Optimization

Develop a portfolio optimization algorithm using a gate-based quantum computing model. Your objectives are to:

1. Implement the Variational Quantum Eigensolver (VQE) algorithm for portfolio optimization.
2. Use a quantum circuit simulator or a real quantum device through a cloud service.
3. Optimize a medium-sized portfolio (e.g., 20-50 assets).

Refer to the paper "Best practices for portfolio optimization by quantum computing" published in Nature[2]. This study provides insights into using VQE for portfolio optimization, including guidance on selecting appropriate hyperparameters and quantum circuits.

*You are encouraged to use actual hardware for this step.*

### Tier 3: Performance Evaluation and Computational Cost Reduction

Demonstrate the effectiveness of your quantum algorithms by:

1. Running both the annealer-based and gate-based algorithms on sample portfolios of increasing sizes.
2. Comparing the performance and computational costs against classical optimization methods.
3. Analyzing and visualizing the results to show any reduction in computational cost or improvement in solution quality.

For this tier, you can draw insights from the paper "Exploring the synergistic potential of quantum annealing and gate model computing for portfolio optimization" by Jain et al.[4]. This study presents a hybrid approach combining quantum annealing and gate-based methods for large-scale portfolio optimization problems.

Bonus points will be awarded for:
- Implementing error mitigation techniques
- Exploring hybrid classical-quantum approaches
- Demonstrating scalability to larger portfolios (100+ assets) or 100+ factors in fewer assets

Good luck to all participants!

## Working on qBraid

[<img src="https://qbraid-static.s3.amazonaws.com/logos/Launch_on_qBraid_white.png" width="150">](https://account.qbraid.com?gitHubUrl=https://github.com/qbraid/nyc-haq-qbraid.git)



## References

For more detailed information, please refer to the following sources:

1. [Quantum Computing for Optimizing Investment Portfolios - MathWorks](https://blogs.mathworks.com/finance/2023/07/24/quantum-computing-for-optimizing-investment-portfolios/)
2. [Best practices for portfolio optimization by quantum computing - Nature](https://www.nature.com/articles/s41598-023-45392-w)
3. [Quantum Annealer Based Portfolio Optimization - Mphasis](https://www.mphasis.com/content/dam/mphasis-com/global/en/home/innovation/next-lab/mphasis-quantum-annealer-based-portfolio-optimization-whitepaper.pdf)
4. [Quantum Algorithms for Portfolio Optimization - arXiv](https://arxiv.org/abs/2305.01480v1)
5. [Assessment of Quantum Algorithm for Portfolio Optimization - AWS](https://aws.amazon.com/blogs/quantum-computing/a-detailed-end-to-end-assessment-of-a-quantum-algorithm-for-portfolio-optimization-released-by-goldman-sachs-and-aws/)
6. [Quantum Algorithm for Financial Services - The Quantum Insider](https://thequantuminsider.com/2022/10/07/quantum-algorithm-developed-for-financial-services-sector-successfully-builds-high-return-low-risk-portfolios/)
