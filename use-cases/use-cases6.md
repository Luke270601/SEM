# USE CASE: 6 To produce a report on the salary of employees in a department so that HR can support financial reporting of the organisation.

## CHARACTERISTIC INFORMATION

### Goal in Context

As an HR advisor I want to produce a report on the salary of employees in a department so that I can support financial reporting of the organisation.

### Scope

Company.

### Level

Primary task.

### Preconditions

Database contains current Employees of the company.

### Success End Condition

A report of employees salary in a given  department 

### Failed End Condition

No report is produced.

### Primary Actor

HR

### Trigger

A request to get information about an employee, their salary and department

## MAIN SUCCESS SCENARIO

1. Information about employees is captured from database.
2. Database is queried to get those of a given department and their salary 
3. The query is passed producing a report of the employees

## EXTENSIONS

None

## SUB-VARIATIONS

None.

## SCHEDULE

**DUE DATE**: Release 1.0