# Calculation notes and document scope

The original assignment brief and submitted report are included unchanged. These notes identify selected review points found while preparing this repository; they are not a complete technical audit or a revised design.

## Source map

| Topic | Report pages |
|---|---|
| Site and roof assessment | 2–4 |
| Modules and array sizing | 5–6 |
| Electrical layout and strings | 6 |
| Hostel demand estimates | 7–8 |
| PVGIS resource and seasonal analysis | 8–16 |
| Performance and temperature | 17–20 |
| Revenue and energy balance | 21–23 |
| Financial analysis | 24–26 |
| Group contribution statement | 27 |

## Selected points to reconcile

- **Annual energy:** Table 5 on page 18 sums to **144,300.41 kWh**. Page 21 reports **131,365.35 kWh** and repeats July's figure in the displayed August position. Both the month entry and annual arithmetic need reconciliation before recalculating export income or revenue.
- **Financial cash flow:** page 24 shows maintenance and replacement costs separately, but its cumulative totals do not consistently reflect those deductions. Page 26 uses the gross annual revenue as annual cash flow without the listed O&M and replacement deductions. The reported NPV should be recalculated using consistent net cash flows.
- **Replacement timing:** the brief specifies replacement after five years. The report's table also lists replacements at years 10 and 15. State the intended schedule before a revised calculation.
- **Self-consumption:** an annual generation-minus-demand balance alone does not establish direct solar self-consumption. Use time-aligned generation and load data, with the applicable metering arrangement, for a revised savings estimate.
- **Inverter wording:** page 5 describes two 50 kW units as single-phase. Confirm the intended phase configuration and actual selected inverter specifications before practical design use.
- **Orientation:** page 3 describes selection of west-facing roof area, while page 17 records an azimuth of −90°. Reconcile this with the simulation's azimuth convention and roof orientation.
- **Multiple PVGIS results:** the report includes figures in both the resource and performance sections. Confirm location, capacity, orientation, loss assumptions, and source period for each run before comparing outputs.

## Included data

`../data/monthly_pv_output_report_table_5.csv` transcribes Table 5 exactly. It does not silently replace the report's annual figure, certify a simulation, or revise the submitted report. No raw PVGIS export was supplied with this repository package.

The home-system summary in the README comes from the author's installation details. The hostel simulation results do not represent measured generation from the home system.
