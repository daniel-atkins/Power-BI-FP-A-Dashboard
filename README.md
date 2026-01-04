# Power BI FP&A Dashboard — Actuals vs Forecast Performance

## Overview
This project is an FP&A-focused Power BI dashboard designed to compare **actual performance vs forecast** with a clear emphasis on **EBITDA tracking and variance analysis**. The dashboard is structured to support executive-level review while retaining drill-down capability for monthly analysis.

<img width="1186" height="705" alt="image" src="https://github.com/user-attachments/assets/bc57586e-7de1-4016-b6ff-7baba76aca31" />

## Key Features
- KPI cards summarizing:
  - EBITDA (Actual)
  - EBITDA (Forecast)
  - EBITDA Variance ($)
  - EBITDA Variance (%)
- Monthly Actuals vs Forecast comparison table with automatic rollups
- Line chart visualizing monthly EBITDA trends (Actual vs Forecast)
- Interactive month slicer for focused analysis
- Consistent variance formatting (parentheses and color treatment for negatives)

## Metrics Included
- Total Actuals
- Total Forecast
- Variance ($ and %)
- EBITDA (Actual)
- EBITDA (Forecast)
- EBITDA Variance ($ and %)

## Design Principles
- Clear information hierarchy (KPIs → table → trend)
- Executive-friendly formatting and labeling
- Minimal visual noise to emphasize trends and variances
- Consistent metric definitions across visuals

## Tools & Technologies
- Power BI Desktop
- DAX (for variance and percentage calculations)
- Star-schema data model (Fact Actuals, Fact Forecast, Date dimension)

## Use Case
This dashboard mirrors a typical **FP&A monthly performance review** and is suitable for:
- Management reporting
- Forecast accuracy analysis
- Variance explanation discussions
- Interview and portfolio demonstration of FP&A and Power BI skills

## Future Enhancements (Optional)
- YTD and FY views
- Prior-year comparison
- Waterfall variance bridge
- Department or business-unit drilldowns
