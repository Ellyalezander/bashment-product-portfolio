# Bashment Forecasting Approach

## Objective

Bashment's forecasting capability is designed to provide transparent attendance estimates that can improve as more real-world event data becomes available.

The initial approach prioritizes explainability, measurable baselines, and continuous validation.

---

## Initial Forecasting Strategy

The MVP should begin with transparent statistical and baseline forecasting methods rather than relying on opaque machine learning models.

Potential inputs may include:

- Historical event performance
- Event characteristics
- Location
- Timing
- Current event activity
- Engagement signals
- Available historical attendance data

The specific signals and their relative importance should be validated through beta data.

---

## Why Start With Baselines?

A baseline approach provides a measurable starting point.

It allows Bashment to:

- Establish initial forecast performance
- Understand which signals are useful
- Explain forecast results
- Identify data gaps
- Compare future approaches against a known benchmark

---

## Forecast Explanation

Each forecast should provide a transparent explanation of the factors contributing to the estimate.

Rather than presenting:

> "Expected attendance: 500"

Bashment should progressively be able to communicate:

- What factors influenced the forecast
- Which signals increased or decreased the estimate
- How confident the system is
- What historical or current data supports the estimate

---

## Confidence

Forecasts should include an appropriate confidence indicator based on the quality and availability of supporting data.

Confidence should reflect factors such as:

- Amount of historical data
- Data completeness
- Similarity to previously observed events
- Strength of available signals
- Reliability of the underlying inputs

Confidence should not be presented as certainty.

---

## Forecast vs. Actual

Completed events create an opportunity to measure forecast performance.

The feedback loop is:

**FORECAST → EVENT → ACTUAL ATTENDANCE → COMPARE → LEARN**

Forecasts should be stored alongside actual outcomes where appropriate so that performance can be evaluated over time.

---

## Measuring Performance

As sufficient data becomes available, Bashment can evaluate:

- Forecast accuracy
- Forecast error
- Signal usefulness
- Confidence reliability
- Performance across event types
- Performance across locations
- Performance across different event characteristics

---

## Evolution Toward Machine Learning

As Bashment accumulates sufficient completed-event data, the forecasting approach can evolve toward more advanced machine learning methods.

Any future model should be evaluated against the initial baseline.

The objective is not to introduce machine learning simply because it is available.

The objective is to determine whether a more advanced approach produces:

- Better predictions
- Better calibration
- More useful signals
- Consistent performance
- Sufficient explainability

---

## Product Principle

Bashment's forecasting system should prioritize:

**TRANSPARENT → MEASURABLE → EXPLAINABLE → IMPROVABLE**

The forecasting capability should become more intelligent as the underlying dataset and measured outcomes grow.
