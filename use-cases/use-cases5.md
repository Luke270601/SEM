# USE CASE: 5 To produce a report on the salary of employees in manager's department so that they can support financial reporting for my department.

## CHARACTERISTIC INFORMATION

### Goal in Context

As an department manager I want to produce a report on the salary of employees in my 
department so that I can support financial reporting for my department.

### Scope

Company.

### Level

Primary task.

### Preconditions

Database contains current Employees of the company.

### Success End Condition

A report of employees salary in a given managers department 

### Failed End Condition

No report is produced.

### Primary Actor

Department Manager

### Trigger

A request to get information about an employee, their salary and department

## MAIN SUCCESS SCENARIO

1. Information about employees is captured from database.
2. Database is queried to get those of a given department and their salary and manager
3. The query is passed producing a report of the employees

## EXTENSIONS

None

## SUB-VARIATIONS

None.

## SCHEDULE

**DUE DATE**: Release 1.0