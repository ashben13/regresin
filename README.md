# regresin

This repository contains utilities for simple regression analysis.

## CLSI EP25 Regression Example

The script `ep25_regression.py` reads measurement data from a CSV file and
produces a regression plot similar to those described in the CLSI EP25 guideline.

```
python ep25_regression.py data.csv output.png
```

The input CSV file must include two columns named `time` and `response`.
The generated PNG file will contain the scatter plot with the fitted regression
line and the coefficient of determination.
