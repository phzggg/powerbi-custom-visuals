# Viora UI Calendar - User Guide

## 1. Introduction

Viora UI Calendar is a custom Power BI visual designed for date range selection with an enhanced calendar interface.

## 2. Requirements

- Power BI Desktop compatible with API version **5.11.0**.
- Windows environment for visual import and report editing.

## 3. Installation

1. Download VioraUI_Calendar_1.7.0.3.pbiviz from the Custom Visuals/viora-ui-calendar/ folder.
2. Open Power BI Desktop.
3. Select ... (More visuals) > Import from file.
4. Choose the .pbiviz file.
5. Add the visual to your report canvas.

## 4. Configuration

- Drag the appropriate date field(s) into the visual's field well.
- Use the formatting pane to adjust the visual's appearance and behavior.
- Set any available preset or effects options from the formatting settings.

## 5. Features

- Calendar-style date range selection
- Independent effects toggle
- Global presets support
- Custom date formatting in supported Power BI layouts

## 6. Limitations

- The visual is provided "as-is" and may not work in all Power BI versions.
- Some date formats or locales may not display correctly.
- The visual requires being positioned on the top layer in Power BI's selection pane.
- Even when collapsed, the calendar overlay can still overlap visuals below it, which may interfere with filtering and report interactions.
- There has been limited testing with diverse data models and scenarios.
- The visual is not certified and should be validated before use in production.

## 7. Important note about distribution

This visual is intentionally not intended for Power BI AppSource submission at this time.

- Microsoft plans to release a native date range filter visual later this year.
- The current overlay behavior and limited testing make this version more suitable for experimentation and design feedback than for production use.

## 8. Troubleshooting

- If the visual does not import, ensure Power BI Desktop supports custom visuals.
- If the visual does not display dates correctly, verify the source field is a valid date or datetime column.
- Restart Power BI Desktop after importing if the visual does not appear immediately.

## 9. Support

For updates or new versions, check this repository.
