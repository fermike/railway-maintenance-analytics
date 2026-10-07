# Methodology

## Data preparation

Work orders are aggregated by unique OT number to avoid counting repeated intervention segments as separate work orders.

## Reliability indicators

MTBS, MTTR and mechanical availability are taken from the monthly maintenance KPI dataset.

## Work-order classification

- CO: corrective work
- PV: preventive work
- INSP: inspection
- Other classes remain available in the source analysis for further study.

## Important limitation

Calendar elapsed time between OT request and closure is not automatically equivalent to MTTR. It may include waiting time, spare-parts delays, supplier activities, administrative time and follow-up. Actual labor/work time should be used when calculating a strict labor-based MTTR.
