# Commercial Auto Ratemaking Project
Reviewing 2014-2018 Experience to Determine the Required 2027 Rate Structure

### Summary
Based on the CAS Loss Ratio framework, the commercial auto portfolio requires a Final Indicated 2027 Rate 
Change of +438.36%. An indication of this magnitude reveals that the company's current rate structure is 
severely deficient. To maintain structural solvency and cover prospective 2027 claim obligations, premium rates 
would theoretically need to be increased to more than 5 times their current levels.

### Core Strategic Drivers
1. The overriding driver behind this pricing deficiency is the **9-to-13-year chronological gap** separating the historical experience period (2014-2018) from the target pricing year (2027).
* Timeline Projection: Actuaries must project ultimate claim costs forward to the prospective average future accident date of **January 1, 2028**.
* Compounding Impact: Compounding an industry-standard annual loss trend rate of **5.0%** over this timeline creates massive exponential leverage:
  * 2014 Losses are amplified by a 1.886 multiplier (an 88.6% inflationary increase).
  * 2018 Losses are amplified by a 1.551 multiplier (a 55.1% inflationary loading).
* When historical claim liabilities expand exponentially due to compounding inflation while the  historical premium revenue baseline remains relatively flat, the projected loss ratios expand dramatically.
2. Severe Projected Loss & LAE Ratio (420.69%)
The model calculates a Weighted Multi-Year Projected Loss & LAE Ratio of 420.69%. This indicates that for every $1 of baseline premium the company earns at current rate tiers, it is projected to pay out $4.21, purely in claims and internal claim-adjusting operations in the year 2027.

3. Operational Expense & Profit Loadings
The underwriting structure incorporates the following operational parameters:
* **Fixed Administrative Costs:** 10%(IT systems, overhead, rent)
* **Variable Expense Ratio:** 15% (Agent commissions, state premium taxes, licensing)
* **ULAE Loading Factor:** 1.05 (5% add-on to fund the internal claims department overhead)

### Structural Methodology: The 5-Phase Actuarial Sequence
The data flows sequentially through five distinct modules to establish the final indication:  
**Phase A: Loss Development** - Raw paid losses are adjusted upward using industry benchmark Loss Development Factors (LDFs) to account for open claims and long-tail settlement realities.   
**Phase B: Premium On-Leveling** - Historical premiums are brought up to current price tiers under a market-hardening scenario (+4% in 2015 and +6% in 2017) to create a fair revenue baseline.  
**Phase C: Loss & Premium Trending** - Bridges the chronological gap by compounding a 5% annual loss trend forward to the target 2027 year, while holding premium trend flat.  
**Phase D: Expenses, Profit, and ULAE** - Integrates operational fixed/variable overhead and profit margin provisions into the structural framework.  
**Phase E: Indication Calculation** - Feeds the finalized projections into the classic CAS Loss Ratio Method formula to yield the final required rate movement percentage.  

### Actuarial Realities
While a +438.36% rate increase is mathematically justified by the static flatfile data sample, executing a 400%+ rate hike all at once in a competitive insurance market is practically impossible. It would trigger a complete collapse in policyholder retention.

### Tech Stack & Environment
* **Language:** Python
* **Libraries:** pandas (data processing), numpy (vector math), matplotlib (visual trend analystics)
* **IDE: Visual Studio Code / Jupyter Notebooks
