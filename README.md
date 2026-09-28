# Import Data Using Transform Maps (Spreadsheet)

## Project Overview
This ServiceNow Administrator project demonstrates how spreadsheet data can be imported into ServiceNow using an Import Set and Transform Map.

### Project Flow
Spreadsheet (CSV) -> Import Set -> Transform Map -> Field Mapping -> Target Records

## Source Spreadsheet Fields
- Employee ID
- Name
- Email
- Department
- Location

## Sample Data
The `data/employee_data.csv` file contains the sample employee data used for the project.

## ServiceNow Implementation
1. Prepare the employee spreadsheet as CSV.
2. Create/use the required target Employee table in ServiceNow.
3. Create an Import Set and upload `employee_data.csv`.
4. Create a Transform Map from the Import Set table to the target Employee table.
5. Map the source fields to the corresponding target fields.
6. If required, use Employee ID as the unique/coalesce field to prevent duplicate records.
7. Run the transform.
8. Verify the imported records in the target table.
9. Check the Import Set/Transform history for errors or ignored records.

## Field Mapping
| Source Field | Target Field |
|---|---|
| Employee ID | Employee ID |
| Name | Name |
| Email | Email |
| Department | Department |
| Location | Location |

## Team Work Distribution
- Member 1: Prepare and validate spreadsheet data.
- Member 2: Configure Import Set and upload data.
- Member 3: Configure Transform Map, field mappings and coalesce.
- Member 4: Run/verify the transform and prepare screenshots/documentation.

## GitHub Contents
- `data/employee_data.csv` - sample spreadsheet data
- `docs/PROJECT_DOCUMENTATION.md` - project explanation and implementation checklist
- `docs/TEAM_WORK.md` - suggested team responsibilities
- `README.md` - project overview

> Note: ServiceNow configuration itself is stored in the ServiceNow instance. GitHub contains the project documentation and source spreadsheet/CSV used for the implementation.
