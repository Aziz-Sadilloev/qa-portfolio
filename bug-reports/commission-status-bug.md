## Title
"Commission Confirmed" status not updating and
"Reviewed"/"Rejected" buttons not visible after
5 expert reviews completed

## Summary
After all 5 experts have reviewed application #XXX,
the system fails to update the status from
"Commission is Reviewing" to "Commission Confirmed."
As a result, the "Reviewed" and "Rejected" action
buttons are not displayed, blocking the commission
workflow entirely.

## Environment
- Device: MacBook Air
- OS: macOS Sequoia 15.7.4
- Browser: Chrome 145.0.7632.117
- URL: https://example-app.com/

## Preconditions
- User is logged in with a valid account
- User has access to IT-VISA module
- Application #XXX has been reviewed by all 5 experts

## Steps to Reproduce
1. Navigate to https://example-app.com/
2. Go to module "IT-VISA"
3. Open submodule "Applications"
4. In filter field "Application Number" enter "#XXX"
5. Click the "Actions" button for the application
6. Observe the application status and available buttons

## Expected Result
After all 5 experts have reviewed the application,
the system should automatically update the status
to "Commission Confirmed" and display "Reviewed"
and "Rejected" buttons to allow further action.

## Actual Result
The status remains "Commission is Reviewing" despite
all 5 expert reviews being completed. The "Reviewed"
and "Rejected" buttons are not visible, making it
impossible to proceed with the commission decision.

## Severity
Critical

## Priority
High

## Frequency
100% reproducible

## Attachments
Screenshot available upon request.
(Personal data omitted for privacy reasons)
