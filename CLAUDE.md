```markdown
# CLAUDE.md

## Project Name
Dynamic Average Calculator

## Project Objective
Build a modern, responsive, single-file HTML application that calculates the average of user-entered numbers. The application must automatically expand input fields as needed and update the average in real time.

---

## Technology Stack

- HTML5
- CSS3
- Vanilla JavaScript
- No frameworks
- No backend
- No database
- No external libraries
- No CDN dependencies

Everything must be contained inside a single file:

average-calculator.html

---

## User Interface Requirements

### Layout

Create a two-column layout.

#### Left Side
Display number input fields vertically.

Default visible fields:

- Number 1
- Number 2
- Number 3
- Number 4
- Number 5

Each field should:

- Have black border
- Rounded corners
- Clean spacing
- Placeholder text:
  - Number 1
  - Number 2
  - Number 3
  - etc.

#### Right Side

Display a large output box.

Requirements:

- Black border
- Center aligned text
- Modern appearance
- Fixed minimum height
- Responsive

Default message:

Enter numbers to calculate average

---

## Dynamic Input Expansion

### Default

Show 5 fields initially.

### Auto Expansion Logic

When the user enters a valid number into the last visible field:

Example:

Number 5 gets filled

Automatically create:

Number 6

When Number 6 gets filled:

Automatically create:

Number 7

Continue indefinitely.

Always keep one empty field available at the bottom.

---

## Average Calculation Logic

Calculate average automatically while typing.

No Calculate button required.

### Rules

- Ignore empty fields
- Ignore invalid entries
- Allow decimals
- Allow negative values
- Recalculate instantly on every input event

### Formula

Average = Sum of Valid Numbers ÷ Count of Valid Numbers

### Decimal Formatting

Always display result rounded to 2 decimal places.

Example:

Input:

Number 1 = 23.53
Number 2 = 24.62
Number 3 = 28.79
Number 4 = 28.77

Output:

Average is 26.42

---

## Validation Rules

Use:

input type="text"

not:

input type="number"

Reason:
Custom validation handling.

### Valid Inputs

Examples:

23
23.45
-15
-10.55

### Invalid Inputs

Examples:

abc
23x
@
1..5

For invalid entries:

Show red validation message below field:

Please enter a valid number

Do not include invalid values in average calculation.

---

## Instruction Button

Create a button with exact text:

Average Calculator - Insturctions

Important:

Keep spelling exactly as above.

---

## Instruction Popup Modal

When button is clicked:

Open modal popup.

### Modal Title

How to Use

### Modal Content

Show exactly 5 bullet points:

• Enter numbers in the boxes one by one.

• Empty boxes are ignored in the average.

• A new box appears after the last box is filled.

• The average updates automatically.

• Use decimal numbers when needed.

### Modal Features

- Close button
- Click outside to close
- Smooth animation
- Mobile friendly

---

## Design Requirements

### Theme

Professional

Minimal

Corporate

Clean

### Styling

- White background
- Black borders
- Subtle shadow effects
- Modern typography
- Responsive layout

### Button Effects

Add:

- Hover effect
- Smooth transition
- Cursor pointer

---

## Responsive Requirements

Desktop:

- Inputs on left
- Output box on right

Mobile:

- Stack vertically
- Full width controls
- Proper spacing

---

## Accessibility

- Proper labels
- Keyboard friendly
- Focus indicators
- Readable font size

---

## Code Quality

- Clean code
- Well commented
- Modular JavaScript functions
- Easy to maintain

Functions should be separated logically:

- createInputField()
- calculateAverage()
- validateInput()
- addNewFieldIfNeeded()
- openInstructionsModal()
- closeInstructionsModal()

---

## Deliverable

Generate only one complete file:

average-calculator.html

The file must contain:

- HTML
- CSS
- JavaScript

inside the same document.

Return only the final production-ready HTML code.

Do not provide explanations.

Do not provide pseudocode.

Do not provide partial snippets.

Return complete working code only.
```
