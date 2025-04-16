# 🧪 Test Plan – UI Rendering Bug (Nx Console in IntelliJ)

## 1. Objective

To validate the visual integrity and usability of the **Nx Console plugin UI** inside **IntelliJ IDEA**, ensuring that UI components (targets and buttons) are displayed without overlapping or misalignment.

---

## 2. Scope

- ✅ Nx Console UI rendering in IntelliJ
- ✅ Targets panel interaction
- ✅ Visual layout of action buttons (`build`, `run`, `graph`, etc.)
- ❌ Functional correctness of each target's execution

---

## 3. Tools

- IntelliJ IDEA (2023.x+)
- Nx Console Plugin (latest version)
- Windows 10/11 (tested), macOS (optional)
- Screenshot tools
- GitHub for reporting

---

## 4. Resources

- QA Engineer (1)
- Developer for plugin validation (optional)

---

## 5. Risks & Assumptions

- Risk: Plugin layout varies across IntelliJ versions.
- Assumption: Plugin is fully updated and configured.

---

## 6. Deliverables

- Test Report (in this repo)
- Screenshots
- GitHub Issue (if reported upstream)
