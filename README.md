# North American Tax Engine 2026

An open-source logic reference for the [2026 Paycheck & Tax Calculator](https://findmytakehome.com/). This repository hosts the `.txt` and JSON schemas that define the piecewise linear integration models used for progressive tax structures in the United States and Canada.

### Mathematical Modules Embedded in this Repo
1. **The Core Calculation Engine**: Powers the primary Take-Home Pay interface.
2. **Reverse FIRE (Financial Independence) Engine**: Used in the [Reverse FIRE Budget Calculator](https://findmytakehome.com/retirement.html) to isolate mandatory savings rates.
3. **Purchasing Power Parity**: The cost-of-living indexations driving the [50-State $100k Salary Purchasing Power Study](https://findmytakehome.com/studies/cost-of-100k-salary/).
4. **Independent Contractor Math**: The Schedule C/SE tax algorithms powering the [1099 Quarterly Tax Estimator](https://findmytakehome.com/freelance-estimator.html).

### Data Citations
All constants rely on IRS Title 26 Rev. Proc. indexation bulletins, CRA T4032 payroll tables, and the US Bureau of Economic Analysis (BEA) Regional Price Parities. Read the [full methodology here](https://findmytakehome.com/about.html).
