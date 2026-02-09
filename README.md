# Matplotlib Charting GUI (SQL)

A lightweight Qt-based GUI for creating, editing and saving Matplotlib charts from SQL data.

Features
 - Create many chart types (bar, scatter, histogram, contour, 3D plots, etc.)
 - Interactive chart tabs with toolbar for pan/zoom, copy, and settings
 - Persist charts and settings in a SQLite-backed project file
 - Import data from CSV/SQLite and map columns to chart roles
 - Export charts to images and copy to clipboard

Quick start
1. Create or open a project file (`.prj`) from the app UI, or run:
   ```bash
   python Main.py
   ```
2. Import or connect to a SQLite database, select a table, assign roles and build charts.

Development
- Python 3.10+ recommended (virtualenv optional).
- Install dependencies in `requirements.txt` (project uses PySide6 and Matplotlib).

Notes
- Chart thumbnails are stored under `chartimages/`.
- Chart implementations live in the `charts/` package and inherit from `chart_base.py`.

License
MIT-style — feel free to adapt for your repository.
