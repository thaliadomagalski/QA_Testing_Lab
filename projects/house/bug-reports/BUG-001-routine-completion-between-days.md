# BUG-001 — Completion Status Persists When Navigating Between Days

**Bug ID:** BUG-001
**Module:** Routine
**Bug Type:** Functional Bug
**Severity:** Medium
**Priority:** Medium
**Status:** Open

## Description

The completion status of a routine activity remains marked as completed when navigating from one day to another.

## Preconditions

* A routine activity is available.
* The user can mark the activity as completed.
* The application allows navigation between different days.

## Steps to Reproduce

1. Access the **Routine** module.
2. Select the current day.
3. Select a routine activity.
4. Mark the activity as **"Concluída"**.
5. Navigate to the following day.
6. Observe the status of the same activity.

## Expected Result

The completion status should correspond to the selected day.

Completing an activity on one day should not automatically mark the same activity as completed on another day.

## Actual Result

The activity remains displayed as **"Concluída"** after navigating to another day.

## Impact

This behavior may lead users to believe that an activity was completed on a day when it was not actually completed, reducing the reliability of the routine tracking feature.

## Evidence

The behavior was manually reproduced during functional testing of the application.

## Environment

**Application:** House
**Platform:** Web
**Testing Type:** Functional Testing
