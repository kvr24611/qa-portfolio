
# 🧰 QA Toolbox – Kabir Raj Panthy

This is a personal collection of tools, commands, and use-cases I regularly encounter as a QA Engineer.

---

## 📌 Format

Each tool is documented with the following structure:

- **Tool Name**
- **Purpose / When to Use**
- **Key Features / Concepts**
- **Cheat Sheet / Common Commands**
- **Useful Links**

---

## 🧪 Postman – API Testing

**When to Use:**  
For manual API testing, automating test cases, chaining requests, and environment-based tests.

**Key Features:**
- Collections & Environments
- Tests & Pre-request Scripts
- Newman CLI for automation

**Cheat Sheet:**
```js
pm.test("Status is 200", function () {
    pm.response.to.have.status(200);
});
```

**Useful Links:**
- https://learning.postman.com/
- https://www.npmjs.com/package/newman

---

## 🧰 Playwright – UI Automation

**When to Use:**  
For end-to-end UI test automation of web applications.

**Key Features:**
- DOM interaction
- Fixtures & Commands
- API mocking

**Cheat Sheet:**
```js
page.goto('https://google.com')
page.locator('//button[@text='Submit']').click()
```

**Useful Links:**
- https://docs

---

## 📉 JMeter – Performance Testing

**When to Use:**  
For load testing APIs, services, or web apps.

**Key Features:**
- Thread Groups
- HTTP Samplers
- Assertions & Reports

**Useful Links:**
- https://jmeter.apache.org/

---

## 🛠 Git – Version Control

**When to Use:**  
To manage code versions and collaborate with developers.

**Cheat Sheet:**
```bash
git clone <repo-url>
git checkout -b feature/branch-name
git commit -am "Your message"
git push origin feature/branch-name
```

**Useful Links:**
- https://git-scm.com/doc

---

## 🧪 Test Planning Docs

**When to Use:**  
To define scope, objectives, resources, schedule of testing activities.

**Templates:**
- [ ] Test Plan
- [ ] Test Strategy
- [ ] Traceability Matrix
- [ ] Bug Report Template

---

## 📌 SQL – Data Validation

**When to Use:**  
To query and validate data in databases.

**Cheat Sheet:**
```sql
SELECT * FROM users WHERE status = 'active';
```

---

## ⚙️ GitHub Actions – CI/CD

**When to Use:**  
To automate test execution on pull requests or main builds.

**Example Workflow Snippet:**
```yaml
jobs:
  cypress-run:
    runs-on: ubuntu-latest
    steps:
      - uses: actions/checkout@v2
      - run: npm install
      - run: npm run test
```

---

## 🌐 JIRA – Test Management

**When to Use:**  
To create, track, and manage test cases, issues, and bugs.

**Common Workflow:**
- Create Issue > Assign > In Progress > QA > Done

---

## 📘 Notes

> Keep updating this toolbox whenever you learn something new or come across tricky issues.

