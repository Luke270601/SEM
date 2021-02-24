# USE CASE: 3 To add a new employee's details so that I can ensure the new employee is paid.

## CHARACTERISTIC INFORMATION

### Goal in Context

As an HR advisor I want to add a new employee's details so that I can ensure the new employee is paid.

### Scope

Company.

### Level

Primary task.

### Preconditions

Database contains current Employees of the company.

### Success End Condition

Details of the new employee are added to the database

### Failed End Condition

No report is produced.

### Primary Actor

HR

### Trigger

A request to add information pertaining to create a new employees

## MAIN SUCCESS SCENARIO

1. Information about employees is captured from database.
2. Database is queried to alter each table to add new information about the new employee
3. The query is passed adding employee information

## EXTENSIONS

None

## SUB-VARIATIONS

None.

## SCHEDULE

**DUE DATE**: Release 1.0