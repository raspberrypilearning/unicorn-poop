## Style the new rows

Then add style the new rows and shapes in the CSS

### Step 1

Change the background colours on each row.

--- code ---
---
language: css
filename: style.css
line_numbers: true
line_number_start: 65
line_highlights: 71-93
---
.row-two { background: mediumseagreen; }
.row-three { background: deeppink; }
.row-four { background: blueviolet; }
.row-five { background: greenyellow; }
.row-six { background: orange; }
--- /code ---


### Step 2

Add shapes and experiment how they look.

--- code ---
---
language: css
filename: style.css
line_numbers: true
line_number_start: 65
line_highlights: 71-93
---
.rounded {
  background: linear-gradient(190deg, deeppink, yellow);
  border-radius: 999px;
}

.banner {
  background: radial-gradient(circle, aqua, red);
  border-radius: 22px;
  padding: 5px;
  width: 100px;
  font-weight: 700;
}

.rectangle {
  background: radial-gradient(MediumSpringGreen, blue);
}

.circle {
  width: 66px;
  height: 66px;
  background: radial-gradient(circle, lime, mediumorchid);
  border-radius: 50%;
  font-size: 10px;
}
--- /code ---

### Now run your code
Run your code and check that the final row scrolls across the screen again and again.
