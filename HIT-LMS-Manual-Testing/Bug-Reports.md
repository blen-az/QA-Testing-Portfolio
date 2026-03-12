# 🐛 Bug Reports

## Summary
| Bug ID | Title | Module | Severity | Priority | Status |
|--------|-------|--------|----------|----------|--------|
| [BUG_01](#bug_01) | Duplicate password visibility icons | Login / Registration | Low | Medium | 🟢 Open |
| [BUG_02](#bug_02) | Delete button disabled with no explanation | Instructor | Medium | Medium | 🟢 Open |

---

## Detailed Reports

### <a id="bug_01"></a>BUG-01: Duplicate Password Visibility Icons
**Module:** Login / Registration  
**Severity:** Low | **Priority:** Medium | **Status:** Open

**Steps to Reproduce:**
1. Open Login page
2. Enter phone number and password
3. Observe password field icon

**Expected Result:**
Only one visibility toggle icon should appear.

**Actual Result:**
Two visibility icons appear.

**Impact:**
Minor UI issue that may confuse users.

---

### <a id="bug_02"></a>BUG-02: Disabled Delete Button Without Explanation
**Module:** Instructor  
**Severity:** Medium | **Priority:** Medium | **Status:** Open

**Steps to Reproduce:**
1. Instructor logs in
2. Creates and publishes course
3. Enroll learner
4. Open course management

**Expected Result:**
System should either:
- Allow deletion with confirmation
- Hide delete button
- Display clear message explaining restriction

**Actual Result:**
Delete button appears but is disabled with no explanation.

**Impact:**
Poor UX and unclear workflow.
