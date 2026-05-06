## Style all the shapes

Give the shapes spacing and alignment.

In the **CSS tab** add a shared style for both the shape classes.

<div class="c-project-code">

--- code ---
---
language: css
filename: style.css
line_numbers: true
line_number_start: 28
line_highlights: 28-43
---
.rounded,
.square {
  display: inline-flex;
  align-items: center;
  justify-content: center;
  box-sizing: border-box;
  margin: 4px 6px;
  padding: 8px;
  text-align: center;
  vertical-align: middle;
  min-height: 50px;
  min-width: 50px;
}
--- /code ---

</div>

### Now run your code
Check that the words sit in the middle of each shape. 

<div class="c-project-output">

![Two coloured rows with centred text inside the shapes.](images/step4.png)

</div>
