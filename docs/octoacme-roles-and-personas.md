# OctoAcme Personas

This document defines typical roles and responsibilities used in OctoAcme project docs and exercises.

... [existing roles: Developers, Product Managers, Project Managers] ...

---

## QA Lead

### Role Summary
The QA Lead is responsible for the overall quality strategy. They ensure that the "Definition of Done" is met and that features are verified against acceptance criteria before they reach production.

### Responsibilities
- Define the test strategy (Unit, Integration, and E2E smoke tests).
- Perform manual QA for feature acceptance.
- Verify that security scanning and linting results are addressed in CI.
- **Interaction:** Works closely with Developers during "In Review/QA" stages and provides the final quality sign-off to the Project Manager.

---

## Release Manager

### Role Summary
The Release Manager coordinates the deployment lifecycle, ensuring that releases are stable, documented, and communicated to stakeholders.

### Responsibilities
- Maintain the "Deployment Checklist" and schedule deployment windows.
- Coordinate post-deploy verifications and "Smoke tests."
- Draft and distribute Release Notes based on the provided template.
- **Interaction:** Collaborates with PMs on the release plan and coordinates with Developers for hotfixes or rollbacks.

---

## UX/UI Designer

### Role Summary
The Designer ensures the "Customer-first" principle is upheld by translating business goals into usable, intuitive interface designs.

### Responsibilities
- Create wireframes and high-fidelity mockups for the "Project One-pager."
- Ensure designs account for usability and accessibility standards.
- **Interaction:** Consults with Product Managers during Initiation and provides design specs to Developers during Planning.

---

## Security Engineer

### Role Summary
Provides oversight for risk mitigation and ensures that security best practices are integrated into the CI/CD pipeline and codebase.

### Responsibilities
- Configure and monitor security scanning tools in CI.
- Manage the "Security incident runbook" and lead "Post-incident retrospectives."
- **Interaction:** Acts as an escalation point for the PM/Developers when a high-impact security risk is identified in the Risk Register.

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.