# Uruguay Properties - Test Cases

Version: 1.0
Status: Draft

## RF-002 - Property Search

### Preconditions

- Five test properties are available.
- The property catalog is loaded.
- No additional filters are active.

## Test Cases

| ID | Description | Test Data | Expected Result | Status |
|---|---|---|---|---|
| TC-001 | Search by partial title | apartamento | P001, P003 | Not Run |
| TC-002 | Case-insensitive search | CASA | P002, P004 | Not Run |
| TC-003 | Search without matches | castillo | No results and informative message | Not Run |
| TC-004 | Empty search | Empty string | All properties | Not Run |
| TC-005 | Search with surrounding spaces | "  Pocitos  " | P001 | Not Run |