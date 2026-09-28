# Project Documentation

## 1. Title
**Import Data Using Transform Maps (Spreadsheet)**

## 2. Objective
To import employee information from a spreadsheet into ServiceNow and transform the imported source data into records in a target table.

## 3. Input Data
The sample spreadsheet contains:
- Employee ID
- Name
- Email
- Department
- Location

## 4. Architecture / Process
```text
Employee Spreadsheet
        |
        v
    Import Set
        |
        v
   Import Set Table
        |
        v
   Transform Map
        |
        v
    Field Mapping
        |
        v
   Target Employee Table
```

## 5. Field Mapping
| Source | Target |
|---|---|
| Employee ID | Employee ID |
| Name | Name |
| Email | Email |
| Department | Department |
| Location | Location |

## 6. Expected Result
After a successful transform, the employee information from the spreadsheet should be available as records in the configured target table.

## 7. Validation Checklist
- [ ] CSV file prepared
- [ ] Import Set created
- [ ] Source data loaded successfully
- [ ] Transform Map created
- [ ] All required fields mapped
- [ ] Unique field/coalesce configured if required
- [ ] Transform completed successfully
- [ ] Target records verified
- [ ] Screenshots captured for project report

## 8. Screenshots to Add
Add your own ServiceNow screenshots to the GitHub repository if your college/training requires them:
1. Import Set creation
2. Uploaded data / Import Set table
3. Transform Map
4. Field mappings
5. Transform run result
6. Final target records
