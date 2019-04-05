## VaRCalculator

# Tips
1. To change which stocks are considered, change them in the csv file in the resources folder.

2. To change the period being considered, change the variables startDate and/or endDate in the VaRCalculator.py file under the portfolio_VaR function.

3. For just the calculations without the plots, go to the VaRCalculator.py file and find the portfolio_VaR function. This function calls another function called single_stock_VaR. Change the vizData attribute to False to turn off plots and reduce run time.

4. To see more information on runtime and function calls, find the main function call and change the 0 in p.strip_dirs().sort_stats('time', 'ncalls').print_stats(0).
