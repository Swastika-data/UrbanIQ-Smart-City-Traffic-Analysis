# Snowflake Data Model (UrbanIQ)

## Overview
This document describes the analytics-ready data model used for UrbanIQ dashboards and reporting.

## Core Tables
### TRAFFICROUTES
- FROM
- TO
- TRAVELTIMEINSECONDS
- TRAFFICDELAYINSECONDS

### TRAFFICFLOW
- TYPE
- LOCATION
- CURRENTSPEED


## Design Notes
- Separated route-level metrics (TRAFFICROUTES) from real-time flow metrics (TRAFFICFLOW) for clean analysis.
- Structured the model to support aggregation, filtering, and consistent dashboard KPIs.

