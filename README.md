# YouVan_App
YouVan Ops — Campervan Business Manager (MVP)

YouVan Ops is a “Python + Tkinter + SQLite” desktop app for managing our campervan rental business.  
This is the “MVP (Minimum Viable Product)” version: a simple but working release that covers the essential operations.
Features
- Vehicles: Add, update, or delete vehicles (plate, make, model, year, odometer).  
- Fuel logs: Record fills (date, odometer, liters, cost, station).  
- Expenses: Track expenses with GST flag (linked to a van or general).  
- Reminders: Set reminders for COF, services, rego (by date or odometer).  
- Dashboard: See upcoming reminders and basic fuel economy stats.  

Tech stack
- [Python 3](https://www.python.org/)  
- [Tkinter](https://docs.python.org/3/library/tkinter.html) (built-in GUI toolkit)  
- [SQLite](https://sqlite.org/) database (lightweight, file-based)  

Project structure
YouVan_App/
│── main.py - GUI app
│── db.py - database helper (creates DB from schema.sql)
│── schema.sql - database schema (tables & views)
│── README.md - project info (this file)
│── checklist.md - operational checklist (COF, rego, insurance, etc.)
└── data_templates/ CSV templates for bulk data entry
├── vehicles_template.csv
├── fuel_logs_template.csv
├── expenses_template.csv
└── reminders_template.csv

