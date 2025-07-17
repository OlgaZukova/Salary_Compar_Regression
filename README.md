Linear regression fits a straight line across the data. It does not capture the curve or any nonlinear relationship between position level and salary. Result: It overestimates the salary at level 6.5, giving ~330k.

Polynomial regression (with degree 4, as used in the code) fits a curve that better matches the actual distribution. It adapts to local patterns in the data. Result: The salary prediction (~158k) aligns more closely with what you'd expect in the mid-level positions (if the actual trend isn’t linear).

The linear line missing most of the data points. The polynomial curve fitting smoothly across the real salaries — especially matching lower and higher levels better.

Polynomial Regression is the better technique in this scenario, as it models the non-linear relationship between position level and salary more accurately.
