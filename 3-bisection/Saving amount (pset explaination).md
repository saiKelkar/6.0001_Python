1. either 0% (nothing saved) of the salary can be saved or 100% (everything saved)
2. to find is the best % saved to reach the down payment amount in 36 months
3. $100 is the margin of error, i.e., it is hard to find the best % to reach the exact down payment amount, so we keep a margin of error. 
   If x is the down payment, our calculation should reach x + 100 or x - 100. if it is above or below these values, we adjust the high and low accordingly. 
4. we use high and low as 10000 and 0 respectively, cause we need to find the % till 2 decimal places. since it's tough to find in floating point, we do it in integer instead, and hence 100 x 100 and later divide by 10000 to convert to the decimal places. 