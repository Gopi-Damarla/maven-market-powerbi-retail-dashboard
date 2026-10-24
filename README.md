# Maven Market Retail Performance Dashboard \| Power BI

## Project Overview

**Maven Market Retail Performance Dashboard** is a Power BI dashboard
that brings retail performance metrics into one executive view,
including transactions, profit, returns, product-brand performance,
geographic distribution, weekly revenue, and revenue-target progress.

> **Data note:** The figures below are read from the supplied dashboard
> screenshot. The screenshot does not establish the data source, full
> reporting period, or metric definitions. Values should be treated as
> displayed dashboard figures, not independently audited results.

## Dashboard at a Glance

  KPI                                   Displayed value
  ----------------------------------- -----------------
  Current Month Transactions                     18,325
  Current Month Profit                         \$71,682
  Current Month Returns                             496
  Total Revenue                                  \$120K
  Revenue Target                                 \$240K
  Revenue Target Progress                           50%
  Reference value shown above gauge              \$119K

The visible brand table shows **Hermanos** with approximately **6,072
transactions**, **\$23,167 total profit**, **58.1% profit margin**, and
**1.1% return rate**. These are approximate readings from the
screenshot.

## Business Objective

Retail stakeholders need to understand whether performance is on track,
which brands contribute to results, where sales are distributed, and how
revenue changes over time. This dashboard supports those questions
through a set of connected views.

-   **Performance:** What are the current-month transaction, profit, and
    return levels?
-   **Target tracking:** How does revenue compare with the target?
-   **Brand performance:** How do brands compare on transactions,
    profit, margin, and returns?
-   **Geographic mix:** How is sales activity distributed across
    locations?
-   **Time trends:** How does weekly revenue change over the displayed
    period?

## Dashboard Components

### 1. Executive KPI Cards

The cards show **18,325 current-month transactions**, **\$71,682
current-month profit**, and **496 current-month returns**.

**Business value:** These headline metrics give stakeholders a quick
view of activity, profitability, and returns before they explore the
detailed visuals.

### 2. Product Brand Performance

The table compares brands using total transactions, total profit, profit
margin, and return rate. In the visible table, **Hermanos** stands out
on transactions and profit.

**Business value:** Comparing volume with profitability and return rate
helps avoid evaluating brands on sales volume alone. It can help
identify strong performers and brands that may need further
investigation.

### 3. Sales by Location

The map visualizes sales activity geographically, with points visible
across parts of North and South America.

**Business value:** Geographic views can help stakeholders explore
market concentration and decide where deeper regional analysis may be
useful. Exact location rankings cannot be reliably inferred from the
screenshot alone.

### 4. Country Distribution

The treemap shows the USA as the largest displayed segment, followed by
Mexico, with Canada and Others also represented.

**Business value:** This view communicates the relative geographic mix
and can support follow-up questions about regional focus and market
development.

### 5. Weekly Revenue Trend

The weekly revenue chart shows fluctuations across the displayed period,
with higher bars in some later weeks.

**Business value:** Trend analysis helps teams investigate stronger and
weaker periods. To determine why revenue changed, the chart should be
compared with promotions, seasonality, inventory availability, or other
supporting data.

### 6. Total Revenue vs. Revenue Target

The gauge displays **\$120K total revenue** against a **\$240K target**.
Based on those displayed figures, revenue has reached **50% of the
target**. The visual also shows a reference value of approximately
\$119K above the gauge.

**Business value:** Target tracking makes the performance gap visible
and provides a basis for reviewing progress and potential actions.

## Business Story: From KPIs to Decisions

### Start with the performance pulse

The current-month cards report 18,325 transactions, \$71,682 in profit,
and 496 returns. Together, they provide a compact view of activity,
profitability, and returns.

### Understand what contributes to performance

Brand-level comparisons add context behind the headline figures.
Hermanos is a standout in the visible table for transactions and profit,
while margin and return rate offer additional dimensions for evaluating
performance.

### Explore where sales are distributed

The map and treemap add a geographic perspective. The USA is the largest
displayed country segment, with Mexico, Canada, and Others also
represented.

### Track the revenue gap

The gauge shows \$120K against a \$240K target---half of the displayed
target. This prompts a practical management question: what actions or
opportunities could help close the remaining gap?

### Investigate trends rather than stopping at totals

Weekly revenue changes offer a starting point for investigating high-
and low-performing periods. Combining this view with brand, geography,
promotion, and inventory data could help explain what is driving those
changes.

**The story:** Monitor KPIs → understand brand contribution → explore
geographic mix → track target progress → investigate revenue trends →
identify next actions.

## Potential Business Actions

Based on the dashboard views, a retail team could:

-   Review the revenue gap against the \$240K target and monitor
    progress regularly.
-   Investigate the drivers behind Hermanos' displayed transaction and
    profit performance.
-   Compare profit margins and return rates across brands to identify
    candidates for quality or merchandising review.
-   Explore geographic sales patterns to assess opportunities for
    localized marketing or market development.
-   Investigate weekly revenue peaks and dips alongside promotions,
    stock availability, and seasonality.
-   Monitor transactions, profit, and returns together so growth is
    evaluated alongside profitability and customer outcomes.

These are **recommended follow-up analyses**, not proven causal findings
from the screenshot alone.

## Tools & Skills

**Primary tool:** Microsoft Power BI

The dashboard demonstrates:

-   KPI cards and executive reporting
-   Brand performance comparison
-   Geographic mapping
-   Treemap visualization
-   Weekly trend analysis
-   Revenue target gauge
-   Profit margin and return-rate monitoring
-   Dashboard layout and visual storytelling

Add DAX, Power Query, data modeling, or source-system details only if
you used them in the project.

## Key Takeaways

-   The dashboard displays **18,325 current-month transactions**,
    **\$71,682 current-month profit**, and **496 current-month
    returns**.
-   Displayed revenue is **\$120K against a \$240K target**, or **50% of
    target**.
-   Hermanos stands out in the visible brand table for transactions and
    profit.
-   The USA is the largest displayed country segment in the treemap.
-   Weekly revenue fluctuates over the displayed period and offers a
    starting point for deeper trend investigation.

## Future Enhancements

-   Add month-over-month and year-over-year KPI comparisons.
-   Show revenue and profit variance against targets.
-   Add drill-through pages for brand and country performance.
-   Include return-rate trends and return reasons, if available.
-   Add profit contribution by brand and geography.
-   Document KPI definitions, data sources, and refresh frequency.
-   Add filters for date, brand, product, and country, if supported by
    the model.

## Suggested Repository Structure

``` text
maven-market-powerbi-retail-dashboard/
├── README.md
├── images/
│   └── maven-market-dashboard.png
└── report/
    └── maven-market-dashboard.pbix
```

Include the `.pbix` file only if you are permitted to share it. Save the
dashboard screenshot in `images/` and update the path if you use another
filename.


**Project type:** Retail Analytics & Business Intelligence\
**Role:** Data Analyst / Power BI Developer 
**Primary tool:** Microsoft Power BI\
**Focus:** KPI Reporting \| Sales Performance \| Profitability \|
Returns Analysis \| Geographic Analysis \| Revenue Target Tracking
