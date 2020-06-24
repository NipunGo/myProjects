Port_analysis_kit.py - This file contains basic functions to do analysis and optimization of the portfolio.
					   Following are the analysis tools present in the file-
                       - skewness, kurtosis, sharpe ratio, drawdown, semideviation, Conditional value at risk, Gaussian value at risk.
                       Foolowing are the computational tools present in the file-
                       - weights of the stocks that can minimize volatility
                       - weights of the stocks that maximizes sharpe ratio
                       - Global minimum variance portfolio
                       Following are the drawing tools present in the file-
                       - to plot the efficient frontier.
                       Following are the prediction tools present in the file-
                       - Evolution of Geometric Brownian Motion trajectories, such as for Stock Prices through Monte Carlo
                       - The evolution of interest rates by Cox–Ingersoll–Ross (CIR) model.
                       - The current and future prices along with the return of the given bond
                       - To find out the Macauly duration of the given security
                       Following are the optimization tools present in the file-
                       - To run the constant proportion portfoio insurance(CPPI) strategy to optimize the given portfolio.
                       - To hedge the given portfoio with the risk free asset (bonds) by using several types of allocator.
                                - fixed ratio mixing allocation
                                - Glidepath allocation (Allocates weights to r1 starting at start_glide and ends at end_glide
                                                        by gradually moving from start_glide to end_glide over time)
                                - floor allocation (Allocate between PSP and GHP with the goal to provide exposure to the upside
                                                    of the PSP without going violating the floor. Uses a CPPI-style dynamic risk budgeting algorithm by investing a multiple
                                                    of the cushion in the PSP)
                                                    (PSP: Profit Seeking Portfolio, GHP: Goal hedging portfolio)
                                - drawdown allocation.
                          
                       
                       
