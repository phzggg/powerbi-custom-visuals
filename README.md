# powerbi-custom-visuals

This repository is a clean collection of Power BI custom visuals packaged for direct import.

Each visual is stored in its own folder so the package, usage guide, screenshots, and license stay together.

## Why this repository exists

Power BI visuals can be shared directly as `.pbiviz` files without requiring an AppSource listing. This repo is intended to keep those visuals small, easy to browse, and easy to import into Power BI Desktop.

## Visual folder structure

This repository stores custom visuals in self-contained folders. One visual is available under:

- [`Custom Visuals/Date Range Filter/`](./Custom Visuals/Date Range Filter/)

## Why the name `Viora UI`

In this repo, `Viora UI` works like a component brand prefix. You will see components referred to as `Viora UI` + a feature name, and that is my naming convention for package metadata and component branding.

## Repository structure

- `README.md` — repository overview and usage notes
- `LICENSE` — repository license
- `Custom Visuals/` — each custom visual lives in its own folder
- `Custom Visuals/<visual-folder>/` — contains the `.pbiviz`, `USER_GUIDE.md`, `LICENSE`, and `Images/`

## How to use this repository

1. Open the `Custom Visuals/` folder.
2. Open the folder for the visual you want.
3. Download the `.pbiviz` package.
4. In Power BI Desktop, choose `...` (More visuals) > `Import from file`.
5. Select the downloaded `.pbiviz` file.

## Notes

- This repo is a direct-download collection, not an AppSource submission.
- Each visual folder is self-contained to make future additions simple.
- Additional visuals can be added later with the same folder pattern.

## Future visuals

Add one folder per visual under `Custom Visuals/`, and keep each folder self-contained with:

- `.pbiviz`
- `USER_GUIDE.md`
- `LICENSE`
- `Images/`

