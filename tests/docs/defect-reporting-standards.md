# CleanCity Defect Reporting Standards

## 📋 Purpose
These standards define how defects should be reported, tracked, and managed for the CleanCity application to ensure consistent and effective communication between QA, developers, and project stakeholders.

---

## 🛠️ Defect Reporting Guidelines

### 1. **Defect ID**
- Assign a unique identifier to each defect (e.g., `DEF001`, `DEF002`).

### 2. **Reporter Information**
- Name and role of the person reporting the defect.
- Date and time of reporting.

### 3. **Environment**
- Browser, operating system, and device where the defect was observed.
- Example: `Chrome 115, Windows 10, Desktop` or `Safari iOS 16, iPhone 12`.

### 4. **Module / Feature**
- Identify the specific module or feature affected.
- Examples: `Pickup Scheduling Form`, `Admin Panel`, `Blog Module`, `Community Forum`.

### 5. **Defect Description**
- Provide a concise and clear explanation of the defect.
- Include any unexpected behavior and why it is an issue.

### 6. **Steps to Reproduce**
- Numbered step-by-step instructions to reproduce the defect.
- Include any specific input values, actions, or settings used.

### 7. **Expected Result**
- Describe what should happen under normal conditions.

### 8. **Actual Result**
- Describe what actually happens when the defect occurs.

### 9. **Severity**
- **Critical:** Application crash, data loss, or security breach.  
- **Major:** Key functionality broken but application still usable.  
- **Minor:** Non-critical functionality or feature impacted.  
- **Cosmetic:** UI/UX issues, typos, layout inconsistencies.

### 10. **Priority**
- **High:** Needs immediate attention.  
- **Medium:** Should be fixed in the next release.  
- **Low:** Can be addressed in future updates.

### 11. **Attachments**
- Include screenshots, video recordings, or logs to support the defect report.

### 12. **Status**
- Open, In Progress, Resolved, or Closed.

### 13. **Assigned To**
- Developer or team responsible for fixing the defect.

---

## 📝 Additional Notes
- All defects must be reproducible before reporting.
- Avoid vague descriptions like "doesn’t work"; specify the behavior.
- Reference related defects if applicable.
- Include version numbers for the CleanCity application if relevant.
- Track defect history for QA follow-up and regression testing.

---

## 📊 Recommended Defect Tracking Tools
- Jira and Github Project
- GitHub Issues

---

## ✅ Best Practices
- Use consistent formatting for defect reports.
- Report defects immediately after discovery.
- Re-test defects once fixed before closing.
- Prioritize defects based on impact to users and business logic.