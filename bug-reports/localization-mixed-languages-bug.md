## Title
[Localization] Action buttons show mixed languages
on "Commission Confirmed" applications

## Summary
When interface is set to EN or UZ, action buttons
display in mixed languages — one in English,
another in Russian.

## Environment
- Device: MacBook Air
- OS: macOS Sequoia 15.7.4
- Browser: Chrome 145.0.7632.117
- URL: https://example-app.com/

## Preconditions
- Logged in with a valid account
- IT-VISA module access available
- Interface language set to EN or UZ

## Steps to Reproduce
1. Navigate to https://example-app.com/
2. Set interface language to EN or UZ
3. Go to IT-VISA → Applications
4. Filter by status "Commission Confirmed"
5. Open any application
6. Observe action buttons

## Expected Result
All buttons display in selected interface language.

## Actual Result
"Rejected" shows in English, "Рассмотрено" shows
in Russian regardless of selected language.

## Severity
Major

## Priority
Medium

## Frequency
100% reproducible

## Attachments
<img width="253" height="141" alt="Снимок экрана 2026-03-06 в 12 13 15" src="https://github.com/user-attachments/assets/50e94a7b-a1f3-45ff-8d7d-131b0080f13c" />

<img width="234" height="130" alt="Снимок экрана 2026-03-06 в 10 29 18" src="https://github.com/user-attachments/assets/fddb7827-87dc-43a6-9363-08b117552c5d" />
