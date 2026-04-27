# Viora UI Calendar

This folder contains the Viora UI Calendar custom visual package for Power BI.

Although this visual is a date filter / calendar control, the package name keeps the original `Viora UI` naming that comes from the source package. That helps preserve the package metadata and keeps the visual easy to identify.

## Folder contents

- `VioraUI_Calendar_1.7.0.3.pbiviz` — Power BI visual package
- `USER_GUIDE.md` — installation, usage, and limitations
- `LICENSE` — license for this package
- `Images/` — screenshot gallery

## Install

1. Download `VioraUI_Calendar_1.7.0.3.pbiviz` from this folder.
2. Open Power BI Desktop.
3. Select `...` (More visuals) > `Import from file`.
4. Choose the `.pbiviz` package.
5. Add the visual to your report canvas.

## Why not AppSource?

This visual remains available here as a direct GitHub download because it still has important limitations for Power BI production use.

### Primary limitation

The visual must stay on the top layer in Power BI's selection pane. When the calendar is visible, it overlaps any visuals beneath it, even when it is collapsed. That overlay behavior can block underlying visuals, making it harder to select or filter them. For this reason, the visual is not ideal for reports where users need to interact with multiple visuals in the same area.

### Additional limitation

This package has had limited testing against real report data. That means the current version is better suited for experimentation, design exploration, and early feedback rather than being treated as a fully supported AppSource visual.

### Roadmap context

Microsoft is planning a native Power BI date filter / range selection visual later this year. Because of this roadmap and the current overlay limitation, the best path is to keep this package on GitHub as a preview and idea reference.

That way users can:

- test the behavior
- see how it could fit in their reports
- think about how they would use it
- contribute feedback or improvements

## Documentation

- Read the visual-specific guide: [`USER_GUIDE.md`](./USER_GUIDE.md)

## Screenshots

The screenshot files are available in the `Images/` folder:

- [Screenshot 1](./Images/img%201.png)
- [Screenshot 2](./Images/img%202.png)
- [Screenshot 3](./Images/img%203.png)
- [Screenshot 4](./Images/img%204.png)

Or open the folder directly: [Images/](./Images/)
