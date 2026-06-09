# Test Case Management — Documentation

This repository contains the documentation source for the [Test Case Management (TCM) tool](https://github.com/cashfree-tech/TestFlow).

## About the TCM tool

The TCM tool is an end-to-end platform that streamlines testing operations across the software development lifecycle. It gives teams visibility into test plan status, automation coverage, assignee progress, and KPI trends — from initial planning and stakeholder approvals through execution and final sign-off.

**Key capabilities:**

- Feature management with a structured approval and sign-off workflow
- Test case CRUD with version history, revert, and admin restore
- Bulk import from Google Sheets
- KPI dashboard with automation coverage metrics and sprint trends
- In-app and email notifications via n8n
- Threaded comments with `@mention` and emoji reactions

## Running the docs locally

Install the [Mintlify CLI](https://www.npmjs.com/package/mintlify), then run from this directory:

```bash
npm install -g mintlify
mintlify dev
```

The docs site will be available at `http://localhost:3000`.

## File structure

```text
.
├── docs.json                  # Mintlify site configuration
├── overview.mdx               # Platform overview and key features
├── get_started.mdx            # Local setup, Docker, login, OAuth, n8n
├── features_and_workflow.mdx  # Feature lifecycle and approval workflow
├── test_cases.mdx             # Test case CRUD, versioning, and restore
├── import.mdx                 # Google Sheets bulk import
├── collaboration.mdx          # Comments, reactions, and notifications
├── dashboard_and_kpi.mdx      # KPI dashboard and automation coverage
└── api-reference.mdx          # Full endpoint reference by domain
```

## Resources

- [TCM source repository](https://github.com/cashfree-tech/TestFlow)
- [Postman collection](https://www.postman.com/cashfreedevelopers/cashfree-test-case-management-tool/collection/xhr9ke4/test-case-management-tcm)
