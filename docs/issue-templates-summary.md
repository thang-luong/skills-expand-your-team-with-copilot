# Issue Templates Summary

This repository now has 6 GitHub issue template forms designed specifically for teachers who are not comfortable coding.

## Available Templates

### 1. 🐛 Bug Report
**Purpose:** Report problems with the website  
**Auto-assigned to:** @copilot  
**Required Information:**
- What went wrong
- What should have happened
- Steps to recreate the problem
- What part of the website has the issue

**Context Provided to Copilot:**
- Will review issue and identify root cause
- Will fix bug in appropriate file
- Will test the fix
- Will verify no other functionality is broken

---

### 2. ➕ Add New Activity
**Purpose:** Add a completely new activity to the website  
**Auto-assigned to:** @copilot  
**Required Information:**
- Activity name
- Description
- Category (Sports, Arts, Academic, Community, Technology, Other)
- Schedule days
- Start and end times
- Maximum number of students

**Context Provided to Copilot:**
- Will add to database in src/backend/database.py
- Will ensure it appears in activity list
- Will verify filtering works
- Will test student registration

---

### 3. ✏️ Modify Existing Activity
**Purpose:** Change details of an existing activity  
**Auto-assigned to:** @copilot  
**Required Information:**
- Activity name
- What needs to be changed (schedule, description, capacity, name)
- Specific change details
- Reason for changes

**Context Provided to Copilot:**
- Will locate activity in database
- Will update specified fields
- Will ensure changes display correctly
- Will verify filters still work

---

### 4. ❌ Remove Activity
**Purpose:** Remove an activity that's no longer offered  
**Auto-assigned to:** @copilot  
**Required Information:**
- Activity name
- Reason for removal
- How to handle enrolled students

**Context Provided to Copilot:**
- Will remove from database
- Will ensure it no longer appears
- Will handle enrolled students per instructions
- Will clean up related data

---

### 5. 🎨 UI/Design Improvement
**Purpose:** Improve website appearance or usability  
**Auto-assigned to:** @copilot  
**Required Information:**
- What part should be improved
- Current situation
- Suggested improvement
- Priority level
- Why it's needed

**Context Provided to Copilot:**
- Will analyze current implementation
- Will make improvements to HTML/CSS/JavaScript
- Will test across screen sizes
- Will ensure accessibility

---

### 6. ✨ New Feature Request
**Purpose:** Add completely new functionality  
**Auto-assigned to:** @copilot  
**Required Information:**
- Feature description
- Problem it solves
- How it should work (step-by-step)
- Who would use it
- Priority level
- Acceptance criteria

**Context Provided to Copilot:**
- Will analyze requirements
- Will design implementation
- Will add backend and frontend code
- Will test thoroughly
- Will document the feature

---

## Key Features

✅ **No coding required** - Simple forms guide teachers through providing all necessary information  
✅ **Auto-assigned** - Copilot coding agent is automatically assigned to each issue  
✅ **Clear context** - Each template explains what will happen and provides implementation hints  
✅ **Required fields** - Ensures all necessary information is collected upfront  
✅ **User-friendly** - Written in simple, non-technical language  
✅ **Well-structured** - Follows best practices with clear problem description, acceptance criteria, hints, and context

## How Teachers Use Templates

1. Go to GitHub Issues page
2. Click "New issue"
3. Choose the appropriate template
4. Fill out the form fields
5. Submit
6. Copilot automatically starts working on it

Teachers never need to write code or understand technical implementation details!
