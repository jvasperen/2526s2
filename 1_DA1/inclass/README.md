# In-Class Teaching Materials

This folder contains 4 Jupyter notebooks designed for a Python introduction for Communication Science students.

## Structure

Each topic has two versions:

1. **STUDENT version**: For live teaching (project on screen)
   - Empty code cells for students to type along
   - Guided exercises with prompts
   - Clear explanations suitable for beginners

2. **SOLVED version**: For instructor reference (keep private)
   - Complete solutions for all exercises
   - Teaching notes and common errors to watch for
   - Tips for explaining difficult concepts

## Session Overview (30 minutes each)

### Session 1: Getting Started & Data Types (30 min)
**File**: `01_GettingStarted_DataTypes_STUDENT.ipynb`

**Topics**:
- What is Python and Jupyter Notebooks
- Running cells (Shift + Enter)
- Data types: integers, floats, strings
- Using `print()` and `type()`
- Basic math operations

**Key Concepts**:
- Strings need quotes
- Python as a calculator
- Type checking

**Time Allocation**:
- Introduction (5 min)
- Jupyter basics (5 min)
- Data types & demos (10 min)
- Practice exercise (10 min)

---

### Session 2: Variables & Operations (30 min)
**File**: `02_Variables_Operations_STUDENT.ipynb`

**Topics**:
- Creating variables with `=`
- Variable reassignment
- Operations with variables
- Shorthand operators (`+=`)
- Combining variables
- Naming rules

**Key Concepts**:
- Variables store values
- Operations don't change variables unless reassigned
- Good variable naming practices

**Time Allocation**:
- Variable basics (8 min)
- Operations & reassignment (8 min)
- Combining variables (7 min)
- Practice exercise (7 min)

---

### Session 3: Lists & Dictionaries (30 min)
**File**: `03_DataStructures_STUDENT.ipynb`

**Topics**:
- Creating lists `[item1, item2]`
- Indexing (0-based!)
- List methods: `append()`, `len()`, `sum()`, `max()`
- Creating dictionaries `{'key': value}`
- Accessing dictionary values
- When to use each structure

**Key Concepts**:
- Python counts from 0
- Lists for ordered collections
- Dictionaries for labeled data
- Negative indexing

**Time Allocation**:
- Lists introduction & indexing (10 min)
- List methods (5 min)
- Dictionaries (8 min)
- Practice exercise (7 min)

---

### Session 4: Conditions & Loops (30 min)
**File**: `04_ControlFlow_STUDENT.ipynb`

**Topics**:
- if/elif/else statements
- Comparison operators (`==`, `>`, `<`, etc.)
- Logical operators (`and`, `or`, `not`)
- for loops
- while loops (brief)
- Functions with `def`

**Key Concepts**:
- Indentation is critical
- For loops for lists
- Functions make code reusable

**Time Allocation**:
- Conditions (10 min)
- For loops (8 min)
- While loops + functions (7 min)
- Practice exercise (5 min)

---

## Teaching Tips

### General Approach
1. **Type along**: Never show complete code - type it live with students
2. **Pause frequently**: Check if everyone is keeping up
3. **Encourage errors**: Run broken code to show error messages
4. **Use examples**: Social media metrics are relatable for comm students

### Common Student Mistakes

**Session 1**:
- Forgetting quotes around strings → Show error message
- Trying to run Markdown cells as code
- Not using Shift+Enter (just pressing Enter)

**Session 2**:
- Thinking `x + 5` changes `x` automatically
- Using spaces in variable names
- Confusing `=` (assignment) with `==` (comparison)

**Session 3**:
- Forgetting Python counts from 0
- Mixing up list brackets `[]` and dict braces `{}`
- Off-by-one errors in slicing

**Session 4**:
- Indentation errors (most common!)
- Using `=` instead of `==` in conditions
- Forgetting colons after if/for/def
- Infinite while loops

### Pacing Guidance
- **First 10 minutes**: Tend to move slower - students setting up
- **Middle 15 minutes**: Pick up pace once comfortable
- **Last 5 minutes**: Buffer time for questions and exercises

### If You Run Over Time
- Skip optional demonstrations (keep only core examples)
- Reduce practice exercises from 4 tasks to 2 key ones
- Move While loops to "homework reading" in Session 4
- Emphasize that practice outside class is essential

### If You Finish Early
- Add extra practice problems from existing exercises
- Take questions about real research applications
- Preview next week's topics briefly
- Show interesting Python libraries they'll learn later (pandas, matplotlib)

## Using These Materials

### Before Class
1. Open STUDENT version for projection
2. Have SOLVED version open in another window for reference
3. Test that Python kernel starts properly
4. Have example data ready (social media metrics, survey scores, etc.)

### During Class
1. Share screen with STUDENT notebook
2. Type code with students (don't copy-paste!)
3. Run cells as a group
4. For exercises: give 5-7 minutes, then review solutions
5. Use SOLVED notebook for quick reference when answering questions

### After Class
- Students should practice all exercises at home
- Encourage experimentation with changing values
- Remind them errors are normal and helpful
- Point them to documentation: python.org, docs.python.org

## File Privacy

⚠️ **SOLVED files are configured to stay private** (via .gitignore)

If pushing to GitHub:
- STUDENT files will be shared publicly
- SOLVED files will remain only on your local machine
- This lets students access blank exercises while keeping your teaching notes private

---

## Quick Reference

| Concept | Syntax | Example |
|---------|--------|---------|
| Print | `print(value)` | `print('Hello')` |
| Variable | `name = value` | `age = 22` |
| List | `[item1, item2]` | `[1, 2, 3]` |
| Dictionary | `{'key': value}` | `{'name': 'Emma'}` |
| Condition | `if condition:` | `if x > 5:` |
| Loop | `for item in list:` | `for x in [1,2,3]:` |
| Function | `def name(param):` | `def greet(name):` |

