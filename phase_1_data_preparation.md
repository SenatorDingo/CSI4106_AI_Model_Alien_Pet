# Phase 1: Data Preparation

## Objective
Prepare the Alien Pet Health dataset for downstream modeling by improving data quality and consistency.

## What Was Done

- Loaded the dataset and validated shape, schema, and sample records
- Investigated missing-value patterns, including token-based missing markers
- Standardized missing representations to `NaN`
- Coerced numeric-like attributes into numeric dtypes where appropriate
- Reviewed categorical values and normalization needs
- Assessed class balance and feature distributions
- Exported a cleaned dataset variant for later phases

## Why It Matters
This phase reduces data-quality risk before model training and ensures later results are driven by signal rather than formatting or missing-data artifacts.
