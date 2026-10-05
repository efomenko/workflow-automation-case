# Workflow Templates

## Purpose

Defines the reusable workflow template capability. It explains template structure, default configuration, required user customization, publishing, adoption, and metrics for measuring template effectiveness.

## Goal

Reduce the effort required to create common workflows.

## Template Structure

A template contains:

- Name
- Description
- Category
- Trigger
- Actions
- Required parameters
- Optional parameters
- Documentation

## Example

### Backup Failure → PSA Ticket

Trigger:

`Backup Failed`

Action:

`Create PSA Ticket`

Parameters:

- Ticket priority
- Assignment group
- Customer
- Notification recipient

## Template Success Metrics

- Template usage
- Template activation rate
- Time from template selection to activation
- Template modification rate
