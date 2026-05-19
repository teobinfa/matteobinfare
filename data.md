---
layout: single
title: "Data & Code"
permalink: /data/
author_profile: true
---

# Data & Code

<div class="paper-card">
  <h3 class="paper-title">A New Lease on Firm Behavior</h3>
  <div class="paper-authors">Updated data underlying the paper</div>

  <details class="paper-details" open>
    <summary>Data Description &amp; Download</summary>

    <p>
      This page provides an updated version of the data underlying our paper
      <em>A New Lease on Firm Behavior</em>. This data is obtained by scraping each firm’s
      10-K and 10-Q accounting reports to acquire two variables disclosed under the
      Financial Accounting Standards Board’s Accounting Standards Update (ASC) 2016-02:
      Leases (Topic 842).
    </p>

    <p>Among other changes, this accounting standards update required firms to begin disclosing:</p>

    <ul>
      <li>The weighted average discount rate used to compute the present value of operating lease commitments</li>
      <li>The weighted average remaining life of the firm’s operating leases</li>
    </ul>

    <p>
      Below, we provide summary statistics associated with each of these two variables
      for all firms preparing accounting statements in accordance with these updated
      requirements, provided the firm reports a strictly positive lease liability and
      the discount rate is not missing.
    </p>

    <p>
      We also provide the data in <code>.xlsx</code> format for other interested academic researchers.
      If you use this data in your own research, please cite our paper
      <em>A New Lease on Firm Behavior</em>.
    </p>

    <p class="paper-links">
      <a href="https://drive.google.com/file/d/1eCLv2PRYfw9X5bw9Dii3zwda0A8u-Jj3/view">Data (zipped .xlsx file)</a>
    </p>
  </details>
</div>

<div class="paper-card">
  <h3 class="paper-title">Summary Statistics</h3>

  <details class="paper-details" open>
    <summary>Summary Statistics &amp; Variable Definitions</summary>

    <div class="summary-table-wrap">
      <table class="summary-table">
        <thead>
          <tr>
            <th>Variable</th>
            <th>N</th>
            <th>Mean</th>
            <th>SD</th>
            <th>p25</th>
            <th>Median</th>
            <th>p75</th>
          </tr>
        </thead>
        <tbody>
          <tr>
            <td>Weighted Average Discount Rate (%)</td>
            <td>43,169</td>
            <td>5.74</td>
            <td>2.80</td>
            <td>3.86</td>
            <td>5.10</td>
            <td>7.00</td>
          </tr>
          <tr>
            <td>Weighted Average Remaining Life (Years)</td>
            <td>43,169</td>
            <td>7.67</td>
            <td>9.09</td>
            <td>3.90</td>
            <td>6.00</td>
            <td>8.56</td>
          </tr>
        </tbody>
      </table>
    </div>

    <p>The data contains the following variables:</p>

    <ul>
      <li><code>CIK</code>: The Central Index Key of the filer</li>
      <li><code>FDATE</code>: The filing date of the statement</li>
      <li><code>RDATE</code>: The fiscal period end date associated with the statement</li>
      <li><code>OPLEASE_DR</code>: The weighted average discount rate used to value operating lease liabilities, disclosed in accordance with ASC 842</li>
      <li><code>OPLEASE_WAL</code>: The weighted average remaining life of operating leases, in accordance with ASC 842</li>
    </ul>
  </details>
</div>
