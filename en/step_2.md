<h2 class="c-project-heading--task">Add another row</h2>

Add one more `wallpaper-row` inside the same `wallpaper` container so the pattern starts to spread.

<h2 class="c-project-heading--explainer">Make this change</h2>

Stay in `index.html` and put the new row underneath the first one.

<div class="c-project-code">

--- code ---
---
language: html
filename: index.html
line_numbers: true
line_number_start: 9
line_highlights: 17-22
---
  <body>
    <div class="wallpaper" aria-hidden="true">
      <div class="wallpaper-row">
        <img src="maze.gif" alt="">
        <img src="leopard.gif" alt="">
        <img src="maze.gif" alt="">
        <img src="leopard.gif" alt="">
      </div>
      <div class="wallpaper-row">
        <img src="dots.gif" alt="">
        <img src="eye.gif" alt="">
        <img src="dots.gif" alt="">
        <img src="eye.gif" alt="">
      </div>
    </div>
  </body>
--- /code ---

</div>

## Now run your code

You should now see two rows of pattern images making a stronger wallpaper.

<div class="c-project-output">
  <img src="images/step_2_output.png" alt="Expected project output after step 2 showing two rows of decorative pattern images.">
</div>
