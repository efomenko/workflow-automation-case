# Workflow: Alert → PSA Escalation

## Purpose

Demonstrates integration between the workflow platform and a PSA system. It shows how critical alerts can create and prioritize tickets, notify responsible teams, and trigger escalation when required.

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
