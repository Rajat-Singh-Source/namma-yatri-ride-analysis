# Namma Yatri â€” Ride Demand, Revenue & Cancellation Analysis

Analysis of ride-booking data for Namma Yatri to understand demand patterns, revenue
concentration and the cancellation funnel, and to recommend operational improvements.

**Stack:** Python Â· Pandas Â· SQL Â· Power BI Â· Tableau

---

## Problem

A ride-hailing platform loses revenue both when customers cancel and when drivers cancel.
The analysis quantifies where rides drop out of the funnel and which times and zones carry
the most demand and revenue.

## Dataset

- **5 relational tables** integrated into a unified ride/revenue dataset
- Ride-level records with timestamps, pickup/drop zones, fare, ride status and
  cancellation reasons

## Approach

1. Cleaned and joined the five tables into a single analysis-ready dataset.
2. Demand analysis by hour of day, day type and zone â€” peak windows and high-performing areas.
3. Revenue analysis â€” revenue share by time period and zone.
4. Cancellation/funnel analysis â€” completion rate split by who cancelled.
5. Dashboards built in Power BI and Tableau for operational review.

## Results

| Metric | Value |
|---|---|
| Overall ride completion rate | **45.5%** |
| Customer cancellation rate | **48.2%** |
| Driver cancellation rate | **47.3%** |

- Demand concentrates in identifiable peak hours, with strong zone-level variation.
- Cancellations are almost evenly split between customers and drivers â€” so fixing only one
  side of the marketplace would recover less than half of the lost rides.

## Recommendations

- Target driver-side cancellations with acceptance incentives and better trip-assignment
  radius in low-supply zones.
- Reduce customer cancellations with accurate ETA and upfront fare at booking.
- Focus supply in the top demand zones during peak windows.

## Files

| File | Description |
|---|---|
| `Namma_Yatri_Methodology_Report.docx` | Methodology, data preparation, analysis and findings |

---

**Author:** Rajat Singh Â· [LinkedIn](https://www.linkedin.com/in/rajatsingh-dataanalyst) Â· [Portfolio](https://github.com/Rajat-Singh-Source/data-analytics-portfolio) Â· [Profile](https://github.com/Rajat-Singh-Source)

