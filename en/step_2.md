## Colour the rows

### Step 1

Open the CSS file from the project files tab.

### Step 2

Add the CSS code to style the rows with bright colours.

> ### Tip
> 
> To change a colour, start typing your favourite colour and the editor will autocomplete. 
> Visit <a href="https://www.w3schools.com/colors/colors_hex.asp">this website</a> to find more colour names.
{: .c-project-callout .c-project-callout--tip}

Replace the colour name with your own.

--- code ---
---
language: css
filename: style.css
line_numbers: true
line_number_start: 3
line_highlights: 7-17
---
  font-family: Helvetica, Arial, sans-serif;
  text-align: center;
}

.row {
  padding: 8px 0;
}

.row-one { 
  background: blue; 
}

.row-two { 
  background: mediumseagreen; 
}
--- /code ---

### Now run your code
Check that each row has a different background colour.

<div class="c-project-output">

![Two rows with blue and green backgrounds.](images/step_2_output.png)

</div>
