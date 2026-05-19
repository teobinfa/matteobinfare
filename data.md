---
layout: single
title: "Data & Code"
permalink: /data/
author_profile: true
---

# A New Lease on Firm Behavior

This page provides an updated version of the data underlying our paper *A New Lease on Firm Behavior*. This data is obtained by scraping each firm’s 10-K and 10-Q accounting reports to acquire two variables disclosed under the Financial Accounting Standards Board’s recently implemented Accounting Standards Update (ASC) 2016-02: Leases (Topic 842). Among other changes, this accounting standards update required firms to begin disclosing:

- The weighted average discount rate used to compute the present value of operating lease commitments
- The weighted average remaining life of the firm’s operating leases

Below, we provide summary statistics for each of these two variables for all firms preparing accounting statements in accordance with these updated requirements, provided that the firm reports a strictly positive lease liability and the discount rate is not missing.

We also provide the data in `.xlsx` format for other interested academic researchers. If you use this data in your own research, please cite our paper *A New Lease on Firm Behavior*. See the BibTeX reference for our paper here.

## Data

[Data: Updated data underlying *A New Lease on Firm Behavior*](https://drive.google.com/file/d/1eCLv2PRYfw9X5bw9Dii3zwda0A8u-Jj3/view)

The data contains the following variables:

- `CIK`: The Central Index Key of the filer
- `FDATE`: The filing date of the statement
- `RDATE`: The fiscal period end date associated with the statement
- `OPLEASE_DR`: The weighted average discount rate used to value operating lease liabilities, disclosed in accordance with ASC 842
- `OPLEASE_WAL`: The weighted average remaining life of operating leases, in accordance with ASC 842

## Summary Statistics
