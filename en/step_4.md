<h2 class="c-project-heading--task">Make a ticker</h2>

Make the last row scroll like a news ticker.

### Step 1

Replace the last row in `index.html` with two matching ticker sets.

<div class="c-project-code">

--- code ---
---
language: html
filename: index.html
line_numbers: true
line_number_start: 41
line_highlights: 42-57
---
  <section class="row row-six">
    <section class="ticker">
      <section class="ticker-set">
        <p class="circle">Never</p>
        <p class="circle">trust</p>
        <p class="circle">beige</p>
        <p class="circle">unicorn</p>
        <p class="circle">poop</p>
      </section>
      <section class="ticker-set">
        <p class="circle">Never</p>
        <p class="circle">trust</p>
        <p class="circle">beige</p>
        <p class="circle">unicorn</p>
        <p class="circle">poop</p>
      </section>
    </section>
  </section>
--- /code ---

</div>

### Step 2

Add this CSS to move the ticker across the row.

<div class="c-project-code">

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

</div>

<h2 class="c-project-heading--task">Test</h2>

Run your code and check that the final row scrolls across the screen again and again.
