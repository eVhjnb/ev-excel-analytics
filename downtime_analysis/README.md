## Downtime Analysis

This Excel model evaluates downtime windows for individual inventory items.
Based on:

- Work schedules (per inventory ID)
- Operating hours (Mon–Sun)
- Timestamp logs

Outputs:
- Total downtime inside working hours only
- Business-time deltas
- Clean visual UI for operations teams

Technically:
- Heavy use of date-time logic
- Dynamic formulas to evaluate working-hour overlap
