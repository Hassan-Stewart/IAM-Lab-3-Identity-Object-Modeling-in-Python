# IAM-Lab-3-Identity-Object-Modeling-in-Python
## Repository Note
This lab is also included in my primary portfolio repository:
**IAM-Automation-Labs-and-Projects**
The code, screenshots, and documentation contained in this repository are duplicated in the consolidated portfolio repository. This standalone repository is maintained to preserve the individual progression of each IAM automation lab, while the primary portfolio repository serves as the central location for all labs, projects, diagrams, screenshots, and future enhancements.
## Overview
This lab introduces identity modeling using Python as part of my IAM/PAM automation learning path. Instead of provisioning users directly in Active Directory, I created identity objects that represent user attributes such as username, department, role, and MFA status. These objects mirror how identity data is structured before being sent to IAM systems like Entra ID, Okta, AWS IAM, and CyberArk.

This lab focuses on building clean, modular Python code that models identity data and prepares it for JSON serialization, a foundational step toward API-based IAM automation. 
## Skills Demonstrated
- Python scripting
- Identity object modeling
- JSON serialization
- IAM data structure design
- Modular code organization
## Lab Steps 
- Created Python dictionaries representing user identities
- Structured identity attributes:
- Username
- Department
- Role
- MFA Status
- Stored multiple identity objects inside a list
- Printed identity records in a readable format
- Converted identity objects into JSON using `json.dumps()`
## Files Included

### `lab2_identity_objects.py`
Contains identity objects.

### `lab3_json_payload.py`
Converts identity objects into JSON.
 
## Screenshots
- Identity objects printed in the terminal
- JSON payload printed with indentation
 
## Lessons Learned
- How identity data is represented before provisioning
- How JSON payloads are prepared for IAM APIs
- How modular Python files improve automation structure
67
- How identity attributes map to real IAM systems
