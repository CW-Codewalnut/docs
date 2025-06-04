# ✅ Codewalnut PR Checklist – Front-End Web Applications

A high-quality pull request (PR) is essential for maintaining scalable, maintainable, and bug-free code. This checklist ensures every PR meets our code quality and delivery standards.

---

## 🚀 PR Standards

- [ ] This branch implements **a single responsibility** (e.g., feature, bugfix, style, refactor).
- [ ] I have used **conventional commit messages** and **descriptive branch names**.
- [ ] All modified or newly created folders/files follow **clear, descriptive naming conventions**.
- [ ] The PR includes a link to the **associated task/ticket** (JIRA, Rally, Trello, GitHub issue).

---

## Testing checklist
- [ ] I have written **unit tests** for all components I worked on—covering user-visible behavior and UI state changes.
- [ ] I have written **unit tests** for helper functions, covering both expected and edge case scenarios.
- [ ] I have written **integration tests** for all new features, ensuring components work together as intended.
- [ ] I have checked **SonarQube quality gate results** and resolved any blocking issues.

### **If any of the above tests are not applicable or intentionally skipped, explain why:**
...

## ✅ Definition of Done

- [ ] I have completed the **PR Standards** and **Testing Checklist** above and am confident the code performs reliably across different use cases.
- [ ] I have **ESLint and Prettier** set to run on file save, and I have resolved all linting and formatting issues as well as warnings.
- [ ] I have defined **PropTypes or TypeScript types** for all components and helpers without using `any`
- [ ] I have removed **all dead code, TODOs, and non-descriptive comments** from the files I have touched.
- [ ] I have **rebased** my branch with the target base branch, and all commits in this PR are authored by me.

---

## Why this checklist?

This checklist is part of **Codewalnut’s quality-first delivery process**. It ensures consistency, prevents regressions, and gives clients confidence in the maintainability of their front-end systems—especially those built in **React** and TypeScript.

---

## 🔍 Reviewer Checklist

- [ ] PR is limited to a single logical unit (feature, fix).
- [ ] All tests pass locally and in CI.
- [ ] Code is readable, self-explanatory, and adheres to project conventions.
- [ ] No obvious performance issues or accessibility concerns.
- [ ] PR is ready for merge and deployment.
