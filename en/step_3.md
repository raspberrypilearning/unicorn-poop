## Make shapes

### Step 1
In the HTML file, add shape classes `square` and `rounded` inside both of the `<p>` tags.

--- code ---
---
language: html
filename: index.html
line_numbers: true
line_number_start: 11
line_highlights: 13-48
---
<body>

  <section class="row row-one">
    <p class="square">Mostly glitter</p>
  </section>

  <section class="row row-two">
    <p class="rounded">A SERIOUS ART</p>
  </section>

</body>
--- /code ---

### Step 2

Style the CSS to make the shapes how you want:

- edit the colour of the gradients by changing the colour names
- experiment with the `border-radius` number to make the shape more rounded.

--- code ---
---
language: css
filename: style.css
line_numbers: true
line_number_start: 16
line_highlights: 16-64
---
.square {
  background: radial-gradient(MediumSpringGreen, blue);
}

.rounded {
  background: linear-gradient(190deg, deeppink, yellow);
  border-radius: 999px;
}
--- /code ---


### Now run your code
Check that each row has a different background colour.

