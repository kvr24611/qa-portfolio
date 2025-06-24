# ✅ Test Strategy vs Test Plan

Understanding the **difference between a Test Plan and a Test Strategy** is key for any QA professional. Here’s a clear comparison with real-world context.

---

## ✅ Test Strategy

- **What it is**: A **high-level document** that outlines the **overall testing approach** across projects or products.
- **Scope**: Organization-wide or project-wide.
- **Focus**: *How* testing will be done.
- **Audience**: QA Managers, Project Stakeholders, Product Owners.

### 🔍 Contents Typically Include:
- Testing objectives and principles
- Testing types (manual, automation, performance, security)
- Tools and frameworks to be used
- Roles and responsibilities
- Entry/exit criteria
- Risk management
- Reporting and communication processes

### 🌍 Real-World Examples:

#### 🔹 CyberX
> At **CyberX**, the QA leadership defined a Test Strategy where:
> - API testing had to be automated using Postman + Newman.
> - JMeter was the standard for performance tests.
> - Security testing had to align with OWASP Top 10.
> - CI pipelines had to include all automated tests via GitHub Actions.
> - Logs collected by various agents had to be validated in SIEM across different configurations (Linux, Windows, Syslog, etc.).

#### 🔹 DartaChalani
> At **DartaChalani**, the Test Strategy included:
> - Prioritizing automation for core features like Document Processing, Review, and Archive.
> - UI automation with Playwright, API tests via Postman, and database validation using manual test passes.
> - Staging and production parity in testing environments.
> - Use of GitHub Actions for CI/CD and test reports for every pull request.

> 🧠 **Think of it as**:  
> “The **why and how** we test across the board.”

---

## ✅ Test Plan

- **What it is**: A **detailed document** that focuses on the testing of a **specific project or feature**.
- **Scope**: Individual application or feature.
- **Focus**: *What, when, who, and where* to test.
- **Audience**: QA Team, Developers, PMs, Business Analysts.

### 🔍 Contents Typically Include:
- Objectives and scope of testing for that release
- Features to be tested and not tested
- Test items (code, APIs, UI, etc.)
- Test schedule and timelines
- Environment setup
- Deliverables
- Approvals

### 🌍 Real-World Examples:

#### 🔹 CyberX
> For the “**Agent v3.5**” release at CyberX:
> - **Scope**: Test new log ingestion and parsing enhancements.
> - **Test Items**: Agent APIs, Configuration UI, Syslog input.
> - **Timeline**: 10 working days.
> - **Test cases**: 60 manual, 25 automated.
> - **Roles**: Alisha (UI), Kabir (API and integration).
> - **Out of Scope**: Legacy connectors.

#### 🔹 DartaChalani
> For the “**Document Optimization**” feature:
> - **Scope**: Verify automatic assignment logic for review based on seniority, liesure, and department.
> - **Test Items**: Review UI, backend API, assignment logic, and Google Docs integration.
> - **Timeline**: 2 sprints (4 weeks).
> - **Test cases**: 45 automated (Playwright + Postman), 15 exploratory.
> - **Team**: Rishi (Automation), Kabir (Manual & Coordination), QA Intern (Data setup).
> - **Out of Scope**: Mobile app UI changes.

> 🧠 **Think of it as**:  
> “The **blueprint** for how we’ll test this particular product/release.”

---

## 🆚 Summary Comparison Table

| Aspect              | Test Strategy                              | Test Plan                                 |
|---------------------|---------------------------------------------|--------------------------------------------|
| **Level**            | Organization or project-wide                | Specific project/module                    |
| **Purpose**          | Defines approach and guidelines             | Defines exact steps and scope              |
| **Content**          | High-level, generic                         | Detailed, specific                         |
| **Owner**            | QA Manager/Test Manager                     | QA Lead/QA Engineer                        |
| **Time of creation** | Early in the SDLC or once per project       | Before the test phase of a release         |
| **Flexibility**      | Stable across multiple projects             | Changes per release/project                |

---
