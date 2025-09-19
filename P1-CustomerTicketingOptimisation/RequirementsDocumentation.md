# Business Requirements Documents (BRD)

**Project:** Customer Ticketing System Optimisation
**Business Analyst:** Ragganpreet Singh
**Date:**

## Purpose
To optimise the customer support ticketing system, reduce SLA breaches, improve response times, and enhance customer satisfaction.

## Background
The support team currently utilises a manual ticketing system, resulting in delays, inconsistent ticket categorisation, and limited visibility for managers.This BRD will define the functional and non-functional for improvements.

## Scope
**In the scope:**
- Automation of ticketing triaging to reduce repetitive actions
- Categorisation and prioritisation of tickets
- Dashboard for manager for visibility on KPIs and trends
- Reporting on ticket resolution times
- Integration with knowledge base to provide agents with suggested solutions for common issues

**Out of scope:**
- Changes to external customer-facing systems outside ticketing
- Hardware upgrades for support agent
- System replacement

## Stakeholders
Please refer to [Stakeholder Analysis](StakeholderAnalysis.md)
- Support agents (Users)
- Support team manager (Product/Service owner)
- IT system administrator (Technical Implementer)
- Customers (End user)
- Business Analyst (BA)

## Functional Requirements
| ID  | Requirement                                                     | Priority    | Notes                                                     |
|-----|-----------------                                                |-------------|--------|
| FR1 | System should automatically categorise common ticket types                | Must Have  | for example, password resets, how-to                      |
| FR2 | System should priorise tickets based on SLA and priority     | Must Have|Ensure high priority issues are resolved first |
|FR3 | Managers should view dashboard of ticket trends, resolution times, and SLAs | Must Have | Visual representation through Power BI or equivalent | 
|FR4 | Agents should be able to add notes and update ticket status | Must Have | Support workflow and collaboration |
|FR5 | System should generate weekly performance reports | Should have | Helps managers track SLA compliance |
|FR6 | System should generate KB articles when agents are viewing tickets | Could have | Reduce repetitive queries and improve efficiency|

## Non-functional Requirements
| ID  | Requirement     | Priority    | Notes |
|-----|-----------------|-------------|--------|
| NFR1 | System uptime should be at least 99%| Must have | Ensure reliability|
| NFR2 | Dashboard should load within 5 seconds | Should have | Improves usability |
| NFR3 | Ticket data should be backed up daily | Must have | Ensures data integrity |
| NFR4 | System should comply with company data security policy | Must have | Protects customer information|
| NFR5 | Solution should be accessible via standard browsers | Should have | Supports remote working |

## MoSCoW Prioritisation

## Assumptions

## Constraints


