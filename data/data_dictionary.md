# Data dictionary

All monetary values are in ₹ crore. Percentages are stored as decimal values in the processed CSV; for example, `0.018` represents `1.8%`.

| Field | Description |
| --- | --- |
| bank | Reporting entity used in the peer set |
| ownership | Private or public-sector bank |
| nii | Net interest income |
| non_interest_income | Income other than interest income |
| operating_income | NII plus non-interest income |
| net_profit | Profit after tax |
| assets_fy25 / assets_fy24 | Total assets at year end |
| advances_fy25 / advances_fy24 | Gross advances at year end |
| deposits_fy25 / deposits_fy24 | Customer deposits at year end |
| casa_fy25 / casa_fy24 | Current-account and savings-account deposits |
| equity_fy25 / equity_fy24 | Equity used for ROE approximation |
| investments_fy25 / investments_fy24 | Investments used in the interest-earning-asset proxy |
| gnpa / nnpa | Gross and net NPA ratios |
| pcr | Provision coverage ratio |
| operating_expense | Operating expense |
| employees | Employee count where disclosed on a comparable basis |
| cet1 / tier1 / car | Capital ratios |
| gross_npas | Gross non-performing asset balance |
| provisions | Provision expense used to approximate credit cost |

See `docs/methodology.md` for calculated KPI definitions.
