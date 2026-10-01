# Experiment 4: BPMN Process with User Task and Form in Camunda 8

**Name:** <your name>
**Roll No:** <your roll number>
**Course/Subject:** <subject>

## Aim
To model a simple Leave Request process in BPMN, attach a Camunda Form to a
User Task, deploy it to Camunda 8, and verify the submitted values as
process variables.

## Process
Start Event → User Task (Fill Leave Request Form) → End Event

## Form Fields
| Field | Key |
|---|---|
| Employee Name | employeeName |
| Leave Date | leaveDate |
| Leave Type | leaveType |
| Reason | reason |

The form ID is `leaveRequestForm`, linked to the User Task.

## Steps Performed
1. Modeled the process in Camunda Modeler.
2. Created the form with keyed fields.
3. Linked the form to the User Task using the Form ID.
4. Deployed the BPMN and form to Camunda 8.
5. Started an instance, claimed the task in Tasklist, filled the form and completed it.
6. Checked the variables in Operate.

## Screenshots
See the `screenshots/` folder.

## Result
The values entered in the form appeared as process variables in Operate.
