# Workflow: Alert → PSA Escalation

## Business Scenario

A critical monitoring alert should automatically create a PSA ticket
and notify the responsible team.

## Trigger

Alert Created

## Conditions

```text
Alert Severity = Critical
AND
Customer Environment = Production
