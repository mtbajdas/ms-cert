# ms-cert
Playbook and artifact storage for Microsoft Certifications

## Purpose
This repository serves as a centralized location for storing all artifacts, lab exports, diagrams, and learning materials related to Microsoft certification exams. It provides a structured approach to tracking progress, documenting mistakes, and organizing practice materials.

## Folder Breakdown

### `/AZ-104/` - Microsoft Azure Administrator
Resources and materials for the AZ-104 certification exam.

### `/DP-700/` - Microsoft Fabric Data Engineer
Resources and materials for the DP-700 certification exam.

### `/PL-300/` - Microsoft Power BI Data Analyst
Resources and materials for the PL-300 certification exam.

### `/PL-600/` - Microsoft Power Platform Solution Architect
Resources and materials for the PL-600 certification exam.

### `/AZ-305/` - Designing Microsoft Azure Infrastructure Solutions
Resources and materials for the AZ-305 certification exam.

## How Mocks Are Logged
- Mock exam results should be documented with date, score, and weak areas identified
- Include screenshots or exports of practice test results
- Note any patterns in incorrect answers for future review
- Track progress over time with timestamps

## Lab Naming Conventions
Lab files should follow this naming pattern:
```
YYYY-MM-DD_<exam-code>_<lab-topic>_<version>.<ext>
```

Examples:
- `2025-12-24_AZ-104_virtual-networks_v1.md`
- `2025-12-24_DP-700_data-pipeline_lab-export.json`
- `2025-12-24_PL-300_dashboard-design_diagram.png`

## Commit Rule
**Every lab export, diagram, or mistake writeup gets pushed here**
- Commit immediately after completing a lab or practice session
- Use descriptive commit messages that reference the exam code and topic
- Keep artifacts organized in their respective certification folders
