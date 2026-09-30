# My Budget Tracker - Week 2

## What I Built
This is a simple Budget Tracker website built on top of Week 1 project. It helps users view their expenses and add new ones.

## What Each Part Does

**index.html:**
- Header with logo using <img> tag
- Expense Table with <table>, <thead>, <tbody>, <tr>, <th>, <td> - shows 5 sample expenses
- Add Expense Form wrapped in <form> with inputs for name, amount, category (as <select> dropdown with 5 options), and date. Button has type="button"
- <details> and <summary> for collapsible instructions
- <iframe> embedding YouTube budgeting video

**style.css:**
- Table styling with border-collapse: collapse, padding, colored header, alternating row colors using tr:nth-child(even)
- Hover effect on table rows (tr:hover)
- Button with cursor: pointer
- Advanced selectors used:
    1. Descendant selector (.expenses-section td)
    2. Direct child selector (.add-expense-section > form)
    3. Pseudo-class position (tr:nth-child(even) and tr:first-child)
    4. Negation (input:not([type="submit"]))
    5. Focus state (input:focus)

## How to Run
Open index.html in browser.