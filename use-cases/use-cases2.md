# USE CASE: 2 To update an employee's details so that employee's details are kept up-to-date.

## CHARACTERISTIC INFORMATION

### Goal in Context

As an HR advisor I want to update an employee's details so that employee's details are kept up-to-date.

### Scope

Company.

### Level

Primary task.

### Preconditions

Database contains current Employees of the company.

### Success End Condition

The specified employees having their information up to date in the database

### Failed End Condition

Nothing changes

### Primary Actor

HR

### Trigger

A request to update information pertaining to an employee

## MAIN SUCCESS SCENARIO

1. Information about employees is captured from database.
2. Database is queried to alter each table to update any information related to an employee
3. The query is passed updating employee information

## EXTENSIONS

None

## SUB-VARIATIONS

None.

## SCHEDULE

**DUE DATE**: Release 1.0