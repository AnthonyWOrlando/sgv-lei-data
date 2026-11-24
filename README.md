# San Gabriel Valley Leading Economic Index: Data

Published by the Tarkington Business Futures Institute, Cal Poly Pomona. Developed by Anthony W. Orlando and Gerd Welke.

## Files

- `lei.csv`: monthly index, from March 2002.
  - `index_monthly`: the monthly reading.
  - `index_3mo_avg`: the 3-month trailing average (the headline number).
- `lei.json`: the same series in a compact format for the website chart, with `updated` and `data_through` fields.
- `archive/`: each published version, named by the last month of data and the publication date.

## Reading the Index

- 0 = the inputs at their averages outside March 2020–June 2021.
- Above 0: leading indicators stronger than usual. Below 0: weaker than usual.

## Inputs

- ISM Manufacturing New Orders index (national).
- California initial unemployment insurance claims (state; FRED: CAICLAIMS).
- Housing units authorized by building permits in 31 San Gabriel Valley cities (local; U.S. Census Bureau Building Permits Survey; HUD SOCDS for 2001–2007).

Full methodology: [Tarkington Institute website](https://www.tarkingtoninstitute.org).

## Citation

Orlando, A. W., & Welke, G. San Gabriel Valley Leading Economic Index [Data set]. Tarkington Business Futures Institute, Cal Poly Pomona.
