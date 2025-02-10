# Jira Cloud Authentication & Access Control Test Notebook

## Purpose
This Jupyter Notebook is designed to automate security and access control tests for Jira Cloud integrated with Okta authentication. It helps validate:

1. Whether non-admin users can access Jira Cloud.
2. If Active Directory (AD) group membership correctly enforces expected access levels.
3. Whether Okta-based authentication correctly enforces user permissions.
4. If unauthorized users can escalate privileges or gain access improperly.

## Features
- Uses **ipywidgets** for interactive execution.
- Runs authentication checks via **Jira REST API**.
- Validates whether Okta users have proper access to Jira Cloud.
- Generates an audit report in **CSV format**.
- Displays **user directory details** for further verification.
- Each test case can be executed independently using dropdown selection.
