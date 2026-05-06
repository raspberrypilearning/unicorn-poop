## Make some shapes

### Step 1
In the **HTML tab**, add shape the classes `square` and `rounded` inside both of the `<p>` tags.

<div class="c-project-code">

--- code ---
---
language: html
filename: index.html
line_numbers: true
line_number_start: 9
line_highlights: 10, 14
---
  <section class="row row-one">
    <p class="square">Mostly glitter</p>
  </section>

  <section class="row row-two">
    <p class="rounded">A SERIOUS ART</p>
  </section>
--- /code ---

</div>

### Step 2

In the **CSS tab**, style the shapes:

- edit the colour of the gradients by changing the names
- experiment with the `border-radius` and `linear-gradient` values.

<div class="c-project-code">

--- code ---
---
language: css
filename: style.css
line_numbers: true
line_number_start: 19
line_highlights: 19-26
---
.square {
  background: radial-gradient(MediumSpringGreen, yellow);
}

.rounded {
  background: linear-gradient(190deg, deeppink, yellow);
  border-radius: 999px;
}
--- /code ---

</div>

### Now run your code
Check that the words have colourful shape backgrounds.

<div class="c-project-output">

![Two coloured rows with gradient shapes behind the text.](images/step3.png)

</div>
