# Bashment Product Decisions

This document captures key product decisions and the reasoning behind them.

## 1. Beta Before Advanced Intelligence

### Decision

Prioritize beta user and event data collection before investing heavily in advanced machine learning.

### Rationale

The quality of future intelligence depends on the quality and volume of real-world data available.

Starting with real users allows Bashment to:

- Validate product assumptions
- Identify meaningful signals
- Understand user behavior
- Establish baseline measurements
- Collect completed-event outcomes

---

## 2. Transparent Forecasting

### Decision

Use transparent statistical and baseline approaches as the starting point for attendance forecasting.

### Rationale

Users should understand why a forecast was generated.

A transparent baseline also provides a measurable benchmark against which future predictive approaches can be evaluated.

---

## 3. Explainability Over Black-Box Outputs

### Decision

Forecasts and intelligence signals should provide understandable explanations.

### Rationale

A useful intelligence product should help users make decisions, not simply provide unexplained scores.

The product should progressively communicate:

- What influenced the result
- How strong the available signals are
- How confident the system is
- What additional data could improve the result

---

## 4. Forecast vs. Actual Measurement

### Decision

Measure forecasts against completed-event outcomes.

### Rationale

Forecasting performance cannot be evaluated without comparing predictions to actual results.

This creates a continuous feedback loop:

**FORECAST → ACTUAL → COMPARE → LEARN → IMPROVE**

---

## 5. Data Before Complexity

### Decision

Prioritize useful data collection and measurable product outcomes before introducing unnecessary technical complexity.

### Rationale

The MVP should establish a strong foundation while avoiding premature optimization.

As the dataset grows, technical and intelligence capabilities can evolve based on evidence.

---

## 6. Separate Public and Beta Environments

### Decision

Maintain separate public and beta environments.

### Rationale

The public website and beta product serve different purposes.

**Public:** External-facing product and company presence.

**Beta:** Early-user testing, product validation, feedback, and data collection.

This separation allows the product to evolve through controlled beta testing while maintaining a distinct public-facing experience.

---

## 7. Build → Test → Measure → Learn

### Decision

Use an iterative product development cycle.

### Rationale

Bashment is being developed as a real-world product where user behavior and measured outcomes should continuously inform product decisions.

**BUILD → TEST → MEASURE → LEARN → IMPROVE**
