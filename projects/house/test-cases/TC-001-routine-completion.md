# TC-001 — Verify Routine Completion Status by Day

**Test Case ID:** TC-001
**Module:** Routine
**Test Type:** Functional Testing
**Status:** Failed

## Objective

Verify whether the completion status of a routine activity is correctly associated with the selected day.

## Preconditions

* The application is accessible.
* A routine activity is available.
* The user can mark the activity as completed.
* The application allows navigation between different days.

## Test Steps

1. Access the **Routine** module.
2. Select the current day.
3. Select a routine activity.
4. Mark the activity as **"Concluída"**.
5. Navigate to the following day.
6. Observe the status of the same activity.

## Expected Result

The completion status should be associated with the specific day on which the activity was completed.

When navigating to another day, the activity should display the status corresponding to that day.

## Actual Result

The activity continues to appear as **"Concluída"** when navigating to another day.

## Test Result

**FAIL**

The observed behavior does not correspond to the expected behavior for daily routine tracking.
