## Challenge: add a moving ticker style

Add the animation in CSS to move the ticker across the row.

--- code ---
---
language: css
filename: style.css
line_numbers: true
line_number_start: 65
line_highlights: 71-93
---
.row-six {
  overflow: hidden;
  background: orange;
}

.ticker {
  display: flex;
  width: max-content;
  animation: ticker 12s linear infinite;
}

.ticker-set {
  display: inline-flex;
  gap: 12px;
  min-width: 100vw;
  flex-shrink: 0;
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

### Now run your code
Check that the final row scrolls across the screen again and again.
