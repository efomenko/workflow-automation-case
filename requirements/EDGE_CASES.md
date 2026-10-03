# Edge Cases

## Trigger Issues

- Event contains missing properties
- Event schema changes
- Duplicate event
- Event arrives out of order

## Condition Issues

- Property does not exist
- Incorrect data type
- Null value
- Unsupported comparison

## Action Issues

- External system unavailable
- Authentication expired
- Rate limit exceeded
- Required parameter missing

## Workflow Issues

- Workflow disabled during execution
- Workflow version changed
- Circular dependency
- Multiple workflows triggered by the same event

## Product Requirement

The system should fail predictably and provide enough information
for the user to understand what happened.
