<h2 class="c-project-heading--task">Fill the background</h2>

Add a third `wallpaper-row` so the provided pattern images tile across much more of the page.

<h2 class="c-project-heading--explainer">Make this change</h2>

Stay in `index.html` and put the new row underneath the second one.

<div class="c-project-code">

--- code ---
---
language: html
filename: index.html
line_numbers: true
line_number_start: 9
line_highlights: 23-28
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
      <div class="wallpaper-row">
        <img src="chainlink.gif" alt="">
        <img src="red.gif" alt="">
        <img src="purple_shine.gif" alt="">
        <img src="rainbow.gif" alt="">
      </div>
    </div>
  </body>
--- /code ---

</div>

## Now run your code

You should now see the pattern images tiled across the background instead of just sitting in one area.

<div class="c-project-output">
  <img src="images/step_3_output.png" alt="Expected project output after step 3 showing three rows of tiled pattern images across the background.">
</div>
