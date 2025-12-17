# Phase 1 — Rollback-Capable Infrastructure

## Definition
Infrastructure is “rollback-capable” if it can tolerate:
- partial idle
- uneven utilization
- pauses in expansion
- non-continuous demand

…and **stopping does less harm than continuing blindly**.

## What this is not
This is not a specific design, product, or vendor recommendation.
It is a survivability requirement.

## Practical meaning
- idle must be operationally acceptable
- pause must be contractually and culturally executable
- success metrics must not be tied to constant expansion

## Plain-English summary
Rollback-capable means the system can slow down without breaking.  
It treats idle and pauses as normal operating states.  
It is a requirement, not a specific implementation.
