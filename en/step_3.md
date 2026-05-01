<h2 class="c-project-heading--task">Style the shapes</h2>

Style the pill, banner, square, and circle shapes used in your poster.

Add this code to the bottom of `style.css`.

<div class="c-project-code">

--- code ---
---
language: css
filename: style.css
line_numbers: true
line_number_start: 16
line_highlights: 16-64
---
.pill,
.banner,
.square-1,
.square-2,
.circle {
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

.pill {
  background: linear-gradient(190deg, deeppink, yellow);
  border-radius: 999px;
  padding: 8px 14px;
}

.banner {
  background: radial-gradient(circle, aqua, red);
  border-radius: 22px;
  padding: 5px 5px;
  width: 100px;
  font-weight: 700;
}

.square-1 {
  background: linear-gradient(145deg, LemonChiffon, orchid);
}

.square-2 {
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

</div>

<h2 class="c-project-heading--task">Test</h2>

Run your code and check that the facts now sit inside colourful shapes.
