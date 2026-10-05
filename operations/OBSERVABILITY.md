# Observability

## Purpose

Defines how workflow execution is made visible and understandable to users and operators. It covers execution status, logs, errors, metrics, troubleshooting information, and operational monitoring.

## Product Requirements

Users should be able to answer:

1. Did my workflow run?
2. When did it run?
3. What triggered it?
4. Which actions were executed?
5. Did any action fail?
6. Why did it fail?

## Execution Status

Possible states:

- Queued
- Running
- Completed
- Failed
- Cancelled

## Metrics

### Platform

- Execution throughput
- Execution latency
- Error rate
- Queue depth

### Product

- Successful workflow executions
- Failed executions
- Failure recovery rate
- Active workflows
