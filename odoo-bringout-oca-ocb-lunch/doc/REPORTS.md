# Reports

Report definitions and templates in lunch.

```mermaid
classDiagram
    class CashmoveReport
    Model <|-- CashmoveReport
```

## Available Reports

### Analytical/Dashboard Reports
- **Control Accounts** (Analysis/Dashboard)
- **My Account** (Analysis/Dashboard)


## Report Files

- **__init__.py** (Python logic)
- **lunch_cashmove_report.py** (Python logic)
- **lunch_cashmove_report_views.xml** (XML template/definition)

## Notes
- Named reports above are accessible through Odoo's reporting menu
- Python files define report logic and data processing
- XML files contain report templates, definitions, and formatting
- Reports are integrated with Odoo's printing and email systems
