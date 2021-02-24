# USE CASE: 1 to delete an employee's details so that the company is compliant with data retention legislation.

## CHARACTERISTIC INFORMATION

### Goal in Context

As an HR advisor I want to delete an employee's details so that the company is compliant with data retention legislation.

### Scope

Company.

### Level

Primary task.

### Preconditions

Database contains current Employees of the company.

### Success End Condition

The specified employees removed from the database

### Failed End Condition

The employees' information isnt removed

### Primary Actor

HR

### Trigger

A request to remove information pertaining to an employee

## MAIN SUCCESS SCENARIO

1. Information about employees is captured from database.
2. Database is queried to alter each table to remove any information related to an employee
3. The query is passed removing employee information

## EXTENSIONS

None

## SUB-VARIATIONS

None.

## SCHEDULE

**DUE DATE**: Release 1.0