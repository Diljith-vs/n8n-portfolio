# Company Directory Filter

## Description
This n8n workflow retrieves employee data from a public REST API, filters employees based on their company, and classifies them as either **Target Company** or **Other Company**.

## Workflow Steps
1. HTTP Request – Fetch employee data from JSONPlaceholder API.
2. IF Node – Check whether the employee belongs to the target company.
3. Edit Fields – Format the output with:
   - Employee
   - Company
   - Email
   - City
   - Status
4. Merge – Combine both branches into a single output.

## Features
- REST API integration
- Conditional filtering
- Dynamic expressions
- Data transformation
- Merge node

## Technologies Used
- n8n
- HTTP Request
- IF Node
- Edit Fields
- Merge Node
- JSONPlaceholder API

## Output
The workflow generates a directory containing:
- Employee Name
- Company Name
- Email Address
- City
- Company Status (Target Company / Other Company)
