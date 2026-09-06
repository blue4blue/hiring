# Rubric — L2 Junior Product Analyst

A junior analyst answers scoped questions reliably. Assessed on **technical correctness
and analytical honesty**; interpretation is still supervised.

## Competencies and the bar

| Competency | Below level (1–2) | At level (3) | Above level (4) |
| --- | --- | --- | --- |
| **SQL & modelling** | Struggles with window functions | Window functions, dedup, grain awareness; understands the warehouse | Improves the model, not just the query; thinks about cost |
| **Metrics** | Uses whatever the dashboard says | Writes precise definitions; designs a tracking plan | Catches an instrumentation flaw before it ships |
| **Analysis** | Answers the question literally | Structures an investigation; segments; sanity-checks | Reframes the question and finds the real cause |
| **Communication** | Method first, conclusion buried | Answer first with caveats; charts fit the question | Changes a decision with a clear written case |
| **Rigour** | States conclusions with no caveat | Knows the limits of the data and says so | Refuses to answer when the data genuinely cannot |

## Must have

* Live SQL including at least one window function.
* Has defined a metric precisely and defended the definition.
* Has investigated a metric anomaly end to end.
* Says "I don't know" when appropriate.

## Nice to have

* dbt or equivalent.
* Python for analysis.
* Experience with an experimentation platform.

## Red flags

* Every answer is a dashboard screenshot.
* Cannot explain what their own query does line by line.
* Treats a p-value as a decision rule with no context.
* Has never found a data quality problem — which means they have never looked.

## First 90 days if hired

Own the metric definitions for one area, build or fix one core dashboard, and deliver
two written analyses that change something.
