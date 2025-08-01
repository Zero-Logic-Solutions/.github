---
name: Bug Report
description: File a bug report
title: "[Bug]: "
labels: bug
---

Thanks for taking the time to fill out this bug report!

### Steps to reproduce (Required)
A clear and concise description of what happened and how to reproduce the issue.
<!-- Tell us what you see! -->

### Relevant log output (Required)
Please copy and paste any relevant log output. This will be automatically formatted into code, so no need for backticks.
```
<PASTE LOGS HERE>
```

### What did you expect to happen? (Required)
A clear and concise description of what you expected to happen.
<!-- Describe your expectations. -->

---

### Environment Details

**App Name (Required):**
<!-- Which application are you working on? -->

**App Version (Required):**
<!-- On which version of the Application are you working? -->

**Docker Version (if used):**
<!-- On which Docker version are you working? -->

**Operating System (Required):**
<!-- Please check the box of the OS you are using by putting an "x" in it: [x] -->
- [ ] Windows
- [ ] Linux
- [ ] MacOS
```

### Key Differences and How This Works

*   **YAML Frontmatter:** The section at the top between `---` is YAML frontmatter. GitHub reads this to get the template's `name`, `description`, pre-filled `title`, and automatically apply `labels`. This is the most powerful part of the Markdown template.
*   **No Dropdowns:** The "OS" dropdown is converted into a checklist. Users can mark the appropriate box by putting an `x` inside the brackets (e.g., `- [x] Windows`).
*   **No Placeholders:** The `placeholder` text from your YAML form is converted into comments (`<!-- ... -->`) or instructional text to guide the user.
*   **Required Fields:** We signify required fields by adding `(Required)` to the heading to make it clear to the user.
