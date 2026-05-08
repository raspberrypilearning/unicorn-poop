## Challenge: style the ticker

Add the **CSS** to move the ticker text. The animation slides the ticker sideways, and the row hides anything that moves outside its edges.

<div class="c-project-code">

--- code ---
---
language: css
filename: style.css
line_numbers: true
line_number_start: 61
line_highlights: 65-95
---
  min-height: 50px;
  min-width: 50px;
}

.row-five {
  background: orange;
  overflow: hidden;
}

.circle {
  width: 66px;
  height: 66px;
  background: radial-gradient(circle, lime, mediumorchid);
  border-radius: 50%;
  font-size: 10px;
}

.ticker {
  width: max-content;
  animation: ticker 12s linear infinite;
}

.ticker-set {
  display: inline-flex;
  gap: 12px;
}

@keyframes ticker {
  from {
    transform: translateX(0);
  }
  to {
    transform: translateX(-50%);
  }
}
--- /code ---

</div>

### Now run your code
Check that the final row scrolls across the screen. You can experiment with speed by editing the `animation: ticker` values or change the layout by editing the `gap:`.

<div class="c-project-output">

![A colourful page with circular ticker words moving across the final row.](images/step10.gif)

</div>
