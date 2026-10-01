# Calisthenics-app
Used for logging my calisthenics progression over time

## Local checks
Run `node scripts/test.cjs` from this folder.

## Exercise history and workout edits
- Each exercise card has a history button. The graph plots the best clean set per saved calendar day; selecting a point shows all valid saved sets for that exercise on that day.
- Weighted graphs compare weight × reps, assisted exercises compare lower assistance (then reps), and other exercises compare reps or duration. Best day cards compare total daily work instead of an individual set.
- Adding, removing or reordering exercises on Today only edits that date and workout type. These lists persist on the device and are included in exported backups. Edit My plan to change a recurring workout template.
- Existing templates are preserved; this update does not attempt to infer which earlier template changes were accidental.
