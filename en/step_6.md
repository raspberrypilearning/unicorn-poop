## Style the new rows

Then style the new rows and shapes in the CSS.

### Step 1
Change the background colours on each new row.

--- code ---
---
language: css
filename: style.css
line_numbers: true
line_number_start: 19
line_highlights: 19-25
---
.row-three { 
  background: deeppink; 
}

.row-four { 
  background: blueviolet; 
}
--- /code ---

### Step 2
Experiment with the shapes and colours in CSS.

--- code ---
---
language: css
filename: style.css
line_numbers: true
line_number_start: 53
line_highlights: 53-63
---
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
--- /code ---

### Now run your code
Run your code and check that the new rows and shapes have colours.

> ### Debugging
> 
> If a shape does not change, check that the class name in your HTML matches the CSS name exactly.
{: .c-project-callout .c-project-callout--debug}

<div class="c-project-output">

![Four colourful rows with styled banner and rectangle shapes.](images/step_6_output.png)

</div>
