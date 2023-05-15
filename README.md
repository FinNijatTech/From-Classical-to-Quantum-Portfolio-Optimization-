# Portfolio Optimization: Classical Computing with MPT (Modern Potfolio Theory) versus Quantum Computing with VQE (Variational Quantum Eigensolver)

In this project, my goal is to compare portfolio optimization using classical computing and quantum computing methodologies.

In the classical computing approach, I will utilize Modern Portfolio Theory (MPT) in conjunction with the Sharpe ratio. The user will input the names of the companies they want in their portfolio. By employing Monte Carlo simulation, I will identify the portfolio with the maximum Sharpe ratio and the one with the minimum volatility. In the final step of the classical computing part, O will calculate the optimal portfolio based on the user's risk aversion. If the user has a low risk aversion, they will specify a higher volatility, while a user with high risk aversion will indicate a preference for lower volatility. Using this volatility information provided by the user, I will determine the optimal portfolio.

For the quantum computing part, I will leverage IBM Quantum Access to access quantum computers. Since there will be a limited number of qubits available, I will employ the Variational Quantum Eigensolver (VQE) algorithm. I will not use the Quantum Approximate Optimization Algorithm (QAOA) due to the constrained number of qubits. VQE requires fewer qubits compared to QAOA, making it a suitable choice for our purposes.

By comparing the results obtained from classical computing and quantum computing approaches, I aim to assess the potential benefits and limitations of quantum computing in portfolio optimization tasks.
