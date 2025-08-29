# Reports

Report definitions and templates in membership.

```mermaid
classDiagram
    class ReportMembership
    Model <|-- ReportMembership
```

## Available Reports

### Analytical/Dashboard Reports
- **Members Analysis** (Analysis/Dashboard)


## Report Files

- **__init__.py** (Python logic)
- **report_membership.py** (Python logic)
- **report_membership_views.xml** (XML template/definition)

## Notes
- Named reports above are accessible through Odoo's reporting menu
- Python files define report logic and data processing
- XML files contain report templates, definitions, and formatting
- Reports are integrated with Odoo's printing and email systems
