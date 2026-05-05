## Colour the rows

### Step 1

Open the CSS file from the project files tab.

### Step 2

Add the CSS code to style the rows with bright colours.

> ### Tip
> 
> The background to each row is a different built in colour. 
> Start typing your favourite colour and the editor will autocomlete. Or visit <a href="https://www.w3schools.com/colors/colors_hex.asp">this website</a> to find more colour names.
{: .c-project-callout .c-project-callout--tip}

Experiment with different colours.

--- code ---
---
language: css
filename: style.css
line_numbers: true
line_number_start: 7
line_highlights: 8-15
---
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
