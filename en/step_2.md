<h2 class="c-project-heading--task">Colour the rows</h2>

Add CSS to turn the plain rows into bright coloured bands.

Add this code to `style.css` below the `body` rule.

<div class="c-project-code">

--- code ---
---
language: css
filename: style.css
line_numbers: true
line_number_start: 7
line_highlights: 8-15
---
/* Rows make horizontal bands across the page. */
.row {
  padding: 8px 0;
}

.row-one { background: blue; }
.row-two { background: mediumseagreen; }
.row-three { background: deeppink; }
.row-four { background: blueviolet; }
.row-five { background: greenyellow; }
.row-six { background: orange; }
--- /code ---

</div>

<h2 class="c-project-heading--task">Test</h2>

Run your code and check that each row has a different background colour.
