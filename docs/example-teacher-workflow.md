# Example: Teacher Using Issue Templates

## Scenario
Ms. Rodriguez wants to add a new "Yoga Class" activity to the school website, but she doesn't know how to code.

## What She Does

### Step 1: Go to GitHub Issues
She navigates to: `https://github.com/thang-luong/skills-expand-your-team-with-copilot/issues`

### Step 2: Click "New Issue"
She sees a list of template options:

```
┌─────────────────────────────────────────────────────┐
│  Select an issue template                           │
├─────────────────────────────────────────────────────┤
│  🐛 Bug Report                                       │
│  Report a problem with the school activities website│
│  [Get started]                                      │
├─────────────────────────────────────────────────────┤
│  ➕ Add New Activity                                 │
│  Request to add a new extracurricular activity      │
│  [Get started]  ← She clicks here                   │
├─────────────────────────────────────────────────────┤
│  ✏️ Modify Existing Activity                         │
│  Request changes to an existing activity            │
│  [Get started]                                      │
├─────────────────────────────────────────────────────┤
│  ... (other templates)                              │
└─────────────────────────────────────────────────────┘
```

### Step 3: Fill Out the Form

She sees a friendly form with clear instructions:

```
━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━
[NEW ACTIVITY] 

Thank you for requesting a new activity! Please fill out all the 
details below.

### What happens next
After you submit this form, the Copilot coding agent will:
1. Add the new activity to the database in src/backend/database.py
2. Ensure it appears in the activity list on the website
3. Verify it can be filtered by category and schedule
4. Test that students can register for it

### Tips for filling out this form
- Activity names should be unique and descriptive
- Categories help students find activities they're interested in
- Be specific with times (include AM/PM)
- Consider realistic capacity based on available resources

━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━

Activity Name *
┌─────────────────────────────────────────────────┐
│ Yoga Class                                      │
└─────────────────────────────────────────────────┘
What is the name of the new activity?

Activity Description *
┌─────────────────────────────────────────────────┐
│ Learn yoga poses and breathing techniques for   │
│ relaxation and physical fitness                 │
└─────────────────────────────────────────────────┘
Write a brief description of what students will do.

Activity Category *
[v] Arts ← She selects this

Which days will this activity meet? *
☑ Monday
☐ Tuesday
☑ Wednesday
☐ Thursday
☑ Friday
☐ Saturday
☐ Sunday

Start Time *
┌─────────────────────────────────────────────────┐
│ 3:30 PM                                         │
└─────────────────────────────────────────────────┘

End Time *
┌─────────────────────────────────────────────────┐
│ 4:30 PM                                         │
└─────────────────────────────────────────────────┘

Maximum Number of Students *
┌─────────────────────────────────────────────────┐
│ 15                                              │
└─────────────────────────────────────────────────┘

Additional Details
┌─────────────────────────────────────────────────┐
│ Students should wear comfortable clothing and   │
│ bring a yoga mat if they have one.              │
└─────────────────────────────────────────────────┘

          [Submit new issue]
━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━
```

### Step 4: Submit

She clicks "Submit new issue" and that's it! 

### What Happens Next

The system automatically:
- Creates issue #X with title "[NEW ACTIVITY] "
- Assigns @copilot to the issue
- Tags it with "enhancement" and "new-activity" labels
- Copilot receives all the information needed to add the activity

### Result

Within minutes/hours, Copilot:
1. ✅ Adds Yoga Class to the database
2. ✅ Makes it appear on the website
3. ✅ Ensures it's filterable by Arts category
4. ✅ Verifies students can register
5. ✅ Comments on the issue when complete

Ms. Rodriguez never had to:
- Write any code
- Understand the database structure
- Know HTML, CSS, JavaScript, or Python
- Figure out what information to provide (the form guided her)

## Key Benefits

✅ **No coding required** - Simple web form
✅ **Guided process** - Each field explains what's needed
✅ **Examples provided** - Placeholders show correct format
✅ **Complete information** - Form ensures all details collected
✅ **Automatic processing** - Copilot handles implementation
✅ **Teacher-friendly** - Simple language, no jargon

This is exactly what teachers need: **A simple way to request changes without technical knowledge!**
