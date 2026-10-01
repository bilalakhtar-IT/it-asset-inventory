# IT Asset Inventory
 
A sample IT asset tracking spreadsheet built to demonstrate how hardware and software assets are documented and managed in a real IT environment.
 
## What's Inside
 
| File | Format | Purpose |
|---|---|---|
| IT Asset Inventory.xlsx | Excel | Main tracking sheet with dropdown validation and conditional formatting |
| IT Asset Inventory.csv | CSV | Plain data export for compatibility with other systems |
 
The workbook includes 20 sample assets across 5 device categories (Laptop, Desktop, Monitor, Peripheral, Mobile), with a mix of statuses (In Use, Unused, Faulty, Retired) to reflect what a real inventory looks like over time.
 
## Each entry tracks:
 
- Asset Tag (type-prefixed and sequential, e.g. LT-0001, DT-0001)
- Device Type, Model, Serial Number
- Assigned User, Email, Department, Work Location
- Purchase Date and Warranty Expiration
- Status, with Notes for context on Faulty, Retired, or Unused devices

## Why Excel and CSV
 
The workbook uses Data Validation dropdowns and Conditional Formatting to make the sheet usable the way a real IT team would use it day to day. The CSV version holds the same raw data but strips out formatting entirely, since CSV is a plain text format with no concept of styling, dropdowns, or rules. It's included to show an understanding of when each format is the right choice: Excel for a human to read and interact with, CSV for moving data between systems.
 
## Skills
 
This project has allowed me to build and demonstrate:
 
**Technical**
- Excel Data Validation (dropdown lists)
- Conditional Formatting (status-based highlighting)
- Structuring asset data the way real IT asset management systems do

**Process & Documentation**
- Asset tagging conventions used in real IT environments
- Understanding the difference between Excel and CSV formats and when each is appropriate
- Git & version control (GitHub)

## Project Goal
 
 The main purpose of this project is to understand how IT departments track hardware throughout a company's lifecycle, from the day it's purchased to the day it's retired, and to build a usable template that reflects real asset management practices.
 
## Moving Forward
 
This project may be expanded with additional sample data or extra tracking fields as I continue building out my IT portfolio.