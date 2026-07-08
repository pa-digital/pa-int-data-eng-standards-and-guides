# Testing

## Purpose

Define minimum testing requirements for data pipelines and data products.

## Why This Is Important

Testing helps identify issues before data reaches consumers. Effective testing improves reliability, reduces production incidents, and increases confidence in analytical outputs.


## Required Checks

- Schema validation
- Duplicate detection
- Null checks on required fields
- Row count validation

## Rule

All pipelines must include validation before promotion.

## Good Example

A pipeline validates:

- Schema
- Record counts
- Duplicate records
- Required fields

The pipeline automatically fails when validation checks fail.

## Bad Example

Data is processed without validation and issues are only discovered after dashboards, reports, or downstream systems are impacted.