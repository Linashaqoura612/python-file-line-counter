# File Line Counter - Requirements Document Template

---

## Purpose
This document contains the **ACTUAL REQUIREMENTS** for the File Line Counter application. 
---

## Functional Requirements

### FR-1: File Input
**Requirement:** The application shall accept a single text file as input.

**Details:**
- Supported file extensions: .txt, .log, .md
- Maximum file size: 10MB
- File encoding: UTF-8

**Error Handling:** see FR-4

---

### FR-2: Line Counting Logic
**Requirement:** The application shall count lines according to the following rules:

**What Counts as a Line:**
- Any text content
- Empty lines
- Lines with only whitespace
- Lines with only comments

**What Doesn't Count:**
- t.b.d

**Line Delimiter:**
- \n, \r\n, \r

---

### FR-3: Output Format
**Requirement:** The application shall display the line count in the following format:

**Display Format:**
For a file with 42 lines, the following is returned as result:
```
42
```
---

### FR-4: Error Messages
**Requirement:** The application shall return appropriate error messages for:

**Invalid File:**
```
"Error: File not found"
```

**Unsupported Format:**
```
"Error: Unsupported file type"
```

**Access Denied:**
```
"Error: Permission denied"
```

**File Too Large:**
```
"Error: File exceeds size limit"
```

---

## Non-Functional Requirements

...
---

### NFR-3: Compatibility
**Requirement:** The application shall work on the following platforms:

....
---

## Out of Scope

**The following are explicitly NOT requirements:**

- Counting words
- Counting characters
- Multiple file support
- Directory scanning
- Recursive file processing
- File content analysis beyond line counting
- Code syntax highlighting
- Export results to file

---

